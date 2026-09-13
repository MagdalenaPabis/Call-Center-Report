# Call-Center-Report

The “Call Center Report” project was carried out as part of the “From Data to Report” course organized by Polska Fundacja Przedsiębiorczości in 2026.
The link to the event is provided below:


https://umio.to/wydarzenia/3062?editionId=4274

Course participants were given the following tasks to complete:


•	Display 4 metrics at the top (number of calls, number of successful calls, number of contracts concluded, sales value)


•	These 4 metrics can be filtered using the slicer—use the icons


•	The report will display a pivot table with the fields from point 1 visible for each salesperson


•	The table from point 3 will have conditional formatting using data bars


•	The tables from point 3 should not be filtered using the slicer from point 2


•	Add charts:


•	A column chart showing the total number of successful calls and the total number of contracts concluded—both broken down by month


•	Total sales value broken down by month


•	Average call duration broken down by month


•	Consider what could be improved and make the necessary corrections


Project aim:


Create an interactive report in Excel that allows users to analyze calls, successful calls, contracts concluded, and effectiveness by operator and transaction time.


Tools:


The project was created using Microsoft Excel.

Data:


The source data was in an Excel file. It contained 313 rows and 8 columns with the following headers: Operator, Data, Połączenia, Skuteczne połączenia, Czas trwania, Zawarte umowy, Konwersja, Wartość sprzedaży.


<img width="945" height="486" alt="image" src="https://github.com/user-attachments/assets/7210f804-e84d-4ed3-b6fe-391a1b4c1437" />


This is what the data copied from the source file looks like.


Notes:


This project was carried out to improve my skills and organize the knowledge I have gained in the field of data analysis. I am including this project in my portfolio as evidence of the practical experience I have gained. To expand my knowledge of formulas and working in Excel, the report will be prepared in English.


Data preparation:


The report will be prepared in English, so I am translating the headings into English and will be working in the English version of Excel.


<img width="945" height="471" alt="image" src="https://github.com/user-attachments/assets/15ae8c1e-2e12-45aa-8387-fd43c25f7b77" />


Next, I check the data and see what else needs to be corrected.


There is a small error here, and the operators’ names are still duplicated. I fix it by selecting the names and double-clicking in the lower corner of the selected area.


Then I set the date format.


<img width="945" height="465" alt="image" src="https://github.com/user-attachments/assets/cbde51c3-19cb-4c71-ac88-939c0c3655e6" />


After that, I select the currency format for the column containing the sales figures.


<img width="945" height="475" alt="image" src="https://github.com/user-attachments/assets/589b34da-db3d-4d87-a670-ac63c2a1fd2c" />


There is another empty column there called “Conversion.” I need to calculate the conversion rate in that column to determine how effective the sales are.


<img width="945" height="473" alt="image" src="https://github.com/user-attachments/assets/b72faba6-64e4-4fb1-88ee-7a54274fee46" />


I divide the number of contracts signed by the number of calls, and then set the format to a percentage.


If the data is already complete, then it is a good idea to convert this range into a table so that you can add more rows in the future, and the report will be dynamic and remain useful for a long time. Therefore, with the cursor in this range, press CTRL + T.


<img width="945" height="466" alt="image" src="https://github.com/user-attachments/assets/41802b94-d314-4ce6-8f76-a1c9dbfa99d8" />


I approve the creation of the table, select its color scheme, and rename it.


<img width="945" height="464" alt="image" src="https://github.com/user-attachments/assets/a18ed2ae-7e2b-4a00-b931-6a73fcf80e2c" />


Analysis process:


The table is ready. I return to the guidelines to make sure I know exactly what I need to calculate.


Project guidelines:


•	Display 4 metrics at the top (number of calls, number of successful calls, number of contracts concluded, sales value)


•	These 4 metrics can be filtered using the slicer—use the icons


•	The report will display a pivot table with the fields from point 1 visible for each salesperson


•	The table from point 3 will have conditional formatting using data bars


•	The tables from point 3 should not be filtered using the slicer from point 2


•	Add charts:


•	A column chart showing the total number of successful calls and the total number of contracts concluded—both broken down by month


•	Total sales value broken down by month


•	Average call duration broken down by month


•	Consider what could be improved and make the necessary corrections



First, I create a new worksheet called “Analysis,” which will contain a pivot table with the calculations.


<img width="945" height="477" alt="image" src="https://github.com/user-attachments/assets/7fe26afa-cec0-4557-b17f-525f0e9ddcb7" />


I transfer the following values to the field called Values, in that order: Calls, Successful Calls, Concluded Contracts, Sales.


