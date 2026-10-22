# Project instructions

Project: a data website built from the College-town home sales dataset.

Rules:
- Use plain HTML, CSS and JavaScript only. No frameworks, no build step, no server-side code. Libraries loaded with a script tag are fine.
- GitHub Pages publishes the site from the repository root. Use relative paths (data/file.csv, not /data/file.csv) and match the exact upper and lower case of file names. No file or folder name starts with _.
- The data is in data/college_town_home_sales.csv. Read docs/data_description_sheet.md before writing any analysis code, and follow its warnings. Read zipcode, county_fips and parcel_number as text.
- Never edit data/college_town_home_sales.csv. Save any file made from it under a new name, and put the script that makes it in scripts/.
- Never invent or estimate numbers. Compute every number on the site from the data.
- Work in small steps. Before a large change, describe your plan and wait for my approval.
- After each change, tell me what you changed and how I can check it.
- Never put passwords, API keys or other secrets in any file.
- Keep the .nojekyll file. It makes GitHub Pages publish every file as it is.
