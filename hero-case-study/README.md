# Hero Case Study  
## Improving Message Delivery Reliability and Reducing End‑to‑End Latency for an Enterprise B2B Messaging Platform.

This case study demonstrates how I led a cross‑functional initiative to improve message delivery reliability and reduce end‑to‑end latency for a B2B messaging platform used by enterprise customers.

## System Overview (High-Level Architecture)

```mermaid
flowchart LR
    A[API Ingestion Layer] --> B[Queue]
    B --> C[Worker Pools]
    C --> D[Carrier Routing]
    D --> E[Delivery Confirmation]
    C --> F[Retry Logic]
    B --> G[Monitoring & Alerts]

It includes:
- Discovery  
- Strategy  
- Roadmap  
- PRD  
- Execution  
- Outcomes  
- What I’d do differently  

### 📄 Files
- [`discovery.md`](discovery.md)
- [`strategy.md`](strategy.md)
- [`roadmap.md`](roadmap.md)
- [`prd.md`](prd.md)
- [`execution.md`](execution.md)
- [`outcomes.md`](outcomes.md)
