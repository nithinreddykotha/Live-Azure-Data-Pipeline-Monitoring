# Azure ETL Pipeline Monitoring using Log Analytics Workspace 💠

🔹This project contains Azure portal dashboards backed by KQL queries that read from Log Analytics workspaces to visualize Azure Pipelines and database execution metrics.

🔹One dashboard panel focuses on longest-running pipelines by aggregating run durations over a given time range and ordering them so outliers and performance issues become immediately visible.

🔹Another panel analyzes longest-running database activities, using KQL to group log and performance data by query or operation and present them as tables and time-series charts.

🔹The project includes failure-focused views that track the most frequently failing pipelines, highlighting counts and trends to support debugging and reliability work.

🔹Multiple KQL queries are combined into a single Azure dashboard/workbook, providing a consolidated view of pipeline health, performance, and database activity with interactive filters (time range, environment, etc.).

