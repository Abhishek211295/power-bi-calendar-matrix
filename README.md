# Power BI Calendar Matrix

A beginner-friendly Power BI project showcasing a calendar date table with calendar, weekday, weekend, and fiscal-period fields.

## Overview

This project demonstrates how dates can be organized into a calendar table and displayed in a Power BI report. The table contains one row per date, along with useful attributes for exploring dates by month, year, weekday, weekend status, and fiscal period.

## Report preview

![Calendar Matrix report](screenshots/calendar-matrix.png)

> Add a screenshot of your report to the `screenshots` folder and name it `calendar-matrix.png`, or update the image path above.

## Date table fields

| Field | Description |
|---|---|
| Date | Individual calendar date |
| Month | Numeric month value |
| Month Name | Short month name |
| Year | Calendar year |
| Year Month | Year and month in `YYYY-MM` format |
| Weekday | Numeric weekday value |
| Weekday Name | Name of the weekday |
| Weekday/Weekend | Indicates whether the date is a weekday or weekend |
| Is Weekend? | Weekend indicator |
| Fiscal Period | Fiscal year and quarter label |

## Fiscal calendar

The report currently displays fiscal periods using an April–March fiscal-year convention. For example, January 2025 appears as `FY2024-Q4`.

## How to view the report

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. View the **Calendar Matrix** report page.
4. Explore the date table and its calendar and fiscal-period fields.

## Skills practiced

- Organizing date attributes in a Power BI table
- Working with calendar and fiscal-period fields
- Displaying date data in a Power BI table visual
- Practicing Power BI report layout and presentation

## Project files

- `Calendar-Matrix.pbix` — Power BI report
- `screenshots/calendar-matrix.png` — report screenshot

## Future improvements

- Add slicers for year and month.
- Add month-start, month-end, week-number, and day-of-year fields.
- Add sorting columns for month and weekday names.
- Add holiday and working-day indicators.
- Connect the date table to a sample fact table and demonstrate date filtering.

## About

This project was created for Power BI and DAX practice. It is a learning project and may be expanded with additional date fields and report features.
