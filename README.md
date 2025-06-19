# Overview
---
DigitalPath Innovations, a leader in digital marketing solutions, seeks to enhance its website's user experience to improve engagement metrics, conversion rates, and customer satisfaction. The company has conducted an A/B test over two weeks, presenting two distinct versions of its webpage (Version A and Version B) to a randomised group of users. This experiment aims to identify which webpage version performs better across various user engagement metrics.

DigitalPath Innovations has compiled a detailed dataset capturing user interactions, behaviours, and responses to each webpage version. This dataset presents a unique opportunity to analyse the effectiveness of each design, inform future design iterations, and ultimately enhance user experience based on data-driven insights.


# Data Dictionary
---
- `UserID:` Unique identifier for each user
- `SessionID:` Unique identifier for each user session
- `Version:` The version of the webpage the user was shown (A or B)
- `Date:` Date of the session
- `TimeSpent:` Total time spent on the webpage in seconds
- `PagesViewed:` Number of pages viewed during the session
- `ActionsTaken:` Total number of actions taken (e.g., clicks, form submissions)
- `ProductViewed:` Number of products viewed
- `ProductAdded:` Number of products added to cart
- `CheckoutInitiated:` Whether the user-initiated checkout
- `PurchaseMade:` Whether a purchase was made
- `FeedbackSubmitted:` Whether feedback was submitted
- `VideoWatched:` Whether any video content was watched
- `ReferralSource:` The referral source that led the user to the webpage

# Analysis Goals
---
The project's focus is to perform a comprehensive analysis of user behaviour across the two webpage versions, employing Tableau for visual analytics. The project's objectives include: 
**Engagement Metrics Analysis**
Assess how each webpage version impacts user engagement, as indicated by time spent on the site, pages viewed, and actions taken.

**Conversaion Rate Optimisation**
Compare the conversion funnel for both versions, analysing metrics from product views to purchase completion. 

**User Feedback Analysis**
Evaluate the correlation between user feedback submission and the webpage version to gauge user engagement/satisfaction.

**Content Interaction**
Investigate the influence of webpage version on content interaction, specifically video watching behaviours.

**Referral Source Impact**
Analyse how different referral sources affect user behaviour and preferences for each webpage version.



# Analysis
---

![Dashboard 2](https://github.com/user-attachments/assets/d7e2b539-b4f4-4833-86a6-34569e3df68e)

**Average time spent (mins)** - In scenario A, website users exposed to Version A spent more time on the website (average of 5 minutes) compared to scenario B (3.3 minutes), indicating that scenario A was more engaging.

**Average pages viewed** - Website users navigating scenario A viewed an average of 10 pages, while scenario B users only explored about 5 pages, showing deeper engagement with scenario A.

**Average action taken** - The number of actions taken per session was nearly the same across both scenarios, with 4.9 actions in scenario A and 5.0 in scenario B, implying comparable interaction levels

**Average products viewed by users** - In scenarios A and B, there was a marginal average viewers across products 1, 2 and 3. However, product 3 had the most views in both scenarios.

**Percentage of feedback** - Feedback submission was low overall in both scenarios, with 18.7% in scenario A and 17.9% in scenario B, suggesting user satisfaction or willingness to give feedback was similarly low.

**Percentage of cart additions by users** - A significant number of users added items to their cart in both scenarios: 71.5% in scenario A and 72.6% in scenario B, with scenario B showing a slight advantage.

**Percentage of checkout** - Over half of the users proceeded to checkout in both scenarios: 62.8% in scenario A and 61.4% in scenario B, which aligns with e-commerce best practices.

**Percentatge of conversion** - Scenario A showed a high conversion rate of 70.5%, while scenario B lagged behind at 38.2%. Interestingly, scenario A’s conversion rate exceeded its cart addition rate, hinting at possible external conversions or tracking anomalies.

**Content interactions** - It is observed that in scenarios A and B, website users interact with content within a certain timeframe across different referral sources marginally. Notably, in scenario A, 178, 151, and 163 users had interactions with content across direct, search engine, and social media referral sources, respectively, within an almost the same time frame of 5 minutes. This pattern was also observed in scenario B.

# Recommendations
---
- **Adopt Version A as the Default Page Design**: Due to better engagement metrics like time spent and pages viewed, Version A seems more effective at holding user attention.

- **Investigate Conversion Path Discrepancies**: The unusually high conversion rate in Version A (compared to cart addition) suggests external purchases or tracking issues. This should be investigated and addressed.

- **Optimise and Promote Product 3**: Since Product 3 consistently attracted the most views, consider spotlighting it more prominently or bundling it with other products to maximise conversion.

- **Enhance Feedback Collection**: Implement proactive strategies (e.g., exit surveys, incentivised feedback) to boost the low feedback rates and better understand user satisfaction.

- **Improve Content Strategy Across Channels**: Since engagement with video content is uniform across referral sources, create more targeted and platform-optimised content to increase stickiness and personalisation.

- **Monitor and Compare Post-Conversion Behaviour**: Track whether users who convert return, leave reviews, or refer others. Understanding post-conversion engagement will help improve long-term value.















