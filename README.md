# mod

# Benefit-Cost Analysis: Inventory Decision Model

## 📌 Introduction

In the realm of Business Analytics, continuous decision modeling plays a pivotal role in ensuring that organizations can harness the power of data-driven insights. These insights pave the way for actionable decisions that are assessed and tuned based on their tangible impact on key performance indicators. The essence of this project is to design and employ an evaluation method—a conceptual framework that fosters understanding, coordination, and seamless integration of the business logic behind strategic decision-making.

The crux of our analysis revolves around a decision model tailored for an inventory study of a specific retail outlet. With the overarching goal to streamline and optimize inventory processes, our model aids in pinpointing the precise quantity of inventory orders that harmonizes the scales of demand and overarching inventory costs.

## 📊 Objectives

- **Inventory Maintenance:** Delve into the significance of device maintenance and its impact on inventory management.
- **Cost Analysis:** Conduct a meticulous breakdown of the financial facets associated with ordering and holding inventory.
- **Optimal Ordering:** Utilize analytical frameworks to determine the most cost-effective order quantity based on a plethora of influencing parameters.

## 📈 Dataset Overview

Our analysis leans on the foundation of the following data:

- **Unit Cost:** A fixed cost of $80 per unit.
- **Demand Dynamics:** An expected annual demand pinned at 15,000 units, with consistent demand throughout the year.
- **Carrying Costs:** A carrying cost rate set at 18% of the unit cost.
- **Ordering Mechanism:** Standardized at $220 per order.
- **Reorder Strategy:** The company adopts a strategy to order double the products required to meet demands, triggering reorders at a specific inventory threshold.

## 🔍 Analysis

Harnessing the capabilities of MS Excel and R, our analysis embarks on a journey to decipher the optimal design. The first leg of our exploration begins with Excel, paving the way for intricate modeling. Data visualization breathes life into our findings, with Excel and R working in tandem to paint a vivid picture.

### Part 1: Excel's One-Way & Two-Way Tables

#### One-Way Table:

This approach is instrumental in providing a holistic view of the total cost. Diving deep into the model's attributes, we unravel the intricacies of the cost dynamics, with our findings encapsulated in **Table 1: Company Dataset** and **Table 2 & 3**.

#### Two-Way Table:

A more granular exploration, the two-way table factors in an array of variables that mold the overall cost. The visual symphony of our insights can be witnessed in **Figure 2 & 3**.

### Part 2: Distributional Dynamics

This segment introduces variations in annual demand and the nuances of the triangular distribution factor. Embarking on 1000 trials, our endeavor is to extract insights about the optimal inventory quantity, order frequencies, and the financial silhouette of total costs. The robustness and reliability of our results are cross-verified using statistical stalwarts—the chi-square test and the Shapiro-Wilk normality test.

Our narrative is further enriched with visual aids presented in **Figure 4-12**.

## 💡 Conclusion

- The one-way table stands testament to the cost-effectiveness of ordering stock quantities ranging between 280 and 420 units.
- Venturing into the realm of two-way tables, with parameters like an $80 unit cost and a $220 ordering cost, we arrive at a cumulative cost of $9,750.40.
- The versatility of our model allows for a dynamic analysis, accommodating varied design variables in diverse scenarios.

## 📚 References

- [Enterprise Data Modeling](https://tdan.com/enterprise-data-modeling/17058)
- [Data Modeling - Tools & Techniques](https://www.xenonstack.com/insights/data-modelling)
- [Data Modeling: An In-depth Overview](https://www.simplilearn.com/what-is-data-modeling-article)
- [Data Modeling - A Comprehensive Guide](https://www.techtarget.com/searchdatamanagement/definition/data-modeling)

