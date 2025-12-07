# Advanced Data Visualization: Sunburst Diagram

This repository contains the deliverables for the RAWGraphs Sunburst Diagram assignment.

## Student Details

- Email: 24f3000312@ds.study.iitm.ac.in

## Project Description

The visualization analyzes organizational spending by **department** and **expense type**, using a Sunburst Diagram created with **RAWGraphs**.

### Data Structure

The dataset has the following columns:

- `department`: High-level cost center (e.g., Sales, Operations, IT, HR, etc.)
- `expense`: Expense category within each department (e.g., Travel, Advertising, Cloud Services)
- `amount`: Annual spending amount in the local currency

The data represents realistic budget allocations that can be used for **budget analysis** and **cost center optimization**.

### Visualization

- Chart type: **Sunburst Diagram**
- Tool: **RAWGraphs 2.0**
- Hierarchy:
  - Inner ring: `department`
  - Outer ring: `expense`
- Size: `amount`
- Color: `department`
- Export format: `chart.png` (PNG, ~400×400 px)

The Sunburst Diagram is designed to be suitable for **executive presentations**, highlighting which departments have the highest overall spend and how that spend is distributed across different expense categories.