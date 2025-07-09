# CnA_2025_Capstone

# Real-Time Dynamic Parking Pricing

**Summer Analytics 2025 Capstone Project**  
Consulting & Analytics Club × Pathway

This repository contains a baseline dynamic pricing model using real-time data for urban parking lots.

## Project Overview

Urban parking prices are often static, leading to either underuse or overcrowding. In this project, we simulate **real-time pricing** using historical parking data and adjust prices based on occupancy.

### Implemented Model

**Model 1: Baseline Linear Pricing**

Price changes linearly with occupancy rate.

**Formula:**
Price_t = 10 + α × (Occupancy / Capacity)
- Base Price = \$10
- α = 5 (sensitivity factor)

---

## Tech Stack

| Tool        | Usage                              |
|-------------|------------------------------------|
| Python      | Core programming language          |
| Pandas      | Preprocessing CSV data             |
| Pathway     | Streaming & stateful computation   |
| Bokeh       | Real-time plotting in Colab        |
| Panel       | Dashboard embedding with Bokeh     |

---

## Architecture

View architecture_diagram.png

---

## Output (Example Visualization)

View Model_1_Output_example.jpg

---

## Assumptions

- All parking lots start with a base price of \$10.
- Occupancy is the only factor affecting price in Model 1.
- Capacity is static per lot and accurate.

---

## How to Run

1. Download Model_1_Capstone.ipynb, dataset.csv.

---

2. Download the libraries included in `requirements.txt`

  ```txt
  pathway
  pandas
  bokeh
  panel
  ```

3. Run the Model_1_Capstone.ipynb file (using Google Colab).
