# Byke buyers:
We have to work on an excel sheet where we get the information of the people who buy or do not a bike in a store.
The columns are the identification of the client (ID), the Marital Status, Gender, Number of children (Children), Education, Occupation, if they are homeowners (Home Owner), the number of cars (Cars), Commute Distance, Region, Age and if the Purchased a Bike.

### First step: Create 3 new sheets
We will call them Working Sheet (here we gonna modify the data without touching the original), Pivot Table (), and Dashboard (where the information of interest will be shown).

### Second step: Move de information to the Working Sheet
Just a copy-and-paste procedure to preserve the original or raw data and start cleaning the information.
Here we will change the format to a table and start seeing the categories and ranges of the different columns.
We found that:
-The Marital Status is M for Married or S for Single. 
-The Genders are F for females or M for Males.
-The Income ranges from 10,000 up to  170,000.
-The children ranges from 0 up to 5.
-The Educations are Bachelor,  Graduate Degree, High School, Partial College, and Partial High School. 
-The Occupations are Clerical, Management, Manual, Professional and Skilled Manual. 
-Can be Home owners or not. 
-The number of Cars ranges from 0 to 4. 
-The Commute Distance is categorized by ranges of 0 to 1 Mile, 1 to 2 Miles, 2 to 5 Miles, 5 to 10 Miles, and +10 Miles.
-The regions are Europe, the Pacific, and North America
-The Age ranges from 25 up to 89
-Purchased or do not purchase a Bike

### Third step: Start cleaning!
The next thing that we should do is remove duplicates. This is an easy task, just by selecting all the data, going to the Data Tab on Excel, and clicking on Remove Duplicates.
Next, we gotta spell out the classifications on the Marital Status and Gender Columns so everyone can understand what M, S of F means. 
The Age of each individual is not as useful as if we put it in brackets, so we are going to create 3 categories and we will put those in a new column:
-from 0 to 30 will be Adolescents
-from 31 to 55 will be Middle Age
-from 55 and beyond will be Old

### Fourth step: Building the pivot table
We are going to select all the information on the Working Sheet go to the Insert tab and insert a pivot table.
Here we gonna answer some questions that can bring valuable information from the table, for example:
Which is the average income per customer by gender?
Which is the most frequent Commute Distance per customer?
Which are the customer's ages?
In every single one of the questions, we gotta always keep in mind that the focus of the business is to sell bikes so the information we put on the graphics giveback value to the company.
Then we will make graphs for every single pivot table that we created, that so the information is really simple to understand.

### Fifth step: Building the Dashboard
Here we copy the graphs we created on the Pivot Table sheet and paste them onto the Dashboard sheet.
Now we can go to the PivotChart Analyze tab and insert slicers, so we can see more information on the same graph.
Here we take the sub-questions that can be asked from our first visualization and can be answered by clicking a new filter.
We can use the slicers so that they affect only a few charts and leave others as they are. These make it easier to find more information using multiple filters for the same chart.
Finally, to get a more clear view, we are going to select all, go to the View tab, and remove the gridlines.