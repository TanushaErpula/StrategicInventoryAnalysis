# mod



# Prescriptive Modeling in Inventory Management

## Introduction

In the realm of Business Analytics, continuous decision modeling plays a pivotal role. These models help translate data-driven insights into actionable decisions that positively affect key performance metrics. This, in turn, aids in refined strategic planning. One such vital tool is the evaluation method, which acts as a conceptual framework to understand, coordinate, and integrate the business logic behind strategic decisions.

The focus of this project revolves around building a decision model for a retail outlet's inventory study. Our primary goal is to establish a framework to ascertain the optimal amount to procure from inventories. This ensures a balance between meeting demands and managing total inventory costs.

The importance of efficient device maintenance cannot be stressed enough. Holding excess stock can point towards an inefficiency in business operations. On the other hand, inadequate stock levels can lead to operational halts. For optimal operations, a business needs to strike a balance, deciding on the appropriate inventory levels to purchase, produce, and maintain.

Our study will mainly consider two factors:
- Cost of ordering
- Holding expenses

## Key Considerations

Here are some of the considerations based on which our analysis is founded:

- Each unit's cost is $80, with an anticipated annual demand of 15,000 units.
- Based on the company's financial data, the estimated cost of holding onto stock for an extended period is 18% of the unit cost.
- The service cost stands at approximately $220 per order.
- The company's strategy involves ordering double the product amount required to fulfill demand. This is executed when inventory reaches a specific reordering point, pending the supplier's delivery.

## Analysis Procedure

Our methodology involves leveraging tools like MS Excel and R programming to derive our insights. Initially, the modeling work will be performed in Excel, and subsequently, relevant charts will be developed using both Excel and R.

### Key Components of the Analysis:
- **One-way table**: Here, we will capture the total cost by examining the model's specifics.
- **Two-way table**: This will help us ascertain the various components influencing the overall cost.

## Part 2 Analysis

This segment has a structure akin to Part 1. However, it distinguishes itself by introducing variations in the annual demand and the incorporation of a triangular distribution factor. These distributional statistics will be pivotal in executing 1000 trials to derive determinant factors like Quantity of Inventory, Number of Orders, and Total Costs.

To validate the distribution's authenticity, statistical tests like the chi-square test and the Shapiro-Wilk test for normality will be employed.

## Conclusion

Through our analysis:
- We deduced that procuring stock between 280 and 420 units ensures minimized costs, thus optimizing expenditures.
- Using a two-way table, with a unit cost of 80 and an order cost of 220, we derived a total cost of 9750.40.
- By manipulating model variables, we can gauge the total cost under different scenarios, aiding in effective decision-making.

## References
- [Enterprise data modeling](https://tdan.com/enterprise-data-modeling/17058) - TDAN.com, 2015
- [Data modeling - understanding tools and techniques involved](https://www.xenonstack.com/insights/data-modelling) - XenonStack
- [What is data modelling? overview, basic concepts, and types in detail](https://www.simplilearn.com/what-is-data-modeling-article) - Simplilearn.com, 2022
- [What is Data Modeling?](https://www.techtarget.com/searchdatamanagement/definition/data-modeling) - SearchDataManagement, 2021
