---
layout: post
title: League of Retroheroes
date: 2021-07-05 19:30:00 +0300
description: An Android Studio app working with Firebase.
img: retroheroes.PNG # Add image post (optional)
tags: [Android, Kotlin] # add tag
---
League of Retroheroes is an app made in Android Studio with Kotlin. It was developed in ESAT by myself recreating an app connected with a database. In this app it is included a login made with firebase as well as a registration for new users. After that, it has a main menu with different sections:

* A ranking where people could see the best users from the game, being able to filter by kills, goals or points.
* A page with a picture of the user's character and its inventory, including all the items that the user had.
* A page with all the matches from the user, so they can look at their stats.
* A link with a contact method.

All the information was recovered using JSon and then filled accordingly. It was completated that, if the user was new, it won't have a JSon asignated (after all, it was only a demo), and it showed a message that they should create a character first or play a match.
