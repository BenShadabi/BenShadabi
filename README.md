# Hi, I'm Ben Shadabi

**Finance and analytics student in Toronto.** I'm in the Honours BBA, Business Analytics program at George Brown College. Before school I co-founded and ran a dine-in and take-out restaurant for three years: I ran the P&L, built forecasts and a staff scheduling model, and led the sale of the business. So I like questions where numbers meet real operations, and I check my work with public data, SQL, Excel and Python. I build with Claude Code and say so in every project: Claude drafts, and I decide the question, edit, test and explain it.

[LinkedIn](https://www.linkedin.com/in/benshadabi) · [All repositories](https://github.com/BenShadabi?tab=repositories)

---

## Featured: finance and operations analysis

### Canadian Restaurant Profitability Benchmark
**Question:** where does a typical Canadian restaurant make and lose money, and how much would tighter labour, overhead and waste control change its profit?

[![Dashboard](https://raw.githubusercontent.com/BenShadabi/canadian-restaurant-profitability-benchmark/main/assets/dashboard_page.png)](https://benshadabi.github.io/canadian-restaurant-profitability-benchmark/dashboard.html)
- **Finding:** The average restaurant kept a 2.5% net margin in 2024 ($21,500 on $849,200). 42.3% lost money.
- **Scenario:** Labour -10%, overhead -15%, waste -20% (waste share assumed at 5%) takes profit from $21,500 to $68,169, a margin of 2.5% to 8.0%. A scenario, not a forecast. A conservative case on published cost lines only gives $48,549 (5.7%).
- **Method:** Statistics Canada and ISED data, SQL queries, Python charts, an Excel model, and a script that re-checks every headline number on each push.
- **Open:** [Dashboard](https://benshadabi.github.io/canadian-restaurant-profitability-benchmark/dashboard.html) · [Compare your restaurant](https://benshadabi.github.io/canadian-restaurant-profitability-benchmark/calculator.html) · [Stress test](https://benshadabi.github.io/canadian-restaurant-profitability-benchmark/stress.html)
- **Files:** [Excel workbook](https://github.com/BenShadabi/canadian-restaurant-profitability-benchmark/blob/main/data/Canadian_Restaurant_Benchmark.xlsx) · [SQL queries](https://github.com/BenShadabi/canadian-restaurant-profitability-benchmark/blob/main/sql/queries.sql) · [Methodology](https://github.com/BenShadabi/canadian-restaurant-profitability-benchmark/blob/main/docs/methodology.md) · [Repo](https://github.com/BenShadabi/canadian-restaurant-profitability-benchmark)

---

## Featured: metrics and experiment design

### Rockstar Games GTA VI search analytics (team of four, class project)
**Question:** what should a launch website measure, and would a pre-order banner help?

[![Metrics deck](https://raw.githubusercontent.com/BenShadabi/rockstar-gta-vi-search-analytics/main/docs/img/deck.gif)](https://github.com/BenShadabi/rockstar-gta-vi-search-analytics)

- **Metrics:** Four website objectives, a critical and a supporting metric each, formulas, and eight recommended actions.
- **A/B test:** A two-proportion z-test in Excel on 20,000 **simulated** users: 4.00% vs 5.20% click rate, z = 4.05. It shows the method, not a real result.
- **Files:** [Metrics deck (PDF)](https://github.com/BenShadabi/rockstar-gta-vi-search-analytics/blob/main/docs/slides/Rockstar_Multiple_Outcome_Analysis.pdf) · [A/B deck (PDF)](https://github.com/BenShadabi/rockstar-gta-vi-search-analytics/blob/main/docs/slides/GTA_VI_Banner_AB_Test.pdf) · [A/B Excel workbook](https://github.com/BenShadabi/rockstar-gta-vi-search-analytics/blob/main/ab-test/GTA6_AB_Test.xlsx) · [Repo](https://github.com/BenShadabi/rockstar-gta-vi-search-analytics)

Independent class project, not affiliated with Rockstar Games or Take-Two. Public information only.

---

## Featured: analytics tools I built for real use

### Co-op Job Tracker
A one-page tracker for a student job search: newest postings first, scoring, applications, follow-ups, employer events and a funnel view. I use it every day.

[![Tracker](https://raw.githubusercontent.com/BenShadabi/coop-job-tracker/main/docs/img/hot.png)](https://github.com/BenShadabi/coop-job-tracker)

**Try it:** clone it and open `index.html` (it starts with made-up postings). [Repo and demo GIF](https://github.com/BenShadabi/coop-job-tracker) · [How it works](https://github.com/BenShadabi/coop-job-tracker/blob/main/docs/how-it-works.md)

### Resume Builder skill for Claude
Builds an honest, one-page, ATS-friendly resume (plus cover letter and prep sheet) from about 10 questions, using only the answers and files you give it. It pairs with the tracker: the tracker shows what to apply to, the skill builds each package.

[![Resume builder](https://raw.githubusercontent.com/BenShadabi/resume-builder-skill/main/docs/img/walkthrough.png)](https://github.com/BenShadabi/resume-builder-skill)

[Repo](https://github.com/BenShadabi/resume-builder-skill) · [Sample resume (PDF)](https://github.com/BenShadabi/resume-builder-skill/blob/main/examples/sample-resume.pdf)

### Study Maps
A study app for my Semester 5 courses: spaced review that flags "sure but wrong" answers, exam mode, readiness tracking and a plan tab. Plain HTML, CSS and JavaScript, tested at phone and iPad sizes with Playwright.

[![Study Maps](https://raw.githubusercontent.com/BenShadabi/study-map-showcase/main/docs/img/current_plan.png)](https://github.com/BenShadabi/study-map-showcase)

[Repo](https://github.com/BenShadabi/study-map-showcase) · [What we built](https://github.com/BenShadabi/study-map-showcase/blob/main/docs/01-what-we-built.md)

---

## Tools
Excel (pivot tables, XLOOKUP) · SQL (SQLite) · Python (pandas, matplotlib) · Tableau · Power BI (learning) · HTML and CSS · GitHub Actions · Claude Code and Codex

## How I use AI
Claude Code drafts code, queries and pages. I decide the question and the assumptions, edit the drafts, test every formula and number, and can walk through each one. Each project's README says where AI was used.
