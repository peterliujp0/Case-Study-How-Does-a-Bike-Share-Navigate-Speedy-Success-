# Case-Study-How-Does-a-Bike-Share-Navigate-Speedy-Success-
Coursera Google DA Certificate Project 1 

Three questions will guide the future marketing program:
1.
How do annual members and casual riders use Cyclistic bikes differently?
2.
Why would casual riders buy Cyclistic annual memberships?
3.
How can Cyclistic use digital media to influence casual riders to become members?

Case Study Roadmap -Prepare
Guiding questions ● Where is your data located? ● How is the data organized? ● Are there issues with bias or credibility in this data? Does your data ROCCC? ● How are you addressing licensing, privacy, security, and accessibility? ● How did you verify the data’s integrity? ● How does it help you answer your question? ● Are there any problems with the data?
Key tasks 1. Download data and store it appropriately. 2. Identify how it’s organized.

Follow these steps:
1.
Download the previous 12 months of Cyclistic trip data.
2.
Unzip the files.
3.
Create a folder on your desktop or Drive to house the files. Use appropriate file-naming conventions.
4.
Create subfolders for the .CSV file and the .XLS or Sheets file so that you have a copy of the original data. Move the downloaded files to the appropriate subfolder.
5.
Follow these instructions for either Excel (a) or Google Sheets (b):
a.
Launch Excel, open each file, and choose to Save As an Excel Workbook file. Put it in the subfolder you created for .XLS files.
b.
Open each .CSV file in Google Sheets and save it to the appropriate subfolder.
6.
Open your spreadsheet and create a column called “ride_length.” Calculate the length of each ride by subtracting the column “started_at” from the column “ended_at” (for example, =D2-C2) and format as HH:MM:SS using Format > Cells > Time > 37:30:55.
7.
Create a column called “day_of_week,” and calculate the day of the week that each ride started using the “WEEKDAY” command (for example, =WEEKDAY(C2,1)) in each file. Format as General or as a number with no decimals, noting that 1 = Sunday and 7 = Saturday.
8.
Proceed to the analyze step.

Case Study Roadmap -Analyze
Guiding questions ● How should you organize your data to perform analysis on it? ● Has your data been properly formatted? ● What surprises did you discover in the data? ● What trends or relationships did you find in the data? ● How will these insights help answer your business questions?
Key tasks 1. Aggregate your data so it’s useful and accessible. 2. Organize and format your data. 3. Perform calculations. 4. Identify trends and relationships.
Deliverable A summary of your analysis

Follow these steps for using spreadsheets
Open your spreadsheet application, then complete the following steps:
1.
Where relevant, make columns consistent and combine them into a single worksheet.
2.
Clean and transform your data to prepare for analysis.
3.
Conduct descriptive analysis.
4.
Run a few calculations in one file to get a better sense of the data layout. Options:
●
Calculate the mean of ride_length
●
Calculate the max ride_length
●
Calculate the mode of day_of_week
5.
Create a pivot table to quickly calculate and visualize the data. Options:
●
Calculate the average ride_length for members and casual riders. Try rows = member_casual; Values = Averageof ride_length.
●
Calculate the average ride_length for users by day_of_week. Try columns = day_of_week; Rows = member_casual; Values = Average of ride_length.
●
Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.
6.
Open another file and perform the same descriptive analysis steps. Explore different seasons to make some initial observations.
7.
Once you have spent some time working with the individual spreadsheets, merge them into a full-year view. Do this with the tool you have chosen to use to perform your final analysis, either a spreadsheet, a database and SQL, or R Studio.
8.
Export a summary file for further analysis.

Follow these steps for using SQL
Open your SQL tool of choice, then complete the following steps:
1.
Import your data.
2.
Explore your data, perhaps looking at the total number of rows, distinct values, maximum, minimum, or mean values.
3.
Where relevant, use JOIN statements to combine your relevant data into one table.
4.
Create summary statistics.
5.
Investigate interesting trends and save that information to a table.

Follow these steps for using R
Open R Studio and use this script to complete the following steps:
1.
Import your data.
2.
Make columns consistent and merge them into a single dataframe.
3.
Clean up and add data to prepare for analysis.
4.
Conduct descriptive analysis.
5.
Export a summary file for further analysis.

Case Study Roadmap -Share
Guiding questions ● Were you able to answer the question of how annual members and casual riders use Cyclistic bikes differently? ● What story does your data tell? ● How do your findings relate to your original question? ● Who is your audience? What is the best way to communicate with them? ● Can data visualization help you share your findings? ● Is your presentation accessible to your audience?
Key tasks 1. Determine the best way to share your findings. 2. Create effective data visualizations. 3. Present your findings. 4. Ensure your work is accessible.
Deliverable Supporting visualizations and key findings

Follow these steps:
1.
Take out a piece of paper and a pen and sketch some ideas for how you will visualize the data.
2.
Once you choose a visual form, open your tool of choice to create your visualization. Use a presentation software, suchas PowerPoint or Google Slides; your spreadsheet program; Tableau; or R.
3.
Create your data visualization, remembering that contrast should be used to draw your audience’s attention to the most important insights. Use artistic principles including size, color, and shape.
4.
Ensure clear meaning through the proper use of common elements, such as headlines, subtitles, and labels.
5.
Refine your data visualization by applying deep attention to detail.

Case Study Roadmap -Act
Guiding questions ● What is your final conclusion based on your analysis? ● How could your team and business apply your insights? ● What next steps would you or your stakeholders take based on your findings? ● Is there additional data you could use to expand on your findings?
Key tasks 1. Create your portfolio. 2. Add your case study. 3. Practice presenting your case study to a friend or family member.
Deliverable Your top three recommendations based on your analysis

Follow these steps:1.
If you do not have one already, create an online portfolio. (Use Creating an Interactive Portfolio with Google Sites or Build a Portfolio with Google Sites.)
2.
Consider how you want to feature your case study in your portfolio.
3.
Upload or link your case study findings to your portfolio.
4.
Write a brief paragraph describing the case study, your process, and your discoveries.
5.
Add the paragraph to introduce your case study in your portfolio.
