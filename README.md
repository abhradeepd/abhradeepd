<div align="center">

<img src="assets/header.svg" alt="Abhradeep Das — Analytics Engineer" width="100%">

<p>
  <a href="https://abhradeepd.github.io"><img src="https://img.shields.io/badge/Portfolio-0F1124?style=for-the-badge&logo=githubpages&logoColor=E67E22" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/abhradeep-das-ds09ji3/"><img src="https://img.shields.io/badge/LinkedIn-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMSIgeT0iMSIgd2lkdGg9IjIyIiBoZWlnaHQ9IjIyIiByeD0iNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjOUQ3Q0Q4IiBzdHJva2Utd2lkdGg9IjIuMiIvPjxjaXJjbGUgY3g9IjcuMiIgY3k9IjcuMyIgcj0iMS43IiBmaWxsPSIjOUQ3Q0Q4Ii8%2BPHJlY3QgeD0iNS45IiB5PSIxMC4yIiB3aWR0aD0iMi43IiBoZWlnaHQ9IjguMiIgZmlsbD0iIzlEN0NEOCIvPjxwYXRoIGQ9Ik0xMS4yIDE4LjR2LTguMmgyLjZ2MS4xYTMuMiAzLjIgMCAwIDEgNS40IDIuNHY0LjdoLTIuN3YtNC4yYTEuNiAxLjYgMCAwIDAtMy4yIDB2NC4yeiIgZmlsbD0iIzlEN0NEOCIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a>
  <a href="mailto:abhradeep.das@gwu.edu"><img src="https://img.shields.io/badge/Email-0F1124?style=for-the-badge&logo=maildotru&logoColor=D6456E" alt="Email"></a>
  <a href="https://abhradeepd.github.io/assets/Abhradeep_Das_AE.pdf"><img src="https://img.shields.io/badge/Resume-0F1124?style=for-the-badge&logo=readthedocs&logoColor=E67E22" alt="Resume"></a>
</p>

</div>

---

### <samp>// 01 · hello</samp>

Hey, I'm Abhradeep — thanks for stopping by <img src="assets/wave.svg" width="24" alt="wave" align="center">

I'm an **Analytics Engineer** with an MS in Data Science from The George Washington University. My favourite kind of problem is the messy one: five systems disagreeing about the same number, and nobody sure which to trust. I like turning that into one tested, documented model everyone can point at — and then handing people a dashboard they can actually answer their own questions with.

```sql
select
    name,
    role,
    stack,
    open_to,
    location
from  engineers
where name = 'Abhradeep Das';

-- 1 row returned -------------------------------------------------------------
-- name      | Abhradeep Das
-- role      | Analytics Engineer
-- stack     | {dbt, sql, snowflake, bigquery, power bi, python}
-- open_to   | {full-time roles, open-source collaboration}
-- location  | anywhere in India · open to relocating
```

- 👯 **Open to collaborating on open-source data engineering projects** — pipelines, dbt packages, tooling, docs. Send an issue or a message.
- 🇮🇳 **Open to work anywhere in India**, and to relocating internationally with visa sponsorship.
- 💬 Ask me anything about **dbt, dimensional modelling, SQL or BI** — genuinely, I enjoy these conversations.
- 📫 Reach me at **abhradeep.das@gwu.edu**

> 🔍 **Currently seeking:** full-time **Analytics Engineer**, **BI Engineer**, or **Data Analyst** roles.

<details>
<summary><samp>&nbsp;🍥&nbsp; a few things that aren't on my résumé</samp></summary>

<br>

- My portfolio site is hand-built — no framework, no build step — and its colour palette is quietly borrowed from **Obito Uchiha**. If you spotted that, we'll get along.
- I'd rather ship a small model with tests than a large one without.
- The fastest way to my heart is a well-named column.

</details>

---

### <samp>// 02 · what i build</samp>

```text
  raw sources  ──▶   ingest   ──▶     warehouse      ──▶  model + test ✓ ──▶    serve
 CSV·API·events    dlt·Airflow   Snowflake·BigQuery·DuckDB    dbt·tests·docs   Power BI·Tableau
```

---

### <samp>// 03 · how i work</samp>

