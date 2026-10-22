# [Your site's title]

## Start here (delete this section before you submit)

This repository is your starting point for the Campus Comps case. It already holds the dataset, its description sheet, project instructions for your AI coding agent, and outlines of the README and agent log that the case asks for.

1. **Turn on GitHub Pages.** In this repository, open **Settings**, then **Pages**. Under "Build and deployment," set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, then click **Save**. A few minutes later your site is at `https://your-username.github.io/your-repo-name/`. It shows a placeholder page until you replace `index.html`.
2. **Open the repository in your AI coding agent.** Its project instructions are in `AGENTS.md`. If your agent reads its instructions from a file with a different name, check its documentation and copy `AGENTS.md` to that name. Add to the instructions as you learn what your agent needs.
3. **Read `docs/data_description_sheet.md`** before you ask the agent for any analysis.
4. **Build in small steps,** as the setup guide describes. Add an entry to `AGENT_LOG.md` each time you work with the agent.
5. **Fill in every section below** before you submit.

| Path | What it is |
|---|---|
| `index.html` | A placeholder page. Replace it with your site. |
| `data/college_town_home_sales.csv` | The dataset, version 1.0: 35,442 rows. Don't edit it. |
| `docs/data_description_sheet.md` | What every column means, and five problems in the data |
| `AGENTS.md` | Project instructions for your AI coding agent |
| `AGENT_LOG.md` | Your agent log |
| `scripts/` | Scripts that make smaller data files for the site |
| `checks/` | Your separate checks of the site's numbers |
| `.nojekyll` | Tells GitHub Pages to publish every file as it is. Don't delete it. |

The dataset is also available as Excel, SQLite, DuckDB and Parquet files, with identical values, from this template's [v1.0 release](https://github.com/uidfc-business-emerging-technologies/campus-comparables-template/releases/tag/v1.0). Your site needs only the CSV file, but the other formats can make checking numbers easier, for example with a SQL query on the SQLite file.

## What this site is for

_Replace this line with your site's question and audience, or a short description of the site._

## Live site

https://your-username.github.io/your-repo-name/

## Preview it on your own computer

From the repository folder, start a local web server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/. Opening `index.html` straight from the file won't load the data.

_If you preview the site another way, describe that way here instead._

## Data notes

_Replace this line. Say which rows you left out and why, and how each figure on the site is defined. "Five things that will bite you" in the description sheet lists the problems to cover._

## How we checked our numbers

_Replace this line. List at least three numbers shown on the site. Check each one with a calculation that is separate from the site's own code, such as a spreadsheet formula, a SQL query or a short script in `checks/`._

| Number on the site | Where it appears | How we checked it | Result |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

## Tools we used

_Replace this line with your AI coding agent or agents, and any libraries and other tools you used._

## Citation

College-town home sales dataset, version 1.0 (2026). University of Illinois-Deloitte Foundation Center for Business Emerging Technologies. Data collected March 2026.

## Who did what

_For teams: replace this line with each member's name and what they did. If you worked alone, delete this section._
