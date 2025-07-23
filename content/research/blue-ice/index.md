---
title: "Ice Fracture Mechanics"
summary: "My first research project evaluating the yield stress of glacial ice in Antarctic blue ice zones."
description:  "My first research project evaluating the yield stress of glacial ice in Antarctic blue ice zones."
draft: true
hidemeta: false
comments: false

cover: 
    image: "images/shirase-blue.png"
    relative: true
    hidden: false
    hiddenInList: false
    hiddenInSingle: true
---

## The Problem

Ice is breaking, we don't know how. 50% of Antarctic ice mass loss is through calving, greatly increasing the amount of error on sea level rise prediction. Field observations are difficult to get, and thus sparse. There is a wealth of remotely sensed satellite data over Antarctica. 

How can we observe the propagation of crevasses? How can we measure the strength of glacial ice using satellite data?

### A Continental Algorithm

Anywhere above 80$^{\circ}$ latitude can use the following algorithm:

![Continental Aglorithm Flowchart](images/flowchart.png#center)

With the fracture maps from Surawy et. al. and the velocity field from ITS_LIVE, we can observe the propagation of crevasses

### Blue Ice Zones

Blue ice zones are regions in Antarctica with no snow or firn overlying the glacier's ice. This provides us the unique opportunity to observe glacial ice directly, avoiding stress and strain measurements over snow and firn. 

![Shirase Glacier](images/shirase-modis.jpg#center)

For this project, we focused on Shirase Glacier, a small glacier in East Antarctica. This glacier has a high velocity and large fracture towards its terminus. 

## The Dataset

Using this algorithm, we are able to produce a dataset with monthly observations from July 2018 to January 2023. Over Shirase Glacier alone, each month has over 130,000 data points.

### Quantifying time-varying stresses

We have the unique opportunity to monitor crevasses, and the stress field nearby, as they open and advect. 

![Crevasse GIF](images/04-c1.gif#center)

We can also monitor the stresses exterted on a single percel of ice as it crevasses.

![Parcel GIF](images/04-p1.gif#center)

## GitHub Repository

See my github repository for more information about the data processing for this project:
[repo link](https://github.com/jackplogan33/ice-fracture-mechanics)