```yaml
# principles.yml
- one_definition_per_metric:  agreed with stakeholders before it ships
- tests_are_not_optional:     not_null, unique, relationships, freshness
- documented_or_it_doesn't_exist: every model, every column
- readable_beats_clever:      the next person is usually me
- start_from_the_question:    dashboards are answers, not tables on a page
```

---

### <samp>// 04 · toolbox</samp>

**Transformation & modeling**

<p>
  <img src="https://img.shields.io/badge/dbt-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iNSIgY3k9IjUuNSIgcj0iMyIgZmlsbD0iI0U2N0UyMiIvPjxjaXJjbGUgY3g9IjUiIGN5PSIxOC41IiByPSIzIiBmaWxsPSIjRTY3RTIyIi8%2BPGNpcmNsZSBjeD0iMTkiIGN5PSIxMiIgcj0iMyIgZmlsbD0iI0U2N0UyMiIvPjxwYXRoIGQ9Ik03LjYgNi43IDE2LjQgMTAuOSIgc3Ryb2tlPSIjRTY3RTIyIiBzdHJva2Utd2lkdGg9IjEuOCIvPjxwYXRoIGQ9Ik03LjYgMTcuMyAxNi40IDEzLjEiIHN0cm9rZT0iI0U2N0UyMiIgc3Ryb2tlLXdpZHRoPSIxLjgiLz48L3N2Zz4%3D" alt="dbt" title="models, tests and docs as version-controlled SQL">
  <img src="https://img.shields.io/badge/Jinja-0F1124?style=for-the-badge&logo=jinja&logoColor=E67E22" alt="Jinja" title="templating and macros inside dbt models">
  <img src="https://img.shields.io/badge/MetricFlow-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iNSIgY3k9IjUuNSIgcj0iMyIgZmlsbD0iI0U2N0UyMiIvPjxjaXJjbGUgY3g9IjUiIGN5PSIxOC41IiByPSIzIiBmaWxsPSIjRTY3RTIyIi8%2BPGNpcmNsZSBjeD0iMTkiIGN5PSIxMiIgcj0iMyIgZmlsbD0iI0U2N0UyMiIvPjxwYXRoIGQ9Ik03LjYgNi43IDE2LjQgMTAuOSIgc3Ryb2tlPSIjRTY3RTIyIiBzdHJva2Utd2lkdGg9IjEuOCIvPjxwYXRoIGQ9Ik03LjYgMTcuMyAxNi40IDEzLjEiIHN0cm9rZT0iI0U2N0UyMiIgc3Ryb2tlLXdpZHRoPSIxLjgiLz48L3N2Zz4%3D" alt="MetricFlow" title="metrics defined once, served everywhere">
  <img src="https://img.shields.io/badge/Star_%26_Snowflake_schema-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iOSIgeT0iOSIgd2lkdGg9IjYiIGhlaWdodD0iNiIgcng9IjEiIGZpbGw9IiNFNjdFMjIiLz48cmVjdCB4PSIxIiB5PSIxLjUiIHdpZHRoPSI0LjYiIGhlaWdodD0iNC42IiByeD0iMSIgZmlsbD0iI0U2N0UyMiIvPjxyZWN0IHg9IjE4LjQiIHk9IjEuNSIgd2lkdGg9IjQuNiIgaGVpZ2h0PSI0LjYiIHJ4PSIxIiBmaWxsPSIjRTY3RTIyIi8%2BPHJlY3QgeD0iMSIgeT0iMTcuOSIgd2lkdGg9IjQuNiIgaGVpZ2h0PSI0LjYiIHJ4PSIxIiBmaWxsPSIjRTY3RTIyIi8%2BPHJlY3QgeD0iMTguNCIgeT0iMTcuOSIgd2lkdGg9IjQuNiIgaGVpZ2h0PSI0LjYiIHJ4PSIxIiBmaWxsPSIjRTY3RTIyIi8%2BPHBhdGggZD0iTTUuOCA1LjQgOS40IDlNMTguMiA1LjQgMTQuNiA5TTUuOCAxOC42IDkuNCAxNU0xOC4yIDE4LjYgMTQuNiAxNSIgc3Ryb2tlPSIjRTY3RTIyIiBzdHJva2Utd2lkdGg9IjEuNiIvPjwvc3ZnPg%3D%3D" alt="Star & Snowflake schema" title="dimensional modelling: facts and conformed dimensions">
  <img src="https://img.shields.io/badge/SCD_Type_2-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iOC42IiBmaWxsPSJub25lIiBzdHJva2U9IiNFNjdFMjIiIHN0cm9rZS13aWR0aD0iMi4xIi8%2BPHBhdGggZD0iTTEyIDYuOFYxMmw0IDIuNCIgc3Ryb2tlPSIjRTY3RTIyIiBzdHJva2Utd2lkdGg9IjIuMSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBmaWxsPSJub25lIi8%2BPC9zdmc%2B" alt="SCD Type 2" title="slowly changing dimensions with full history">
  <img src="https://img.shields.io/badge/Elementary-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSI0LjUiIHI9IjIuOCIgZmlsbD0iI0U2N0UyMiIvPjxjaXJjbGUgY3g9IjUiIGN5PSIxOSIgcj0iMi44IiBmaWxsPSIjRTY3RTIyIi8%2BPGNpcmNsZSBjeD0iMTkiIGN5PSIxOSIgcj0iMi44IiBmaWxsPSIjRTY3RTIyIi8%2BPHBhdGggZD0iTTEwLjYgNyA2LjIgMTYuNCIgc3Ryb2tlPSIjRTY3RTIyIiBzdHJva2Utd2lkdGg9IjEuOCIvPjxwYXRoIGQ9Ik0xMy40IDcgMTcuOCAxNi40IiBzdHJva2U9IiNFNjdFMjIiIHN0cm9rZS13aWR0aD0iMS44Ii8%2BPHBhdGggZD0iTTcuOCAxOWg4LjQiIHN0cm9rZT0iI0U2N0UyMiIgc3Ryb2tlLXdpZHRoPSIxLjgiLz48L3N2Zz4%3D" alt="Elementary" title="dbt-native data observability and anomaly alerts">
