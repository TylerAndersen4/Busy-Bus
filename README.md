# Busy-Bus

Challenges for this project:

The first challenge for this project was figuring out the overall architecture and how the different elements should be nested within each other. To make this challenge easier, I drew wrote out my ideas on paper and drew different diagrams to think about the organization. 

Another challenge was to figure out how to best align the bus line, direction, destination, and arrival time. I solved this by using flex box in the CSS. After I solved that, I had to figure out how to make all of the directions vertically align with each other, while also making all of the destinations left-justified. At the same time, the arrival times needed to be left-justified. These tasks were difficult because all of these items are in the same flex box. To solve this, I used justify-content and text-align in the CSS, along with adding widths to these elements, in order to achieve the desired outcome. 

A final challenge was figuring out how to make sure double-digit arrival times didn't break the line on pages with a changing width. To solve this, I set a min-width in the CSS for the section element which houses the entire app. 
