### **Main Project 1: Netflix Data Wrangling, Exploration & Metadata Enrichment**  
*(Foundational Data Skills)*  

#### **Subproject 1.1: Data Cleaning & Preprocessing**  
**GitHub Title**: `netflix-data-cleaning`  
**Description**: Fix structural issues in the raw dataset (missing values, duplicates, inconsistent formats) to prepare it for analysis.  
**Detailed Breakdown**:  
- **Skills**: Data profiling, handling missing data, data type conversion, regex, duplicate detection.  
- **Tech Stack**: Python (Pandas, NumPy), Matplotlib/Seaborn (for validation), Great Expectations (data validation).  
- **Deliverables**: Cleaned CSV/Parquet dataset, data cleaning report (missing value imputation strategy, duplicate removal logic).  
- **Example Tasks**:  
  - Impute `date_added` missing values using `release_year` or external calendar data.  
  - Standardize `country` entries (e.g., "United States" vs. "USA").  
  - Fix `duration` format (e.g., "60 min" → 60).  
  - Remove duplicate `show_id` entries (if any).  


#### **Subproject 1.2: Exploratory Data Analysis (EDA) & Visualization**  
**GitHub Title**: `netflix-eda-visualization`  
**Description**: Uncover patterns in content (type, country, rating), trends over time, and audience preferences using visual analytics.  
**Detailed Breakdown**:  
- **Skills**: Statistical analysis, data storytelling, interactive visualization.  
- **Tech Stack**: Python (Pandas, Plotly Dash/Tableau), Seaborn/Matplotlib, WordCloud.  
- **Deliverables**: Interactive dashboards, key insights report (e.g., "Top 5 countries by content count," "Rating distribution by type").  
- **Example Tasks**:  
  - Analyze `release_year` trends (e.g., surge in streaming content post-2015).  
  - Compare `type` (Movie vs. TV Show) by `country` (e.g., Netflix Originals vs. licensed content).  
  - Visualize `listed_in` genres (e.g., "Most common genres: International Movies, Dramas").  


#### **Subproject 1.3: Metadata Enrichment**  
**GitHub Title**: `netflix-metadata-enrichment`  
**Description**: Enhance the dataset with external data to improve model performance (e.g., IMDB ratings, genre keywords, actor popularity).  
**Detailed Breakdown**:  
- **Skills**: Web scraping/API integration, data merging, feature engineering.  
- **Tech Stack**: Python (Requests, BeautifulSoup, Pandas), TMDB API (The Movie Database), IMDBpy.  
- **Deliverables**: Enriched dataset with new columns (e.g., `imdb_rating`, `genre_tags`, `actor_followers`).  
- **Example Tasks**:  
  - Scrape TMDB for missing `release_year` or `genre` details.  
  - Use IMDBpy to fetch user ratings for cross-validation.  
  - Extract top 3 actors from `cast` and link to their social media followings (via Wikipedia/IMDB).  


---

Dataset: Netflix Movies and TV Shows, Version 5, accessed from https://www.kaggle.com/datasets/shivamb/netflix-shows