</p>

**Languages & databases**

<p>
  <img src="https://img.shields.io/badge/Python-0F1124?style=for-the-badge&logo=python&logoColor=D6456E" alt="Python" title="pipelines, parsing and analysis">
  <img src="https://img.shields.io/badge/SQL-0F1124?style=for-the-badge&logo=postgresql&logoColor=D6456E" alt="SQL" title="the day job: modelling, window functions, performance">
  <img src="https://img.shields.io/badge/PostgreSQL-0F1124?style=for-the-badge&logo=postgresql&logoColor=D6456E" alt="PostgreSQL" title="relational workhorse">
  <img src="https://img.shields.io/badge/MySQL-0F1124?style=for-the-badge&logo=mysql&logoColor=D6456E" alt="MySQL" title="relational workhorse">
  <img src="https://img.shields.io/badge/MongoDB-0F1124?style=for-the-badge&logo=mongodb&logoColor=D6456E" alt="MongoDB" title="document stores when the schema won't sit still">
  <img src="https://img.shields.io/badge/R-0F1124?style=for-the-badge&logo=r&logoColor=D6456E" alt="R" title="statistics and exploratory work">
  <img src="https://img.shields.io/badge/Bash-0F1124?style=for-the-badge&logo=gnubash&logoColor=D6456E" alt="Bash" title="glue, cron and CLI plumbing">
</p>

**Orchestration & DevOps**

