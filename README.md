<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com/?lines=Data%20Engineer;Code%20|%20Eat%20|%20Sleep%20|%20Dream&font=Fira%20Code&center=true&width=440&height=45&color=bf002a&vCenter=true&size=22"></a>
</p>


<h1 align="center">Angel Santana</h1>

<p align="center">
  <b>Staff Data Engineer</b> · Data Platform Architecture &amp; Migration
</p>

<p align="center">
  I design and migrate enterprise data platforms — the kind where the numbers feed <br/>
  financial decisions, so they have to tie out, trace back, and survive an audit.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI" />
</p>



## What I do

### Platform migration &amp; consolidation

Moving enterprise workloads off legacy warehouses and onto a single platform, without the business noticing a gap.

- **Inventory before movement** — every object, every downstream consumer, and who would notice if it stopped
- **Sequencing** — what moves first, what it unblocks, what can't move until a contract is confirmed
- **Parallel-run reconciliation** — legacy and target produce the same numbers at each close, and cutover happens only after they tie out
- **Decommission** — the shutdown checklist, so the old platform actually goes away instead of quietly costing money for another two years

### Data architecture &amp; modeling

- **Medallion architecture** with layer boundaries that mean something: staging layers stay mechanical, business logic lives in one place, and "is this metric right?" is a question you answer by reading one folder
- **Semantic and consumer layers** — the published boundary between the model and everything that reads it
- **Dependency resolution** — breaking circular table dependencies that legacy schedulers hid behind alphabetical run order and declarative pipelines will reject outright
- **Multi-region conforming** — regional ERP data standardized and unioned into global, cross-domain data products
- **Naming and SQL conventions** written down and enforced, so a model built by four people reads like it was built by one

### Financial &amp; operational modeling

Customer and enterprise profitability models built from company source data — including the allocation logic, the eligibility rules, and the validation and guard-rail outputs that prove the allocation is correct. Plus revenue and cost allocation, CAC, and churn modeling for enterprise-level financial analysis.

### Automation &amp; engineering enablement

- Python frameworks for SQL execution, pipeline orchestration, release promotion, data validation, and API ingestion — if it's run by hand twice, it gets a CLI
- **Governed dev → test → prod promotion** across catalogs and environments
- **Infrastructure as code** for platform provisioning
- **Data quality scorecards** and automated validation, generated rather than hand-maintained
- **AI-assisted data engineering** — repo-level agent config, shared prompt skills, and Claude Code workflows committed alongside the code, so the whole team inherits the same tooling instead of each person reinventing it

### Standards, governance &amp; ways of working

I write the documents the team actually works from: repo conventions, branch strategy, secrets hygiene, onboarding guides, architecture decision records, and open-decision logs that get updated when the answer changes.

---

## Skills

| | |
|---|---|
| **Platforms** | Databricks (Unity Catalog, Lakeflow Declarative Pipelines, Genie) · Snowflake · Azure Data Warehouse · SQL Server |
| **Modeling** | Medallion architecture · dbt · Semantic layers · Incremental processing · Dimensional modeling · Data contracts |
| **Languages** | Python · SQL (multi-dialect) · JavaScript / TypeScript |
| **Pipelines** | ETL / ELT · Declarative pipelines · Orchestration · API ingestion · CDC &amp; incremental loads |
| **Quality &amp; governance** | Data validation frameworks · DQ scorecards · Lineage · Reconciliation &amp; tie-out · Access and catalog governance |
| **Analytics** | Power BI · Financial &amp; profitability analytics · Self-serve semantic layers · Executive reporting |
| **Sources** | ERP (JD Edwards) · Financial systems · REST APIs · Multi-region operational data |
| **Ops &amp; tooling** | Git · GitHub · Azure DevOps · Bitbucket · Docker · IaC · CI/CD · CLI tooling |
| **AI-assisted DE** | Claude Code · RAG over code &amp; SQL · Vector search (Qdrant) · Agent and skill design |

---

### Exploring right now

`AI-assisted data engineering` · `Automated data quality systems` · `Data governance frameworks` · `Real-time pipelines` · `Declarative pipeline patterns`

---

<details>
<summary><b>A bit more on how I think about this work</b></summary>

<br/>

Good data systems aren't defined by the tools in them — they're defined by whether the next engineer can change them safely. That means:

- **Auditable over clever.** If you can't trace a number back to its source, it isn't a metric, it's a rumor.
- **Automated over heroic.** Manual release steps are outages waiting for a calendar slot.
- **Documented over tribal.** Onboarding time is a real architectural metric.
- **Modular over monolithic.** SQL/Python is code. It deserves the same structure, review, and versioning as anything else.
- **Contain the uncertainty.** When a design question isn't settled, isolate it in one layer and write down what would change if it resolves the other way. Unknowns are fine; unrecorded unknowns are not.

Most of my work sits at the intersection of data engineering, platform engineering, and analytics engineering — close enough to the business to know what the numbers mean, close enough to the infrastructure to keep them correct.

</details>

---

<p align="center">
  <a href="https://www.linkedin.com/in/angelsantanahernandez">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:angxlsxntxnx@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>