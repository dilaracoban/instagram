# Days of my Period and Evolution of Instagram Posting Patterns

## Objective
I love using social media as my diary. I had this private account just for my friends where I posted smallest details of my life along with memes, my blog posts, biology olympiads tricks, YKS (higher education exam) prep tips, my research on molecules etc. I always knew that there are some months / or days of months where I just post, and I believe that it is possible to find strong correlations between my mood and posting behaviors. My period affects my mental situation and stress conditions, which presumably affects in posting behavior. This project aims to analyze how my Instagram posting frequency and content types have evolved since 2017, identifying trends related to period data, seasons, events, and personal milestones such as holidays, travels, and exam periods.

## Motivation
Understanding personal social media habits provides insights into how external factors like hormonal raise and periods, seasons, events, and stress influence online activity. This project aims to uncover meaningful patterns and trends that reflect changes in personal behavior and preferences over time.

## Research Questions
1. How has my Instagram posting frequency changed over time?
2. What content types (e.g., travel photos, holiday updates, exam stress posts) are predominant in different time periods?
3. Are there seasonal trends in posting frequency, such as increased activity during summer or holidays?
4. How do life events (e.g., period, stomach ache, travels, exams) impact the type and frequency of posts?

## Planned Data Collection
- **Source:** Instagram’s data export feature for personal accounts.
- **Source:** Period data from samsung health, Flo app, and my diaries combined, manually to some extent. Will be stored in a pandas dataframe.
- **Content:** Extract metadata such as timestamps, captions, hashtags, and archived post information.

## Proposed Methodology
### 1. Data Preprocessing
- Parse Instagram data into a structured dataset with fields like `date`, `time`, `caption`, `hashtags`, and `content type`.

### 2. Exploratory Data Analysis (EDA)
- Analyze posting frequency by year, month, and day.
- Identify periods of increased activity and link them to specific events or contexts (e.g., summer holidays, exam periods).

### 3. Content Categorization
- Either use Natural Language Processing (NLP) to analyze captions and hashtags or use an image recognition AI to describe content in pictures. (I do not remember some of my posts, therefore some captions should be empty)
- Classify posts into categories such as travel, holiday, academic, fun, opinions, teenage life and miscellaneous.

### 4. Seasonal and Event-Based Trends
- Perform time-series analysis to identify seasonal patterns.
- Correlate posting spikes with personal events (e.g., ovulation, period, travel logs, exam periods).

### 5. Visualizations
- Trends over time (line graphs for posting frequency) over time of the female month
- Content distribution for seasons (pie charts or bar plots for categories).
- Seasonal heatmaps to show activity by month and year.
