---
title: "Segments, Outcomes, and Action Maps"
chapter: false
weight: 20
---

### Segments
#### Definition:
Group of visitors that share similar behavior or characteristics. Session segments expire when the single session ends. Customer segments persist across sessions. For more information, see **[Create segments](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_segments)**.
#### What this means:
Segments are used to identify visitors based on their shared characteristics. Later, you design action maps to engage specific segments of visitors and then filter by segments to evaluate how well you are engaging them. 
Some examples of segments are: 
- Visitor attributes
    - Location 
    - Browser Type 
    - Device Type & OS
- Visitor Journey
    - Page URL
    - Search Query 
    - Keyword Search
![Segment](/images/SegmentConfig.png)
### Outcomes
#### Definition:
Business goal that you want to track and achieve. For more information, see **[Create outcomes](https://all.docs.genesys.com/ATC/Current/AdminGuide/Manage_outcomes)**.
#### What this means:
Genesys Predictive Engagement uses AI-powered machine learning to predict the probability of visitors achieving your unique business outcomes.   
Some examples of trackable conditions and characteristics
- Idle TIme
- Abandon Form
- Submission
- Viewed Page
![Outcomes](/images/OutcomeConfig.png)
### Action Maps
#### Definition:
Defines how you want Genesys Predictive Engagement to interact with a visitor based on the visitor's matching segments and your preferred outcomes. For more information, see **[Create an action map](https://all.docs.genesys.com/ATC/Current/AdminGuide/Action_maps)**.
#### What this means:
Action maps use different types of actions to enhance and extend a visitor's journey. 
Some actions that can be triggered based on Visitor Segments: 
- Offer Web Chat or Web Message
- Content Pop offer
    - Discount code
    - Special Offers
- Advanced Orchestration (Architect Flow to queries, bots, or to update a third-party system)
![ActionMap](/images/ActionMapConfig.png)