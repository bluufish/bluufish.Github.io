---
layout: post
title: Big Trouble in Little Chinatown
published: true
---

My introduction to Tableau and the horror that is Restaurant Inspection Health Grades

My third and final project at General Assembly didnt come with a topic but instead we were to look for our own data, get it approved and basically figure out what we want to do with it. It was quite an interesting experience seeing all the data that was publically available on the net and finding out what interested me. Originally I wanted to do AirBNB again except with the Tokyo market since I've used AirBNB in Tokyo but the data was either insufficient or was not publically available which led me to the frustration of not finding the data I wanted. Ultimately at the recommendation of the instructors, I decided to browse New York City's [own publically available database](https://opendata.cityofnewyork.us/) for interesting topics. Seeing our city full of looming skyscrapers deconstructed down into spreadsheets was very enjoyable. From transportation, to schools, to business and everything about zoning regulation you never cared about, it was all available at the click of my mouse. I settled on the thing thats been staring at me my entire life, which were all the restaurants with all the B Sanitary Inspection grades near my house. How bad is a B exactly and what does it mean? Does the city have a problem with Bs or is it certain areas or just certain restaurants? All these questions suddenly rushed into my head as I downloaded the data provided by the DOHMH in their New York City Restaurant Inspection Results report.

<p align="center">
<img src="http://newyork.seriouseats.com/images/20100728sanitation.jpg"/>
</p>

Sanitary Inspection Results are basically like having a driving test except you're driving a hotdog instead of a car. You start at zero points and as you gaint points as you fail to make a right turn into proper temperature control. If you rack up more than thirteen points, you get a B, and if you get more than twenty seven you get a C. Failure to get an A is essentially not passing and you are immediately signed up for another inspection at which point you either get an A or you are allowed to stick with the grade that you received, whether it be a B or a C. So it turns out when you see a B graded restaurant, they actually failed at least two inspections. Health violations are also similar to driving tests in that there are minor and major violations. Minor violations are things like not having food stored at the right temperature while major violations involves things like pest infestations or things that immediately endanger customers. Enough major violations can get you shutdown immediately until it has been resolved. As I read these all these rules for inspection the questions I had previously came storming back in. Just what does the map of health inspections look like and can I somehow visualize it?

<img src="http://i.imgur.com/CAMqP3B.jpg">

Fortunately the tool we learned for this project was Tableau, a visualizing software which did exactly everything I wanted for this project. Tableau allows the instaneous generating of graphs and visualizations through simple drag and drops with a few tweaks for refinement and even allows interactive options. Of course before I could inject my data into Tableau, I ran to run through the gauntlet of cleaning and sorting through the data I had obtained for this project and boy was it an endeavor. Loading the sheet itself was troublesome since it recorded every violation of every restaurant in the city for the last 5 years so I decided to focus on Chinese restaurants which are notorious for not being the cleanest of places. 
