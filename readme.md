# Beginner Data Analytics -- Indian Start-up Funding Analysis 🇮🇳 🕴️
![flag-india](https://github.com/Azie88/LP1-Data-Analysis/assets/101363399/33d9e0c6-0b2a-42ce-8473-129932025fec)


This project involved using the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to analyze data on startup growth, funding patterns, success rates, regional concentration, and market penetration of the Indian Startup Ecosystem between **2018 and 2021**.

The objective, as a data analyst, was to draw insights on the available data from 4 tables and give actionable insights and recommendations to our team that, hypothetically speaking, wants to venture into the Indian startup market. The project utilized advanced statistical techniques and visualization tools to draw meaningful conclusions and present our findings effectively.


## Summary 📄

| Code | Name | Published Article | PowerBi Dashboard |
|------|------|-------------------|-------------------|
| LP1 | Indian Startup Funding Analysis | <a href="https://medium.com/@obandoandrew8/beginner-data-analytics-indian-startup-ecosystem-dataset-2018-2021-e4a5a2fb5516">Medium Article</a> | <a href="https://app.powerbi.com/view?r=eyJrIjoiZjFiMjUyNTAtYTBlOC00Njk3LWI4OWUtZWI3MWI0YjMwMDVlIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9">PowerBI Dashboard</a> |




## **Column names and description in Final Data:**

- **Company/Brand**: Name of the company/start-up

- **Sector**: Sector of service

- **What it does**: Description about Company

- **Investor**: Investors

- **Amount(\$)**: Raised fund

- **Stage**: Round of funding reached

- **Year**: The year of funding

<h2> Some Tools Used For The Project 🚀</h2>

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="45" height="45"/>
</p>



## Process 🪜

- Pull data from remote database with pyodbc; save as csv files

- Develop questions and a hypothesis to base analysis of the project on

- Understand the data and make decisions on how to process the data

- Data preprocessing, cleaning and merging- The data was very messy and 90% of the project involved cleaning and making the data ready for analysis and visualizations

- Visualise the data with seaborn and pyplot

- Created a PowerBI dashboard with the visualizations

- Wrote a medium article and briefly described the process, findings and recommendations



## Project Structure 📂

- `Dataset/`: Contains the dataset used for analysis.
- `.gitignore`: Holds files to be ignored by Git.
- `LICENSE`: Project license.
- `Project_notebook.ipynb`: The jupyter notebook with data cleaning, EDA and visualizations
- `README.md`: Project overview, links, highlights, and information.



## Key Insights :chart_with_upwards_trend:

1. India's startup ecosystem is positive and thriving with strong favor towards technological companies
2. Equal opportunities exist for non-technological sectors as well
3. Fintech and edtech sectors are particularly active in the Indian startup ecosystem
4. Mumbai is at the forefront of these developments in fintech and edtech sectors
5. Non-technical industries have a few large investments that skew the mean higher
6. Technical industries have a larger number of smaller investments, driving up the sum.

The Indian startup ecosystem is a vibrant and influential force in the global market. This project provides valuable insights into funding patterns and industry preferences. By leveraging this information, stakeholders can make informed decisions and contribute to the growth and success of startups in India.



## Dashboard 📺
![Dashboard](https://github.com/Azie88/LP1-Data-Analysis/assets/101363399/82c784e7-f817-4642-905c-a5f7d2ed724f)

## Getting Started🏁

You need to have [`Python 3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: repository_name> ...`

1. Clone this repository: `git clone https://github.com/Azie88/LP1-Data-Analysis.git`
2. On your IDE, create A Virtual Environment and Install the required packages for the project:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; 
        python -m pip install -q --upgrade pip; 
        python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; 
        source venv/bin/activate; 
        python -m pip install -q --upgrade pip; 
        python -m pip install -qr requirements.txt  

The two long command-lines have the same structure. They pipe multiple commands using the symbol ` ; ` but you can manually execute them one after the other.

- **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
- **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
- **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
- **Install the required libraries/packages** listed in the `requirements.txt` file so that they can be imported into the python script and notebook without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

3. Explore the Jupyter notebook for detailed steps and code execution.
4. Check out the Power BI dashboard for interactive visualizations.
5. Read the published article for a comprehensive understanding of the project.

## Author✍️

Andrew Obando

Connect with me on LinkedIn: [Andrew Obando](https://www.linkedin.com/in/andrewobando/)

---

Feel free to star ⭐ this repository if you find it helpful!
