# Frog in the Pan Replication

## Overview

This Jupyter Notebook replicates the key findings of the paper **"Frog in the Pan: Continuous Information and Momentum"** by Zhi Da (University of Notre Dame), Umit G. Gurun (University of Texas at Dallas), and Mitch Warachka (Robert Day School of Economics and Finance, Claremont McKenna College). The paper explores the impact of continuous information on momentum in stock prices, proposing that gradual information dissemination affects stock price momentum differently compared to abrupt information releases.

## Basic Idea of the Paper

The central hypothesis of the paper is that stocks experiencing continuous information flow exhibit different momentum patterns compared to those subject to discrete information shocks. The "Frog in the Pan" (FIP) hypothesis posits that investors are less likely to react promptly to continuous information due to its gradual nature, leading to a smoother, more predictable momentum pattern. This contrasts with the conventional view where sudden information changes cause sharp price adjustments and momentum effects.

## CRSP Data Variables

The replication uses data from the Center for Research in Security Prices (CRSP), specifically the daily and monthly stock data. Key variables used from the CRSP dataset are:

### Daily Data
- **calt**: The calendar trading date.
- **permno**: The unique permanent identifier for each security.
- **ret**: The daily return of the security.
- **prc**: The closing price of the security.

### Monthly Data
- **calt**: The calendar trading date (month-end).
- **permno**: The unique permanent identifier for each security.
- **ret**: The monthly return of the security.
- **prc**: The closing price of the security at the end of the month.

## Authors and Acknowledgments

This replication study is based on the work of the following authors, whose contributions to finance and momentum literature are invaluable:

- **Zhi Da** - University of Notre Dame
- **Umit G. Gurun** - University of Texas at Dallas
- **Mitch Warachka** - Robert Day School of Economics and Finance, Claremont McKenna College

## How to Use This Notebook

1. **Setup**: Ensure you have all necessary libraries installed, including pandas, numpy, and any other dependencies.
2. **Data**: Load the CRSP daily and monthly data files as specified in the notebook.
3. **Replication Steps**: Follow the steps outlined in the notebook to replicate the analysis, including data cleaning, variable construction, and empirical tests.
4. **Results**: Compare the results obtained from the notebook with those reported in the original paper to verify the replication.
