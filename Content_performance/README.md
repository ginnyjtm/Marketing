# Instagram Content Performance Analysis & Strategy

## Objective
This a part of project focused on increasing Instagram content performance and shifting audience demographics by implementing a 1-month content strategy. The project aimed to grow content views and followers by 15%, gain English-speaking audiences in the GTA, and improve content alignment through targeted Reels and storytelling techniques.


## 📊 Sample Dataset (Anonymized)

The dataset is a sanitized version of real social media performance data.  
To protect privacy, identifying fields such as post captions and image links were removed.  
Only the following columns were retained:

| Column         | Description                                        |
|----------------|----------------------------------------------------|
| Post ID        | Unique identifier for the post                     |
| Category       | Content type (e.g., Relationships, Self-Growth)    |
| Duration (sec) | Length of the post (Reels only)                    |
| Publish Time   | Time of day the post was published                 |
| Post Type      | Format (Reel, Carousel, Image)                     |
| Date           | Date the content was posted                        |
| Views          | Total views per post                               |
| Reach          | Unique accounts reached                            |
| Likes          | Number of likes                                    |
| Shares         | Number of shares                                   |
| Follows        | Follows attributed to the post                     |
| Comments       | Number of comments                                 |
| Saves          | Number of saves                                    |

> 🔒 *Note: All data is anonymized and used for educational/portfolio purposes only.*

## Methodology
### 1. Data Preprocessing
- **Filtering Columns:** Retained only relevant columns for analysis: `Duration (sec)`, `Views`, `Reach`, `Likes`, `Shares`, `Follows`, `Comments`, and `Saves`.
- **Data Cleaning:** Removed null or invalid entries to ensure consistency in calculations.
- **Feature Engineering:** Created an `Engagement` metric by summing:
  - Likes
  - Comments
  - Shares
  - Saves
  - *(Follows were included optionally for deeper analysis.)*

### 2. Engagement Rate Calculation
Two different engagement rate formulas were applied to evaluate content performance from distinct perspectives:
1. **Reach-based Engagement Rate**
- Measures the percentage of users who engaged with the content out of all who saw it.
2. **View-based Engagement Rate**
- Measures the percentage of engagements relative to the number of times the content was viewed.

### 3. Visualization
- Created scatter plots to illustrate the distribution of Reach, Views, and Engagement Rate.
- Added a trend line to identify general performance patterns.
- Outliers were highlighted to examine posts with unusually high or low performance.

## Key Findings
*(Replace this placeholder with your summarized insights once analysis is complete — for example:)*  
- Posts with shorter durations tend to have higher engagement rates.
- A small number of posts received disproportionately high views compared to the majority.
- Engagement rates vary significantly between content categories.

## Tools & Technologies
- **Python**: Data processing and calculations.
- **Pandas**: Data cleaning and transformation.
- **Matplotlib**: Data visualization.
- **Jupyter Notebook**: Interactive analysis and documentation.

## How to Run This Project
1. Clone this repository:
git clone https://github.com/ginnyjtm/Marketing.git

2. Open the Jupyter Notebook:
jupyter notebook

3. Run each cell in order to reproduce the analysis.

## 📌 Key Insights

- Reels generated 98% of total follower growth.
- Relationship-themed Reels had the highest engagement and follower conversion.
- Self-Growth and Brand-Involved posts underperformed in follower acquisition but have potential with better targeting and structure.
- Thai-language content attracted high engagement but limited international growth potential.


## 🧠 Strategy Highlights

- **Target Audience Shift:** Focused on English-speaking, GTA-based viewers through content localization, relatable hooks, and strategic geo-tagging.
- **Reel-First Format:** Increased Reel output to 4–5 per week to maximize visibility and engagement.
- **Content Language:** Switched to English-first captions and audio, with optional Thai subtitles for transitional inclusivity.
- **Hashtag Strategy:** Local + emotional hashtags (e.g., `#TorontoLife`, `#MovingToCanada`, `#SelfGrowth`)
- **Performance Forecasting:** Used past engagement rates to model realistic reach/follower growth projections.


## 📂 Files Included

- `Instagram-jan-jun2025.csv` — Anonymized post-level dataset  
- `README.md` — Project summary and context  


## 👩‍💻 About Me

Hi! I'm Ginny — a data analyst with a full-stack dev background, a brain wired for data (INTJ-T ✌️), and a love for meaningful content strategies. This project reflects my passion for helping creators make smarter decisions with their data and align their content with the right audience.

## 📬 Let’s Connect

- [LinkedIn](https://www.linkedin.com/in/ginny-jutamat/)  
- [Portfolio Website](https://ginnyjutamat.com)  
- [Email](mailto:work.ginnysangka@gmail.com)

# Tags: Instagram Analytics · Social Media Strategy · Content Marketing · Audience Growth · Digital Marketing · Portfolio Project


