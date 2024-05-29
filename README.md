# Planet Fitness - Roswell Alpharetta Gym Performance Analysis

## Introduction
Welcome to the Planet Fitness - Roswell Alpharetta Gym Performance Analysis repository. This project delves into the performance of the Planet Fitness gym located in Roswell Alpharetta, highlighting areas of underperformance compared to nearby competitors. Through data analysis and forecasting, we aim to identify opportunities for improvement and provide actionable recommendations to enhance the gym's performance.

## Overview
This project utilizes a data-driven approach to analyze various aspects of the gym's performance, including customer acquisition, activation, retention, referral, and revenue. By leveraging the AARRR framework (Acquisition, Activation, Retention, Referral, and Revenue), we aim to gain insights into key metrics and develop strategies for improvement.

## Data Analysis
The project involves extensive data exploration and visualization to uncover insights into customer behavior, preferences, and trends. We analyze factors such as foot traffic patterns, demographics of visitors, customer feedback, and facility conditions to identify areas of strength and weakness.

### Key Insights from Data Analysis
- **Competitive Landscape**: Nearby competitors include another Planet Fitness with better facilities and a Crunch Fitness located in the same shopping area.
- **Customer Feedback**: Negative reviews mention theft, homeless individuals, and poor customer service, impacting customer satisfaction and retention.
- **Visitor Behavior**: Visitors stay on average 25 min at the underperforming gym compared to almost 50 min at competitors, indicating dissatisfaction with amenities and services.

## Data Forecasting
In addition to retrospective analysis, this project involves forecasting future performance based on historical data trends and market dynamics. We utilized machine learning models to predict gym visitor counts for different locations.

### Forecasting Results
#### Milton Gym:
- Linear Regression: MSE of 14580.08
- Random Forest: MSE of 15348.06
- Neural Network: MSE of 23766.88
(More details about model performance and interpretation)

#### Woodstock Gym:
- Linear Regression: MSE of 51991.50
- Random Forest: MSE of 51145.39
- Neural Network: MSE of 56525.90
(More details about model performance and interpretation)

#### Roswell Gym:
- Linear Regression: MSE of 39674.90
- Random Forest: MSE of 36798.62
- Neural Network: MSE of 43643.06
(More details about model performance and interpretation)

#### Underperforming Roswell Gym:
- Linear Regression: MSE of 24191.68
- Random Forest: MSE of 20758.33
- Neural Network: MSE of 33002.04
(More details about model performance and interpretation)

## Repository Structure
- **Data**: Contains datasets used for analysis and forecasting.
- **Notebooks**: Jupyter notebooks documenting data analysis, visualization, and forecasting methodologies.
- **Reports**: Reports summarizing key findings, insights, and recommendations.
- **Presentations**: Presentation slides for communicating analysis results to stakeholders.
- **Scripts**: Python scripts for data preprocessing, modeling, and visualization.

## Conclusion
By leveraging data analysis and forecasting techniques, this project aims to provide actionable insights and recommendations to enhance the performance of the Planet Fitness gym in Roswell Alpharetta. Continuous monitoring and adaptation based on data-driven insights will be crucial for achieving long-term success and maintaining a competitive edge in the fitness market.


# Gym Performance Analysis Details

## Introduction

While conveniently situated for many residents, recent data and customer feedback suggest the Alpharetta gym is underperforming compared to nearby competitors, like Crunch Fitness and another Planet Fitness just a 10-minute drive away.

Here's a summary of the key challenges:
* Negative reputation due to facilities and service, as highlighted by customer reviews.
* Shorter visit durations compared to competitors with better amenities.
* Convenience might attract locals initially, but it's not enough to compete for retention against superior experiences offered elsewhere.


ROADMAP: 
- Let's delve into the reasons behind this and explore opportunities to make the Roswell Alpharetta gym a thriving destination.
- We will also use the AAARR framework to orient ourselves along the Planet Fitness customer journey.
- I will make some recommendations for how the gym could improve for that stage of the customer journey.

## Understanding Our Customers (AARRR Framework)

The Pirate Metrics framework (AARRR – Acquisition, Activation, Retention, Referral, Revenue) is a valuable tool for analyzing a gym's performance because it allows you to pinpoint specific areas for improvement and track progress in a systematic and timely manner.

