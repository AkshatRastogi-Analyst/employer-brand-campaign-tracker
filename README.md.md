# Employer Brand Campaign Tracker (Excel)

**[Download the Excel workbook (Employer_Brand_Campaign_Tracker.xlsx)](https://github.com/AkshatRastogi-Analyst/employer-brand-campaign-tracker/raw/main/Employer_Brand_Campaign_Tracker.xlsx)** | [All project files on GitHub](https://github.com/AkshatRastogi-Analyst/employer-brand-campaign-tracker)

An Excel workbook for planning, running and reporting on recruitment marketing campaigns. It keeps the content calendar, channel results, careers website checks and partner follow-ups in one place, and turns them into a single dashboard.

**Tools:** Microsoft Excel (SUMIFS, COUNTIFS, INDEX/MATCH, data validation, conditional formatting, charts)

> **Note on the data:** every row in this repository is **sample data for a fictional company**, made up to show how the tracker works. It is not real campaign data. Delete the sample rows and enter your own to use it.

## The problem

Employer brand and recruitment marketing work is spread across many places: a content plan in one file, results in each platform, careers page changes in emails, and follow-ups with recruiters and agencies in chat. When someone asks "how did the campaign do?" or "what is late?", the answer takes hours to put together.

## What the workbook does

| Sheet | Purpose |
|---|---|
| **Dashboard** | Headline numbers, results by channel and by campaign, content and task status, careers page check rate, and two charts |
| **Settings** | Report date, the two targets (click-through rate, visit-to-apply rate) and the channel names |
| **Campaigns** | One row per campaign: ID, name, goal, dates, status |
| **Content_Calendar** | What goes out, when, on which channel, who owns it, and its status. Late items are flagged automatically |
| **Performance** | Results by campaign, channel and week: impressions, clicks, careers page visits, applications |
| **Careers_QA** | Checklist for careers website pages: pass, needs update, or fail, with notes |
| **Tasks** | Follow-ups with recruiters, agencies, suppliers and internal teams, with due dates and overdue flags |
| **Guide** | How to use the file and what every measure means |

## How the measures are worked out

| Measure | Formula |
|---|---|
| Click-through rate (CTR) | Clicks / Impressions or sends |
| Visit-to-apply rate | Applications / Careers page visits |
| Result | On target if CTR and visit-to-apply rate are both at or above the targets on Settings, otherwise Below target |
| Overdue | The date is before the report date and the item is not Live, Done or closed |

The targets on Settings (2% CTR, 4% visit-to-apply) are the author's assumptions and can be changed.

## How to use it with your own data

1. Open `Employer_Brand_Campaign_Tracker.xlsx`.
2. Delete the sample values in the yellow cells on each sheet. Leave the formula columns alone.
3. Add your campaigns on **Campaigns**, then use each Campaign ID on the other sheets.
4. Set the report date and targets on **Settings**.
5. Read the **Dashboard**.

Yellow cells with blue text are inputs. All other cells are formulas, so changing any entry updates the Dashboard and both charts. Data check and ID check columns flag numbers that do not add up and campaign IDs that are missing or repeated. Anything on a channel or campaign that is not listed lands in an Other row, so the totals always match the data sheets. The Content Calendar and Performance sheets each have room for 300 rows.

## Files

```
employer-brand-campaign-tracker/
├── Employer_Brand_Campaign_Tracker.xlsx
└── README.md
```

## Author

Akshat Rastogi | [GitHub](https://github.com/AkshatRastogi-Analyst) | akshatrastogi0425@gmail.com
