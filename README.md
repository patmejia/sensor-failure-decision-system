# Sensor Failure Decision System

Baseline machine learning pipeline to predict equipment failure from sensor data.

## Overview
This project builds a simple and interpretable decision system using sensor inputs to detect potential equipment failure. It combines machine learning predictions with clear risk levels and actionable outputs.

## What it does

* loads and validates sensor data
* cleans duplicates and checks structure
* trains a RandomForest model
* predicts failure probability
* converts probability into risk levels
* assigns actions (inspect, check, normal)
* evaluates performance
* analyzes threshold tradeoffs
* visualizes feature importance and decision behavior

## Dataset
Based on Kaggle dataset and reference notebook by Stefan Clim:
[https://www.kaggle.com/code/climstefan/machine-failure-prediction-using-sensor-data/notebook](https://www.kaggle.com/code/climstefan/machine-failure-prediction-using-sensor-data/notebook)

## Structure

* notebook: full pipeline, evaluation, and decision logic

## Why this matters
This project shows how to move from raw sensor signals to practical decisions, not just predictions.

## Next steps
* compare multiple models
* improve visual diagnostics
* tune decision thresholds
* build simple interactive app
Tell me when done and we go to Version 2.
