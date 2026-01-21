# Module 2.2: Analyze Data

## Data-Driven Product Decisions with CSV Analysis

**Estimated time:** 25 minutes

---

## What You'll Learn

PMs make better decisions with data. You'll learn to:

1. ✅ Load and explore CSV data
2. ✅ Perform basic data analysis
3. ✅ Generate insights and recommendations
4. ✅ Create data-driven narratives

---

## The Data Challenge

You have user survey data and need to:
- Understand user satisfaction
- Identify improvement areas
- Prioritize features
- Present findings to leadership

---

## The Dataset

Look at `sample-data.csv` in this folder. It contains:
- User ID
- Signup date
- Plan type
- NPS score
- Feature usage
- Satisfaction ratings
- Feedback comments

---

## Step 1: Explore the Data

Get familiar with what you have.

```
> Read the sample-data.csv file and tell me:
> 1. How many rows (users)?
> 2. What columns are available?
> 3. What date range does it cover?
> 4. What are the unique values for plan_type?
```

---

## Step 2: Basic Statistics

Calculate key metrics.

```
> Analyze the survey data and calculate:
> 
> NPS Analysis:
> - Average NPS score
> - NPS by plan type (Free, Pro, Enterprise)
> - NPS distribution (% Promoters, Passives, Detractors)
> 
> Satisfaction Scores:
> - Average overall satisfaction
> - Satisfaction by feature (tasks, projects, integrations)
> - Lowest-rated areas
```

---

## Step 3: Segment Analysis

Break down by user segments.

```
> Segment the data and analyze:
> 
> By Plan Type:
> - Which plan has highest/lowest satisfaction?
> - What features does each plan value most?
> 
> By Tenure (time since signup):
> - Are new users (<30 days) different from veterans (>90 days)?
> - Does satisfaction change over time?
> 
> By Feature Usage:
> - Do heavy integrations users have different satisfaction?
> - Is there a correlation between feature usage and NPS?
```

---

## Step 4: Feedback Analysis

Analyze the qualitative feedback.

```
> Analyze the feedback_comment column:
> 
> 1. Categorize comments into themes (positive, negative, feature request)
> 2. Extract the top 5 most mentioned pain points
> 3. Pull out the best quotes for each theme
> 4. Identify any urgent issues mentioned
```

---

## Step 5: Correlations & Insights

Find relationships in the data.

```
> Look for correlations and patterns:
> 
> 1. What predicts high NPS scores?
> 2. What features are most correlated with satisfaction?
> 3. Are there any surprising findings?
> 4. What segments need the most attention?
```

---

## Step 6: Create Executive Summary

Package findings for leadership.

```
> Create an executive summary of the survey analysis with:
> 
> Key Findings (top 5):
> - [Finding with specific numbers]
> 
> Opportunities (prioritized):
> - [Opportunity with expected impact]
> 
> Risks:
> - [Risk with supporting data]
> 
> Recommended Actions:
> - [Action with expected outcome]
> 
> Save to outputs/survey-analysis-exec-summary.md
```

---

## Step 7: Create Detailed Report

For the full analysis.

```
> Create a detailed survey analysis report with:
> 
> 1. Executive Summary (from above)
> 2. Methodology (what data, how analyzed)
> 3. Key Metrics Dashboard (table format)
> 4. Segment Analysis (by plan, tenure, usage)
> 5. Qualitative Insights (feedback themes)
> 6. Recommendations (prioritized with rationale)
> 7. Appendix (data tables, additional charts)
> 
> Save to outputs/survey-analysis-full-report.md
```

---

## Data Analysis Best Practices

### Start with Questions

Don't just explore - start with what you need to know:
- What's our NPS trend?
- Which users are at risk?
- Where should we invest?

### Segment Everything

Overall averages hide insights. Always break down by:
- Plan type
- User tenure
- Feature usage
- Geography

### Mix Quant and Qual

Numbers tell you what. Quotes tell you why.
- "NPS is 35" + "Users say onboarding is confusing"
- Data + context = actionable insight

### Lead with So What

Don't just present data. Present implications:
- ❌ "NPS is 35"
- ✅ "NPS is 35, below our target of 50. Enterprise users are happiest (45), while Free users are unhappiest (25). This suggests our upgrade path is working but we're losing potential converters."

---

## Common Analysis Prompts

| Task | Prompt |
|------|--------|
| Basic stats | "Calculate average, median, min, max for [column]" |
| Group by | "Break down [metric] by [dimension]" |
| Find patterns | "What correlates with [outcome]?" |
| Identify outliers | "Find unusual values in [column]" |
| Compare segments | "Compare [group A] vs [group B] on [metrics]" |

---

## Checkpoint ✅

Before moving on, make sure you have:
- [ ] Explored and understood the dataset
- [ ] Calculated key metrics by segment
- [ ] Analyzed qualitative feedback
- [ ] Created executive summary and full report

---

## Next Steps

In **Module 2.3: Product Strategy**, you'll learn to use Copilot for strategic planning and competitive analysis.

**Tell Copilot:**
```
Let's start Module 2.3 - Product Strategy
```

---

**You're making data-driven decisions! 📊**
