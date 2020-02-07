# Project Proposal - Eliana Villafranca (eiv208)
## Project title
FootTraffic

## What and why?
I would like to build a maps application that displays walking routes by time. This application would take into account how crowded the streets along the route are, and take into account multiple route options, finally selecting the route with the least amount of crowding on the sidewalk. This way, walkers could get to their destinations faster and with the least amount of hassle. 

## For whom?
This software would be created for people who live in large, crowded, walkable cities like NYC, where crowd congestion in areas like Times Square can extend walking times by a lot.

## How?
The system would take a starting and ending destination and plot the quickest walking path there by considering all possible routes and comparing congestion. Crowd congestion of a certain street would be predicted by taking historical data from businesses on that street on how busy they are during the given time and day (this type of information can be obtained from google, yelp, etc.). The application would then show the path with the least predicted crowdedness to the walker.

## Scope
The scope of this project would be to do a test construction of this application only for manhattan in NYC. The google maps API could be integrated into the application so that the specifics of path calculation, etc. would not have to be built completely from scratch, however the manipulation of the congestion data would have to be handled by the team.
