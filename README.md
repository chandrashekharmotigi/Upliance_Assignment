## Introduction
This project analyzes user behavior, cooking session engagement, and order details from three datasets:
- **UserDetails**: Demographic and engagement information of users.
- **CookingSessions**: Records of user-participated cooking events.
- **OrderDetails**: Logs of orders placed by users.

The combined data provides insights into user preferences, engagement patterns, and business impact.

---

## Methodology

### Data Cleaning and Preparation
1. **Loading and Exploring**:
   - Loaded datasets into dataframes using Pandas.
   - Conducted initial data exploration for completeness and structure.

2. **Cleaning**:
   - Handled missing values through appropriate imputation or removal.
   - Removed duplicate records to ensure data integrity.
   - Standardized data types, particularly for date and time fields.

3. **Feature Engineering**:
   - Created new metrics:
     - `Order Frequency`: Orders per day since user registration.
     - `Cooking Engagement`: Number of cooking sessions per user.
     - `Revenue Contribution`: Total revenue contributed by each user.

### Data Integration
- Merged datasets based on common keys:
  - `User ID` for UserDetails and CookingSessions.
  - `Session ID` for CookingSessions and OrderDetails.
- Added derived features for deeper insights.

### Data Analysis
1. **Behavior Analysis**:
   - Performed correlation analyses to identify relationships between user activities, orders, and engagement levels.
   - Extracted insights into popular meal types, top dishes, and user-specific engagement patterns.

2. **Segmented Insights**:
   - Analyzed user engagement and order frequency across age groups and locations.
   - Identified top-performing locations by revenue contributions.

---

## Findings

1. **User Engagement**:
   - Higher cooking engagement correlated with more orders (correlation coefficient: 0.554).

2. **Top Dishes and Meal Types**:
   - Most ordered dishes: *Spaghetti* and *Grilled Chicken*.
   - Meal Type Preference: Dinner was the most popular, followed by lunch and breakfast.

3. **Demographic Insights**:
   - The age group *26-35* had the highest cooking engagement and order frequency.
   - *New York* and *Los Angeles* were the top revenue-contributing locations.

4. **Revenue Analysis**:
   - Cooking engagement positively impacted revenue contribution, emphasizing the value of encouraging participation.

---

## Recommendations

1. **Targeted Campaigns**:
   - Design campaigns to engage the *26-35* age group and boost cooking session participation.
   - Focus marketing on high-revenue locations like *New York* and *Los Angeles*.

2. **Menu Optimization**:
   - Promote top dishes like *Spaghetti* and *Grilled Chicken*.
   - Develop meal plans for the most popular meal type: *Dinner*.

3. **Engagement Initiatives**:
   - Introduce loyalty programs rewarding cooking session participation and frequent orders.
   - Offer incentives for low-engagement users to increase activity.

4. **Data Utilization**:
   - Continuously monitor user engagement and revenue metrics to refine strategies.



