---
title: "Numerical Modeling and Control of Supercritical Carbon Dioxide Power Cycles" 
date: 2024-08-02
tags: ["Supercritical Carbon Dioxide","System Simulation","Model Predictive Control","State Space Control","Inventory Control"]
author: ["Shrey Sahai Gupta","Pramod Kumar"]
description: "Research Overview"
summary: ""
editPost:
    URL: "https://www.researchgate.net/publication/396498915_Inventory_Management_and_Control_Options_for_Transient_Operation_of_sCO2_Brayton_Cycles"
    Text: "ResearchGate"
showToc: true
disableAnchoredHeadings: false

---

## Graphical Abstract

![sCO₂ Brayton cycle](graphicalabstract1.png)

## Overview

The doctoral research focuses on the numerical modeling and control of supercritical CO₂ Brayton cycles for power generation and waste heat recovery. I develop first-principles, component-level models integrated into closed-loop cycle simulations to study steady-state, part-load, off-design, and transient behavior. A key emphasis of my work is control-oriented model reduction to enable systematic analysis of classical control strategies and their limitations, followed by the design and implementation of advanced controllers, including Model Predictive Control, for load regulation and dynamic operation. This work contributes to the broader goal of improving the operability and commercial viability of sCO₂ power systems.

---

## View dataset

+ Irregular verbs in Portugese: [data](https://github.com/pmichaillat/feru)
+ Irregular verbs in Italian: [data](https://github.com/pmichaillat/unemployment-gap)
+ Irregular verbs in French: [data](https://github.com/pmichaillat/job-rationing)
+ Irregular verbs in Spanish: [data](https://github.com/pmichaillat/countercyclical-multiplier)

---

## Source of data

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


---

## Using data with Python

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Start Python:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

```python
import numpy as np
import pandas as pd
```

### Open the file:

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat `data.csv`.

```python
file_path = 'data.csv'
with open(file_path, 'r') as file:
```

### Read data:

Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.

```python
    lines = file.readlines()
```

### Parse and process data:

Duis aute `line_data` irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur `data.extend`.

```python
data = []
for line in lines:
    line_data = line.strip().split(',')  # Split the line into a list of values
    line_data = [float(value) for value in line_data]  # Convert values to floats
    data.extend(line_data)  # Extend the main list with values from the line
```

#### Compute summary statistics using NumPy:

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum: `data_array`. 

```python
data_array = np.array(data)  # Convert the list to a NumPy array
mean = np.mean(data_array)
median = np.median(data_array)
std_dev = np.std(data_array)
min_value = np.min(data_array)
max_value = np.max(data_array)
```

#### Display summary statistics:

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat `print`.

```python
print(f"Mean: {mean}")
print(f"Median: {median}")
print(f"Standard Deviation: {std_dev}")
print(f"Minimum Value: {min_value}")
print(f"Maximum Value: {max_value}")
```

---

## Description of simulation parameters

| Parameter |   Value   |  Language  | Time period |           Description            |
| :-------: | :-------: | ---------- | :---------: | :------------------------------: |
|  $\alpha$ |   $1/2$   | French     |  1930–1954  |         Tempor dolor in          |
| $\lambda$ |   $e/2$   | French     |  1930–1954  |       Fugiat sint occaecat       |
|  $\gamma$ |  $\ln(3)$ | Spanish    |  1833–1954  |      Duis officia deserunt       |
|  $\omega$ | $10^{-4}$ | Italian    |  1930–1994  | Excepteur et dolore magna aliqua |
|  $\sigma$ |   $1.5$   | Portuguese |  1990–2023  |         Lorem culpa qui          |
|  $\chi^2$ |  $\pi^2$  | Portuguese |  1990–2023  |         Labore et dolore         |
