---
layout: project
type: project
image: images/fly.png
title: Fly!
permalink: projects/fly
date: 2017
labels:
  
  - ThreeJS
  - Blender
  
summary: Fly! is a fun and interactive 3D flight simulator for kids.
---

<img class="ui centered middle image" width = "35%" src="../images/fly.png">  

  <h1>INTRODUCTION</h1>

  <p>Aloha!</p>

  <p>Fly! is a fun and interactive flight simulator designed for kid passengers to see what's going on under the Earth as they fly above it. </p>
  
  <h1>INSPIRATION</h1>

  <p> How do child passengers visualize what's going on beneath them as they're flying across continents? What do they think about? How can they digest lots of information? </p>

  <p>We decided to tackle flight visualization for children passengers by providing a simple and fun way to visualize lots of data. </p>

  <h1>OUR PROJECT</h1>

  <p> Users can type in a destination that will pin itself upon the Earth, then use arrow keys to create their own flight path. We used Blender and 3js to create custom 3D models and controls. Weather data is grabbed from OpenWeather's api and visualized through sunny, windy, and cloudy animations on the plane. We used trigonometry to map real coordinates to our Earth model while using Google's geocoder to convert physical addresses to polar coordinates. Google Map's api was also used to allow users to see what's nearby in that area. To top it off, we used NASA's land satellite images from their Open Data portal, analyzed it to grab the dominant color shown, and displayed it through spheres that appear along the flight path so people can see pockets of the real Earth's color as they fly about. </p> 
  <p> We strived for a way to display lots of data in a simple, easy, and entertaining way that would appeal and inspire children. It's our hope that Fly! will encourage kids to find an adventure of their own.</p>

  <h1> RESOURCES </h1>
  <ul>
    <li> 3js </li>
    <li> jQuery </li>
    <li> Blender </li>
    <li> OpenWeather API </li>
    <li> Google Geocoder </li>
    <li> Google Map's API </li>
    <li> NASA's Land Satellite Images </li>
  </ul>
  <h1> CODE </h1>
  <p> https://github.com/ilungj/nasa-space-app </p>

<p> You can learn more about the category the app targeted at <a href="https://2017.spaceappschallenge.org/challenges/earth-and-us/pilots-plus/details">NASA SpaceApps</a>.</p>