<img width="945" height="438" alt="image" src="https://github.com/user-attachments/assets/4669882f-3197-4643-8cbb-886c6b41bb9f" />


These totals should appear in the top row of the report, so I create a new worksheet named “Report” and set up the fields that will be filled with the calculated values.


<img width="945" height="465" alt="image" src="https://github.com/user-attachments/assets/f3b42cdb-3ccd-479b-90f4-a9540411e187" />


Once the text field is ready, I reference the pivot table, and this is how the selected values appear there.


<img width="945" height="477" alt="image" src="https://github.com/user-attachments/assets/b218134e-6e02-481f-933a-01496b701568" />


I copy the text field containing the formula and modify it to match the range from which each field is supposed to retrieve its values.


<img width="945" height="465" alt="image" src="https://github.com/user-attachments/assets/ded54137-d13a-4cf8-aa2b-f2fea0778ff9" />


These values are to be filtered by the operator. I insert a slicer by selecting the “operator” category.


<img width="945" height="475" alt="image" src="https://github.com/user-attachments/assets/ab01e95b-bde4-4057-8e0e-1e408c4cf61d" />


Next, I cut the slicer from the current worksheet, paste it into the report worksheet, and adjust its appearance to match the dashboard.


<img width="945" height="499" alt="image" src="https://github.com/user-attachments/assets/62400985-ff9d-4757-babf-06ecf1c83214" />


I add a second pivot table and change the headers by removing the text “Sum of.”


<img width="945" height="460" alt="image" src="https://github.com/user-attachments/assets/0050ddc0-7a8b-4b6d-a7ae-7b5be1efd5dd" />


To make it easier to analyze the values, I insert data bars, which will visually engage the report's audience and improve readability.


<img width="945" height="476" alt="image" src="https://github.com/user-attachments/assets/d2c227ee-3d5d-4b2f-8dfb-4983f05f1464" />


It is also worth sorting the results by sales value, because we are most interested in who sold the most.


<img width="945" height="467" alt="image" src="https://github.com/user-attachments/assets/8ae23142-00d6-4496-a0b7-6f851bde9449" />


<img width="945" height="670" alt="image" src="https://github.com/user-attachments/assets/530e725a-cf0b-4a8b-9a46-0fdeba169f9f" />


The values have been sorted. Next, I will prepare additional tables with calculations, which I will use to create charts.


<img width="945" height="483" alt="image" src="https://github.com/user-attachments/assets/47a03b10-fc1a-44a2-a00f-3b5af1520608" />


I create pivot tables that will be used to generate charts. First, a chart showing contracts signed over time, then a chart showing sales over time.


<img width="945" height="469" alt="image" src="https://github.com/user-attachments/assets/27c16a9c-2596-4a9c-bbdf-c7f13bee06f4" />


Finally, the average call duration in seconds.


<img width="945" height="481" alt="image" src="https://github.com/user-attachments/assets/508115c7-b6b9-4bc6-a0d9-a6c44254edc7" />


The tables are now ready to be used to create visualizations.


The process of creating a report and visualizations.


Before I insert the charts based on the pivot tables, I will create one more thing that will improve the report’s readability. Namely, a highlight bar that will appear in the calls table and highlight the operator we selected in the slicer.


A highlighted bar when selecting a call operator.


I copy the pivot table.


<img width="945" height="569" alt="image" src="https://github.com/user-attachments/assets/bf2b0669-4c6c-41c6-817b-31c5bd9c191e" />


I select a call operator.


<img width="945" height="507" alt="image" src="https://github.com/user-attachments/assets/e589102b-349b-4266-b5f4-446da2a083f1" />


Create a reference in another cell.


<img width="945" height="532" alt="image" src="https://github.com/user-attachments/assets/d9dd608e-6146-4f9a-bc5b-65233ed72f2c" />


I use the =IF and =COUNTA functions to create a logical function that finds the exact operator that is selected.


<img width="945" height="557" alt="image" src="https://github.com/user-attachments/assets/06b078a3-9517-4534-8409-17dbe1c1e0a3" />


I select the pivot table, choose conditional formatting, then add a new rule.


<img width="945" height="505" alt="image" src="https://github.com/user-attachments/assets/ff5a33e0-123a-4871-9251-73bf018e58b6" />


Next, I select: “Use a formula to specify the cells to be formatted.”


<img width="945" height="480" alt="image" src="https://github.com/user-attachments/assets/9eaab885-8f39-4fed-80d5-4af6b8349c6a" />


