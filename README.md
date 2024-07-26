# Static Visualization

## Technologies Used
- Pandas : Exploratory Data Analysis
- Bootstrap  : Styles html elements on page
- Javascript : used to provide interative effects
- JQuery : event handling, DOM manipulation
- D3.js : User friendly visualization of the data results
- Git : version control system to track changes to source code
- GitHub : hosts repository that can be deployed to GitHub pages

## Summary
### A static visualization of Santa Clara University waste data management using waste data from 2019 to 2022.

## Data Analysis & Story

> My story is a summary of the category recycle waste for all the buildings in the year 2019. I cleaned the data using python and pandas. I created new columns month, year and specific notes and sorted data based on weight and year to analyze the data further and identify patterns. Then later using pivot tables in excel, I further explored the data and looked at the sum of waste weights for each building. Then, I decided to compare the recycling waste weights of all buildings and hence to make a good comparison, I normalized the data. Upon analyzing the recycling waste data more closely, I observed that in 2019, building Dunne sorted 90% of their total waste weight correctly and Graham building sorted only 63.39% of their total waste weight correctly. So, I decided to rank these buildings based on the correctness of sorting recycle waste and to visualize the ranking, I chose horizontal bar chart as it would be simple and easy to visualize ranking data. To visualize the top ranked building, I just added a trophy icon on top of it. I chose green shade to fill bar since the chart is all about recycle data and I thought green color would be the best. 

> It wouldn’t be fair just to show and rank the correctness of recycle waste sorting as the correctness could have been a consequence of dumping all sorts of waste only to the recycle bin thereby polluting it heavily. Hence, I analyzed other categories of waste that were dumped in recycling. It turns out that the Dunne building that ranked top, did a good job as they only contributed less to polluting the recycle bin. On the other hand, Graham building which ranked last, polluted the recycle bin heavily. Almost 70% of the total Landfill in Recycling category comes from Graham building. To visualize this analysis, I chose column bar chart as I wanted to show three different waste categories and their respective weights for each building and since this graph talks about a bit of negativity, I chose shades of red to visualize missorted data.

> Furthermore, I got curious to find out which type of waste polluted the recycle bin most in 2019. It turns out that, compost waste contributed to 47% of pollutants and food waste contributed to only 18% of the pollutants. To visualize this analysis, I chose waffle chart as I thought it would be great for this kind of analysis since the data gives a relation to the whole. 

> Since, the image is all about visualizing recycle data, I added a recycle icon. To understand different types of waste that goes into bin, I added icons in dark dirt color to help visualize better. I preferred a dark background over lighter one as I felt it would be visually appealing to view shades of green and red over a dark background and hence, I chose dark blue color. I chose uppercase for all headers and sub headers as I wanted it to differentiate from rest of the text in graph. Header has to look bright so for that I chose a shade of yellow and a shade of pick for the rest of sub headers as I felt that would go well with the dark background color. 

> I developed bar chart, column chart and waffle chart using D3.js and combined all those into one poster using html, css and javascript. The icons were added using MS power point.

## Author Links
[LinkedIn](https://www.linkedin.com/in/mahisha-gunasekaran-0a780a88/)

[GitHub](https://github.com/Mahi-Mani)