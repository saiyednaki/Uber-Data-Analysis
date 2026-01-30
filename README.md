# Uber-Data-Analysis

**Maximizing Revenue for Taxi Drivers Through Payment Type 
**
**Project Overview
**
In the highly competitive taxi booking industry, maximizing revenue is critical for both long-term business sustainability and driver satisfaction.
This project uses data-driven analysis to examine whether payment type (card vs cash) influences fare amounts, and explores how encouraging certain payment methods can help increase driver revenue without harming customer experience.

The analysis is based on NYC Taxi Trip Records, applying statistical methods and regression techniques to uncover actionable insights.

**Research Objectives**
  - Analyze the relationship between payment type and total fare amount
  - Determine whether customers paying by card generate higher revenue
  - Explore opportunities to nudge customers toward higher-revenue payment methods
  - Provide data-backed recommendations for drivers and taxi platforms

**Research Questions**
  - Is there a statistically significant relationship between payment type and fare amount?
  - Can customers be encouraged to use payment methods that generate higher revenue for drivers without negatively impacting user experience?

**Dataset**
Source: NYC Taxi Trip Records
Scope: Cleaned and preprocessed to focus only on relevant features

**Key Columns Used**
  - passenger_count (1–5)
  - payment_type (Card, Cash)
  - fare_amount
  - trip_distance (miles)
  - trip_duration (minutes)

**Methodology**
1. Descriptive Analysis
Summary statistics for fare amount, trip distance, and payment type
Comparison of average fares and distances between card and cash payments

2. Hypothesis Testing
Two-sample T-test to evaluate differences in average fare by payment type
Tested whether payment method has a significant impact on fare amount

3. Regression Analysis
Linear regression to analyze the relationship between trip duration and fare amount
Helped validate fare behavior across different trip lengths

**Key Findings**
Journey Insights

Card-paying customers have:

  - Higher average fare amount
  - Longer average trip distance
  - Customers tend to prefer card payments for longer and more expensive trips

Metric	Card	Cash
Average Fare	13.70	12.25
Fare Std Dev	6.50	6.20
Avg Trip Distance (miles)	3.23	2.80

**Payment Preference**

  - 67.5% of transactions were card payments
  - 32.5% were cash payments

**Indicates strong customer preference for card payments due to convenience and security**

**Passenger Count Insights**

Single-passenger trips dominate both payment types:

  - 40.08% of card payments
  - 20.04% of cash payments

Transaction frequency decreases as passenger count increases

Hypothesis Testing Results

Null Hypothesis (H₀): No difference in average fare between card and cash payments

Alternative Hypothesis (H₁): A difference exists

**Results:**

**T-statistic: 165.5**
**P-value: < 0.05**

**Null hypothesis rejected
Payment type has a statistically significant impact on fare amount**

Recommendations

  - Encourage credit card payments through:
  - Incentives or small discount
  - Loyalty or reward programs
  - Improve and promote seamless, secure card payment experiences
  - Use insights to guide platform-level nudges that increase revenue while maintaining customer satisfaction

Tools & Technologies

  - Python (Pandas, NumPy, SciPy)
  - Statistical Testing (T-test)
  - Linear Regression
  - Data Cleaning & Feature Engineering
  - Data Visualization (optional dashboards)

**Conclusion**
This project demonstrates that payment method influences fare amount, with card payments consistently generating higher revenue. Strategic nudging toward card payments can meaningfully increase driver earnings without compromising customer experience.
