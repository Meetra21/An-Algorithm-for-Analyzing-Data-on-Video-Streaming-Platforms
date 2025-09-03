# Netflix Content Analysis  

This project explores and analyzes the content available on **Netflix**, one of the world’s largest video streaming platforms. By examining movies and TV shows across multiple dimensions such as type, year, country, ratings, and genres, the project uncovers key insights about Netflix’s **global content offerings**.  

---

## 🎯 Project Objective  

- Analyze Netflix’s catalog to identify **patterns and trends**.  
- Compare **movies vs. TV shows** in terms of distribution and characteristics.  
- Understand **production trends** across years and countries.  
- Explore **audience segmentation** using ratings.  
- Investigate **genres, directors, durations, and release timing**.  

---

## 🔑 Key Questions  

1. What is the **distribution of content types** (movies vs TV shows)?  
2. How has the **volume of content evolved** over the last decade?  
3. Which **countries produce the most content** on Netflix?  
4. How does Netflix classify content based on **age ratings**?  
5. What are the **most frequent genres**?  
6. Which **directors** have directed the most titles on Netflix?  
7. What is the **distribution of movie durations** and TV show seasons?  
8. What proportion of content was **added in the last 5 years**?  
9. Which **months** see the highest content additions?  

---

## 📂 Dataset  

- **Source**: [Kaggle Netflix Dataset (2021)](https://www.kaggle.com/shivamb/netflix-shows)  
- **Content**: Movies and TV shows available on Netflix up to 2021  
- **Key Attributes**:  
  - `title` – Name of the movie/TV show  
  - `type` – Movie or TV Show  
  - `director` – Director(s) of the title  
  - `cast` – Main cast  
  - `country` – Country of production  
  - `date_added` – Date title was added to Netflix  
  - `release_year` – Year of original release  
  - `rating` – Audience classification (e.g., TV-MA, PG, R)  
  - `duration` – Movie runtime or number of TV show seasons  
  - `listed_in` – Genres/categories  

### Missing Data Handling  
- Columns such as `director`, `cast`, `country`, and `date_added` contain missing values.  
- Missing values are filled with `"Unknown"` to preserve dataset completeness.  

---

## 🧭 Workflow  

### 1. Data Preprocessing  
- Handle missing values (fill with `"Unknown"`)  
- Convert date columns into datetime objects  
- Extract year/month for trend analysis  

### 2. Exploratory Data Analysis (EDA)  
- Movies vs TV shows distribution  
- Trends in content production over years  
- Country-wise distribution of titles  
- Distribution of audience age ratings  
- Most frequent genres and directors  
- Movie durations & TV show seasons  
- Monthly content addition patterns  

### 3. Visualization  
- Bar charts, histograms, and line plots for trends  
- Heatmaps for country/content relationships  
- Word clouds for popular genres  

---

## 📂 Repository Structure  

- `data/` – Netflix dataset (CSV)  
- `notebooks/` – Jupyter notebooks for preprocessing and EDA  
- `visualizations/` – Charts and plots generated from analysis  
- `results/` – Summarized insights  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/netflix-content-analysis.git
   cd netflix-content-analysis
