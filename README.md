### Project Overview

The goal of this project is to move beyond simple acceptance rates and understand the underlying behaviors and characteristics of customers who accept promotional coupons. By analyzing two distinct coupon types—Bar and Coffee House—this report identifies key predictive factors and builds customer personas. The final objective is to provide the marketing team with actionable, data-driven recommendations to increase campaign efficiency and return on investment (ROI).

### Key Questions

1.  What are the universal principles that drive coupon acceptance, regardless of the coupon type?
2.  What are the specific, distinguishing characteristics of a customer who will accept a **Bar coupon**?
3.  What is the profile of a customer who is most receptive to a **Coffee House coupon**?

### Key Findings

The analysis revealed two primary principles that govern coupon acceptance: the power of existing habits and the importance of context.

#### 1. The Habit Principle: Coupons Reinforce, They Don't Create

The most significant predictor of acceptance for any coupon is whether it aligns with a customer's pre-existing, frequent behavior.

*   **Bar Coupon Evidence:** While the overall acceptance rate for bar coupons was only 41%, it skyrocketed to **77%** among customers who already frequent bars more than three times a month.
*   **Coffee House Evidence:** This same trend held true for coffee coupons. Customers who are already regular visitors to coffee shops showed a dramatically higher acceptance rate than those who rarely or never go.

#### 2. Context is King: Demographics and Situation Drive Decisions

Once a habit is established, secondary factors like demographics, time of day, and social situation determine the final decision.

*   **Demographic Context:** Bar coupons were most effective with patrons **over the age of 25** who have an established social routine.
*   **Situational Context (Time):** Coffee House coupons saw the highest success rate when offered in the **morning (7 AM and 10 AM)**, aligning with daily commute and work routines.
*   **Social Context (Passengers):** The ideal candidate for a bar coupon was typically with friends or a partner, not children. Conversely, coffee coupons were highly effective for customers who were driving **alone**, suggesting a personal, routine-based purchase.

### Actionable Recommendations

Based on these findings, the following strategic recommendations can be implemented to improve future marketing campaigns:

1.  **Adopt a Habit-Based Targeting Model.**
    Instead of broad campaigns, segment customers based on their visit frequency. Target bar promotions exclusively to users who are already identified as frequent bar-goers. Do the same for coffee, restaurants, and other categories. This single change will drastically increase conversion rates.

2.  **Develop Context-Aware Campaigns.**
    Leverage secondary data to deliver the right offer at the right time. For example:
    *   Promote coffee offers primarily during morning hours.
    *   Target bar coupons to users over 25, with promotions weighted towards evenings and weekends.
    *   Consider suppressing offers that conflict with a user's context, such as sending a bar coupon to someone who is frequently with their children.

3.  **Personalize Offers Based on Social Context.**
    Tailor the messaging and offer type to the customer's likely social situation. An offer for "2-for-1 drinks" is perfect for the social bar-goer, while a "50% off your morning coffee" deal is better suited for the solo commuter.

### Files in this Repository

*   `Coupon_Acceptance_Analysis.ipynb`: The complete Jupyter Notebook containing the Python code, exploratory data analysis, and visualizations for this project.
*   `data.csv`: The raw dataset used for the analysis.