<p>
  <img src="https://img.shields.io/badge/Airflow-0F1124?style=for-the-badge&logo=apacheairflow&logoColor=9D7CD8" alt="Airflow" title="scheduling and orchestrating transformation DAGs">
  <img src="https://img.shields.io/badge/Dagster-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSI0LjUiIHI9IjIuOCIgZmlsbD0iIzlEN0NEOCIvPjxjaXJjbGUgY3g9IjUiIGN5PSIxOSIgcj0iMi44IiBmaWxsPSIjOUQ3Q0Q4Ii8%2BPGNpcmNsZSBjeD0iMTkiIGN5PSIxOSIgcj0iMi44IiBmaWxsPSIjOUQ3Q0Q4Ii8%2BPHBhdGggZD0iTTEwLjYgNyA2LjIgMTYuNCIgc3Ryb2tlPSIjOUQ3Q0Q4IiBzdHJva2Utd2lkdGg9IjEuOCIvPjxwYXRoIGQ9Ik0xMy40IDcgMTcuOCAxNi40IiBzdHJva2U9IiM5RDdDRDgiIHN0cm9rZS13aWR0aD0iMS44Ii8%2BPHBhdGggZD0iTTcuOCAxOWg4LjQiIHN0cm9rZT0iIzlEN0NEOCIgc3Ryb2tlLXdpZHRoPSIxLjgiLz48L3N2Zz4%3D" alt="Dagster" title="asset-aware orchestration">
  <img src="https://img.shields.io/badge/dlt-0F1124?style=for-the-badge&logo=python&logoColor=9D7CD8" alt="dlt" title="declarative extract-and-load in Python">
  <img src="https://img.shields.io/badge/GitHub_Actions-0F1124?style=for-the-badge&logo=githubactions&logoColor=9D7CD8" alt="GitHub Actions" title="CI on every pull request">
  <img src="https://img.shields.io/badge/Docker-0F1124?style=for-the-badge&logo=docker&logoColor=9D7CD8" alt="Docker" title="reproducible environments">
  <img src="https://img.shields.io/badge/Kubernetes-0F1124?style=for-the-badge&logo=kubernetes&logoColor=9D7CD8" alt="Kubernetes" title="container orchestration">
  <img src="https://img.shields.io/badge/Git-0F1124?style=for-the-badge&logo=git&logoColor=9D7CD8" alt="Git" title="version control, always">
  <img src="https://img.shields.io/badge/JIRA-0F1124?style=for-the-badge&logo=jira&logoColor=9D7CD8" alt="JIRA" title="tickets, sprints and the paper trail">
</p>

**Warehouses & cloud**

<p>
  <img src="https://img.shields.io/badge/Snowflake-0F1124?style=for-the-badge&logo=snowflake&logoColor=E67E22" alt="Snowflake" title="cloud warehouse — my primary production platform">
  <img src="https://img.shields.io/badge/BigQuery-0F1124?style=for-the-badge&logo=googlebigquery&logoColor=E67E22" alt="BigQuery" title="cloud warehouse — partitioning and cost-aware SQL">
  <img src="https://img.shields.io/badge/DuckDB-0F1124?style=for-the-badge&logo=duckdb&logoColor=E67E22" alt="DuckDB" title="a whole warehouse in a single file">
  <img src="https://img.shields.io/badge/AWS-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTYuNiAxOS41YTUuMSA1LjEgMCAwIDEtLjUtMTAuMiA3IDcgMCAwIDEgMTMuMyAxLjYgNC4zIDQuMyAwIDAgMS0xLjEgOC42eiIgZmlsbD0iI0U2N0UyMiIvPjwvc3ZnPg%3D%3D" alt="AWS" title="S3, Lambda and friends">
  <img src="https://img.shields.io/badge/GCP-0F1124?style=for-the-badge&logo=googlecloud&logoColor=E67E22" alt="GCP" title="BigQuery and the Google side of the house">
</p>

**BI & reporting**

