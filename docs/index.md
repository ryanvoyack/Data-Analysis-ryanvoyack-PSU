## Creating an interactive tic-tac-toe app that dynamically uses a question bank to serve as a quiz game <br> 7.29.2018

The research opportunity with the Department of Statistics at PSU this past summer (2018) that I was involved in works to create learning supplements for undergraduate statistics courses using R Shiny applications. I am highlighting interactive tic tac toe game that I originally coded for the research program's estimation and testing module. The apex of the codes capabilities is that the tic tac toe game itself could be used in other researchers' apps, where they only need to create their own question banks to quiz users with (of course, they need to create the question bank using the same format as my original bank). In total, this tic tac toe game structure that I have coded is being used in 4 of the apps in the research programs book of apps. 

<blockquote>
    as of 8.22.2018
</blockquote>

Currently, the Department is working on publishing these 4 apps in quesiton onto their university web page. Also, my tic tac toe app (the original) is published on my [personal Shinyapps account](https://ryanvoyack.shinyapps.io/tic-tac-toe) . I am very proud of this code, there were many challanges, and the end product couldn't have been accomplished had it not been for a great display of reactive programming in the [server logic](https://github.com/ryanvoyack/PSU-shiny-research/blob/master/tic-tac-toe/server.R) . All files for this game can be viewed [here](https://github.com/ryanvoyack/PSU-shiny-research/tree/master/tic-tac-toe) .

<blockquote>
    as of 10.17.2018
</blockquote>

Since the beginning of this fall semester, our shiny research team has been working to perfect the apps in order to get them ready for final publication on our university website. This tic-tac-toe app is being used in 3 of the apps in our book of apps, and through our hard work in conjunction with the Statistics Department staff, the apps are finally published. My tic-tac-toe code was used for a [hypothesis testing concept quiz game](http://shiny.science.psu.edu/apps/boast/Estimation_and_Testing/Hypothesis_Testing_Game/), a [time series analysis concept quiz game](http://shiny.science.psu.edu/apps/boast/Time_Series/Time_Series_Analysis/) and a [regression assumptions concept quiz game](http://shiny.science.psu.edu/apps/boast/Regression/Assumptions/).


<br>
<br>
<br>

## Exploring relationships between Lung Cancer Incidence and Air Pollution <br> 12.9.2016

The project's first publication, using skills acquired after competing my first course in R: 


My first data-analysis project, using the skills I learned in Introduction to R at PSU, can be found [here](http://rpubs.com/ryanvoyack/305351) . This project was completed and submitted for the class's final project assignment during finals week, on December 9th, 2016. This project focused on the techniques learned in the "Introduction to R" class, rather than statistical methods themselves. These techniques included tidying data sets, graphing functions, and web scraping in order to achieve graphical analysis while also formatting documents and code to be (more easily) reproducable and readable. There is a [repository](https://github.com/ryanvoyack/Data-Analysis-Ryan-Voyack) dedicated to the documentation and progress of this project.

<br>
<br>
<br>

## Building an interactive Shiny App that utilizes web scraping in order to Visualize Financial Statements and Compare Companies <br> 12.3.2017

I enrolled in *Stat 297: Special Topics* for its inagural semester during fall semester 2017. This class's final (group) project was to create an app that utilized web scraping, function writing and package building in some sort of way. Our group's final submission barely operational [originally](https://github.com/andywwwww/group3_project) as there were many errors within the server logic of the app, particularly having to do with shiny server function and syntax. This app used a function I wrote that *dynamically* scrapes web data whenever the app is launched, and our group built a package containing these functions. *(I have since moved this package to my repository, where I've continued working on this app)*

<blockquote>
    as of 1.27.2018
</blockquote>

The app's perfection. The current publication is version 1.0, this was completed following a group project at PSU.

After the end of that fall semester, I set out on completing this app. My first Shiny App, using the shiny functions I learned in Stat 297 at PSU, can be found [here](https://ryanvoyack.shinyapps.io/financialPlots/). Fixing the bugs in the app from our final project required me to really get used to the shiny syntax functions. Particularly, I learned how different and more complex the demands were for debugging when it came to debugging Shiny Applications (as opposed to standard R programs). The final product is provided in a [repository](https://github.com/ryanvoyack/financialStatementPlot) that contains a package which includes the functions, their documentation and the Shiny App itself. If you want to install and use this package, run
```
require("devtools")
devtools::install_github("ryanvoyack/financialStatementPlot")
```
in your R console. 
