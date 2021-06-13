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

<br />
- You will get 0.00085762: there is a *tiny* fraction of a pub for each person. This is not very useful for us so adjust the formula: multiply the result by 100 to see how many pubs there are for 100 people:

> =(T2/U2)*100

<br />
- It's still a small fraction of a pub for 100 people in Anglesey (0.085762). Adjust again to get the number of pubs per 10,000 people:

> =(T2/U2)*10000

<br />
- Now you should have a useful number for 'the number of pubs in Anglesey per 100,000 people'. Paste the formula into the cells below, by dragging the small black square straight down. The formula will be adjusted for each row automatically so you will get a number for each area.

![pic zero](/images/questions/sq_corner.png)

<br />
---

## Ireland pubs — Find 2005-18 change as a percentage of 2005 figures

- In the first free column, calculate the difference between the 2005 and the 2018 numbers for a county

> =B2-O2

<br />
- Taking Longford as an example, the 2005-2018 difference is 22, down from 113 to 91. We will want to see this drop (22) as a proportion of the 2005 (113) figure:

> 22/113

<br />
- But we want to see this proportion expressed in 100 rather than out of 1, so:

> (22/113) *  100

- or

> =(P2/B2) * 100

<br />
So the drop in Longford (22) is 19% of the number of pubs that were there in 2005

<br />
---

## Pivot tables to count things (Ireland pubs, Party donations)

Here is a [video walkthrough](https://youtu.be/N8MaHOv0X2Q) of how to build pivot tables to answer the questions about Irish pubs and donations to UK political parties.