<p>
  <img src="https://img.shields.io/badge/Power_BI-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMi41IiB5PSIxMyIgd2lkdGg9IjQuNiIgaGVpZ2h0PSI5IiByeD0iMS4yIiBmaWxsPSIjRDY0NTZFIi8%2BPHJlY3QgeD0iOS43IiB5PSI3LjUiIHdpZHRoPSI0LjYiIGhlaWdodD0iMTQuNSIgcng9IjEuMiIgZmlsbD0iI0Q2NDU2RSIvPjxyZWN0IHg9IjE2LjkiIHk9IjIiIHdpZHRoPSI0LjYiIGhlaWdodD0iMjAiIHJ4PSIxLjIiIGZpbGw9IiNENjQ1NkUiLz48L3N2Zz4%3D" alt="Power BI" title="semantic models, DAX measures and row-level security">
  <img src="https://img.shields.io/badge/Tableau-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTIuNSAyMS41VjIuNSIgc3Ryb2tlPSIjRDY0NTZFIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPjxwYXRoIGQ9Ik0yLjUgMjEuNWgxOSIgc3Ryb2tlPSIjRDY0NTZFIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPjxwYXRoIGQ9Ik02IDE2LjUgMTAuNSAxMSAxNC41IDE0IDIwIDUuNSIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjRDY0NTZFIiBzdHJva2Utd2lkdGg9IjIuMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8%2BPGNpcmNsZSBjeD0iMTAuNSIgY3k9IjExIiByPSIyLjEiIGZpbGw9IiNENjQ1NkUiLz48Y2lyY2xlIGN4PSIyMCIgY3k9IjUuNSIgcj0iMi4xIiBmaWxsPSIjRDY0NTZFIi8%2BPC9zdmc%2B" alt="Tableau" title="dashboards for analysts and executives">
  <img src="https://img.shields.io/badge/Looker_Studio-0F1124?style=for-the-badge&logo=looker&logoColor=D6456E" alt="Looker Studio" title="lightweight sharable reporting">
  <img src="https://img.shields.io/badge/Excel-0F1124?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMiIgeT0iMyIgd2lkdGg9IjIwIiBoZWlnaHQ9IjE4IiByeD0iMiIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjRDY0NTZFIiBzdHJva2Utd2lkdGg9IjIiLz48cmVjdCB4PSIyIiB5PSIzIiB3aWR0aD0iMjAiIGhlaWdodD0iNS4yIiByeD0iMiIgZmlsbD0iI0Q2NDU2RSIvPjxwYXRoIGQ9Ik05IDguMnYxMi44TTE1IDguMnYxMi44TTIgMTQuNmgyMCIgc3Ryb2tlPSIjRDY0NTZFIiBzdHJva2Utd2lkdGg9IjEuOCIvPjwvc3ZnPg%3D%3D" alt="Excel" title="where every stakeholder still wants the export">
</p>

**Analytics & ML**

<p>
  <img src="https://img.shields.io/badge/Pandas-0F1124?style=for-the-badge&logo=pandas&logoColor=9D7CD8" alt="Pandas" title="dataframes and wrangling">
  <img src="https://img.shields.io/badge/NumPy-0F1124?style=for-the-badge&logo=numpy&logoColor=9D7CD8" alt="NumPy" title="the numerical layer underneath">
  <img src="https://img.shields.io/badge/Plotly-0F1124?style=for-the-badge&logo=plotly&logoColor=9D7CD8" alt="Plotly" title="interactive charts">
  <img src="https://img.shields.io/badge/spaCy-0F1124?style=for-the-badge&logo=spacy&logoColor=9D7CD8" alt="spaCy" title="NLP pipelines over messy text">
  <img src="https://img.shields.io/badge/Selenium-0F1124?style=for-the-badge&logo=selenium&logoColor=9D7CD8" alt="Selenium" title="scraping what has no API">
  <img src="https://img.shields.io/badge/PyTorch-0F1124?style=for-the-badge&logo=pytorch&logoColor=9D7CD8" alt="PyTorch" title="deep learning">
  <img src="https://img.shields.io/badge/TensorFlow-0F1124?style=for-the-badge&logo=tensorflow&logoColor=9D7CD8" alt="TensorFlow" title="deep learning">
  <img src="https://img.shields.io/badge/Scikit--Learn-0F1124?style=for-the-badge&logo=scikitlearn&logoColor=9D7CD8" alt="Scikit-Learn" title="classical ML and evaluation">
  <img src="https://img.shields.io/badge/Hugging_Face-0F1124?style=for-the-badge&logo=huggingface&logoColor=9D7CD8" alt="Hugging Face" title="pretrained models and transformers">
  <img src="https://img.shields.io/badge/Llama_70B-0F1124?style=for-the-badge&logo=meta&logoColor=9D7CD8" alt="Llama 70B" title="in-house document classification at The World Bank">
</p>

---

### <samp>// 05 · numbers</samp>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=abhradeepd&show_icons=true&hide_border=true&bg_color=0F1124&title_color=E67E22&icon_color=9D7CD8&text_color=C9D3DD&count_private=true" alt="GitHub stats" height="160">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhradeepd&layout=compact&hide_border=true&bg_color=0F1124&title_color=E67E22&text_color=C9D3DD" alt="Top languages" height="160">

</div>

---

<div align="center">

<sub><samp>Thanks for reading — if any of this is useful to you, my inbox is open.</samp></sub>

<sub><samp>// those who abandon their metrics are worse than scum.</samp></sub>

</div>
