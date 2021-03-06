# Pivot tables in spreadsheets

> A pivot table reorders spreadsheet data so you can get answers that aren't immediately obvious. Below is an example of the kind of calculations a pivot table can carry out for you; the goal is simply to understand the operation that the pivot table is running for you.

---
<br />

In this [Google Sheets workbook](https://docs.google.com/spreadsheets/d/1P8BU2SLGSoRoDpTsTWL982GYcwUpAQwWWahCoUReets/edit?usp=sharing), examine the tab / Sheet labelled 'data'. It is a bigger version of the dataset on plastic bags in English retail chains.

- What size is this dataset?

- How many different years are covered?

How can we compare the total number of plastic bags distributed from year to year?

One (slow!) solution would be to filter by year and get the sum of all bags in 2016-17, then the sum of all bags in 2017-18 and so on.

The first pivot table ('pivot table SUM') has been used to calculate this quickly, and lets us compare the different years.

---

<br />
What if we wanted to compare the *average* number of bags distributed by companies from one year to the next?

We could get a count of the number of shops: in 2016-17 there are 261 shops listed. We can then add up the total number of plastic bags distributed that year (2,116,049,476).

If we divide the total number of bags that year by the number of retail companies, we'll have the average number of plastic bags distributed by a retail company in England in 2016-17:

> 2,116,049,476 (bags) divided by 261 (companies) = 8,107,469 bags per company, on average

Or, just over eight million bags.

But again, we can do this much more quickly using a pivot table (as in the 'pivot table AVR' sheet).

Here you can download [an Excel spreadsheet](csvs/bags_pivots.xlsx) with the same pivot tables.

---

<br />
If you want to build the pivot table yourself, there is a good [Excel tutorial](https://sites.google.com/view/mj-basic-data-academy/excel-basics) for pivot tables by MaryJo Webster.

On her webpage under **Pivot Tables** you'll find a:

- cheat sheet
- video
- link to data
- practice exercise
