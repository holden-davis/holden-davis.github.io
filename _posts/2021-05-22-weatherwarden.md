---
title: WeatherWarden
author: Holden Davis
date: 2021-05-22
categories: [Project, Site]
tags: [CSS, HTML, JavaScript, Git, Github, Github Pages]
---

![Desktop](../../assets/img/weatherwarden/WeatherWardenDesktop.png)
_WeatherWarden in a Browser_

## [WeatherWarden](https://holden-davis.github.io/WeatherWarden) is a simple weather site I built from the ground up with basic HTML, CSS, and Javascript.

 It uses the geolocation feature of a web browser to retrieve the user's location and pass the coordinates to each weather request. Two APIs are used:
* [OpenWeatherMap](https://openweathermap.org/) is the source of the main weather data 
* [WeatherBit](https://www.weatherbit.io/) is the source of the severe weather alerts when applicable

JSON from the initial request is sorted into current, hourly, and daily sections.

CSS of the site enables resolution scaling of the UI and provides compatilbility with mobile devices.

![Mobile](../../assets/img/weatherwarden/WeatherWardenMobile.png){:width="50%"}{:height="50%"}
_WeatherWarden on a Mobile Device_
