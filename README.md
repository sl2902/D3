# Summary
The visual, by default, shows the average delay in minutes for 20 US flights in 2008 that occurred due to various reasons such as: Late flight arrival, Extreme weather, National Aviation System (NAS) related, Security, and Carrier delay. During 2008, 'Late aircraft' delay was one of the single biggest reason for delays, on average, peaking at 28 minutes in December and falling to its lowest, at 15 minutes, in September. Close on its heels were delays due to NAS and Carrier delay; In contrast, Security and Extreme weather delays, on average, were low for the period. Further, the visual also enables the user to view average delay across the various categories for each of the individual carriers for further analysis

# Design choices
I used a multi-line chart to plot the average delay of 20 flights for various reasons.The x-axis shows the months for the year 2008 and the y-axis the average delays in minutes for delay in various categories. Each of the 5 delay categories are color coded for easy identification, which is further supported by a legend. With the feedback received, I added a drop-down menu to allow the user to interact with the visual by letting the user select the carrier type to analyze individual carrier delays. Further, I added bubble plots to improve tooltip animation. Lastly, user feedback seemed to suggest that the gridlines seemed jarring and unnecessary, so, I turned them off. In addition, I replaced the default colors with a neutral set of colors for color blind users, and also played around with the opacity of the bubble plots so the datum of intersecting lines can be seen visually

# Feedback
Feedback 1 - Azeem<br>
The chart conveys what you have tried to tried to describe, but perhaps you could allow the reader to select a particular flight to
see how an individual flights' performance compares with the overall average delay for all airlines

Follow up
To enhance the readers' experience, I have added a drop-down menu, which by default shows the average delay for all the 20 flights. The reader can select his choice from the menu to see how an individual carrier performed in various categories during 2008

Feedback 2 - Radha<br>
I don't have much to add, but you could improve the layout by removing the gridlines. Also, you can change the choice of colors for each category as the current choice of colors looks dull

Follow up
I turned off the gridlines and selected 5 color blind safe colors from colorbrewer

Feedback 3 - Myles<br>
You may want to overlay the multi-line chart with bubbleplots to improve tooltip animation

Follow up
Similar to the basic charts world cup example, I added bubble plots so that it is easy for the user to see the tooltip text when he hovers over a particular datum on the chart

Feedback 4 - Udacity<br>
Add more decimal places for the Security delay category as it is not always 0 minutes

Follow up
I added a customized tooltip for the Security delay category that formats the delay to a fixed place of 2 decimals

# Resources
http://stat-computing.org/dataexpo/2009/the-data.html<br>
http://dimplejs.org/adhoc_viewer.html?id=adhoc_composite_axis_measure<br>
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.color<br>
http://www.w3schools.com/tags/tag_select.asp<br>
http://www.rita.dot.gov/bts/help/aviation/html/understanding.html<br>
https://discussions.udacity.com/t/multi-series-line-chart-in-dimple/192881/9<br>
http://stackoverflow.com/questions/4350937/html-select-dropdown-list<br>
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#assignColor>br>
http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
