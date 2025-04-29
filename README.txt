Empirical Project: How long will the Premier League be the 'Best League' in the world?


This project explores the Premier League's dominance as a top football league globally and how it is fueled by its unmatched financial investment, strong player acquisitions, and global appeal. Despite potential challenges from other leagues, its financial strength and competitive depth ensure its continued position at the top for the foreseeable future.

AUTHOR:
**PADDY WARREN**
GITHUB: https://github.com/padpad2004/blog

Project folder structure:


PL_BLOG_PROJECT/
│
├── PL_BLOG/                # Final blog post in PDF format
├── CSV_FILES/              # Raw CSV files
├── NOTEBOOK/               # Python notebook for scraping, cleaning and analysis - also includes PDF format
├── OUTPUTS/                # Saved plots and visual outputs
├── README.md               # Project overview and setup instructions (this doc)
├── Requirments.txt         # Python dependencies for easy replication
├── AI_DECLARATION/         # Declaring the use of AI
└── BLOG_URL.txt/           # How to find the blog online, in HackerMD


## How to Run:

1. Clone the repository:
   git clone https://github.com/padpad2004/blog
   cd blog

2. Set up your virtual environment:
   python -m venv venv  
   (On Mac/Linux: source venv/bin/activate)  
   (On Windows: venv\Scripts\activate)

3. Install dependencies:
   pip install -r requirements.txt

4. Run the notebook:
   - Ensure no errors in code when scraping the data, if so use the saved CSV files in the CSV_FILES folder. 


Project Information:
- Web Scraping: Selenium + BeautifulSoup used to scrape data from https://www.transfermarkt.co.uk/
- Data Cleaning: Removed headings and unneeded data to create better, more accurate outputs
- Outputs created:
	- Average of clubs values in Europes top 5 leagues (2011-2024)
	- Top 6 vs Bottom 6 Club values in the Premier League (2011-2024)
	- Average club expenditure by league with average arrivals (2011-2024)
	- Average % throughout the year of Stadium Attendance vs Stadium Capacity (2023)
- GIT: I used git to track changes to my blog_v1.ipynb file throughout the creation of my blog. The git link https://github.com/padpad2004/blog

Tools and Libraries used can be found in the requirments.txt document which allows you to install all the dependencies needed. 