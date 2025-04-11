# 🧠 Hacker News Post Analysis

This project analyzes a dataset of submissions to the popular technology site [Hacker News](https://news.ycombinator.com/), aiming to explore user interaction patterns through the number of comments on different types of posts.

📍 **Repository:** [github.com/memetcircus/hacker_news_post_analyze](https://github.com/memetcircus/hacker_news_post_analyze)

---

## 📌 Objectives

The analysis focuses on answering two main questions:

1. **Do "Ask HN" or "Show HN" posts receive more comments on average?**
2. **Does the time a post is created influence the number of comments it receives?**

---

## 📊 Dataset Summary

We're using a downsampled version of the original Hacker News dataset. The dataset was filtered to include only posts that received at least one comment, then randomly sampled to approximately 20,000 entries.

### 📁 Dataset File

- **File:** `hacker_news.csv`
- **How to access:** Available in the Jupyter Notebook environment under `File -> Open -> hacker_news.csv -> File -> Download`

### 🔢 Columns

| Column Name   | Description |
|---------------|-------------|
| `id`          | Unique ID of the post |
| `title`       | Post title |
| `url`         | URL linked in the post (if any) |
| `num_points`  | Points = upvotes - downvotes |
| `num_comments`| Total comments received |
| `author`      | Username of the poster |
| `created_at`  | Timestamp of submission |

---

## 💡 Post Types Analyzed

The dataset includes two special post types:

- **Ask HN:** Posts where users ask the Hacker News community a question  
  - Example: *Ask HN: How to improve my personal website?*
- **Show HN:** Posts where users showcase a project, product, or tool  
  - Example: *Show HN: Shanhu.io, a programming playground powered by e8vm*

These categories are compared in terms of average comment count and time-based trends.



