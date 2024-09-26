```mermaid
  sequenceDiagram
    participant Attacker
    participant ShopNow
    participant CnCServer
    participant BackendServer
    participant User
    activate Attacker
    Attacker->>ShopNow: Identify ShopNow app
    ShowNow->>Attacker: Application identified
    deactivate Attacker
    activate Attacker
    Attacker->>ShopNow Platform: Craft exploit for known vulnerabilities
    ShopNow->>Attacker: Exploit crafted
    deactivate Attacker
    activate Attacker
    Attacker->>ShopNow Platform: Deploy phishing campaign targeting app users
    ShopNow->>User: Phishing email sent
    activate User
    User->>ShopNow: Clicks on malicious link/download attachment
    ShopNow->>User: Malware downloaded
    deactivate User
    deactivate Attacker
    activate Attacker
    Attacker->>ShopNow: Trick users into downloading malware
    ShopNow->>BackendServer: Malicious payload executed
    BackendServer->>CnCServer: Communication established
    CnCServer->>BackendServer: Commands issued
    BackendServer->>CnCServer: Actions performed
    deactivate Attacker









