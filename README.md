# Gridlock-Hackathon-2.0

## Traffic Demand Prediction

This project predicts traffic demand using historical travel, road, weather, and location-based data. The goal is to build a machine learning model that can understand passenger travel patterns, booking behavior, trip cancellations, and traffic demand trends.

## Problem Statement

Cities face increasing traffic congestion due to rising travel demand. This project uses AI/ML techniques to predict traffic demand at different locations and timestamps, helping improve transportation planning and mobility management.

## Dataset

The dataset contains:

- `train.csv` — training data with demand values
- `test.csv` — test data without demand values
- `sample_submission.csv` — required submission format

## Features Used

The dataset includes:

- Index
- geohash
- day
- timestamp
- RoadType
- NumberOfLanes
- LargeVehicles
- Landmarks
- Temperature
- Weather
- demand

## Target Variable

The target variable is:

```text
demand