I select a cell from the pivot table, and if its value matches the formula created in the “Analysis” worksheet using the IF and COUNTA functions, then I select the format and fill the cells.


<img width="945" height="514" alt="image" src="https://github.com/user-attachments/assets/bc3ab15a-e6f7-4268-839a-5a8a4e0678a3" />


And the function did not work—an error appeared, but I found it quickly. It was a duplicate reference to the worksheet.


<img width="945" height="491" alt="image" src="https://github.com/user-attachments/assets/99e5853f-0dba-4980-8cce-b4be47cf10da" />


Corrected.


<img width="945" height="564" alt="image" src="https://github.com/user-attachments/assets/976b62d8-8266-4ccd-aa53-802da70fc8d3" />


The bar works—it worked.


Charts.


Another issue I still need to fix is changing the names of the months from Polish to English.


<img width="945" height="469" alt="image" src="https://github.com/user-attachments/assets/0fffdca1-5764-497b-952c-ecc79f9d78f8" />


After checking the source data, I make sure that the error is not due to the date format, but rather to the fact that when creating a pivot table, Excel pulls the date from the operating system, which is the Polish version. Of course, I could change the system settings, but this is a single project, and I work on this computer all the time, so I choose a different solution to this problem.


I add two additional columns to the source data: Month EN and Month Number.


<img width="945" height="476" alt="image" src="https://github.com/user-attachments/assets/2f724546-7d51-49b1-b26b-d5b6b355591b" />


I enter a formula that will return the month from a date and immediately convert it to the English version. I also enter a formula that will return the number for each month.


<img width="945" height="470" alt="image" src="https://github.com/user-attachments/assets/084072be-9e9e-4b8a-8f47-0da8131b3c29" />


<img width="945" height="487" alt="image" src="https://github.com/user-attachments/assets/a626ad25-fde3-498e-893c-a28da9e308a5" />


In the pivot table, in the Rows field, I remove “Month(Date)” and select “Month EN.” The month names have changed to their English equivalents.


<img width="945" height="474" alt="image" src="https://github.com/user-attachments/assets/0c7633ad-38e0-4399-beb0-f24d62f81b60" />


There is also the issue that the months are listed in alphabetical order. I considered sorting them by number, but it is also possible to create a list of months in order to sort by that.


I select “Advanced” settings in Excel. In the ‘General’ section, I click “Edit Custom List.”


<img width="945" height="518" alt="image" src="https://github.com/user-attachments/assets/b24b6569-8d31-4715-b48e-35dd491e4404" />


I write down the names of the months in the correct order and add a list, because it might come in useful in the future.


<img width="945" height="479" alt="image" src="https://github.com/user-attachments/assets/d49f3a36-d25e-43aa-80c4-ff9e5099f020" />


Next, I click on the pivot table and select more sorting options.


<img width="945" height="491" alt="image" src="https://github.com/user-attachments/assets/212ce6c9-b969-4787-964a-205c3711a78f" />


I choose more options and my new list.


<img width="945" height="488" alt="image" src="https://github.com/user-attachments/assets/1661d9f6-661b-4c97-98bd-f5ce8e420b21" />


I approve, then select “Sort A to Z,” and the list is sorted in exactly the order I wanted.


In the other two tables, I remove the Month(Date) field and insert “Month EN” into the Row field. I no longer need to sort, because everything works correctly.


<img width="945" height="462" alt="image" src="https://github.com/user-attachments/assets/7053121b-99a5-439b-b056-45e07a2c0492" />


I go back to the guidelines once again because I need to create specific types of charts.


The first chart is supposed to show the total number of successful calls and the total number of contracts concluded, both broken down by month. I adjust the chart to match the rest of the report, choose to hide the buttons, move the legend, and change the color. Then I cut the chart and paste it into the finished report.


<img width="945" height="473" alt="image" src="https://github.com/user-attachments/assets/3daf9758-30ab-4c9e-a4dc-dd23b176a051" />


This is what I do with every chart. All that remains is to arrange everything so that it looks aesthetically pleasing and make a few minor cosmetic changes.


<img width="945" height="518" alt="image" src="https://github.com/user-attachments/assets/0d7d0911-fb77-4193-9827-259b3ac6ba9a" />


The report is complete. It can be filtered by operators and the results can be compared.


<img width="945" height="481" alt="image" src="https://github.com/user-attachments/assets/860de8b5-a09e-4da2-b538-fc3cb570ff8c" />





<img width="945" height="430" alt="image" src="https://github.com/user-attachments/assets/cabd1775-114e-4fe0-8ddb-5bc3751d4502" />





























