# 📌 MVP - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP of sprint 1 aims to present the key analyses and data extracted from the 2020 to 2024 dataset, in an initial form without extensive filtering. This is intended to provide the client with a preliminary overview of the material collected so far.

- *What hypothesis will be validated?*

The hypothesis that presenting the initial analyses and extracted data is sufficient to generate an initial understanding and guide the next steps of the project will be validated.

- *What value will be delivered to the end user?*

A clear and structured summary of the preliminary analyses will be delivered, enabling the user to validate the progress of the work and plan the next actions.

---

## 📝 Solution Description
- Presentation of the key analyses and data extracted from the dataset, without detailed filtering.
- Structuring the material to ensure the client understands the current stage of the project.
- Limitations: absence of the dashboard at this stage, with a focus on the initial exploratory work.

---

## 👥 Personas / Target Users
- **Client:** Seeks a clear and objective view of the initial landscape of shipments and the collected data to understand the current context and support the planning of future strategic actions.
- **Project Team:** Needs to validate the quality, consistency, and content of the extracted data to ensure the dataset is suitable before advancing to more in-depth analyses and the development of the dashboard.

---

## 🔑User Stories (MVP Backlog)
| ID  | User Story                                                                 | Prioridade | Partner Requirement|
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | As an analyst, I will collect and filter data from 2020 to 2024 to ensure the information is ready for future analysis         | High      | 5    |
| US2 | As an analyst, I will develop a draft of the home screen with key indicators to have a clear and objective view of what the final Dashboard version will look like         | Medium     | 1  |
| US3 | As an analyst, I will select specific products for deep data analysis         | Low      | 1   |
| US4 | As an analyst, I will develop a Python code to unify the data that will be used for data analysis         | High     | 5   |

---

## 📅 Related Sprint(s)
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01 | Spreadsheets with data extracted from 2020 to 2024 | Completed |
| 01 | Key shipments to be worked on | Completed |
| 01 | Initial code structured in Colab | Completed |
| 01 | Initial analyses | Completed |
| 01 | Dashboard prototype | Completed |
| 01 | PowerPoint presentation | Completed |
| 01 | Structured GitHub repository | In progress 

---

## 📊 Acceptance Criteria
- The MVP should allow the user to view the initial analyses and the data extracted from the dataset, without complex filtering or manipulations.
- The system should record the progress of the work and the content presented to the client.
- Collected metrics: feedback on the clarity of the analyses and understanding of the presented data.

---

## 📈 Validation Metrics
- Number of users (internal and clients) who reviewed and approved the initial analyses.
- Qualitative feedback regarding the usefulness and understanding of the presented information.
- Business indicators: client alignment with the initial scope for the next stages.

---

## 🚀 Next Steps
- Refine the analyses based on the feedback received.
- Develop the initial dashboard for interactive data visualization.
- Include filters and more advanced analytical features in the next cycle.

---

## 📂 Attachments / Evidence
#### Presentation

> The slide provides the project introduction, outlines the activities undertaken during the first sprint, presents the initial data collected, and includes the preliminary draft of the dashboard under development.

[Click here](MVP/Files/Sprit1_presentation.pdf)
  
#### Initial code developed

> The developed code is designed to process and organize port data from 2020 to 2024. The implemented structure consolidates information on cargo handled, weight in kilograms, and other relevant variables for the analysis. This initial processing serves as the foundation for building indicators, conducting port comparisons, and subsequently applying analytical models such as DEA, ensuring consistency and reliability in the results obtained.

[Click here](https://colab.research.google.com/drive/1nxS1R6oM4fPLr0s1wSfmPDeEyWlyZVY7?usp=sharing)   

#### Quantity of cagro movements

> The table compiles data on cargo handled between 2020 and 2024, presenting the name of each cargo along with its full description. In addition, it displays the quantities moved over the years, enabling the analysis of historical trends and the identification of logistical behavior patterns within the port sector.

[Click here](Files/CD_moviment.pdf)
