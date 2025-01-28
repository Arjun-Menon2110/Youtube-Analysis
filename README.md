# YouTube Channel Analysis

This project analyzes data from 1000 of the most subscribed YouTube channels to uncover patterns, trends, and relationships between various metrics such as subscriber count, video views, video count, content categories, and channel growth over time.

## Project Structure

### 1. Data Loading and Cleaning
- Loaded data from `most_subscribed_youtube_channels.csv`.
- Cleaned and converted columns like `subscribers`, `video views`, and `video count` to numerical formats.
- Filled missing values in the `category` column with "NoData".
- Removed duplicate records to ensure data quality.

### 2. Key Analyses and Findings

#### **Analysis 1: Rank vs. Subscribers**
- Investigated the relationship between a channel's rank and its subscriber count using scatter plots and correlation.
- **Findings:**
  - A strong inverse relationship exists between rank and subscriber count.
  - Top-ranked channels hold significantly higher subscriber numbers, following a power-law distribution.

#### **Analysis 2: Category Subscriber Distribution**
- Compared median subscriber counts across content categories.
- **Findings:**
  - "Trailers" had the highest median subscribers, followed by "Activism" and "Movies".
  - Entertainment-centric categories dominate while niche categories like "Travel & Events" attract fewer subscribers.

#### **Analysis 3: Newer Channels vs. Growth**
- Explored growth patterns of channels based on their starting year.
- **Findings:**
  - Channels started after 2010 show faster growth, attributed to improved algorithms and increased global audience reach.
  - Older channels (pre-2000) exhibit slower growth rates.

#### **Analysis 4: Video Count vs. Subscribers**
- Examined if channels with more uploaded videos have higher subscriber counts.
- **Findings:**
  - Weak positive correlation (Pearson coefficient ≈ 0.07) between video count and subscribers.
  - Quality and engagement, rather than quantity, are more significant factors.

#### **Analysis 5: Top Channels by Category**
- Identified the top 3 channels in each category based on subscriber count.
- **Findings:**
  - High-ranking channels tend to specialize in single categories.
  - Examples: "T-Series" (Music), "PewDiePie" (Gaming), "SET India" (Shows).

#### **Analysis 6: Average Video Views by Category**
- Analyzed the average video views across different content categories.
- **Findings:**
  - "Trailers" and "Movies" lead in average video views, driven by large audiences for entertainment content.

#### **Analysis 7: Category Trends Over Time**
- Investigated how the distribution of top 100 channels by category changed over time.
- **Findings:**
  - Categories like "Entertainment" and "Music" have consistently grown post-2010.
  - Early dominance of "Gaming" and "Technology" gave way to broader categories.

### 3. Visualizations
- Plotted histograms, scatter plots, box plots, and heatmaps to support the analysis.
- Examples:
  - Distribution of subscribers across ranks.
  - Count plots for content categories.
  - Correlation matrix heatmap.

### 4. Tools and Libraries
- **Python**: Main programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Scipy**: Statistical analysis.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Arjun-Menon2110/Youtube-Analysis.git
