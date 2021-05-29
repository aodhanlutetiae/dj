# WALKTHROUGH: Calculations in a spreadsheet

<br />
> Often, the fastest way to interview a dataset ("Who had the most...?", "Which company changed the least...?" etc.) is to use simple calculations or functions that are built into your spreadsheet programme that take the information in cells and calculate, for example, the maximum value, or the average value, or the sum of all the values and so on.

<br />
Taking the plastic bags dataset [you've already used](https://aodhanlutetiae.github.io/dj/excel), filter for just the year 2019-20 then copy the column names and all cells with information and paste them into a new sheet.

Give the sheet a name (on the tab in the bottom left), rename the columns, freeze the top row and sort by 'Number of bags', so the biggest numbers are at the top (Z-A).

Type this into any available empty cell and hit Enter.

>=C2+C3+C4

It will give you the sum of the cells C2, C3 and C4, which is the total number of bags from the top three retailer chains (by numbers of bags)

<br />
![pic zero](/images/walkthroughs/e_calc1.png)

<br />
When you select the cell (which shows around 280 million), you can see the calculation (=C2+C3+C4) in the upper left of the sheet:

<br />
![pic zero](/images/walkthroughs/e_calc2.png)

<br />
>=D2/C2

is a simple calculation to divide one cell by another. It will divide the money taken in by Ocado (D2) by the number of bags (C2) given out by Ocado and show you how much was paid per bag by customers.

<br />
>=SUM(C2:C11)

will give you the sum of the top ten retailer chains (by numbers of bags)

<br />
>=AVERAGE(C2:C11)

will give you the average number of bags handed out by a retailer chain in the top ten

<br />
>=SUM(C2:C196)

will add all the numbers in Column C and give you the total number of bags for all the retailers in 2019-20.

<br />
>=SUM(C2:C196) / 52

takes the total number of bags for these retailer chains in 2019, and divides by 52 for a weekly average.

<br />
>=COUNTA(B2:B195)

'Count A' will count *all* items in a column (not just numbers). Here it returns 194 for the number of retailers

<br />
>=COUNTIF(B2:B195, '*University*')

'Count if' will count any cells only if the word 'University' appears. The * is a wildcard and means anything can appear right before or right after the word.
