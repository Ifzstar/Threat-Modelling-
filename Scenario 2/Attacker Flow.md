```mermaid
flowchart TD
    style A1 fill:#F1948A,stroke:#000,stroke-width:2px
    style B1 fill:#E59866,stroke:#000,stroke-width:2px
    style C1 fill:#F4D03F,stroke:#000,stroke-width:2px
    style D1 fill:#F5B041,stroke:#000,stroke-width:2px
    style E1 fill:#EB984E,stroke:#000,stroke-width:2px
    style F1 fill:#BA4A00,stroke:#000,stroke-width:2px
    style F2 fill:#CA6F1E,stroke:#000,stroke-width:2px
    style G1 fill:#82E0AA,stroke:#000,stroke-width:2px

    A1[Attacker] -->|Utilizes AI to optimize DDoS botnet| B1[AI-Powered DDoS Botnet]
    B1 -->|Distributes malicious traffic requests| C1[ShopNow Infrastructure]
    C1 -->|Identifies network weaknesses| D1[Weakness: Insufficient Traffic Filtering]
    D1 -->|overwhelms servers with DDoS traffic| E1[Server Resources Exhausted]
    E1 -->|Service downtime impacts user experience| F1[Operational Disruption]
    E1 -->|Customer access interrupted| F2[Revenue Loss & Customer Frustration]
    C1 -->| ShopNow deploys traffic filters| G1[Mitigation: AI Traffic Analysis Systems]
    G1 -->|Filters bypassed by adaptive AI botnet| D1
    D1 -->|Attacker escalates DDoS traffic| A1