### Identifying Bottlenecks
By analyzing each stage of the customer journey, you can identify where the Roswell gym is underperforming. In this case, while the gym might be attracting a decent number of visitors due to its convenient location (Acquisition), it struggles to convert them into regular members (Activation & Retention) due to issues with facilities and service.

### Targeted Improvements and Timely Measurement
Once you identify bottlenecks, you can focus your improvement efforts on specific metrics. For example, the Roswell gym can target Activation by upgrading facilities and enhancing customer service. The impact of these improvements can then be measured by tracking changes in average visit duration and member retention rates. This allows for a data-driven approach to improvement, ensuring you're addressing the root causes impacting visitation.

### Metrics Can Provide Timely Insights
The Pirate Metrics provide insights you can use to make timely decisions. Analyzing data on Acquisition allows you to adjust marketing campaigns quickly if new member sign-ups are lagging. Similarly, tracking member churn rate (part of Retention) allows you to identify and address issues that might be causing members to cancel before their memberships expire.

The Pirate Metrics framework is powerful because it allows you to strategically focus on improving one stage of the customer journey at a time.

Let’s jump into the customer journey of the Roswell Alpharetta visitor:

## Demographic and Age Structure

Roswell is located in a bustling suburb of Atlanta with a majority of its residents in the 25-29 age range, which is a great fit for fitness amenities. In fact, there are a astonishingly large amount of gyms in the area… and even a Planet Fitness gym located 10 minutes away.

### Acquisition: Attracting New Members

**Question:** Are we effectively attracting new members in Roswell?

**Data Insights:** Our data shows a high concentration of visitors living within 5 miles of the Roswell gym, indicating its convenience is a factor. However, customer acquisition seems to be lagging compared to nearby competitors.

**Actionable Recommendation:** Develop targeted local advertising campaigns highlighting the gym's convenient location. Consider offering referral program incentives for existing members to spread the word about the gym's benefits (this also overlaps with the referral stage later on).

#### Customer Story: Convenience vs. Experience
Imagine Sarah, a resident of Roswell considering gyms. She is an insurance broker who sometimes drives into the office 30 minutes away. She finds two Planet Fitness locations nearby: ours and another with a newer facade and more amenities. Additionally, there's Crunch Fitness in the same shopping area. Convenience initially draws Sarah to our gym, but negative customer reviews mentioning uncleanliness, security concerns with homeless individuals, and poor customer service could make her reconsider.

### Activation & Retention: Converting Visitors into Engaged Members

**Question:** Once people visit, are we effectively converting them into engaged members?

**Data Insights:** Here's where the challenge lies. Compared to competitors, the Roswell gym has shorter average visit durations, suggesting people aren't staying long or coming as frequently. Customer reviews also mention issues with facility condition and service, impacting the overall gym experience.

**Retention:** Though it does look like the 600 or so device IDs that come into the gym are loyal. In fact, Roswell had the highest retention rating after the first visit after 7 days.

**Actionable Recommendations:**
* Invest in facility upgrades to match competitor amenities and address concerns raised in customer feedback. This could involve modernizing equipment, improving cleanliness, and creating a more welcoming environment.
* Enhance customer service training to ensure a friendly, helpful, and secure environment for all members.

### Referral: Leveraging Our Network

**Question:** Are we leveraging our existing members to attract new ones?

**Data Insights:** Given the lower performance in acquisition, referral programs could be underutilized.

**Actionable Recommendations:**
* Expand referral programs to incentivize both referring members and new joiners.
* Encourage social media engagement where members can share positive experiences to amplify word-of-mouth marketing. Highlight the improvements made at the gym to encourage positive testimonials.

## Prioritizing Improvement Stages

Based on the data and customer feedback, the most pressing issue seems to be converting visitors into regular members (Activation & Retention). Focusing on this stage first can yield significant improvements in overall gym visitation.

### Actionable Steps for Activation & Retention
* **Facility Upgrades:** Invest in modernizing equipment, improving cleanliness, and creating a more inviting atmosphere. Track changes in average visit duration after implementing upgrades.
* **Enhanced Customer Service:** Train staff to be friendly, helpful, and create a secure environment. Monitor member satisfaction surveys and track changes in renewal rates.

### Measuring Progress
* Track changes in average visit duration after facility upgrades. An increase suggests people are staying longer, indicating a more enjoyable experience.
* Monitor member satisfaction surveys to gauge the impact of improved customer service. A rise in positive feedback suggests a more welcoming environment.
* Track member churn rate (the rate at which members cancel) before and after implementing changes. A decrease in churn indicates improved retention.

