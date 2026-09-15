# Revenue Intelligence Dashboard for NovaTech Solutions

Project for the AWS AI and ML Scholars program, Future AWS Agentic AI Business Professional, Business Intelligence and Knowledge Management Foundations with Amazon QuickSight.

## Overview

NovaTech Solutions is a B2B SaaS company whose revenue data lived in three separate systems: CRM deals, marketing campaigns, and support tickets. This project unifies those sources into a single interactive dashboard in Amazon QuickSight and adds AI-powered querying through Quick Chat, so the revenue team can ask business questions without waiting for a new report.

## What is in this repo

### Verification and Exploration Logs
- `Step_1_-_7a_Verification_log_RASR.md`, verification of the pre-indexed knowledge bases against the data dictionary, 6 entries
- `Step_4_-_16_Q_Exploration_Log_RASR.md`, Quick Chat exploration log, 5 entries, with dashboard cross-checks and a written reflection

### Written Deliverables
- `NovaTech_ExecutiveReport_RASR.pdf`, written report for VP Sarah Chen, covering data strategy, dashboard design, Topic configuration effects, key insights, and AI vs. dashboard comparison
- `NovaTech_ExecutiveSummaryText_RASR.pdf`, the auto-generated executive summary text from the published dashboard, for all three sheets

### Screenshots
- `NovaTech_Screenshots_DataTransformation_RASR.docx`, join diagram, join configuration, calculated fields, and data type corrections
- `NovaTech_Screenshots_DashboardInteractivity_RASR.docx`, all three dashboard sheets, filter in action, one-click filtering, and the cross-sheet navigation action
- `NovaTech_Screenshots_TopicAndQA_RASR.docx`, baseline Quick Chat questions before the Topic was configured, the Topic setup, and the same questions re-asked after configuration
- `NovaTech_Screenshots_AnnotatedDashboard_RASR.docx`, the five text annotations visible on the dashboard sheets

### Dashboard Export
- Dashboard PDF export, all three sheets, Marketing Funnel, Sales Pipeline, Customer Health

## Dashboard Structure

- **Marketing Funnel**, campaign performance by channel, lead-to-deal conversion, response rates
- **Sales Pipeline**, deal stages, win rates, revenue by segment and product, days to close trend
- **Customer Health**, at-risk accounts built from the unified dataset, support ticket volume, resolution time by priority, customer sentiment

## Data Strategy

The unified dataset joins CRM deals, the anchor table, marketing campaigns, and support tickets on a shared account ID, using left joins to preserve every deal even when an account has no matching marketing or support record. The executive report documents the full reasoning.

## Author

Rhyah Austrie S. Reyes
