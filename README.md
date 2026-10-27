# 📊 Instagram Engagement Analysis – Alfido Tech

## 📌 Project Overview

The **Instagram Engagement Analysis** project analyzes Instagram data to understand audience engagement, content performance, hashtag effectiveness, and follower activity.

The project uses Python and data analysis libraries to explore likes, comments, posts, hashtags, and follower relationships. The findings are used to suggest data-driven strategies for improving Instagram engagement for **Alfido Tech**.

## 🎯 Objectives

* Analyze Instagram likes and comments.
* Calculate post-level engagement metrics.
* Identify hashtags associated with higher engagement.
* Compare performance across photos, videos, and carousels.
* Explore posting patterns and follower activity.
* Provide actionable recommendations for improving Instagram content strategy.

## 📂 Dataset

**Dataset source:** [Instagram Dataset – Kaggle](https://www.kaggle.com/datasets/bhanupratapbiswas/instgram)

The dataset contains seven CSV files:

| File             | Description                              |
| ---------------- | ---------------------------------------- |
| `likes.csv`      | Instagram likes and related information  |
| `comments.csv`   | User comments on posts                   |
| `photos.csv`     | Post details and content types           |
| `users.csv`      | User account information                 |
| `follows.csv`    | Follower and followee relationships      |
| `tags.csv`       | Hashtag information                      |
| `photo_tags.csv` | Relationships between posts and hashtags |

## 🛠️ Technologies Used

* **Python** – Data analysis
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical calculations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualizations
* **Google Colab** – Development environment
* **Jupyter Notebook** – Interactive analysis

## 🔍 Project Workflow

1. **Data Loading:** Imported the seven CSV files into Python.
2. **Data Cleaning:** Standardized column names, converted date columns, and checked for duplicate records and missing values.
3. **Engagement Analysis:** Calculated likes, comments, total interactions, and post-level engagement rates.
4. **Posting Pattern Analysis:** Examined posting days and hours.
5. **Hashtag Analysis:** Compared hashtag usage and average engagement.
6. **Content Type Analysis:** Compared photos, videos, and carousel posts.
7. **Follower Activity Analysis:** Examined follower relationships, account status, verification status, and the relationship between post count and follower count.
8. **Strategy Development:** Prepared recommendations based on the analysis.

## 📈 Key Findings

* **257 posts** were analyzed.
* **8,782 likes** were recorded.
* **7,488 comments** were recorded.
* **16,270 total interactions** were observed across likes and comments.
* Photo posts had the highest average interactions among the analyzed content types.
* Video posts performed similarly to photo posts in average interactions.
* Carousel posts had slightly lower average interactions in this dataset.
* Engagement differences across hashtag counts were small.
* The correlation between post count and follower count was approximately **0.20**, indicating a weak positive relationship.
* All posts had the same recorded posting timestamp, so the dataset cannot reliably identify the best posting day or hour.

*Note: These findings describe the available dataset. They should not be interpreted as guaranteed outcomes for Alfido Tech's own Instagram account.*

## 💡 Recommendations

* Publish educational content about programming, technology, and software development.
* Experiment with Reels, carousel posts, and static images.
* Test relevant hashtags such as `#AlfidoTech`, `#Technology`, `#Coding`, `#SoftwareDevelopment`, and `#LearnToCode`.
* Encourage audience participation through polls, quizzes, questions, and discussions.
* Track reach, likes, comments, shares, saves, profile visits, and follower changes.
* Compare results regularly and adjust the content strategy based on actual Instagram Insights.
* Test different posting times because the dataset does not provide enough variation to determine an optimal schedule.

## ▶️ How to Run the Project

1. Download or clone the project repository.
2. Download the dataset from Kaggle.
3. Open Google Colab or Jupyter Notebook.
4. Upload the dataset ZIP file.
5. Run the notebook cells in order.
6. Review the analysis tables, visualizations, findings, and recommendations.

### Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## 📁 Suggested Project Structure

```text
Instagram-Engagement-Analysis/
│
├── Instagram_Engagement_Analysis.ipynb
├── README.md
├── Instagram_Engagement_Strategy.pdf
└── dataset/
    ├── likes.csv
    ├── comments.csv
    ├── photos.csv
    ├── users.csv
    ├── follows.csv
    ├── tags.csv
    └── photo_tags.csv
```

*The PDF and dataset folder are optional until you add those files to the repository.*

## 👨‍💻 Author

**Gali Shanmuk**

GitHub: [@Shanmuk1920](https://github.com/Shanmuk1920)

## 🏢 Project Context

**Project:** Instagram Engagement Analysis
**Organization:** Alfido Tech
**Purpose:** Data analysis and social media engagement strategy

---

⭐ If you find this project useful, consider giving the repository a star!
