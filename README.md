Vanguard A/B Test

Project Overview

This project analyzes the impact of a new digital interface (UI) for Vanguard customers using A/B testing.

The main goal is to determine whether the Test version improves completion rates, session duration, and error rates across different user segments.

Analysis includes statistical tests, KPI evaluation, step-level insights, and interactive visualizations in Tableau.

Repository Structure

vanguard-ab-test/
│
├── notebooks/
│   └── Testing_hypothesis_dfpivot2_2.ipynb
│   └── KPIs_Analysis_dfpivot.ipynb
│   └── Analysis_df_abtest.ipynb
│
├── data/
│   └── raw/
    │   ├── df_final_web_data_pt_2.txt
    │   ├── df_final_web_data_pt_1.txt
    │   └── df_final_experiment_clients.txt
    │   └── df_final_demo.txt
   └── processed/
    │   ├── tableau_steps_by_age.csv
    │   ├── tableau_steps_by_variation.csv
    │   └── sanity_steps_check.csv
    │   └── tableau_steps_by_tenure.csv

├── tableau/
│   └── vanguard_dashboard.twbx      # Tableau dashboard for KPIs
│
├── slides/
│   └── vanguard_ab_test_presentation.pdf
│
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies


Deliverables

- Working Code: All Python scripts and Jupyter notebooks are provided in src/ and notebooks/.
- Functions: Defined in .py files, used in analysis.
- Data: All source files are in data/.
- Tableau Dashboard: Located in tableau/, includes interactive visualizations of KPIs and step-level insights.
- Presentation Slides: PDF in slides/ folder, also includes URL to the interactive Tableau dashboard.
- README Documentation: This file explains the project, code, data, and how to reproduce results.
- Repository URL: Each student must submit their own repository link in the Student Portal.
- Data Sources
- Client Profiles, Digital Footprints, and Experiment Roster datasets provided for the project.
- Include links to original sources if applicable.