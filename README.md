#Mobile Price Prediction
Project Description:
This project analyzes a dataset of mobile phone specifications to predict the price range of a phone based on its features. It includes EDA, feature engineering, and correlation analysis to understand the impact of different features on pricing.

Dataset Columns:

battery_power, blue, clock_speed, dual_sim, fc, four_g, int_memory, m_dep, mobile_wt, n_cores, pc, px_height, px_width, ram, sc_h, sc_w, talk_time, three_g, touch_screen, wifi, price_range

Key Steps:

Data Exploration: Check distributions, outliers, and missing values.

Feature Engineering:

screen_area = sc_h * sc_w

pixel_density = sqrt(px_height² + px_width²)/screen_area

memory_per_core = int_memory / n_cores

connectivity_score = dual_sim + four_g + three_g + wifi + blue

Visualization:

Histograms, scatter plots, boxplots, bar plots

Correlation heatmap to identify important features

Target Mapping: price_range mapped to Low, Medium, High, Premium

Purpose:

Understand which features influence mobile price.

Prepare data for machine learning models to predict phone price range.

Technologies Used:

Python, Pandas, NumPy, Matplotlib
