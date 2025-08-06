# Mini E-commerce Funnel Drop-off Analysis

This project simulates and analyzes user behavior across an e-commerce funnel. The goal is to identify at which stages users drop off — from viewing a product to completing a purchase — and to generate actionable insights that could help reduce these drop-offs.

---

## Objective

To create a simulated mini e-commerce environment, generate synthetic user behavior data, and analyze where users are exiting the sales funnel. This type of analysis helps e-commerce platforms improve user experience and increase conversions.

---

## Dataset Overview

The dataset is synthetically generated and includes three main components:

1. **Users Data**
   - 1,000 users
   - Attributes include `user_id`, `device type`, and `location`

2. **Products Data**
   - 50 unique products
   - Includes `product_id`, `category`, and `price`

3. **Events Data**
   - 10,000 user interaction events
   - Covers event types like `view`, `add_to_cart`, and `purchase`
   - Tracks the sequence and timestamps of user behavior

Each table is stored as a separate CSV file: `users.csv`, `products.csv`, and `events.csv`.

---

## Tools and Libraries Used

The project is implemented in Python using the following libraries:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `random` and `datetime` for synthetic data generation

---

## Key Steps Performed

1. **Synthetic Data Generation**
   - Created a realistic dataset of user events in an e-commerce environment.
   - Ensured a balance of different devices, locations, product categories, and event types.

2. **Data Exploration**
   - Loaded and inspected the datasets.
   - Visualized the event distribution (e.g., how many users viewed, added to cart, or purchased).

3. **Funnel Drop-off Analysis**
   - Tracked user journeys from `view` → `add_to_cart` → `purchase`
   - Identified major drop-off points.
   - Explored how funnel performance varied by device type and location.

4. **Insights and Recommendations**
   - Noted patterns in conversion rates across locations and devices.
   - Proposed strategies for optimizing drop-off stages based on observed data.

---

## Results and Observations

- A significant number of users dropped off at the `view` to `add_to_cart` stage.
- Mobile users had a slightly higher drop-off rate compared to desktop users.
- Certain locations had better conversion rates, possibly due to better logistics or offers.
- High-priced items were less likely to be purchased, suggesting price sensitivity.

---

## What This Project Demonstrates

- How to simulate and analyze user behavior in a controlled e-commerce setting
- The importance of funnel visualization in identifying bottlenecks
- Basic use of Python for data analysis and storytelling

---

## Folder Structure

```
Mini_E_commerce_Funnel_Drop_off_Analysis.ipynb  <- Main analysis notebook
users.csv                                        <- Simulated user data
products.csv                                     <- Simulated product data
events.csv                                       <- Simulated user-event data
README.md                                        <- Project overview and summary
```

---

## Future Improvements

- Add time-based funnel analysis (e.g., conversion trends over hours/days)
- Include session-level data to study bounce rates and dwell time
- Add segmentation by user demographics or marketing channel