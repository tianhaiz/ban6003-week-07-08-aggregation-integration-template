# Module 7 Lab Guide: Aggregation, Reshaping, and Light Validation

**BAN 6003: Data Management and Analytics Integration**

This module focuses on summarizing and reshaping data with Pandas. The important idea is that aggregation can change what one row means.

For example, `nycflights13.flights` begins with one row per flight. After aggregation, one row might represent a carrier, a route, a month, or a carrier-month combination.

## Lab File

Complete:

`module7_aggregation_reshaping_guided_lab.ipynb`


## GitHub Repository and Running Environment

Start from this public template repository:

https://github.com/tianhaiz/ban6003-week-07-08-aggregation-integration-template

Create your own GitHub repository from the template with **Use this template > Create a new repository**. I recommend making your repository public so the instructor can inspect your submission. If you use a private repository, invite the instructor GitHub account `zzz1990771` or the email `zzz1990771@gmail.com` as a collaborator.

You may run the lab in either environment:

- **Recommended for beginners:** GitHub Codespaces from your own repository.
- **Local option:** clone your own repository, activate the `ban6003` conda environment, install `requirements.txt`, and run JupyterLab locally.

Submit your GitHub repository link or a completed ZIP through Canvas.

## What You Will Practice

You will practice `groupby()`, `agg()`, named aggregation, `reset_index()`, `sort_values()`, `melt()`, `pivot()`, `pivot_table()`, and light validation checks after transformations.

## Recommended Workflow

1. Open the notebook in Codespaces or local Jupyter.
2. Run the setup cells.
3. Work through the aggregation examples.
4. Track what one row means after each summary.
5. Practice wide-to-long and long-to-wide reshaping.
6. Complete each Your Turn section.
7. Complete the final practice and reflection.
8. Save your work, then commit and push if using GitHub.

## What to Pay Attention To

After each transformation, check row counts, duplicate keys, missing values, and the intended unit of analysis. If the row meaning changed, say so clearly.

## Minimum Completion Checklist

Before submitting, make sure:

- You created grouped summaries.
- You used named aggregation.
- You reshaped data with `melt()`.
- You reshaped data with `pivot()` or `pivot_table()`.
- You ran light validation checks.
- You explained what one row means in a transformed table.
- You completed the final reflection.
