# Drug Data Analysis

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![Contributors](https://img.shields.io/github/contributors/mahshid1373/Mechanisms-of-Action-MoA-Prediction.svg)

## Overview

Welcome to the **Drug Data Analysis** project! This repository contains a comprehensive analysis of drug data using various data science techniques. The primary goal of this project is to explore and visualize drug usage patterns, identify significant trends, and provide meaningful insights using Python.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Data Cleaning**: Efficient preprocessing of raw drug data to handle missing values and inconsistencies.
- **Data Visualization**: Interactive visualizations using Matplotlib and Seaborn to showcase drug usage patterns.
- **Statistical Analysis**: In-depth statistical analysis to identify significant trends and correlations.
- **Machine Learning Models**: Implementation of machine learning algorithms to predict outcomes based on drug data.
- **Customizable Pipeline**: A modular pipeline that allows users to customize the analysis according to their needs.

## Getting Started

To get a local copy up and running, follow these simple steps.

## Prerequisites

Make sure you have Python 3.8+ installed on your machine. You can download Python from [python.org](https://www.python.org/).

## Data

The dataset used for this project contains detailed drug usage information. Each row represents an individual entry with specific attributes such as `drug_id`, `cp_type`, and more.

Train Dataset:

| Column Name | Description                                                    |
|-------------|----------------------------------------------------------------|
| `sig_id`    | Unique identifier for each sample.                             |
| `cp_type`   | Type of compound used; `trt_cp` for treatment and `ctl_vehicle` for control. |
| `cp_time`   | Duration of the treatment in hours (e.g., 24, 48, 72).         |
| `cp_dose`   | Dose of the compound used; `D1` for low dose and `D2` for high dose. |
| `g-0` to `g-771` | Gene expression levels for genes 0 to 771.                |
| `c-0` to `c-99`  | Cell viability measurements for markers 0 to 99.          |


Below is a preview of the dataset showing a few sample identifiers (`sig_id`) and their corresponding drug identifiers (`drug_id`).

Drug Dataset: 

| sig_id      | drug_id   |
|-------------|-----------|
| id_000644bb2| b68db1d53 |
| id_000779bfc| df89a8e5a |
| id_000a6266a| 18bb41b2c |
| id_0015fd391| 8c7f86626 |
| id_001626bd3| 7cbed3131 |

