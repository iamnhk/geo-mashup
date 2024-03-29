# GeoMashup

GeoMashup is a geo-location-based application developed as part of the GeoMashup Code Camp at the University of Helsinki. This application integrates Twitter's API and Google Maps to display tweets from specific locations, highlighting traffic congestion in real-time.

## Introduction

GeoMashup aims to visualize the use of social media, particularly Twitter, during traffic congestion. Users can view tweets from specific locations, overlaid on a map showing traffic conditions, providing insights into social media usage patterns during traffic jams.

## Features

- **Tweet Visualization:** Fetch and display tweets from specific locations on Google Maps.
- **Traffic Congestion Overlay:** Shows real-time traffic conditions on the map.
- **Search Functionality:** Users can search for tweets based on specific queries or Twitter user IDs, tracking the movement of users across different locations.
- **Interactive Map:** Users can interact with the map to view tweets from different locations, set the focus area to specific cities like New York or Helsinki, and track the routes of specific Twitter users.

## Limitations

- The application is limited to Twitter due to the unavailability of suitable APIs from other social networking platforms.
- Tweets are only fetched within an 8 km radius of the focused area, and only those containing geolocation data are displayed.
- The search functionality requires a specific query, as Twitter's API does not allow fetching tweets without one.

## User Guide

- The default location is set to New York, and the default query is "and".
- Users can view tweets by clicking on the "Show Marker" button.
- To view older tweets, click on the "Older Tweets" button, then "Show Marker".
- Users can change the query and focus area, and interact with the map to visualize different data.

## Implementation

The application uses Google Maps JavaScript API V3, with overlays for markers, polylines, and traffic congestion. Data is fetched from Twitter's API and displayed on the map. Despite the project's fast-paced nature, the implementation provides a functional and insightful visualization tool.

## Platforms and Tools

- Developed using HTML, JavaScript, and CSS.
- Google Maps API for map visualization.
- Twitter API for fetching tweet data.
- Tested on Google Chrome and Firefox Mozilla web browsers.

## Contributors

- Jukka Leino
- Otto Waltari
- Md. Nazmul Haque Khan

---

*GeoMashup was created as part of the GeoMashup Code Camp, University of Helsinki, Department of Computer Science.*
