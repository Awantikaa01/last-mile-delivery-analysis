<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,50:764ba2,100:f093fb&height=220&section=header&text=Last%20Mile%20Delivery%20Analysis&fontSize=38&fontColor=ffffff&animation=fadeIn"/>

# 🚚 Last Mile Delivery Delay Root Cause Analysis

### AI Data Intelligence Challenge Submission

**Author: Awantika Tripathi**

</div>


## Project Overview

This project analyzes last-mile delivery order data across Indian cities to identify the major causes of delivery delay. The solution covers data loading, cleaning, missing value handling, outlier flagging, exploratory data analysis, statistical testing, dashboarding, and a basic machine learning model.

## 🚀 Project Highlights

✔ Cleaned and analyzed 2,080 delivery records

✔ Performed Exploratory Data Analysis (EDA)

✔ Conducted Statistical Significance Testing

✔ Built City-Level Performance Dashboard

✔ Generated Actionable Business Recommendations

✔ Applied Machine Learning Techniques

## Objective

Transform raw delivery order data into actionable business insights and recommend one operational fix to reduce delays.

## Dataset

File used:

`last_mile_delivery_dataset.csv`

The dataset contains 2,080 delivery orders across 20 original columns, including order date/time, city, zone, rider details, vehicle type, weather condition, delivery time, delay, and delivery status.

## Key Questions Answered

1. Do orders placed during 8-10 AM and 5-8 PM have significantly higher delay than off-peak orders?
2. How does median delay vary across weather conditions, and which order type is hit hardest by rain?
3. Is there a statistically meaningful difference in delay between riders with under 2 years and over 4 years of experience?
4. What does the city-level performance dashboard reveal, and what is the biggest operational fix?

## Files in This Repository

- `Last_Mile_Delivery_Analysis.ipynb` - main Jupyter Notebook solution
- `last_mile_delivery_dataset.csv` - dataset
- `Last_Mile_Delivery_Solution.pptx` - presentation summary
- `README.md` - project documentation and run instructions

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone or download this repository.

2. Open CMD or terminal inside the project folder.

3. Install required libraries:

```bash
python -m pip install pandas numpy matplotlib seaborn scipy scikit-learn notebook
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open:

`Last_Mile_Delivery_Analysis.ipynb`

6. Run all cells:

`Kernel -> Restart Kernel and Run All Cells`

## Main Findings

- Peak-hour orders have much higher delays than off-peak orders.
- Peak-hour average delay is about 23.25 minutes, compared with 7.38 minutes during off-peak hours.
- Fog and rain cause the highest delivery delays.
- During rain, Medicine orders are affected the most.
- Rider experience is not the strongest delay driver in this dataset.
- City-wise and vehicle-wise performance shows that dispatch planning should be more targeted.

## Final Recommendation

Implement a risk-based dispatch plan:

- Add more riders during 8-10 AM and 5-8 PM.
- Prioritize Medicine orders during rain and fog.
- Assign faster vehicles and experienced riders to high-risk city/weather combinations.
- Track city-level on-time rate weekly and rebalance rider supply.

## Submission Items

Submit the following:

- GitHub repository URL
- `Last_Mile_Delivery_Analysis.ipynb`
- `Last_Mile_Delivery_Solution.pptx`
- Dataset file, if required by the submission portal

## 📌 Executive Summary

| Finding | Insight |
|----------|----------|
| Peak Hour Impact | Delays are ~3x higher during peak periods |
| Weather Effect | Fog and Rain cause maximum delays |
| Order Type Risk | Medicine deliveries are most affected |
| Rider Experience | Limited impact on delivery delays |
| Biggest Fix | Peak-hour staffing + weather-aware dispatch |


---

## 👩‍💻 Author

**Awantika Tripathi**

B.Tech Computer Science Engineering

MiniHack: AI Data Intelligence Challenge Submission

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f093fb,50:764ba2,100:667eea&height=120&section=footer"/>

</div>