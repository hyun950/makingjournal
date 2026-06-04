---
layout: default
---
[← Back to Home](../index.md)
# Week 06 - I Waited 30 Minutes on the Phone for StudyLink to Pick Up

<sub>*StudyLink is weird and unusual and I don't like it. What do you mean I waited several weeks for them to check my information when I could've just called them to hurry up and get my allowance on the same day?*<sub>

## Data Exploration

In terms of datasets that I would require for my project, there would be two types of data. For the first (and most important) set of data, I would require live data that has all the information relating to the options that users are able to select every day. This would be data such as weather, gas prices, grocery prices, traffic, etc., and the data would be sourced from public APIs. My second set of data would be the user inputs, so how many users chose a specific topic to be the most interesting to them on that day. This data will be collected live with people voting on the day. 

![Alt text](../assets/week-06/wk6example.jpg)
*Quick sketch of how the data would be collected and shown.*

Both of these types of data aren't quite preexisting, and so I would need to collect/simulate them. In terms of showing the data, I thought it'd be cool if I could somehow visually represent what information was chosen the most and what wasn't chosen as much. For example, perhaps the bubble that they the percentages are encased in are bigger or smaller depending on how popular they are.

My only concern so far is that the collected data might be slow, and the impact of being able to see the large collective of votes will be lost.

## Visual Research and Precedent Study 

<img align="left" src="../assets/week-06/wk6tama.jpeg" width="25%" style="margin-right: 10px;" >

*[The elusive Tamagochi](https://en.wikipedia.org/wiki/Tamagotchi)*

When I pitched my idea to my group, someone suggested maybe the information is put on something like a Tamagochi; it's short, easy to carry, and prevents people from being distracted on their phone as it is its own object. I also like how minimalistic it is.

<img align="right" src="../assets/week-06/wk6weather.webp" width="50%" style="margin-left: 10px;" >

*[Every other weather visualiser](https://geoawesome.com/every-weather-forecast-map-look-like/)*

I also like how simple most weather visualisers look, and how it is able to convey exactly what info it wants to convey with minimal writing.

<img align="left" src="../assets/week-06/wk6widget.jpg" width="50%" style="margin-right: 10px;" >

*[Widget thing](https://culturedcode.com/things/support/articles/2803567/)*

I think widgets are also a pretty good reference. Weather apps and other important apps on phones sometimes have a widget version in order to make the most important data be visible through minimalistic commitment and visuals.

<img align="right" src="../assets/week-06/wk6retailfuel.png" width="50%" style="margin-left: 10px;" >

*[Somewhat grim fuel graph](https://figure.nz/chart/lSYJzICrinllOY7p)*

Unfortunately the downloaded version doesn't demonstrate this, but the graph from the original website allows you to hover over the graph in order to see the information more clearly. I like the idea that people can choose to enquire about the stats more specifically if wanted, though the original visual provides enough too.


## Project Planning and Skills Roadmap 

### 3.1 What do I need to make?

For my project, I have to make two components for my work. Firstly, I have to create some sort of "shell" or visual that stores and displays my work nicely. Secondly, I need to make some sort of of digital painting that is able to house my APIs and present them in a way that is able to visually communicate their order of importance. This will probably be done in p5.js. 

### 3.2 What do I need to learn?

I will need to figure out what the "shell" is. I've had suggestions of making some sort of tamagochi inspired device, but I have no idea how to get around to that. It may be too big for my scope to realise, so I will have to backburner the idea for now.

### 3.3 What are my next steps?

I think I gotta figure out how I want to present my work and also the sets of data I want to use. I believe the scripting part won't be the hardest, so deciding on everything else will be the most important aspect as of now.

## Independent Study

I think the consultation went really well, with me having a solid idea of what I wanted to do. The main piece of criticism I got was that the amount of info I was showing was too broad and unspecific. I think this means I should try to narrow down my final ideas.

I think my biggest technical priority is just finding my data and then having a way to present it. Even if a lot of it may be simulated, it might be important to settle on an idea quickly so I can iterate on it as early as possible. I'll also need to learn p5.js more thoroughly if I want to make my data visually appealing, but that is something I can learn later on.