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
| US1 | As an analyst, I will use the DEA model to measure the efficiency of ports | High      | 1    |
| US2 | As an analyst, I will develop a functional dashboard with information on port efficiency based on processing times in Brazilian ports and specific sector data      | High     | 5  |
| US3 | As an analyst, I will evaluate operation times, focusing on locating which ports have longer waiting times and which are more agile in operation       | Medium      | 2   |
| US4 | As an analyst, I will use GitHub, Jira, and Google Colab tools for project development        | High   | 1   |

---

## 📅 Related Sprint(s)
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
[| 03 | Interactive Dashboard with 4 visualizations | Completed |
| 03 | Efficiency calculation via DEA model | Completed |
| 03 | Cleaned & corrected stoppages dataset | Completed |
| 03 | Presentation video | Completed |
| 03 | Structured GitHub repository | In progress ]

---

## 📊 Acceptance Criteria

- The dashboard must include four complete analytical views
- The DEA model must use berthing time vs. transported cargo as the efficiency criterion.
- Visualizations must clearly represent trends, performance patterns, and efficiency levels.
- The dataset must remain clean, consistent, and integrated into the dashboard.
- The client should be able to navigate and interpret the insights with ease.

---

## 📈 Validation Metrics
- Accuracy of DEA results and efficiency rankings.
- Number and stability of integrated visualizations.
- Client and internal team feedback on clarity and usability.
- Correct functioning of dashboard navigation and data linkage.
- Alignment between insights and the client's operational needs.

---

## 🚀 Next Steps
- Perform the final verification with the client to ensure the analyses and visualizations meet expectations.
- Apply final improvements and refinements based on the client’s feedback.
- Prepare all materials and visual outputs for the Solution Fair presentation, organizing the content clearly and professionally.

---

## 📂 Attachments / Evidence

#### Efficiency Code

> Updated Python code developed for calculating port efficiency using the DEA model, including the processing of berthing time relative to transported cargo.

[📎 Click here](https://colab.research.google.com/drive/1GWo_wNPInjZSoMRdY8L2w1J-c-stXMfm?usp=sharing)


#### Product Overview Video

> Presentation video created to showcase the product, demonstrate the dashboard’s features, and summarize the main activities developed throughout the project.

[📎 Click here](https://youtu.be/3ETfMbm2I5Q?si=deVXr6y_H8eg6Hm5)
