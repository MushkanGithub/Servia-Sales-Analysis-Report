# Servia Sales Analysis Report

### Dashboard Link : https://app.powerbi.com/groups/me/dashboards/f15556f2-331d-4200-a8d9-13ca867e7bce?experience=power-bi

## Problem Statement

This dashboard helps in saving a tremendous amount of time and resources in different organizations. It helps them to view the beautiful report ready without actually opening emails where the raw data (email attachments) are there, no cleaning and massaging data, no understanding data problems and combining them as a whole and presenting it everytime to the stakeholders is required. The whole process becomes automated once taught and the outcome is hence that the company saves a hell lot!


### Steps followed :-

- Step 1 : Load Outlook data into Power BI Desktop, dataset here is both csv and xls files.
- Step 2 : Get data using Microsoft Exchange Online and our interested data is mail data from Outlook.
- Step 3: Here, the condition was to take the data from year 2020 till date excluding 2019's data. Filtered required data in Power Query itself using its subject statement.
- Step 4 : As mentioned before, the dataset here s xls and csv files both but the former was required. Again used filtering in achieving that.
- Step 5 : It was observed that in none of the columns errors & empty values were present except column named "Order Date".
- Step 6 : Can transform the data according to our need by changing data types, to upper or lower cases or any other.
- Step 7 : Once data cleaning is done, click on 'Close and Apply' in Power Query.
- Step 8 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 9 : Now can start with visualization part in Power View.
- Step 10 : Four card visuals, a scroller, a pie chart, a donought chart, a stacked column chart, a stacked bar chart, an area chart, a servia logo and two social media logos have been used.

- Step 11 : A scroller was used to provide the profit based on sales for different states in United States, used area chart to know the sales based on region in different years, used pie chart to know sales by region, donought chart to know sales by segment and column chart to know sales by sub-category. 

- Step 12 : Finally, I created a Power BI service account and published the Servia Sales Analysis report online.

- Step 13 : To keep dashboard updated according to the email attachments, we need to do settings in data source credentials and make exchange data source updated so that Power BI can automatically update the report on any new mail arrival.

- Step 14 : Created a live dashboard to send it to individuals or orgnaization who requires it.

# Snapshot of Dashboard (Power BI Service)

![Servia Sales Analysis Dahboard](https://github.com/MushkanGithub/Servia-Sales-Analysis-Report/assets/125779329/c21d98be-0825-4259-b6cc-6002eed7961f)

 
 # Report Snapshot (Power BI DESKTOP)

 ![Servia](https://github.com/MushkanGithub/Servia-Sales-Analysis-Report/assets/125779329/dbc7b691-3b2e-41d3-a250-5c925a061473)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Sales done based on year, quarter,month and region : 

   Sales done in 2014 year, March month, 1st quarter (central,east,south,west) = 23308, 23776, 131636, 44032 

   Sales done in 2015 year, February month, 1st quarter (central,east,south,west) = 25290, 64630, 11580, 18040  

   Sales done in 2016 year, January month, 1st quarter (central,east,south,west) = 23776, 19448, 16328, 14640  

   Sales done in 2017 year, December month, 4th quarter (central,east,south,west) =  226596, 240996, 182556, 355800

   Sales done in 2018 year, December month, 4th quarter (central,east,south,west) =  152016, 165906, 65388, 198738

   Sales done in 2020 year, April month, 2nd quarter (central,east,south,west) =  29688, 24432, 97480, 74752

   Sales done in 2021 year, November month, 4th quarter (central,east,south,west) =  37814, 69458, 15586, 29100

   Sales done in 2022 year, September month, 3rd quarter (central,east,south,west) =  35008, 40526, 24048, 47246


           thus, highest sales is done in year 2017 in November month.
           
### [2] Sales done based on Region :
    a). Central : 21.82% 
    b). West : 31.58%
    c). East : 29.55%
    d). South : 17.05%
  
### [3] Sales done based on Segment :
    a). Home Office : 18.7%
    b). Corporate : 30.74%
    c). Consumer : 50.56%
  
### [4] Sales based on Sub-category :
    a). Phones : 3960564
    b). Chairs : 3941436
    c). Storage : 2686320
    d). Tables : 2483604
    e). Binders : 2441100
    f). Machines : 2270904
    g). Accessories : 2008800
    h). Copiers : 1794360
    i). Bookcases : 1378548
    j). Appliances : 1290444
    k). Furnishing : 1100448
    l). Paper : 941700
    m). Supplies : 560148
    n). Art : 324744
    o). Envelopes : 197724
    p). Labels : 150060
    q). Fasteners : 36288

### [5] Sales based on State and City
#### Here picking a particular city in a state and displaying its total sales done.

    a). California (Anaheim): 95832
    b). New York (Buffalo): 108780
    c). Texas (Austin): 72720
    d). Washington (Bellingham): 45492
    e). Pennsylvania (Bethlehem): 20268
    f). Florida (Apopka): 10860
    g). Illinois (Aurora): 90840
    h). Ohio (Akron): 32748
    i). Michigan (Ann Arbor): 10668
    j). Virginia (Alexandria): 66228
    k). North Carolina (Asheville): 17712
    l). Indiana (Bloomington): 7236
    m). Georgia (Athens): 20664
    n). Kentucky ():
    o). New Jersey (Bayonne): 2196
    p). Arizona ():
    q). Wisconsin (Appleton): 20064
    r). Colorado (Aurora): 49020
    s). Tennessee (Bristol): 5244

### [6] Total Sales done : 27.57 M

### [7] Total Discount : 10.27 K

### [8] Total Quantity : 454 K

### [9] Total Profit : 3.44 M
