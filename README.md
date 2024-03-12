# TeamOf 1 or 2

### Sonja Sebree
### Henry Stepanus

### Final Proposal
1. Tornado Activity in Nebraska
    1. Persona
    2. Scenario
2. Requirements Document

3. Wireframes Layouts 
* State of Nebraska outline with County synbolized by normalized tornado 1950-2020 total.
* State of Nebraska out of Normalized density map of tornados by County 
* Kernel density polygons of tornados by County, 2015-2020
* Point data of individual locations, shown yearly 2015-2020
* Proportional circle points of tornados, shown yearly by Enhanced Fujita scale, 2015-2020
* Controls to toggle between road base tile layer and aerial imagery tile layer
* Bar chart of normalized density by County, 2015-2020
* Time wheel diagram showing day of week, time of day, month of year 2015,2016,2017,2018,2018,2019,2020.
* Responsive map proportional symbols will change to reflect year selection
* Possible option of viewing cumulative tornado points for each year.

### **Dependencies:**
* [Leaflet 1.69.4](https://leafletjs.com/reference-1.6.0.html)
* D3 libraries, time series bar charts and density surface map plots for activity by month, by year, and by the day of week (DOW). 
* Cover 2015- 2020 to test and start. Other statistics such as count by month, count by year and time will be added on a time wheel.
*
* The top 5 counties by density are in the counties I grew up in: Hall, Hamilton, Thayer, Adams and Buffalo Counties. 
* 
* (*DOW* is not technically relevant; Tornadoes (sic tornados) are caused by extreme weather fronts colliding to 
* generate "Tornado Alley")
* DOW IS useful to explore population demographics in relation to how many residents are home versus 
* absennt at school or work at the hour of the day.
* Normally, tornados in my home state occur in the 2-6 afternoon, but in 2006 we had one go over our house in Omaha 
* at 2:00 AM, and touch down just east in La Vista. 

### **Code Version:**
Last Updated: 9 March, 2024

### **Description:** MODIFY 
This interactive proportional point and polygon symbol map, built using Leaflet, demonstrates 5 years of tornado activity by county in Nebraska from 2015-2020.
