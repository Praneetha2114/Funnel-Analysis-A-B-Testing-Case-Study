# Funnel-Analysis-A-B-Testing-Case-Study

## 1. Problem Statement & Context

Online learning platforms often see a high number of user sign-ups, but only a small percentage of users actively engage with courses or complete them. This gap indicates potential issues in the user journey, such as unclear onboarding, lack of guidance, or insufficient motivation after enrollment.

The objective of this project is to analyze the user funnel of an online learning platform to identify drop-off points, understand user behavior, and propose data-driven improvements to increase engagement and conversion.

## 2. Funnel Definition

The following funnel represents the key stages in the user journey:

1. User Sign-up  
2. Course Browsing  
3. Course Enrollment  
4. Course Start  
5. Course Completion  
6. Paid Conversion

Each stage of the funnel was analyzed to measure user drop-offs and identify areas where users disengage from the platform.

## 3. Metrics & Funnel Analysis

To evaluate user engagement across the funnel, the following metrics were analyzed:

- Sign-up to Enrollment Conversion Rate  
- Enrollment to Course Start Rate  
- Course Completion Rate  
- Free to Paid Conversion Rate  

User activity data was aggregated and analyzed to calculate conversion percentages at each stage. Pivot tables and charts were used to visualize trends and identify significant drop-offs.

## 4. Key Insights & Drop-offs

Key observations from the funnel analysis include:

- A significant drop-off occurs between Course Enrollment and Course Start, indicating possible onboarding friction.
- Users who start the course are more likely to complete it, suggesting early engagement is critical.
- Paid conversion is higher among users who complete at least 30% of a course.

These insights highlight the need for improved guidance and motivation immediately after course enrollment.


## 5. A/B Testing Hypothesis & Design

To address the drop-off between Course Enrollment and Course Start, a mock A/B test was designed.

### Hypothesis
If users receive a clear onboarding prompt immediately after enrolling in a course, the course start rate will increase.

### Test Variants
- **Control (A):** Existing user experience with no onboarding prompt after enrollment.
- **Variant (B):** An onboarding message with a clear “Start Course” call-to-action shown immediately after enrollment.

### Success Metrics
- **Primary Metric:** Course Start Rate (%)
- **Secondary Metrics:** Time to first lesson, Course Completion Rate

### Test Setup
- Duration: 2 weeks  
- Audience: Newly enrolled users  
- Traffic Split: 50% Control, 50% Variant


## 6. Recommendations & Expected Impact

Based on the analysis and A/B test design, the following recommendations are proposed:

- Implement onboarding prompts permanently if Variant B shows improved course start rates.
- Monitor downstream metrics such as course completion and paid conversion.
- Introduce reminder notifications for users who do not start the course within 24 hours.

These changes are expected to improve early engagement, reduce user drop-offs, and increase overall platform conversion.
