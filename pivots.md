# Pivot tables in spreadsheets

> A pivot table reorders data in a spreadsheet so that you can get answers that weren't accessible from the dataset as it was initially organised.

---

In the following Google Sheets workbook, examine the tab / Sheet named 'data':

[google sheet](https://docs.google.com/spreadsheets/d/1P8BU2SLGSoRoDpTsTWL982GYcwUpAQwWWahCoUReets/edit?usp=sharing)

It is a bigger version of the data on plastic bags in English retailers.

- What size is this dataset?

- How many different years are included?

How do we compare the total number of plastic bags distributed by all retail companies from year to year? One (slow) solution would be to filter by year and get a sum for 2016-17, then a sum for 2017-18 and so on.

The pivot table in the next tab ('pivot table SUM') does this for us automatically and lets us compare the four years very quickly.

What if we wanted to compare the number of bags distributed by a retailer *on average* from one year to another?

We could get a count of the number of shops: in 2016-17 there are 261 shops listed. We can then add up the total number of plastic bags distributed that year (2,116,049,476). If we divide the total number of bags that year by the number of retailers with data that year, we'll have the average number of plastic bags distributed by a retail company in England in 2016-17...

> 2,116,049,476 / 261 = 8,107,469

Or just over eight million bags.

This has been done in another tab in the workbook ('pivot table AVR').

Here you can download [an Excel spreadsheet](URL) with the same pivot tables.
