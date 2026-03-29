---
name: performance-reporter
version: "4.1.0"
description: 'Generate consolidated SEO and GEO performance dashboards combining rankings, traffic, backlinks, and AI visibility metrics for stakeholders. Use when the user asks to "generate SEO report", "performance report", "SEO dashboard", "report to stakeholders", "show me the numbers", "monthly SEO report", "traffic report", or "present SEO results to my boss". For detailed rank tracking, see rank-tracker. For link-specific analysis, see backlink-analyzer.'
license: Apache-2.0
compatibility: "Claude Code ≥1.0, skills.sh marketplace, ClawHub marketplace, Vercel Labs skills ecosystem. No system packages required. Optional: MCP network access for SEO tool integrations."
homepage: "https://github.com/aaron-he-zhu/seo-geo-claude-skills"
metadata:
  author: aaron-he-zhu
  version: "4.1.0"
  geo-relevance: "medium"
  tags:
    - seo
    - geo
    - performance report
    - seo report
    - traffic analysis
    - seo dashboard
    - executive summary
    - analytics report
    - kpi tracking
    - seo-reporting
    - kpi-dashboard
    - monthly-report
    - traffic-report
    - analytics-report
    - stakeholder-report
    - seo-metrics
    - organic-traffic
    - ctr-report
  triggers:
    - "generate SEO report"
    - "performance report"
    - "traffic report"
    - "SEO dashboard"
    - "report to stakeholders"
    - "monthly report"
    - "SEO analytics"
    - "show me the numbers"
    - "monthly SEO report"
    - "present SEO results to my boss"
---

# Performance Reporter


