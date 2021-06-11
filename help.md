# Hints for data + journalism practice

> Here are outlines of how to get the answer (or get close to the answer) for some questions in the Practice section.

<br />

---

## Wales pubs — Find the number of pubs per 100,000 people (2018)

- The areas are listed in the same order in the 'population' sheet (by area code), so you can simply select all the numbers in the 'mid-2018 pop' column and copy using CMD / CTRL + C or Edit / Copy

- Paste these numbers into the first empty column in the 'data' sheet (the pub numbers) so they line up with the 22 local areas

- The first row with numbers is Anglesey and should be showing 60 pubs in 2018 and a population of 69,961

- There are 60 pubs and 69,961 people. How many pubs would there be for one person?

> Divide 60 / 69,961 using =T2/U2

- You will get 0.00085762: there is a *tiny* fraction of a pub for each person. This is not very useful for us so adjust the formula: multiply the result by 100 to see how many pubs there are for 100 people:

> =(T2/U2)*100

<br />
- It's still a small fraction (0.085762). Adjust again to get the number of pubs per 10,000 people

> =(T2/U2)*10000

<br />
- Now you should have a useful number for 'the number of pubs Anglesey per 100,000 people'. Paste the formula into the cells below, by dragging the small black square straight down. 

![pic zero](/images/questions/sq_corner.png)

<br />
---

## Ireland pubs — Find 2005-18 change as a percentage of 2005 figures

- Calculate the difference between the 2005 number and the 2018 numbers for the first county

> =B2-O2

- Drag that formula down the rest of the column

- Now you want to consider this figure (for Longford, the difference between 2005 and 2018 is 22) in terms of the 2005 number (113, for Longford).

> 22/113

- We want to see this amount (22) out of 100 rather than out of 113, so:

> (22/113) *  100

- or

> =(P2/B2) * 100

<br />

---

## Ireland pubs — use a pivot table to count things by province
