# AtmoAI: Atmospheric Anomaly Detection and Forecasting

Final project for the Building AI course

## Summary

**AtmoAI** is a machine learning system that detects anomalies in atmospheric data and forecasts air quality and weather-related variables. It supports environmental monitoring by identifying pollution spikes, unusual aerosol activity, or rapid meteorological changes.

## Background

Modern atmospheric models struggle with predicting rapid, localized events like smoke plumes or urban air quality spikes. With climate and health concerns on the rise, we need smarter tools to support real-time air monitoring.

This project aims to:
* Detect sudden changes in atmospheric variables (e.g., pollution, temperature, aerosol behavior)
* Improve short-term predictions (1–48 hours ahead)
* Provide support tools for public health, climate response, and research

As an atmospheric science student, I’m interested in combining AI with physics-based understanding to make real-time atmospheric insights more accessible.

## How is it used?

AtmoAI will be used by environmental researchers, city planners, public health agencies, and meteorological institutions. The system is needed in real-time or near-real-time environments, especially during:
* Urban air quality monitoring
* Forest fires or industrial accidents
* Arctic or remote atmospheric research

The system processes live data, detects anomalies, and outputs forecasts and visualizations through a user-friendly dashboard or API.

<img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Helsinki_air_quality_map.png" width="400">

## Data sources and AI methods

AtmoAI uses openly available datasets:
- OpenAQ (air quality monitoring stations)
- Copernicus CAMS and ECMWF (weather and chemical reanalysis)
- NASA MODIS/Sentinel satellite data (AOD, cloud cover)

AI methods include:
- LSTM and GRU neural networks for time-series forecasting
- Autoencoders for anomaly detection
- Random Forest for pollutant concentration prediction

[Copernicus Atmospheric Monitoring Service](https://atmosphere.copernicus.eu/)

## Challenges

* Limited labeled data for rare anomaly events
* Interpreting neural network outputs for decision-making
* Data sparsity in remote areas
* Balancing model complexity and real-time performance

## What next?

The next steps include:
* Creating a real-time data ingestion pipeline
* Deploying a working dashboard for Helsinki’s air quality
* Extending to other cities or Arctic research stations
* Collaborating with atmospheric modelers to build hybrid physics+AI systems

Support needed:
- AI developers with experience in geospatial/time-series data
- Atmospheric scientists for validation and calibration
- Public organizations interested in testing the system

## Acknowledgments

* Inspired by tools like SILAM, CAMS, and open-source pollution prediction projects
* NASA, ECMWF, Copernicus, and OpenAQ for public data
* Reaktor x University of Helsinki for the Building AI course
* [Air quality map image source](https://commons.wikimedia.org/wiki/File:Helsinki_air_quality_map.png) / [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)
