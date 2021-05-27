# WALKTHROUGH: Get a CSV file into a spreadsheet

<br />
> Background. Since 2015, shoppers in England have had to pay a 5p levy for single-use plastic bags. This was increased to 10p in May 2021. Larger retailers have not only to charge customers but must also collect data on the numbers of bags given to customers, the money collected and what they did with the money. The steps below walk through how to get some of this data into a spreadsheet and start to analyse it.

<br />
- [Higher plastic bag charge comes into force in England (BBC)](https://www.bbc.co.uk/news/business-57193108)
- [Government guidance to retailers on carrier bag charges](https://www.gov.uk/guidance/carrier-bag-charges-retailers-responsibilities)

<br />
---
**IMPORTING YOUR FILE**

Download the following CSV file to your computer: [bags_2years.csv](https://drive.google.com/file/d/15vDqg-u6W4tHouC42uvhMOdy21oTl3ov/view?usp=sharing)

Once the file is on your computer, right-click on it and, under **Open With**, choose the **Text Edit** or **Notepad** programme to look at what's actually in the file.

It's a bit of a jumble but you can see that all the pieces of information are separated by commas:

<br />
![pic zero](/images/walkthroughs/wt0.png)

<br />
Now that you've seen what's inside your file, close it and navigate to a Google Drive online

Open a new Sheet by clicking **+ New**, then **Google Sheets**, then **Blank Spreadsheet**

<br />

![pic new](/images/walkthroughs/wt_new.png)

<br />

In the new Sheet, click on the **Untitled Spreadsheet** box on the top left and give your Sheet a name

Under **File** select **Import**, then **Upload**

Choose your **bags_2years.csv** file from your computer

If asked in a dialogue box about **Import Location**, select **Insert New Sheet** and for **Separator Type**, choose **Comma** or **Detect Automatically**

You should now have the data from the CSV file in your Google Sheet:

<br />
![pic one](/images/walkthroughs/wt1.png)

<br />
---
**ORGANISING YOUR SHEET**

Adjust the width of the four columns (Widen or narrow in the row containing the column letter names: A, B, C etc.). There are several data types here and **numbers** are aligned on the right, while **text** is aligned on the left.

In the bottom left, your sheet will have a tab called **bags_2years**. Right click on the tab and select **Duplicate**. This will generate a copy of your Sheet with a tab entitled **Copy of bags_2years**. Double click on this tab and rename it as **data**.

<br />
![pic two](/images/walkthroughs/wt_dup.png)

<br />
Add another Sheet by using the **+** button just to the left of the tabs. Give this sheet the name **Source** and somewhere in the sheet paste the following url, which is the where the data in your CSV file came from:

- https://data.gov.uk/dataset/682843a8-168c-4056-b6fe-741161a39f60/single-use-plastic-carrier-bags-charge-data-for-england

<br />
---
**THE DATA**

At this point we have imported the CSV file to a Sheet, we have named the Sheet and we have duplicated it so that we have a copy of the original data if we need it. We've also added the source for the data so that if we come back to work on this in six months we'll know where the data came from.

Our data has four columns:

- Year
- Company name
- Number of single use plastic bags issued
- Gross proceeds of charge

It shows how many single-use plastic bags each major retailer issued in England in 2018-19 and 2019-20, and how much money each collected from charging customers for the bags. The data was published in 2020 by the Department for Environment, Food and Rural Affairs (DEFRA).

<br />
---
**NAVIGATING THE SHEET**

Under the menu **View**, choose **Freeze** then **1 row**. This will keep the column names in place as you scroll down through the sheet.

<br />
![pic three](/images/walkthroughs/wt3.png)

<br />
Use CMD and a down arrow to jump to the bottom of the dataset. Use CMD and a right arrow to jump to the right of the dataset and so on.

Use CMD and SHIFT and arrows to *select* all the cells when you jump to the edge of the dataset.

Select all the cells in Column B ('Company Name'). On the bottom right the Sheet will automatically supply a Count of the cells that contain information.

<br />
![pic four](/images/walkthroughs/wt4.png)

<br />
If you select all the cells in Column C ('Number of single use plastic bags issued') that have numbers, there will be numerical calculations in the bottom right and not simply a count of the number of cells.

<br />
![pic five](/images/walkthroughs/wt5.png)

<br />
Adjust the number of decimal points showing in Column D ('Gross proceeds of charge') by using the **Increase / Decrease Decimal Places** buttons

<br />
![pic six](/images/walkthroughs/wt6.png)

<br />
---

**SORT & FILTER**

Select any cell in your data. In the menus, go to **Data** and choose **Create a filter**

<br />
![pic seven](/images/walkthroughs/wt7.png)

<br />

Now you can filter a column and select, for example, only the 2019-20 rows

<br />

![pic filter](/images/walkthroughs/wt_filter.png)

<br />
Go back to **Data** and choose **Remove filter**

Beside the letter of each column (A, B, C etc.), there is a hidden triangle with a drop down menu. Clicking on this lets you select **Sort A-Z** or **Sort Z-A**. You can sort all the company names alphabetically. Or you can sort a column of numbers from the biggest to the smallest. Sort the Company Name column alphabetically.

<br />
![pic nine](/images/walkthroughs/wt9.png)

<br />

Try sorting the "Number of single use plastic bags issued" column to see what company charged for the biggest (or smallest) number of bags over the two years.

<br />

---
**MORE**

The learning platform GCF has [more tutorials (sections 8-16)](https://edu.gcfglobal.org/en/googlespreadsheets) on the steps above.

*[Back to main page](https://aodhanlutetiae.github.io/dj/)*
