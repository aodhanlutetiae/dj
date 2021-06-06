# Hints for data practice questions

## Wales pubs — Find the number of pubs per 100,000 people

- The areas are organised in the same way in the 'population' sheet (by area code), so you can simply select all the numbers in the 'mid-2018 pop' column and copy using CMD / CTRL + C or Edit / Copy.

- Paste these numbers into the first empty column in the 'data' sheet so they line up with the 22 local areas.

- The first row with data is Anglesey and should be showing 60 pubs in 2018 and a population of 69,961.

- There are 60 pubs with 69,961 people. How many pubs would there be for one person? Divide 60 / 69,961 using =T2/U2 and you will get 0.00085762

- Each person represents a tiny fraction of a single pub, which is not very useful. Adjust the formula to multiply the result by 100 to see how many (or what fraction) pubs there are for 100 people: =(T2/U2)*100

- It's still a small fraction. Adjust again to get the number of pubs per 10,000 people.

- Once you have a useful number for Anglesey, drag the formula down the column to get the answers for all the other areas.
