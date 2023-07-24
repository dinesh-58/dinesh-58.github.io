+++
title = "CardsQL"
coders = []
date = 2023-07-24T19:29:09+05:45
draft = false
categories = ["web-dev"]     # Possible values: hackathon, web-dev, mobile. Add in data/portfolio.yml
description = "Flashcards + SQL = CardsQL"
github = ["https://github.com/dinesh-58/cardsQL", "https://github.com/dinesh-58/CardsQL-legacy"]  
image = "/logos/cardsql-logo.png"

[[tech]]
logo = "/logos/php.svg"
name = "PHP"
url = "#"

[[tech]]
logo = "/logos/sqlite.svg"
name = "SQLite"
url = "#"
+++

# Flashcards + SQL = CardsQL  

Was originally my project submission for my 3rd sem Web Tech class. 
Rewrote it from scratch & used it as my 4th sem minor project submission. 

## About Flashcards
Flashcards are a memorization/study revision technique where you write a question on 
one side of a card/ piece of paper & the answer on the other side. 
You then read the question & try your best to remember the answer, before
flipping the card over & see how well you did.

Cognitive researchers have found that trying to recall such facts strengthens 
the relevant neural connections in our brain & thus, allows us to remember it 
for longer periods of time. Flashcard apps like [Anki](https://apps.ankiweb.net/) 
& [Remnote](https://www.remnote.com/) also use spaced repetition algorithms to 
schedule the optimal time for revising cards & retaining info.

## Features
- Add cards 
    + Different directions for cards (not implemented)
- Review/ Study scheduled & overdue cards
    + Rate how well you remembered the answer
- Uses modified version of the SM-2 spaced repetition algorithm.
    + Next review date is scheduled using rating & previous ratings, dates
- Edit & delete cards (not implemented)

## Improvements made in the rewrite:
- Replace `MySQL` with `SQLite` for single-file, serverless `RDBMS`
- Calculate next review dates with the more complex SM-2 algorithm, instead of 
adding a constant number of days
- Overall better code quality

## Screenshots
![Homepage/ Adding cards](/images/portfolio/cardsQL-legacy/screenshot-add.png)
![Reviewing cards](/images/portfolio/cardsQL-legacy/screenshot-review-before.png)
![Rating cards](/images/portfolio/cardsQL-legacy/screenshot-review-after.png)
