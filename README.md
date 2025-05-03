# SAL_BW_Project2

ScrapifyQuotes is a collaborative project aimed at extracting and analyzing inspirational quotes from QuotesToScrape.com. We built a complete data pipeline using Python for web scraping, SQL and Pandas for data structuring and analysis, and various visualization libraries to uncover patterns and present insights. Beyond technical execution, the project emphasized teamwork, version control, and real-world data team practices.

🧠 Problem Statement
We sought to answer key analytical questions using real-world web data:

Which authors are most frequently quoted?

What are the most common themes (tags) in the quotes?

How does quote length vary across authors?

Are there notable patterns or outliers in the data?

How can scraped data be efficiently stored and queried?

🔧 Tech Stack
Task	Tools Used
Web Scraping	Python, BeautifulSoup, Requests
Data Cleaning & Storage	Pandas, CSV, SQL
Data Analysis	SQL Queries, Pandas
Visualization	Matplotlib, Seaborn, WordCloud
Collaboration	GitHub, Juypter, Zoom

📊 Project Workflow
🔹 Web Scraping (by Pranali)
Scraped multiple paginated pages using requests and BeautifulSoup.

Extracted quote text, author names, and associated tags.

Exported the cleaned data to CSV for further processing.

🔹 SQL Design & Querying (by Devesh)
Created a relational database schema with tables for quotes, authors, and tags.

Managed many-to-many relationships via a bridge table.

Wrote SQL queries to identify top authors, common tags, and quote distributions.

🔹 Exploratory Data Analysis (by Anupam)
Structured and cleaned the dataset using Pandas.

Visualized data using bar charts, word clouds, histograms, and box plots.

Derived insights such as author trends, quote length distributions, and thematic focus.

🤝 Team Collaboration
Active collaboration through code reviews, pair programming, and planning meetings.

Conducted a Q&A session to reinforce understanding and communication.

Used GitHub for version control and coordinated tasks via regular team syncs.

🔍 Key Insights
Top Authors: Albert Einstein and Jane Austen appeared most frequently.

Popular Tags: “love,” “life,” and “inspirational” dominated.

Quote Length: Most quotes were concise, making them impactful and shareable.

Thematic Overlap: Some authors consistently used similar tags, reflecting a strong thematic identity.

💡 Learnings
Technical: Gained hands-on experience in scraping, relational modeling, and data storytelling.

Collaboration: Improved skills in teamwork, code reviews, and Git-based workflows.

Time Management: Balanced coding, documentation, and meetings under tight deadlines.

🧑‍💻 Contributors
Pranali: Project Lead, Web Scraping, Data Structuring

Devesh: SQL Design, Query Optimization

Anupam: EDA & Visualization, Documentation
