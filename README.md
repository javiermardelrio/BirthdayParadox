
<!-- # Badges -->
<p align="center">
    <a href="https://jupyter.org/">
        <img src="https://img.shields.io/badge/Jupyter-FFA500?&logo=jupyter&logoColor=white"" /></a>
</p>

# BirthdayParadox


## Table of Contents 

1. [Introduction](#introduction)
2. [Quick Start](#quick-start)
3. [Input Parameters](#input-parameters)
4. [Sample Output Results](#sample-output-results)
5. [Creative Commons](#creative-commons)
6. [Citation](#citation)
7. [Developers](#developers)


## Introduction
Python script to compute various aspects of the birthday paradox using both analytical equations and Monte Carlo simulations.

Given a group of 𝑛 people and assuming a year has 𝑑 possible birthday days (typically 365 days for people born on Earth), the script calculates the following parameters:	
  - Probability of not shared birthdays in the group
  - Probability of at least one shared birthday
  - Expected number of people with unique birthdays
  - Expected number of people with shared birthdays

The calculations assume that each birthday is equally probable.

Additionally, the script can be adapted for other applications by treating 𝑛 as the number of observations and 𝑑 as the number of possible combinations. For example, it can be used to analyze scenarios such as the number of barcodes observed and the number of possible barcode combinations (refer to [FidelityFinder](https://github.com/RTlabCBM/FidelityFinder) for more information on barcode applications in bioinformatics).

## Quick Start
The program is available as a Jupyter Notebook. It can be opened and run with the following Google Colab link: [birthday_paradox](https://colab.research.google.com/github/javiermardelrio/BirthdayParadox/blob/main/JupyterNotebooks/birthday_paradox.ipynb)

## Input Parameters

Parameters that can be provided as input together with example values:

- Number of people in a group (n)
```console
n = 23
```
- Number of days in a year (d)
```console
d = 365
```
- Number of simulations (s)
```console
s = 100000
```

## Sample Output Results
Here is an example of the output data generated using the above input parameters:

![image](https://github.com/javiermardelrio/BirthdayParadox/blob/main/docs/images/sample_results_1k_simulations.png?raw=true)

## Creative Commons
![image](https://github.com/javiermardelrio/BirthdayParadox/blob/main/docs/images/cc_logo.png?raw=true)
**Attribution-NonCommercial-ShareAlike 4.0 International**  
**(CC BY-NC-SA 4.0)** 

## Citation  
We politely request that this work be cited as:  
(Citation details are not yet available)

## Developers

- Javier Martínez del Río
