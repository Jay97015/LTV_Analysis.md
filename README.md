# LTV_Analysis.md

🚀 Data Project Update: Why looking ONLY at initial acquisition costs is a dangerous business trap.

On my last post, a great question was raised about the long-term impacts of ad-spend shifts on overall ROI. To answer that, I built Phase 2 of my SQL marketing analytics project. 

I engineered a new database pipeline to track Customer Lifetime Value (LTV) over a 6-month window. The results completely flipped the strategy upside down! 📊

🔄 The True ROI Breakdown:
• Instagram: Upfront CAC of $4.0, but generates a massive $255.0 LTV — yielding an incredible 63.75x return on ad spend.
• Facebook: Upfront CAC of $6.6, bringing in $75.0 LTV (11.36x return).
• Google: Upfront CAC of $6.4, but drops to a low $25.0 LTV (only a 3.91x return).

🏆 The Strategy Shift:
Before this analysis, shifting budget away from higher upfront channels seemed logical. However, tracking actual transaction history via SQL subqueries proved that Instagram users are highly loyal, long-term spenders, while Google users are mostly one-time buyers. 

🛠️ Tech Stack & Methods:
• Developed transactional database schemas mapping purchase histories to acquisition sources.
• Utilized aggregate subqueries and JOIN operations to isolate true LTV:CAC ratios.

🎯 Final Leadership Recommendation: 
Aggressively protect and scale the Instagram budget to maximize long-term enterprise value, while optimizing Google campaigns to improve retention before adding more spend.

Check out how I solved the long-term ROI puzzle in the repo:
👉 https://github.com/Jay97015/sql-marketing-analytics/blob/main/README.md

#DataAnalytics #SQL #BusinessIntelligence #CustomerLifetimeValue #ROI #DataPortfolio
