+++
title = "Recycling encouragement web-app"
date = 2023-07-24T17:07:45+05:45
draft = false
categories = ["hackathon", "web-dev"]
coders = ["SuggonM", "krishnathapa43", "susmitadhungel"]
github = ["https://github.com/dinesh-58/hex-team-gitignored"]
image = "/logos/hexgenius.svg"

[[tech]]
logo = "/logos/php.svg"
name = "PHP"
url = "#"

[[tech]]
logo = "/logos/sqlite.svg"
name = "SQLite"
url = "#"
+++

Submission for HEX Genius hackathon 2023 for the theme "Smart Cities". 
I was the team lead and divided tasks based on each member's specialty as follows: 

- **Krishna & Susmita**: Research; Writing HTML, website content & documentation
- **Sagun**: Overall design & CSS 
- **Me**: Creating a basic database & user account system with vanilla PHP

You can find their github profiles by hovering over the 'Team Project' 
button under the headline

## Description

Our web app aims to promote a recycling habit among people. Users create
accounts & can bring recyclable waste/ materials to a nearby recycling
station. There, an operator will record it digitally & add reward points
to the user\'s account. Reward points are calculated based on the material 
category & it's weight  Users can exchange these reward points for
recycled products such as notebooks, dustbins, manure etc.

These products are recycled by workers at the recycling station. Each
product is worth some amount of reward points based on its perceived
value & can be sold for real money to generate revenue for the station
as well.

## Features

**Users** can:

-   register & login
-   view reward points & rewards they can currently afford to exchange
-   view nearby recycle stations

**Recycle station operators** can:

-   log/ record recycles for data-keeping
-   add reward points when recycled & deduct when redeemed

## Novelty: What makes our project unique

-   The reward point system is meant to gamify the recycling process.
    + Users are provided return value in the form of tangible, useful
    products & thus, will want to recycle more.

-   Special events can also be held to further boost user engagement.  
    + One such example would be to host competition where users have to
    recycle a minimum amount in order to participate.
    + Random users are
    then selected to give prizes to.

-   Employment opportunities for involved personnel (operators, workers
    that make recycled products, waste collectors)

-   Collected data can be aggregated & analyzed to gain insight
    regarding wastage amount, recycling habits.
    + Historical data can also be used to gague impacts of awareness campaigns, 
    workshops on
    recycling trends.

## Screenshots

![Homepage](/images/portfolio/hexgenius-recycling/homepage.png)
![Dashboard for regular user](/images/portfolio/hexgenius-recycling/user-dash.png) 
![Dashboard for recycle station operator](/images/portfolio/hexgenius-recycling/admin-dash.png)
