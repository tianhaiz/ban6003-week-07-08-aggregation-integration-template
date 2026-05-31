# Module 8 Introduction: Data Integration with Pandas Merge

Until now, most work has happened inside one dataset. This week, we move into data integration. In real organizations, one table rarely contains everything needed for analysis. A flight table may contain a carrier code, while the airline name lives in another table. A transaction table may need customer, account, or product information from separate sources.

Data integration is powerful, but it also creates risk. A merge on the wrong key, a duplicate key in a lookup table, or an unintended many-to-many relationship can produce a misleading table very quickly.

## This Week You Will

- identify primary key and foreign key candidates;
- explain granularity and table relationships;
- use `pd.merge()` to combine related tables;
- compare left, inner, outer, and right joins;
- use `indicator=True` and suffixes for merge auditing;
- check row counts and duplicate keys before and after merges;
- use `pd.concat()` to stack similar datasets.

## Lab Focus

The guided lab uses related `nycflights13` tables such as flights, airlines, airports, and planes. You will practice merge logic, join types, many-to-many risks, and row-count checks.

## Why This Matters

Integration is not just combining tables. It is combining tables correctly. A strong analyst can explain which table is the main table, which table is the lookup table, what key connects them, and why the selected join type fits the business question.

## Project Connection

If your project uses more than one file or table, this module gives you the core workflow for combining them responsibly. Always check keys, row counts, and missing values before trusting the integrated result.
