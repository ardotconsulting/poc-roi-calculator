# poc-roi-calculator

Interactive ROI calculator proof of concept for [The Real ROI of AI Automation: How to Measure It](https://www.ardotconsulting.com/blog/2026/08/24/the-real-roi-of-ai-automation-how-to-measure-it/).

A single-page static app that implements the four-lever ROI framework from the blog post:

1. **Time Saved** — manual vs automated task time × volume × labor rate
2. **Error Reduction** — old vs new error rate × volume × cost per error
3. **Throughput Increase** — added capacity × utilization × revenue per unit
4. **Employee Retention** — reduced turnover × employees × replacement cost

Combines all four into total monthly benefit, subtracts monthly costs, and computes:
- ROI percentage
- Payback period
- ROI without throughput (conservative scenario)

Includes preset scenarios from the blog post's case studies.
