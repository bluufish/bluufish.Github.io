---
layout: post
title: AirBNB Amsterdam Analysis
published: true
---

Introduction to Data Analysis and Microsoft Excel

The first project I worked on at General Assembly was analyzing host data from AirBNB and it was my introduction to the complete process of Data Analysis. 

The data was gathered from publicly sourced AirBNB data available from http://insideairbnb.com/get-the-data.html

AirBNB is an online marketplace which enables people to lease or rent out their homes while not requiring the property owners to have any formal training or a business license. This ease of entry into the market has created its own boom in short-term rental properties while also building up its own pile of legal issues. The goal of this project was to perform an analysis of the AirBNB market in Amsterdam using Excel for a hypothetical client who wanted to invest in property to rent out using AirBNB. 

As my first project, I went through all the steps a data analyst would go through by following the analytical process.

<p align="center">
  <img src="http://i.imgur.com/9pyFeIT.png"/>
</p>

This involved 
>figuring out the problem we're trying to solve
>creating the objectives and goals
>gathering the data needed to solve it
>cleaning and organizing data 
>creating strategies for dealing with null values, duplicated values, irrelevant data
>analyzing it through pivot tables, cross tabulation and other tools
>Preparing a summary of it for presentation. 

The thing I find most interesting about Data Analysis is the fact that in situations, you figure out what problem you want to solve before you even have the data. Its similar to cooking in that you generally decide what you want to cook and then buy the ingredients you need. Of course you can cook with what you have on hand and its also the case that you can identify problems that need solving just from looking at data. 

![Presentation](http://i.imgur.com/sLmsn4k.jpg)

After cleaning up the data, we were tasked with the challenge of figuring the revenue that each host brought in. Data on the exact revenue each host made or their guest count was not publicly available so we used nested if functions to estimate the daily revenue based off the review count, rates, and accomodation capabilities. I then consolidated my finding through the use of pivot tables and histograms. I'm particularly fond of histograms as they would be extremely tedious to do by hand by can be done in seconds on a computer. 

![screenshot]( http://i.imgur.com/me8H5fD.jpg)

Each student came up with their own recommendations on how to move forward in investing in property in Amsterdam: invest where there was little competition, investing in properties that had high returns, investing in hosts who were already popular as a sponsor, etc. My idea was to invest area with the highest concentration of guests following Hotelling's law (the name is just a coincidence). Hotelling's law states that "in many markets it is rational for producers to make their products as similar as possible". This is also the explanation for why there are always laundromats right next to eachother despite it being seemingly out of place. My theory from personal experience in using hotels is that when you need a room, you're going to take what you can get, and theres never enough rooms to go around. So investing in a place with a high concentration of competitors wont be detrimental to your sucess unless you run the place into the ground and even then you might stay afloat.

This brings me to one of my favorite things about looking at data; depending on who looks at it, data will look different. It depends on the mindset of the viewer and their own personal experiences. So someone who has never used a hotel might have different strategies than someone who has used hotels all their life.

The full excel sheet can be found [here](https://github.com/bluufish/AirBNB.git)