## Actionable Recommendations

Based on our data-driven analysis, here are some recommendations to transform the Roswell Alpharetta gym:
* **Facility Upgrades:** Modernize the gym and address concerns raised in customer feedback.
* **Customer Service Training:** Enhance staff training to ensure a welcoming and helpful environment.
* **Targeted Marketing Campaigns:** Highlight the gym's convenient location while showcasing the improvements made.
* **Improved Onboarding Process:** Implement a comprehensive onboarding process for new members to get them acquainted with the gym and its offerings.
* **Loyalty Programs & Flexible Memberships:** Introduce loyalty programs and flexible membership options to cater to different member needs and encourage continued membership.
* **Referral Program Expansion:** Expand referral programs with rewards for both the referring member and new joiners.
* **Social Media Engagement:** Utilize social media to encourage positive member engagement and highlight the gym's improvements.

## Arguments for Keeping the Gym

* **Strong Local Customer Base:** The gym enjoys a loyal customer base from within a 5-mile radius, indicating convenience is a major factor for them. Removing the gym could force them to switch to competitors like LA Fitness or Crunch Fitness.
* **Retention vs. Acquisition:** While acquiring new members might be challenging due to another Planet Fitness nearby, retaining existing loyal members can be more cost-effective than attracting entirely new ones from further away.
* **Data on Cannibalization:** Analyze data on member overlap between the two gyms. If a significant portion of members don't use both locations, cannibalization might be minimal.

## Arguments for Removing the Gym

* **Market Saturation:** Two Planet Fitness gyms within 11 minutes might indicate market saturation. Combining resources at one location could be more efficient.
* **Operational Costs:** Maintaining two locations close together doubles operational costs like rent, utilities, and staff. Consolidating could lead to cost savings.
* **Analyzing Member Traffic:** See if the closer gym is busier than the one you're considering removing. Traffic patterns might suggest which location serves a larger and more active member base.

## Conclusion

By following these data-driven recommendations and focusing on continuous monitoring and adaptation, we can transform the Roswell Alpharetta gym into a thriving destination for fitness enthusiasts in Roswell. We can provide a superior gym experience that not only attracts new members but also retains existing ones, ultimately leading to a more successful gym.

By analyzing this data, you can make a more informed decision about what's best for Planet Fitness. Keeping the gym with a strong local base might be better if member overlap is minimal, while consolidation could be more strategic if operational costs are high and member usage patterns favor the closer location. It's a balancing act between convenience for existing members and optimizing operational efficiency.

### Addressing Other Stages

Once Activation & Retention improve, you can tackle other stages in the Pirate Metrics framework:
* **Acquisition:** With a more positive gym reputation, revisit local advertising campaigns highlighting the improvements. Utilize social media for member testimonials showcasing the enhanced experience. Monitor new member sign-ups after implementing these strategies.
* **Referral Programs:** Expand referral programs with more attractive rewards for both referring members and new joiners. Track the number of new members acquired through referrals.
* **Revenue:** As overall gym performance improves, explore introducing additional services like personal training or offering flexible membership options. Monitor changes in average revenue per member.

### Benefits of a Stage-by-Stage Approach
* **Focused Efforts:** Focusing on one stage allows for concentrated resources and avoids spreading improvements too thin.
* **Measurable Progress:** By focusing on specific metrics within each stage, the gym can track progress and demonstrate the impact of its efforts.
* **Motivation:** Seeing clear improvements at each stage can be motivating for the gym's staff and management, keeping them engaged in the overall improvement process.

Remember, this is a continuous process. As you improve each stage, revisit previous stages to ensure they remain optimized. The Pirate Metrics framework provides a valuable roadmap for the Roswell Alpharetta gym to transform itself into a thriving destination, one well-defined step at a time.

### Recommendation

Instead of a definitive recommendation, here's a data-driven approach to decide:
1. **Analyze Member Demographics:** Compare the demographics of members at both gyms (age, income, workout preferences, etc.).
2. **Track Member Usage:** See how often members use each gym, and if there's significant overlap between the two locations.
3. **Consider Member Feedback:** Conduct surveys or hold focus groups to understand how members feel about each gym's location, amenities, and overall experience.
4. **Run Cost-Benefit Analysis:** Estimate the cost savings from closing one gym and the potential loss of revenue from member churn.



