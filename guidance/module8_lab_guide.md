# Module 8 Lab Guide: Data Integration with Pandas Merge

**BAN 6003: Data Management and Analytics Integration**

This module focuses on combining related datasets with Pandas. You will use `nycflights13` tables to practice joins and to check whether the integrated result still makes sense.

The main idea is:

> Data integration is not just combining tables. It is combining tables correctly.

## Lab File

Complete:

`module8_pandas_integration_guided_lab.ipynb`

## GitHub Classroom Assignment Link

This module is part of the Module 7-8 assignment package. Canvas will provide the GitHub Classroom invitation link if you have not already accepted this package:

**GitHub Classroom invitation link:** [to be added]

If you already accepted the Module 7-8 assignment, return to the same personal assignment repository and reopen your Codespace. If the repository does not open or GitHub says you do not have access, check the GitHub notifications inbox in the upper-right corner of GitHub, or go to `https://github.com/notifications`, and accept any pending repository or organization invitation from GitHub Classroom.

## What You Will Practice

You will practice identifying key columns, checking key uniqueness, using `pd.merge()`, comparing left, inner, outer, and right joins, using `indicator=True`, applying suffixes when column names overlap, using `pd.concat()`, and comparing row counts before and after integration.

## Recommended Workflow

1. Open the notebook in GitHub Codespaces.
2. Run the setup cells.
3. Inspect the tables and possible keys.
4. Check key uniqueness before merging.
5. Work through each join example.
6. Complete all Your Turn exercises.
7. Build the final integrated table.
8. Write the final reflection.
9. Save, commit, and push your work.

## What to Pay Attention To

Before merging, ask what the main table is, what the lookup table is, and whether the key is unique where it should be. After merging, check whether the row count changed and whether new missing values appeared.

## Minimum Completion Checklist

Before submitting, make sure:

- You checked key uniqueness in at least two tables.
- You used a left join.
- You used an inner join.
- You reviewed an outer join with `indicator=True`.
- You reviewed a right join example.
- You used `pd.concat()`.
- You completed the final integrated table and reflection.
