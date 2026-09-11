# Data Analysis Projects

Source of my published portfolio → **https://lpintos14.github.io/Data_Analytics_Projects/**

Five analysis projects taken from raw dataset to published Tableau dashboard, with the SQL and
Python behind each one kept in the repo.

> **If you only look at one thing, don't look here.** My most complete work is
> [**olist-ecommerce-analysis**](https://github.com/LPintos14/olist-ecommerce-analysis) — a
> reproducible pipeline over 9 related tables and 1.5M rows, with a documented data-quality
> audit. The projects below are earlier and lighter; I'm keeping them because they're where I
> learned the workflow.

---

## Projects

| Project | Finding | Stack | Dashboard |
|---|---|---|---|
| **Superstore** | Orders discounted above 20% are 14% of the book. They bill $363K and lose $135K — removing them alone lifts total profit 47%. Every discount tier above 20% is negative. | SQL · Tableau | [View](https://public.tableau.com/views/Resumenejecutivo_17133070144490/Resumenejecutivo) |
| **Wild Bike Store** | Bikes are 72.5% of revenue at 33.2% margin; accessories are 17.7% at **58.6%**, moving 29× the units. The margin isn't where the revenue is. Gender, tested, separates nothing. | SQL · pandas · Tableau | [View](https://public.tableau.com/views/ProyectBikesSales/Dashboard1) |
| **COVID-19** | Among countries past 1M cases, case fatality ranges from 4.88% (Peru) to 0.07% (Singapore) — a 70× spread that measures reporting systems as much as outcomes. | SQL · Tableau | [View](https://public.tableau.com/views/Covid-19Project_17168498376980/Dashboard1) |
| **Airbnb Buenos Aires** | Revenue by neighbourhood and listing type, and monthly seasonality. | SQL · Tableau | [View](https://public.tableau.com/views/AirBnbProject_17165024747360/Dashboard1) |
| **Mercedes-Benz stock** | −56.3% drawdown in ten weeks of 2020, then +322% off that low to the 2024 high. The +70.7% net return hides both. | SQL · Tableau | [View](https://public.tableau.com/views/Merces-BenzProject/Historia1) |

## Repo layout

Each project folder contains:

- `*Presentation*.md` — what the project covers
- `*Visualization*.md` — direct link to the dashboard
- `Datasets/` — the source data, in `.csv` and `.xlsx`
- `SQL_Queries/` — the queries behind the dashboard
- `pandas/` — notebooks, where the project used Python

---

**Stack across these:** SQL (MySQL, SQLite) · Python (pandas) · Tableau

Lautaro Pintos — Buenos Aires, Argentina.
[Profile](https://github.com/LPintos14) · [Portfolio](https://lpintos14.github.io/Data_Analytics_Projects/)
