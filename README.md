<center><img src="image/netflix.jpg"></center>

# 🎞️ Netflix: Movie Analysis

## 📘 Overview
**Netflix**, founded in 1997, started as a DVD rental service before evolving into one of the world’s largest streaming platforms. Today, it serves millions of subscribers across the globe, offering a wide range of movies, TV shows, documentaries, and original content. With its vast entertainment library and global reach, Netflix not only transformed how people consume media but also provides a valuable dataset for analyzing trends in the entertainment industry.

This project analyzes **Netflix movies released between year 2000 to 2010** using Python, Pandas, and Matplotlib. The goal is to uncover patterns in genres, durations, and overall movie distribution during this decade.

---

## 💾 Dataset
The dataset **`netflix_data.csv`** contains following information:
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

---

## 📈 Exploratory Data Analysis (EDA)
These were the steps performed to acquire the insights:

1. **Filtering** → Subsetted the data to keep only movies released between year 2000 to 2010.  
2. **Duration Categorization** → Movies were labeled as:  
   - `Short` (< 90 minutes)
   - `Medium` (< 180 minutes)  
   - `Long` (≥ 180 minutes)  
3. **Genre Distribution** → Counted and visualized the number of movies per genre.  
4. **Duration Distribution** → Counted and visualized movies by duration category.  

---

## 📊 Visualizations
- **Movies by Genre (2000–2010)**  
  A bar chart showing the number of movies produced in each genre.  

- **Movies by Duration (2000–2010)**  
  A bar chart displaying the distribution of movies by length (short, medium, long).  

---

## 🔍 Key Findings
- **Genre Popularity**: The dataset shows a clear concentration in specific genres, with some genre dominating the movie production.  
- **Duration Trends**: Medium-length movies (< 180 minutes) were by far the most common, followed by short-length movies (< 90 minutes) and a few long-length movies (≥ 180 minutes).  
- **Most Preferred Type**: By combining the top genre with the most frequent duration, the **most preferred movie type** of the decade is identified.

---

## 🧩 Technologies Used
- **Python**  
- **Pandas** → Data cleaning and filtering  
- **NumPy** → Logical operations for year filtering  
- **Matplotlib** → Bar charts for genre and duration analysis  
