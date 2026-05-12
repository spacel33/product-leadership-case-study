# Platform Discovery and Root Cause Analysis

## Context
The platform handled millions of messages per day across financial services, logistics, and healthcare customers. Over a 6‑month period, we saw:

- Rising delivery failures  
- Increased latency during peak hours  
- Escalations from enterprise customers  
- SLA credits impacting revenue  

## Problem Signals
- 17% increase in P95 latency  
- 9% increase in delivery failures  
- 3 major incidents in a quarter  
- Customer churn risk flagged by CS  

## What I Did
- Conducted 12 customer interviews  
- Partnered with SRE to analyze incident patterns  
- Mapped the full delivery pipeline (API → queue → worker → carrier)  
- Identified bottlenecks in queue depth and worker concurrency  
- Ran a competitive benchmark on delivery SLAs  

## Key Insight
The problem wasn’t a single failure point — it was **systemic load amplification** during peak traffic, combined with **non‑deterministic retry behavior**.

This shaped the strategy.
