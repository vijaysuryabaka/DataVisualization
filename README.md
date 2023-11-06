# Data Visualization Lab Assignment

This project is part of a Data Visualization Lab assignment and utilizes the Bokeh library to create interactive plots. The assignment includes a simple dashboard with two plots and a widget to control the attributes of the elements within the plots.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Development](#development)

## Overview

The dashboard created for this assignment contains:
- A scatter plot (`plot1`) with fixed data points.
- A line plot (`plot2`) with fixed data points.
- A select widget that allows the user to change the color of the scatter plot.

## Installation

Before running this project, ensure you have Bokeh installed in your Python environment. You can install Bokeh using pip:

```bash
pip install bokeh
```
## Usage
To run this visualization interactively, navigate to the directory containing the script and execute:

```bash
bokeh serve --show DataVisual.py
```
This will start a Bokeh server and automatically open the visualization in your default web browser.

## Features
Interactive Plotting: Utilizes Bokeh's interactive capabilities for data visualization.
Widget Integration: Incorporates a select widget to interact with the plot elements dynamically.

## Development
If you wish to contribute to the development or suggest improvements, you may clone the repository and start by installing the required dependencies:

```
git clone https://github.com/vijaysuryabaka/DataVisualization.git
cd DataVisualization
pip install -r requirements.txt
```
