# Code Refactor Project

Description:
This project receives existing html, css, and image documents for the Horiseon main web page. Upon receipt, the documents and website need to be reviewed to ensure full functionality and ensure accessibility requirements.

Usage:
The Horiseon web site can be utilized by clicking each of the content links. Please see images below.

Accessing the Search Engine Optimization section.
![](assets/images/mainseo.png)
![](assets/images/mainseo2.png)

Accessing the Online Reputation Management section.
![](assets/images/mainorm.png)
![](assets/images/mainorm2.png)

Accessing the Social Media Marketing section.
![](assets/images/mainsmm.png)
![](assets/images/mainsmm2.png)

First Impression:
To begin this project, I received the html, css, and image files for the Horiseon main web page user site. I needed to review the website for functionality, see that the HTML was properly structured, and that all content was labeled clearly for accessibility
When I initially opened up the files in Visual Studio, I noticed that the HTML was not structured properly. The Head, Body, and Div tags were all aligned to the left of the html document. Unordered list and paragraphs had unnecessary spacing with the html tags. Alt attributes were not entered and item classes were missing in one of the DIVS. Scanning through the CSS document I saw a large amount detail, however, I found myself tracing which property attributes belonged to what on the html document, creating a lot of confusion. In order to find out if the documents were even working properly, I opened up my browser to explore. A first glance I confirmed that the title of the webpage was not sufficient. The remainder of the page looked good, however, when I tested the clickable links of “Search Engine Optimization”, “Online Reputation Management”, and “Social Media Marketing”, I noticed that the Search Engine Optimization button did not move to the Search Engine Optimization section lower on the screen.

Project Execution:
Steps
•Structured HTML elements to meet standard format. Put Head, DIV, UL, LI, and P in proper locations. Removed extra spacing between UL, LI, and P tags. 
•Renamed Main title page.
•Reviewed H tags and replaced last tag that was not in proper order.
•Updated Search Engine Optimization content div to proper ID and Class definitions. This provided functionality to the websites click element.
•Added alt = “” to all image elements. Removed unnecessary img tags.
•Reviewed document to ensure the required semantic IDs.
•Reordered CSS to match flow of html document.
•Entered notes over each CSS section to clarify portion of html document.
•Added apostrophes to missing font-family’s.
•Added buttons classes in header of unordered list section.
•Updated all background colors to match headers text to background color ratio.


Lessons Learned:
•For Semantic elements: I almost initially decided to change the DIV classes to Header tags until I learned the restrictions of placing Header tags within other Header tags.
•Test the constrast ratio for font and background colors to ensure they meet accessibility requirements.

Final Product:
The website meets the required specifications and functionality. HTML has been structured properly. All classes, IDs, and CSS layouts meet accessibility requirements. All html and css code flow as required.
