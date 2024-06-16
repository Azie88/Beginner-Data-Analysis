# Beginner Data Analytics -- Indian Start-up Funding Analysis 🇮🇳 :money_with_wings:
![Punjabi Businessmen](https://github.com/Azie88/LP1-Data-Analysis/assets/101363399/cb0f1d49-3d72-4b74-ae74-48c3d83a96f5)



This project involved using the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to analyze data on startup growth, funding patterns, success rates, regional concentration, and market penetration of the Indian Startup Ecosystem between **2018 and 2021**.

The objective, as a data analyst, was to draw insights on the available data from 4 tables and give actionable insights and recommendations to our team that, hypothetically speaking, wants to venture into the Indian startup market. The project utilized advanced statistical techniques and visualization tools to draw meaningful conclusions and present our findings effectively.


## Project Links :link:

| Jupyter Notebook | Published Article | PowerBi Dashboard |
|------|-------------------|-------------------|
| <a href="https://github.com/Azie88/LP1-Data-Analysis/blob/main/Project_notebook.ipynb">Notebook | <a href="https://medium.com/@obandoandrew8/beginner-data-analytics-indian-startup-ecosystem-dataset-2018-2021-e4a5a2fb5516">Medium Article</a> | <a href="https://app.powerbi.com/view?r=eyJrIjoiZjFiMjUyNTAtYTBlOC00Njk3LWI4OWUtZWI3MWI0YjMwMDVlIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9">PowerBI Dashboard</a> |


## Table of Contents 🔖
- [Project Links](#project-links-link)
- [Dataset](#dataset-information_source)
- [Some Tools Used For The Project](#some-tools-used-for-the-project-toolbox)
- [Dataset](#dataset-information_source)
- [Process](#process)
- [Project Structure](#project-structure-open_file_folder)
- [Key Insights](#key-insights-chart_with_upwards_trend)
- [Dashboard](#power-bi-dashboard-tv)
- [How To Use This Repository](#how-to-use-the-repository)
- [Author](#author-writing_hand)


## Dataset :information_source:

- **Company/Brand**: Name of the company/start-up

- **Sector**: Sector of service

- **What it does**: Description about Company

- **Investor**: Investors

- **Amount(\$)**: Raised fund

- **Stage**: Round of funding reached

- **Year**: The year of funding


## Some Tools Used For The Project :toolbox:

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="45" height="45"/>
</p>



## Process

- Pull data from remote database with pyodbc; save as csv files

- Develop questions and a hypothesis to base analysis of the project on

- Understand the data and make decisions on how to process the data

- Data preprocessing, cleaning and merging- The data was very messy and 90% of the project involved cleaning and making the data ready for analysis and visualizations

- Visualise the data with seaborn and matplotlib.pyplot

- Created a PowerBI dashboard with the visualizations

- Wrote a medium article and briefly described the process, findings and recommendations



## Project Structure :open_file_folder:

- `Dataset/`: Contains the dataset used for analysis.
- `.gitignore`: Holds files to be ignored by Git.
- `LICENSE`: Project license.
- `Project_notebook.ipynb`: The jupyter notebook with data cleaning, EDA and visualizations
- `README.md`: Project overview, links, highlights, and information.
- `requirements.txt`: Required libraries & packages



## Key Insights :chart_with_upwards_trend:

1. Top sectors in indian startup ecosystem are **Fintech**, **Retail**, **Edtech**, **Tech** and **E-commerce**.
2. **Bangalore** has the most startups. It seems to be the emerging city with the top sectors being **Retail**, **Food Delivery**, **Innovation Management** and **FinTech**
3. **Mumbai** is the big city with the big money investments, with leading sectors being **Fintech**, **Retail** and a **Multinational conglomerate**
4. There seems to be high demand for finance solutions and shopping experiences. Retail was popular during the pandemic as more people were probably shopping from home.

The Indian startup ecosystem is a vibrant and influential force in the global market. This project provides valuable insights into funding patterns and industry preferences. By leveraging this information, stakeholders can make informed decisions and contribute to the growth and success of startups in India.



## Power BI Dashboard :tv:
![Dashboard](https://github.com/Azie88/LP1-Data-Analysis/assets/101363399/82c784e7-f817-4642-905c-a5f7d2ed724f)

<a href="https://app.powerbi.com/view?r=eyJrIjoiZjFiMjUyNTAtYTBlOC00Njk3LWI4OWUtZWI3MWI0YjMwMDVlIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9">PowerBI Dashboard</a>

## How to Use The Repository

You need to have [`Python 3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: repository_name> ...`

1. Clone this repository: `git clone https://github.com/Azie88/LP1-Data-Analysis.git`
2. On your IDE, create A Virtual Environment and Install the required packages for the project:

- Windows:
        
        python -m venv venv; 
        venv\Scripts\activate; 
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

## Author :writing_hand:

Andrew Obando

<a href="https://www.linkedin.com/in/andrewobando/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Andrew Obando | LinkedIn"/></a>

<a href="https://medium.com/@obandoandrew8">
![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)
</a>

-----

Feel free to star ⭐ this repository if you find it helpful!
