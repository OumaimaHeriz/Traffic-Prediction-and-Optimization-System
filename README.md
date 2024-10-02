# Traffic-Prediction-and-Optimization-System

## Project Overview

The **Traffic Prediction and Optimization System** uses machine learning techniques to predict traffic volume based on historical data and various environmental factors. Additionally, it implements Dijkstra's algorithm to find the shortest path in a simulated traffic network. This project aims to provide insights into traffic patterns and optimize route planning.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Features

- **Traffic Volume Prediction**: Utilizes an LSTM model to predict traffic volumes based on weather, road type, and time of day.
- **Shortest Path Calculation**: Implements Dijkstra's algorithm to determine the shortest path between nodes in a traffic network.
- **Data Visualization**: Provides visual comparisons between actual and predicted traffic volumes.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Keras (for LSTM model)
- Heapq (for implementing Dijkstra's algorithm)

## Dataset

The project uses a synthetic dataset simulating traffic volume, weather conditions, and road types. The dataset contains the following columns:

- `timestamp`: The date and time of the observation.
- `traffic_volume`: Simulated traffic volume.
- `weather`: Weather condition (0 for clear, 1 for rain).
- `road_type`: Type of road (0 for urban, 1 for highway).

## License

Copyright (c) 2024 Heriz Oumaima.
