# Social Distancing on Raspberry Pi

Created by Luxonis

Modified by Augmented Startups

Below you can see 3 people in a scene.  DepthAI monitors their 3D positions and alerts whenever they are closer than 2 meters, displaying `Too Close` when they are below this threshold, and also overlaying the distance betwen the people at all times and also the 3D position of each person (in x,y,z in meters) from the camera.

[![COVID-19 Social Distancing with DepthAI](https://user-images.githubusercontent.com/5244214/90741333-73f89500-e2cf-11ea-919b-b1f47dc55c4a.gif)](https://www.youtube.com/watch?v=kplICBD_wVc&list=PL_Nji0JOuXg0cTjQqOQhjQ69__gngp12c&index=1&ab_channel=AugmentedStartups "DepthAI Social Distancing Proof of Concept")

## Pre-requisites

Purchase a DepthAI model (see https://bit.ly/GetOAKNow)

## Install This Social Distancing Example

```
python3 -m pip install -r requirements.txt
```

## Run The Example

```
python3 social_distance_final.py
```
