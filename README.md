# Tableau Dynamic YoY Comparison with Auto/Manual toggle
Tableau has the ability to change the month of financial year start built in. However, the selection you make is ignored within calculated fields. This becomes a problem when your client has a financial year that does not start in January, and you need to make complex customisations involving financial years and quarters. Most commonly this issue would arise when you want to create a DatePart selector.

With this modular solution you can easily overcome this limitation, with logic that accounts for all possible financial year starting months.
This will work with any date field, so just take the relevant calculated fields and parameters and drop them in your workbook. Then just set your desired financial year start month and you are good to go.

You can test this by swapping the Start Month Selector in the dashboard and watching the FY and Quarter values accurately update.
 
 ## Calculated Fields
- [DatePart (Year)](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/DatePart%20(Year).txt) - Description here!!
- [Previous Year Sales](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Previous%20Year%20Sales.txt) - Description here!!
- [Current Year Sales](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Current%20Year%20Sales.txt) - Description here!!
- [Previous Year Dates](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Previous%20Year%20Dates.txt) - Description here!!
- [Current Year Dates](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Current%20Year%20Dates.txt) - Description here!!
- [Sales YoY Diff #](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Sales%20YoY%20Diff%20%23.txt) - Description here!!
- [Profit YoY Diff %](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Profit%20YoY%20Diff%20%25.txt) - Description here!!
- [Previous Year Dates (MIN)](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Previous%20Year%20Dates%20(MIN).txt) - Description here!!
- [Previous Year Dates (MAX)](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Previous%20Year%20Dates%20(MAX).txt) - Description here!!
- [Current Year Dates (MIN)](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Current%20Year%20Dates%20(MIN).txt) - Description here!!
- [Current Year Dates (MAX)](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Calculated%20Fields/Current%20Year%20Dates%20(MAX).txt) - Description here!!

 ## Parameters
- [Use Manual Dates Toggle](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison/blob/0d210dcdecc756673fa17d05385fbb99fc8d6494/Parameters/Use%20Manual%20Dates%20Toggle.txt) - Sets the month in which the financial year starts
- [Previous Year](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Previous%20Year.txt) - Sets the month in which the financial year starts
- [Current Year](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Current%20Year.txt) - Sets the month in which the financial year starts
- [Previous Year Week Manual MIN](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Previous%20Year%20Week%20Manual%20MIN.txt) - Sets the month in which the financial year starts
- [Previous Year Week Manual MAX](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Previous%20Year%20Week%20Manual%20MAX.txt) - Sets the month in which the financial year starts
- [Current Year Week Manual MIN](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Current%20Year%20Week%20Manual%20MIN.txt) - Sets the month in which the financial year starts
- [Current Year Week Manual MAX](https://github.com/Kyle-Ross/Tableau-Dynamic-YoY-Comparison-with-Auto-Manual-toggle/blob/9a15c6676d8c9f408b0c74eb4782ece537ca7ce1/Parameters/Current%20Year%20Week%20Manual%20MAX.txt) - Selects the DatePart to show
 
 ## Dashboard
   [![tableau dynamic FY Start](https://img.shields.io/badge/review_on_tableau_public-1DA1F2?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/kyle.ross6552/viz/DynamicYoYComparison/DynamicYoYComparison)
 
 The view below is static. Click the link above to use and interact with the dashboard on Tableau Public.
 
<div class='tableauPlaceholder' id='viz1655720865475' style='position: relative'><noscript><a href='https:&#47;&#47;github.com&#47;Kyle-Ross&#47;Tableau-Dynamic-YoY-Comparison'><img alt='Dynamic YoY Comparison ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dy&#47;DynamicYoYComparison&#47;DynamicYoYComparison&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DynamicYoYComparison&#47;DynamicYoYComparison' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dy&#47;DynamicYoYComparison&#47;DynamicYoYComparison&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>
