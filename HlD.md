```mermaid
flowchart TD
    subgraph "User Interface"
        UI[User Interface]
    end
    subgraph "Frontend (EC2)"
        FE[Frontend Server]
    end
    subgraph "Backend"
        BE[Backend Server]
    end
    subgraph "Database"
        DB[Database Server]
    end
    subgraph "External Services"
        CnC[Command and Control Server]
    end
    UI --> FE
    FE --> BE
    BE --> DB
    BE --> CnC

React

Reply

8:54
| Category                | Description                                             | Likelihood | Impact | Risk Rating | Scenario                                               |
|------------------------------|--------------------------------------------------------------|------------|--------|-------------|---------------------------------------------------------------------|
| Data                     | PII and SPI           | Medium     | High   | High        | Data Revealed                |
| Amount of Data                     | 10,000                               | High       | High   | High        | ICO FIne                     |