<div align="center">

# Erfan Naderi

**I build databases that can answer a hard question: *“what did we actually know, on this date?”***

Data Analysis (L-31) · Università degli Studi di Messina · Messina, Italy

</div>

<br/>

<table width="100%">
  <tr>
    <td width="62%" valign="top">
      <p>
        Market and macroeconomic data is rewritten after publication. The value you read
        today in a historical series is not the value that was available back then, so any
        evaluation built on latest-vintage data quietly uses information it did not have —
        and the error makes results look <em>better</em>, not worse.
      </p>
      <p>
        For my bachelor's dissertation I designed <b>AURUM</b>, a point-in-time (bitemporal)
        data platform on PostgreSQL, and measured what getting this wrong costs.
      </p>
      <p>
        I came to the problem from the practical side: three years of trading currency
        markets, where I saw how fragile a backtest is before I studied why.
      </p>
      <p>
        <b>Ask me about</b> bitemporal schema design, as-of queries, ingestion with
        deterministic replay, or how to audit a dataset for lookahead bias.
      </p>
    </td>
    <td width="38%" valign="middle" align="center">
      <img
        src="https://raw.githubusercontent.com/Itsmrefox/Itsmrefox/main/assets/data.svg"
        width="100%"
        alt="Animated data visualisation"
      />
    </td>
  </tr>
</table>

---

### Currently building — [AURUM](https://github.com/Itsmrefox/aurum-showcase)

A point-in-time research data platform. Bachelor's internship + dissertation at UniMe,
supervised by Prof. Ruggeri (Databases).

| | |
|---|---|
| **Store** | 91,078 facts · 22 macro series · three ingest arms · history from 2004 |
| **Leakage** | a naive latest-vintage join leaks future information in **67.3%** of decisions, by up to **49 days**; the correctly built block audits clean at 0% |
| **Correctness** | of three candidate designs, one widely used design is **unsound** — not merely slower — on half the workload |
| **Cost of correctness** | 29× ingest time, 3.9× storage — measured, not assumed |
| **Engineering** | 700+ automated tests (property-based, replay determinism, leakage audit) in CI · 33 architecture decision records |

→ **[Read the full overview](https://github.com/Itsmrefox/aurum-showcase)** *(source private until the dissertation is defended — happy to walk through the code in person)*

---

### Toolbox

Things I actually use, and can defend in an interview:

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=databricks&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Make-427819?style=flat-square&logo=gnu&logoColor=white" alt="Make" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

Learning next: dbt, Spark/Databricks, and the analytics-engineering side of the stack.

---

### Contact

Open to a first **Data / Data Engineering** role in Italy — internship or junior.
Working languages: **Italian**, **English**, **Persian**.

<p>
  <a href="https://www.linkedin.com/in/erfan-naderi-adergani">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:itsmrefox@gmail.com">
    <img src="https://img.shields.io/badge/Email-334155?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
