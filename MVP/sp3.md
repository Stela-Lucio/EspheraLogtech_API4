# 📌 MVP - Port Operations Analysis

## 🎯 Objective of MVP
- *What problem does it solve?*

The MVP for Sprint 3 focuses on delivering the first fully functional version of the port operations dashboard, integrating all analyses developed so far. In this stage, the goal is to provide the client with a clear, interactive environment to explore logistics behavior, port performance, and cargo dynamics between 2020 and 2024.

- *What hypothesis will be validated?*

The hypothesis is that a consolidated dashboard—containing segmented analyses, efficiency metrics, DEA modeling, and operational stoppage insights—will enable the client to easily identify patterns, bottlenecks, and strategic opportunities in port logistics.

- *What value will be delivered to the end user?*

The user will receive an interactive and intuitive dashboard with four structured analytical views:

1. General Analysis
2. Cargo-Specific Analysis
3. Efficiency Analysis (including DEA results)
4. Operational Stoppage Analysis

These visualizations allow for better strategic planning, improved understanding of port behavior, and more informed decision-making.

---

## 📝 Solution Description
- Development of four interactive visualizations, each addressing a key analytical perspective:

1. Overall port movement and trends
2. Behavior by cargo type
3. Port efficiency analysis
4. Main causes of operational stoppages

- Implementation of DEA (Data Envelopment Analysis) to measure port efficiency, using berthing time relative to transported cargo as the primary criterion.
- Integration of the consolidated dataset into all visualizations.
- Refinement of the dashboard layout to improve navigation and clarity.
- Documentation of analytical processes and methodological choices.

Limitations:

- Advanced comparative models and additional KPIs will be expanded in the next sprint.
- Some parameters of the DEA model may require refinement after client feedback.

---

## 👥 Personas / Target Users
-  **Client:** Seeks a clear, objective, and interactive view of port performance to support strategic decisions in logistics operations.
- **Analysts & Planners:** Need detailed breakdowns of cargo performance, efficiency levels, and stoppage causes.
- **Project & Data Team:** Validate consistency, accuracy, and interpretability of the visual outputs before final delivery.

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

#### Updated Code

>Revised Python code adapted for cleaning, consolidation, and updating of port operation data.

[📎 Click here](https://colab.research.google.com/drive/1vFg2igoW8Bx3mTpofzVIToleJ7FgzLXf?usp=sharing)
[📎 Click here](https://colab.research.google.com/drive/1joklk2VO325w9M0ARoECDxMn3niDL73h?usp=sharing)

#### Created Visualizations

> Graphs and tables developed to represent total movements, most active ports, and cargo-type analysis. Filters for year, origin, and destination have been implemented.

[📎 Click here](dashboard)
