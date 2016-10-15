# Summary
The visual, by default, shows the average delay in minutes for 20 US flights in 2008 that occurred due to various reasons such as: Late flight arrival, Extreme weather, National Aviation System (NAS) related, Security, and Carrier delay. During 2008, 'Late aircraft' delay was one of the single biggest reason for delays, on average, peaking at 28 minutes in December and falling to its lowest, at 15 minutes, in September. Close on its heels were delays due to NAS and Carrier delay; In contrast, Security and Extreme weather delays, on average, were low for the period. Further, the visual also enables the user to view average delay across the various categories for each of the individual carriers for further analysis

# Design choices
I used a multi-line chart to plot the average delay of 20 flights for various reasons.The x-axis shows the months for the year 2008 and the y-axis the average delays in minutes for delay in various categories. Each of the 5 delay categories are color coded for easy identification, which is further supported by a legend. With the feedback received, I added a drop-down menu to allow the user to interact with the visual by letting the user select the carrier type to analyze individual carrier delays. Further, I added bubble plots to improve tooltip animation. Lastly, I turned off gridlines and replaced the default colors to use, instead, a neutral set of colors and played around with the opacity of the bubble plots.

# Feedback
1) Provide a menu driven option to allow the user play around with various flight selections<br>
2) Replace the default dimple colors and provide your own colors<br>
3) Improve layout by removing gridlines and enhance user animation by providing a toolip when the user hovers over a data point for a specific month

# Resources
http://stat-computing.org/dataexpo/2009/the-data.html<br>
http://dimplejs.org/adhoc_viewer.html?id=adhoc_composite_axis_measure<br>
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.color<br>
http://www.w3schools.com/tags/tag_select.asp<br>
http://www.rita.dot.gov/bts/help/aviation/html/understanding.html<br>
https://discussions.udacity.com/t/multi-series-line-chart-in-dimple/192881/9<br>
http://stackoverflow.com/questions/4350937/html-select-dropdown-list<br>
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#assignColor
