# 📌 MVP - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP for Sprint 2 aims to deepen the analysis of port operations, focusing specifically on three priority cargo types — Steel, Cellulose, and Fertilizers — while maintaining a general overview of logistics performance from 2020 to 2024.
This stage seeks to deliver a more refined and targeted analysis to the client, with improved visualizations that enhance the understanding of port movements and the main origin-destination routes.

- *What hypothesis will be validated?*

The hypothesis to be validated is that segmenting the analysis by cargo type and adding interactive visualizations and filters will lead to a better understanding of logistical and operational behaviors, generating more strategic insights for the client.

- *What value will be delivered to the end user?*

The user will receive a set of analyses and visualizations highlighting key trends, most relevant ports, and logistics flows. The ability to filter data by year, origin, and destination will support strategic decision-making and operational planning.

---

## 📝 Solution Description
- Review and restructuring of the original dataset, generating a compiled file with the most essential and consistent information.
- Creation of visualizations focused on port activity, main ports, and behavior by cargo type. Implementation of interactive filters (year, origin, destination) to enhance data exploration and navigation.
- Analytical focus on three main cargo categories: Steel, Cellulose, and Fertilizers.
- Continuation of dashboard development, to be finalized in the next sprint.
- Limitations: the final interactive dashboard is still under construction; analyses at this stage are exploratory.

---

## 👥 Personas / Target Users
- **Client:** Seeks a clear and objective view of port logistics behavior, with emphasis on the three priority cargo types (Steel, Cellulose, Fertilizers), to support strategic decision-making in transportation, storage, and operations.
- **Project Team:** Needs to validate the consistency of the new compiled dataset and ensure that the visualizations and filters provide a coherent and accurate representation of operational realities before building the final dashboard.

---

## 🔑User Stories (MVP Backlog)
| ID  | User Story                                                                 | Prioridade | Partner Requirement|
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | As an analyst, I want to visualize the main reasons for operational stoppages to identify the major factors that impact productivity  | High      | 2    |
| US2 | As an analyst, I want to visualize which ports transport the most cargo to identify which ones are most relevant in port movement      | High     | 4  |
| US3 | As an analyst, I want to visualize how many port operations are performed per month at each port to understand the volume of operational activities       | Medium      | 4   |
| US4 | As an analyst, I will identify and analyze which were the most transported cargoes in the established period.        | Medium   | 2   |

---

## 📅 Related Sprint(s)
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 02 | Compiled and validated dataset with essential information | Completed |
| 02 | Exploratory visualizations created (overall and by cargo type) | Completed |
| 02 | Implementation of filters (year, origin, destination) | Completed |
| 02 | Consolidated analytical report | Completed |
| 02 | Dashboard initial | Completed |
| 02 | Structured GitHub repository | In progress 

---

## 📊 Acceptance Criteria

- The MVP must allow users to view segmented analyses by cargo type (Steel, Cellulose, and Fertilizers).
- The compiled dataset must contain consistent and cleaned data.
- Visualizations must include filters for year, origin, and destination.
- The client must be able to easily interpret trends and movements presented.
- Positive feedback should be obtained regarding the clarity and relevance of the analyses.

---

## 📈 Validation Metrics
- Validation of the compiled dataset by both the technical team and the client.
- Number of visualizations implemented and tested.
- Qualitative feedback from the client on usefulness and clarity of insights.
- Level of alignment between Sprint 2 deliverables and the client’s strategic objectives.

---

## 🚀 Next Steps
- Incorporate formal client feedback (after Sprint 2 presentation).
- Develop the interactive dashboard with full filter integration.
- Expand comparative analyses between ports and cargo types.
- Apply analytical models and performance indicators (e.g., DEA).Prepare the consolidated Sprint 3 delivery with a functional dashboard and finalized documentation.

---

## 📂 Attachments / Evidence

#### Compiled Dataset

> Updated file containing essential information from 2020 to 2024, consolidating port, cargo, and movement data.

[📎 Click here](link de todos os dados compilados)


#### Updated Code

>Revised Python code adapted for cleaning, consolidation, and updating of port operation data.

[📎 Click here](https://colab.research.google.com/drive/1vFg2igoW8Bx3mTpofzVIToleJ7FgzLXf?usp=sharing)
[📎 Click here](https://colab.research.google.com/drive/1joklk2VO325w9M0ARoECDxMn3niDL73h?usp=sharing)

#### Created Visualizations

> Graphs and tables developed to represent total movements, most active ports, and cargo-type analysis. Filters for year, origin, and destination have been implemented.

[📎 Click here](dashboard e apresentação)
