# WALKTHROUGH: Calculations in a spreadsheet

> Introduction. The fastest way to interview a dataset ("Who had the most...?", "Which company changed the least...?" etc.) is often to use built-in functions that take the information in cells and calculate for example the maximum value, or the average value, or the sum of all the values.

---
Taking the plastic bags dataset [already used](https://aodhanlutetiae.github.io/dj/sheets), filter for just 2019 then copy all cells with information and paste them into a new sheet. Sort (Z-A) by Number of bags, so the biggest numbers are at the top.

Type these into an empty cell:

>=C2+C3+C4

will give you the sum of the top three retailer chains (by numbers of bags)

>=SUM(C2:C4)

will also give you the sum of the top three retailer chains (by numbers of bags)

>=AVERAGE(C2:C11)

will give you the number of bags a "top ten" retailer chain handed out, on AVERAGE

Go to the bottom of Column C and in the first empty cell in the column. Type:

>=SUM(C2:C196)

will add all the cells in Column C and give you a total for the number of bags

>=SUM(C2:C196) / 52

will give the total number of bags for these retailer chains in 2019, divided by 52 for a weekly average.
