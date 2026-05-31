# Module 7 Lab Guide: Aggregation, Reshaping, and Light Validation

**BAN 6003: Data Management and Analytics Integration**

This module focuses on summarizing and reshaping data with Pandas. The important idea is that aggregation can change what one row means.

For example, `nycflights13.flights` begins with one row per flight. After aggregation, one row might represent a carrier, a route, a month, or a carrier-month combination.

## Lab File

Complete:

`module7_aggregation_reshaping_guided_lab.ipynb`

## GitHub Classroom Assignment Link

Canvas will provide the GitHub Classroom invitation link for this Module 7-8 assignment package:

**GitHub Classroom invitation link:** [to be added]

Click the invitation link, sign in to GitHub, and accept the assignment. If this is your first GitHub Classroom assignment for the course, GitHub may ask you to authorize GitHub Classroom and match your GitHub account to the course roster. Choose your own name or identifier carefully.

After you accept, wait for GitHub Classroom to create your personal assignment repository. Open the repository link shown on the confirmation page. If you see a repository access message, check the GitHub notifications inbox in the upper-right corner of GitHub, or go to `https://github.com/notifications`, and accept any pending repository or organization invitation from GitHub Classroom. You may also receive an email from GitHub with the same invitation.

Once you can see your personal assignment repository, open it in Codespaces with **Code > Codespaces > Create codespace on main**.

## What You Will Practice

You will practice `groupby()`, `agg()`, named aggregation, `reset_index()`, `sort_values()`, `melt()`, `pivot()`, `pivot_table()`, and light validation checks after transformations.

## Recommended Workflow

1. Open the notebook in GitHub Codespaces.
2. Run the setup cells.
3. Work through the aggregation examples.
4. Track what one row means after each summary.
5. Practice wide-to-long and long-to-wide reshaping.
6. Complete each Your Turn section.
7. Complete the final practice and reflection.
8. Save, commit, and push your work.

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
