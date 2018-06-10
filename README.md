# Lab-4

![Alt text](/img/image.jpg)

This is a donut chart that can be used for many different statistic vizualizations. It is essentially a pie chart, but with a hole in the middle. It is used to show data intensity ratios and the hole provides more space for a legend or any other information one wants to add about the chart. This pie is representing the total distance in miles of a sprint triathlon The whole pie represents 15.57 miles which in this case is 100%, so different sections represent different legs which all have varying lengths. Ratio and percentages are the best data to use. I would like to acknowledge David Buezas for supplying the code to create the pie chart on D3. I would also like to thank Vicky Gisel for supplying code for the updated version (v4) on [blockbuilder.org](https://bl.ocks.org/vickygisel/c3f4eb2b16b86dd0f641263383f05a13). 

The first section of the code is doing the styling choices for the entire chart. I named the chart and told the program the font size will be for the legend. From there, I said that I want the font size of the title (heading 1) is and how it'll align on the page. I also styled the width of the end of each section of the donut chart. From there, more styling choices are made for the entire chart like margins, position to the page, and height and width of chart. The svg styling is similar to the chart, but it has more info that allows us to interact with the data of that file and make more customizations. So we are setting up margins, positions, font style and size, the background color, and radius of the boreders.    
![Alt text](/img/1.jpg

After the styling is made for the chart and the svg file, I write a line of code to specifiy which library and version along with which source I want to use for that specific chart type. I want to make a window pop-up that contains more information about the section when a mouse is hovering over a section of the donut chart, which is what the tooltip function is used for. I'm telling it the categories or classes I want shown in the popup window. The classes are label, count, and percent.
![Alt text](/img/2.jpg)

Next, we state the colors and labels we want. In this case we're randomizing the slice size because I didn't actually put data in it.

