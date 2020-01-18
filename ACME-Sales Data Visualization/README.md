# ACME-Sales-Data-Visualization
Explanatory Visualization that helps a sales manager decide with 3 products to discontinue

The Sales - Superstore dataset contains detailed information about your company’s sales. Your manager, Sylvia, has made a decision to cut the three worst performing sub-categories in their region in terms of Sales. To do this, she has asked you to create one data visualization that will identify which three sub-categories are the worst performers by region, and show how much worse they perform than other sub-categories. Sylvia will use this visualization to inform which product categories to cut, and in which regions.

# Design decisions made based on user persona
1. User needs to make decisions based on the visualizations -> Explanatory visualization
2. User's level of data analysis expertise is low -> static visualization
3. Will need to give user little control of data since she has limited face time with executives -> low information density

# Principles used for visualization

1. **Colour** was used to allow user to quickly see the 3 categories with the lowest sales
2. **Orientation** - Bar graphs were ordered in ascending order in terms of sales
3. **Proximity** - The categories with the lowest sales were grouped together
4. **Enclosure** - The 3 categories with the lowest sales were coloured red, and the rest were coloured gray. <br>
                 - A reference line of the average sales was created to show how the sales compared to the average

# Ways that reduced cognitive load
Unnecessary labels were removed - row labels<br>
only 2 colours were used<br>
charts were sorted in ascending order of sales<br>

# Static and interactive visualiation
Static visualization was used to show the sales by categories for the country, and interative visualization was used to show the sales by categories filtered by region. This format was chosen because the user has low expertise with data analysis and will not need a high level of control of the data. However, allowing the user to filter by region will help keep each the visualization simple as she goes through the data for each region. 

> This visualization allowed the user to quickly determine the 3 categories with the lowest sales.

# Link to visualization on Tableau Public:

https://public.tableau.com/profile/rosalind1983#!/vizhome/ACMESuperstore_15789723543890/Salesofeachsub-categorybyregion?publish=yes

https://public.tableau.com/profile/rosalind1983#!/vizhome/ACMESuperstore1/totalsalesofeachsub-category?publish=yes
