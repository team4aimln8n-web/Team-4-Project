# 📊 Cost Analysis

## Objective of Cost Analysis
The purpose of this cost analysis is to estimate the monthly operational cost of the e-commerce automation system built using Supabase, n8n, and AI agents. 
The analysis focuses on transparency, scalability, and buyer-specific usage patterns rather than fixed assumptions.

## Cost Components Considered
The total monthly cost is divided into the following major components:
- Backend Platform (Supabase)

  - Database storage
  - File storage
  - API requests
  - Authentication usage
  - Edge Functions
  - Realtime connections

- Automation Platform (n8n)

  - Workflow executions
  - Peak concurrency
  - Cloud hosting plan

- AI / LLM Usage

  - AI agent executions
  - Token-based processing cost
  - Monthly execution frequency

- Frontend Hosting

  - Treated as a variable cost
  - Not included in final total due to provider dependency

## Static Baseline Cost Estimation

For documentation and evaluation purposes, a **baseline usage scenario** is defined to represent a typical small-to-medium e-commerce store. This baseline is based on the following average usage assumptions:

- Moderate number of monthly active users  
- Standard product catalog size  
- Regular order placement and cart activity  
- Daily AI agent executions for automation and cost estimation  

This baseline provides a **reference point** for understanding the minimum operational cost under normal usage conditions. It is intended for high-level evaluation and does not replace the dynamic cost estimation tool included in this project.

### Static Baseline Monthly Cost (Reference)

The table below shows an approximate monthly cost for operating the system under the baseline assumptions described above.

| Component | Plan Assumed | Estimated Monthly Cost (USD) |
|---------|-------------|-------------------------------|
| Supabase | Pro | $25.00 |
| n8n | Starter | $20 – $30 |
| AI / LLM Usage | Moderate (daily agent executions) | $800 – $1,200 |
| **Total (Estimated)** | — | **$845 – $1,255** |

> ⚠️ **Note:** This table is indicative only. Actual costs may vary depending on usage patterns, execution frequency, and scaling requirements.
