# AI-Based Job Market Intelligence System 🤖

A Streamlit-powered application to scrape, analyze, and visualize the AI job market in Germany and the EU. The system focuses on SAP-related roles and provides insights into job trends, skill demand, and recommendations.

---

## Features
- Scrape SAP job listings from multiple pages
- View latest scraped jobs in a clean table
- Analyze skill demand from job descriptions
- Cluster similar job postings
- Recommend in-demand skills for career growth
- Process and clean job data for analytics

---

## Folder Structure

├── app/
│ └── app.py # Streamlit application
├── data/
│ ├── jobs.csv # Raw job data
│ ├── jobs_live.csv # Latest scraped jobs
│ └── jobs_processed.csv # Cleaned & processed job data
├── scraping/
│ ├── scrape_jobs.py # Job scraping script
│ └── pycache/ # Python cache files
├── cluster_jobs.py # Clustering similar job posts
├── extract_skills.py # Skill extraction from job descriptions
├── process_data.py # Data cleaning & preprocessing
├── recommend_skills.py # Skill recommendation engine
├── skill_demand.py # Skill demand analytics
└── README.md # Project documentation


---

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-job-market-intelligence.git
cd ai-job-market-intelligence

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app/app.py
