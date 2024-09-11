# Modelling and Simulation: Project Descriptions

Welcome to the repository for modelling and simulation exercises! This repository contains projects related to economic growth modelling, compartment models, logistic modifications, strategic conflict, and more. Below, you will find a brief description of each project along with tasks and outcomes.

---

## Set 1 : Logistic Modelling of Economic Data

### 1. The Growth of IBM:
This project involves logistic modelling of IBM's economic growth over time using provided datasets (`groibm.dat` and `prof-ibm.dat`). The first dataset includes IBM's annual revenue, employee count, and year since 1914. The second dataset provides annual profit data. The goal is to:
- Reproduce Figures 3, 4, 5, and 6 from the accompanying research paper (`Im-refer.pdf`) using the logistic function.
- Make necessary improvements to the model, such as better scaling or statistical analysis.
- **Key Deliverables**: Plots of revenue, human resources, profit over time; conclusions about IBM's growth dynamics.

### 2. GDP and Trade of National Economies:
Using data from the top six GDP countries (USA, China, Japan, Germany, India, UK), you will model their GDP and trade dynamics from 1960 (1970 for Germany). The files follow the `Country-GDP-Trade.dat` format. USA has two separate files for GDP and trade.
- Reproduce all tables and plots from the provided papers (`kr0822arX.pdf`, `IJMPC-GDP-trade.pdf`, and `rgdp23.pdf`).
- Predict when India's GDP will reach $4 trillion and $5 trillion based on the model.
- **Key Deliverables**: Comprehensive modelling of GDP and trade, predictions for India's GDP, and key insights.

---

## Set 2 : Compartment Modelling of Linear Systems

### 1. Pollutant Concentration in a Lake:
This exercise models the concentration of pollutants in a lake using a linear differential equation, with fixed flow rate and lake volume.
- **Tasks**: Plot the concentration over time, estimate when it falls below 0.5%, and analyze the effect of clean water inflow.

### 2. Single Dose Medicine Dynamics:
Here, you will simulate the absorption of a single dose of medicine into the bloodstream using two differential equations for GI tract and blood concentration.
- **Tasks**: Plot concentration vs. time, test two values of the rate constants, and determine peak values.

### 3. Course of Medicine:
Simulate the dynamics of a course of medicine administered over time using two separate rate constants.
- **Tasks**: Plot the medicine dynamics for different rate constants and analyze limiting behavior.

---

## Set 3 : Modifications of the Logistic Equation

### 1. Logistic Equation with Harvesting:
The logistic equation is modified to include a harvesting rate. This project will simulate population growth under different harvesting rates.
- **Tasks**: Plot population dynamics with varying harvesting rates and compare analytical and numerical solutions.

### 2. Spread of Agricultural Innovations:
This project models the spread of agricultural innovations among farmers using a modified logistic equation.
- **Tasks**: Recast the dynamical equation, rescale the solution, and plot the spread of innovations under different conditions.

---

## Set 4 : Constrained Growth Beyond the Logistic Model

### 1. Gompertz Equation for Tumor Growth:
The Gompertz equation models tumor growth with rescaled variables.
- **Tasks**: Plot growth dynamics, integrate by Euler’s method, and compare numerical vs. analytical solutions.

### 2. Allee Effect:
This model simulates population growth under the Allee effect, where growth is higher when population is at an intermediate level.
- **Tasks**: Plot growth dynamics, integrate using Euler’s method for different initial populations, and analyze limiting values.

---

## Set 5 : Modelling Data with Power Laws

### 1. Pareto Distribution of Wealth in India:
Using wealth distribution data from 2021, this project models wealth inequality using Pareto’s law.
- **Tasks**: Reproduce the given plot and apply a power-law function to the data.

### 2. Zipf’s Law in Debian Dependency Networks:
Model dependency distributions in Debian releases using Zipf's law.
- **Tasks**: Reproduce the plots and perform parameter analysis based on the provided data files.

---

## Set 6 : Modelling Traffic Flow Data with a Bimodal Function

### 1. Bimodality in Traffic Flows:
Model bi-directional traffic flows using traffic data from Jackson, Alabama.
- **Tasks**: Reproduce plots of traffic patterns using a bimodal function, and calculate relative variations in model fitting.

---

## Set 7 : Modelling Strategic Conflict Between Nations

### 1. Richardson's Model of Conflict:
This project models strategic conflict between two nations using Richardson’s equations.
- **Tasks**: Simulate scenarios like mutual disarmament, unilateral disarmament, and arms race with Euler’s method.

---

## Set 8 : Battles and War Games

### 1. Battle of Iwo Jima:
Model the battle between Japanese and US forces using Lanchester's square law of combat.
- **Tasks**: Predict the battle outcome, plot troop dynamics, and analyze results.

### 2. Battle of Trafalgar:
Model Lord Nelson's battle plan during the Trafalgar naval engagement.
- **Tasks**: Simulate the three stages of the battle using Euler’s method and plot the results.

---

### Note:
For each project, appropriate datasets and reference papers are provided to guide the modelling process. Analytical and numerical solutions are expected for various models, with visualizations and plots being critical deliverables.

--- 

Feel free to explore each set, reproduce the results, and improve upon the models using additional techniques!
