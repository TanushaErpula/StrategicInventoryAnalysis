# mod


# Precriptive Modeling: Inventory Decision Modeling

## Introduction

This project dives into the Business Analytics series of continuous decision modeling. The main aim is to translate data-driven insights into optimal actionable decisions. These decisions are gauged based on their impact on key performance metrics, ultimately leading to enhanced strategic planning.

We focus on creating a decision model for inventory analysis for a specific retail outlet. The core objective is to develop a framework that helps determine the optimal amount to order from inventories, balancing demand with total inventory costs. 

Inefficient management of device maintenance and inventory can either signal business inefficiency (surplus stock) or lead to business halts (stock shortages). The challenge is deciding the inventory levels to purchase, produce, and maintain to minimize costs. Two primary costs are considered:
- Cost of ordering
- Holding expenses

## Analysis

The analysis is based on various company data points, such as unit costs, annual demands, carrying cost rates, and order costs. 

Models are developed in both MS Excel and R. In MS Excel, the modeling work involves the analysis of the one-way and two-way tables, examining different variables affecting total costs. R, on the other hand, is used for creating various graphical representations to better visualize and understand the data.

### Part 1: 

This section primarily involves working with Excel. The models created utilize given company parameters and uncontrollable inputs. Using these, mathematical models are developed to determine inventory prices, holding costs, and order quantities. 

### Part 2:

The variables in Part 2 are consistent with Part 1, but there are changes in the annual requirement and the addition of the triangular distribution factor. Multiple distributional statistics are analyzed, with several trials being performed to evaluate different factors like order quantities and total costs. The data sets from these trials are included in a unique CSV file and an RMD file.

## Conclusion

Based on the analysis:
- An optimal inventory order range is identified which minimizes the total costs.
- Different values of
