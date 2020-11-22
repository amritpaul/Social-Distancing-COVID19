# Social-Distancing-COVID19

## Problem Statement
Identify if people are following social distancing with the help of a camera and object detection algorithm. If people are found to be breaking the rules, high pitch alarms and sounds can be made use to make them attentive. There can also be provisions to let the authorities know if there are any large scale social gatherings. Can you make this happen? Come up with a Proof of Concept.

## Overview
- Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2)
- The disease was first identified in December 2019 in Wuhan, the capital of China's Hubei province, and has since spread globally, resulting in the ongoing 2019–20 coronavirus pandemic.
- As of 25 April 2020, more than 2.86 million cases have been reported across 185 countries and territories, resulting in more than 201,000 deaths. More than 811,000 people have recovered.

## Flow Diagram
The below diagram represents the overall architecture of Social Distancing Project.
![](./images/flow.png)

## Pedestrian Detection and Tracking
The below diagram represents pedestrian detection and tracking using YoloV3 architecture and SORT based tracking algorithm.
![](./images/object_detection_tracking.png)

## Crowd Detection
The below figure represents crowd detection to maintain social distancing based on a fixed distance value.
![](./images/crowd.png)

## Violator Detection
The below figure represents violation detection such that police can take direct action against these people. It will also ensure that the number of Covid cases are less.
![](./images/violator.png)

## Final Output
The below figure represents the output of Social Distancing project.
![](./images/social_distance.png)
