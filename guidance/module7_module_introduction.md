# Module 7 Introduction: Aggregation, Reshaping, and Light Validation

This week moves from changing values and columns to changing the level and shape of a dataset. The core question for this module is simple and important: what does one row mean now?

The original `nycflights13.flights` dataset has one row per flight. After aggregation, one row might represent one carrier, one month, one route, or one carrier-month combination. That change affects interpretation. A table can be technically correct but analytically misleading if the unit of analysis is unclear.

## This Week You Will

- summarize data using `groupby()` and `agg()`;
- use named aggregation and `reset_index()`;
- explain how aggregation changes the unit of analysis;
- reshape data between wide and long formats;
- use `melt()`, `pivot()`, and `pivot_table()`;
- run light validation checks after transformation.

## Lab Focus

The lab uses `nycflights13` to summarize delays by carrier, month, and route. You will create grouped summaries, reshape carrier-month summaries, and check row counts, missing values, and duplicated keys after major transformations.

## Why This Matters

Aggregation and reshaping prepare you for integration and ABT construction. Many analytics projects require transforming lower-level records into one row per customer, employee, route, store, product, or other analytical entity.

## Project Connection

For your project, begin identifying the likely unit of analysis. If your raw data is at a lower level than your final question, you may need aggregation before modeling or reporting.