> **[SEO & GEO Skills Library](https://github.com/aaron-he-zhu/seo-geo-claude-skills)** · 20 skills for SEO + GEO · [ClawHub](https://clawhub.ai/u/aaron-he-zhu) · [skills.sh](https://skills.sh/aaron-he-zhu/seo-geo-claude-skills)

<details>
<summary>Browse all 20 skills</summary>

**Research** · [keyword-research](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/research/keyword-research/SKILL.md) · [competitor-analysis](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/research/competitor-analysis/SKILL.md) · [serp-analysis](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/research/serp-analysis/SKILL.md) · [content-gap-analysis](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/research/content-gap-analysis/SKILL.md)

**Build** · [seo-content-writer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/build/seo-content-writer/SKILL.md) · [geo-content-optimizer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/build/geo-content-optimizer/SKILL.md) · [meta-tags-optimizer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/build/meta-tags-optimizer/SKILL.md) · [schema-markup-generator](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/build/schema-markup-generator/SKILL.md)

**Optimize** · [on-page-seo-auditor](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/optimize/on-page-seo-auditor/SKILL.md) · [technical-seo-checker](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/optimize/technical-seo-checker/SKILL.md) · [internal-linking-optimizer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/optimize/internal-linking-optimizer/SKILL.md) · [content-refresher](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/optimize/content-refresher/SKILL.md)

**Monitor** · [rank-tracker](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/rank-tracker/SKILL.md) · [backlink-analyzer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/backlink-analyzer/SKILL.md) · **performance-reporter** · [alert-manager](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/alert-manager/SKILL.md)

**Cross-cutting** · [content-quality-auditor](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/content-quality-auditor/SKILL.md) · [domain-authority-auditor](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/domain-authority-auditor/SKILL.md) · [entity-optimizer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/entity-optimizer/SKILL.md) · [memory-management](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/memory-management/SKILL.md)

</details>

This skill creates comprehensive SEO and GEO performance reports that combine multiple metrics into actionable insights. It produces executive summaries, detailed analyses, and visual data presentations for stakeholder communication.

## When to Use This Skill

- Monthly/quarterly SEO reporting
- Executive stakeholder updates
- Client reporting for agencies
- Tracking campaign performance
- Combining multiple SEO metrics
- Creating GEO visibility reports
- Documenting ROI from SEO efforts

## What This Skill Does

1. **Data Aggregation**: Combines multiple SEO data sources
2. **Trend Analysis**: Identifies patterns across metrics
3. **Executive Summaries**: Creates high-level overviews
4. **Visual Reports**: Presents data in clear formats
5. **Benchmark Comparison**: Tracks against goals and competitors
6. **Content Quality Tracking**: Integrates CORE-EEAT scores across audited pages
7. **ROI Calculation**: Measures SEO investment returns
8. **Recommendations**: Suggests actions based on data

## How to Use

### Generate Performance Report

```
Create an SEO performance report for [domain] for [time period]
```

### Executive Summary

```
Generate an executive summary of SEO performance for [month/quarter]
```

### Specific Report Types

```
Create a GEO visibility report for [domain]
```

```
Generate a content performance report
```

## Data Sources

> **Note:** All integrations are optional. This skill works without any API keys — users provide data manually when no tools are connected.

> See [CONNECTORS.md](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/CONNECTORS.md) for tool category placeholders.

**With ~~analytics + ~~search console + ~~SEO tool + ~~AI monitor connected:**
Automatically aggregate traffic metrics from ~~analytics, search performance data from ~~search console, ranking and backlink data from ~~SEO tool, and GEO visibility metrics from ~~AI monitor. Creates comprehensive multi-source reports with historical trends.

**With manual data only:**
Ask the user to provide:
1. Analytics screenshots or traffic data export (sessions, users, conversions)
2. Search Console data (impressions, clicks, average position)
3. Keyword ranking data for the reporting period
4. Backlink metrics (referring domains, new/lost links)
5. Key performance indicators and goals for comparison
6. AI citation data if tracking GEO metrics

Proceed with the full analysis using provided data. Note in the output which metrics are from automated collection vs. user-provided data.

## Instructions

When a user requests a performance report:

1. **Define Report Parameters** -- Domain, report period, comparison period, report type (Monthly/Quarterly/Annual), audience (Executive/Technical/Client), focus areas.

2. **Create Executive Summary** -- Overall performance rating, key wins/watch areas/action required, metrics at a glance table (traffic, rankings, conversions, DA, AI citations), SEO ROI calculation.

3. **Report Organic Traffic Performance** -- Traffic overview (sessions, users, pageviews, bounce rate), traffic trend visualization, traffic by source/device, top performing pages.

4. **Report Keyword Rankings** -- Rankings overview by position range, distribution change visualization, top improvements and declines, SERP feature performance.

5. **Report GEO/AI Performance** -- AI citation overview, citations by topic, GEO wins, optimization opportunities.

6. **Report Domain Authority (CITE Score)** -- If a CITE audit has been run, include CITE dimension scores (C/I/T/E) with period-over-period trends and veto status. If no audit exists, note as "Not yet evaluated."

7. **Content Quality (CORE-EEAT Score)** -- If content-quality-auditor has been run, include average scores across all 8 CORE-EEAT dimensions with trends. If no audit exists, note as "Not yet evaluated."

8. **Report Backlink Performance** -- Link profile summary, weekly link acquisition, notable new links, competitive position.

9. **Report Content Performance** -- Publishing summary, top performing content, content needing attention, content ROI.

10. **Generate Recommendations** -- Immediate/short-term/long-term actions with priority, expected impact, and owner. Goals for next period.

11. **Compile Full Report** -- Combine all sections with table of contents, appendix (data sources, methodology, glossary).

   > **Reference**: See [references/report-output-templates.md](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/performance-reporter/references/report-output-templates.md) for complete output templates for all 11 report sections.

## Validation Checkpoints

### Input Validation
- [ ] Reporting period clearly defined with comparison period
- [ ] All required data sources available or alternatives noted
- [ ] Target audience identified (executive/technical/client)
- [ ] Performance goals and KPIs established for benchmarking

### Output Validation
- [ ] Every metric cites its data source and collection date
- [ ] Trends include period-over-period comparisons
- [ ] Recommendations are specific, prioritized, and actionable
- [ ] Source of each data point clearly stated (~~analytics data, ~~search console data, ~~SEO tool data, user-provided, or estimated)

## Example

**User**: "Create a monthly SEO report for cloudhosting.com for January 2025"

**Output** (abbreviated -- full report uses templates from all 11 steps):

```markdown
# CloudHosting SEO & GEO Performance Report — January 2025

## Executive Summary — Overall Performance: Good

| Metric | Jan 2025 | Dec 2024 | Change | Target | Status |
|--------|----------|----------|--------|--------|--------|
| Organic Traffic | 52,100 | 45,200 | +15.3% | 50,000 | On track |
| Keywords Top 10 | 87 | 79 | +8 | 90 | Watch |
| Organic Conversions | 684 | 612 | +11.8% | 700 | Watch |
| Domain Rating | 54 | 53 | +1 | 55 | Watch |
| AI Citations | 18 | 12 | +50.0% | 20 | Watch |

**SEO ROI**: $8,200 invested / $41,040 organic revenue = 400%

**Immediate**: Fix 37 crawl errors on /pricing/ pages
**This Month**: Optimize mobile LCP; publish 3 AI Overview comparison pages
**This Quarter**: Build Wikidata entry for CloudHost Inc.
```

## Tips for Success

1. **Lead with insights** - Start with what matters, not raw data
2. **Visualize data** - Charts and graphs improve comprehension
3. **Compare periods** - Context makes data meaningful
4. **Include actions** - Every report should drive decisions
5. **Customize for audience** - Executives need different info than technical teams
6. **Track GEO metrics** - AI visibility is increasingly important

## Reference Materials

- [Report Output Templates](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/performance-reporter/references/report-output-templates.md) — Complete output templates for all 11 report sections
- [KPI Definitions](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/performance-reporter/references/kpi-definitions.md) — SEO/GEO metric definitions with benchmarks, good ranges, warning thresholds, trend analysis, and attribution guidance
- [Report Templates by Audience](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/performance-reporter/references/report-templates.md) — Copy-ready templates for executive, marketing, technical, and client audiences

## Related Skills

- [content-quality-auditor](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/content-quality-auditor/SKILL.md) — Include CORE-EEAT scores as page-level content quality KPIs
- [domain-authority-auditor](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/domain-authority-auditor/SKILL.md) — Include CITE score as a domain-level KPI in periodic reports
- [rank-tracker](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/rank-tracker/SKILL.md) — Detailed ranking data
- [backlink-analyzer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/backlink-analyzer/SKILL.md) — Link profile data
- [alert-manager](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/monitor/alert-manager/SKILL.md) — Set up report triggers
- [serp-analysis](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/research/serp-analysis/SKILL.md) — SERP composition data
- [memory-management](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/memory-management/SKILL.md) — Archive reports in project memory
- [entity-optimizer](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/cross-cutting/entity-optimizer/SKILL.md) — Track branded search and Knowledge Panel metrics
- [technical-seo-checker](https://github.com/aaron-he-zhu/seo-geo-claude-skills/blob/main/optimize/technical-seo-checker/SKILL.md) — Technical health data feeds into reports

