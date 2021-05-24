# WALKTHROUGH: Calculations in a Google Sheet

---
Taking the plastic bags dataset, filter for just 2019 then copy all cells and paste them into a fresh sheet. Sort by Number of bags (Z-A so the biggest are at the top)

>=C2+C3+C4

will give you the sum of the top three retailer chains (by numbers of bags)

>=SUM(C2:C4)

will also give you the sum of the top three retailer chains (by numbers of bags)

>=AVERAGE(C2:C11)

will give you the number of bags a "top ten" retailer chain handed out, on AVERAGE

Go to the bottom of Column C and in the first empty cell in the column, type:

>=SUM(C2:C196)

will add all the cells in Column C and give you a total for the number of bags

>=SUM(C2:C196) / 52

will give the total number of bags for these retailer chains in 2019, divided by 52 for a weekly average.
