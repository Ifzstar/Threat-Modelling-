# AI Threat Modelling Workshop Summary
## Introduction
A 3-hour threat modeling workshop was conducted to evaluate multiple AI-based attack scenarios against the e-commerce platform, ShopNow, which handles high volumes of online transactions and sensitive customer data.

## Attendess
ShopNow Eng team, Product Managers, DevEx Engineers and the DevSecOps Team.
## Scope
4 Scenarios were run covering: (1) AI Generated External phishing email utilising admin credentials, (2) AI-Powered Fake Reviews, (3) AI-Based Distributed Denial of Service (DDoS) Attack and (4) Automated AI Credential Harvesting.
## Methodology
All scenarios were run against the cyber attack killchain, utilising the Mitre Att&ack methods and STRIDE for control gap assessments. Culminating in identified risks.
## Conclusion
A total of 4 high risks and 3 medium risks were found during the threat modelling workshop.
## Controls Required
- Regular security audits specifically targeting the ShopNow application to detect vulnerabilities and weaknesses in its security measures.
- Patch management to ensure the ShopNow and its underlying technologies are up-to-date and protected against known vulnerabilities.
- Comprehensive employee training on phishing awareness to educate users of the ShopNow platform about the risks of phishing attacks and how to identify and report suspicious emails.
- Implementation of a Web Application Firewall (WAF) tailored to the ShopNow's application traffic to monitor and filter incoming requests for malicious activity.
- Deployment of Multi-factor Authentication (MFA) to enhance authentication security and prevent unauthorized access to the ShopNow application.
- Continuous network traffic monitoring to detect and respond to suspicious activity within the ShopNow application's infrastructure.
- Implementation of Role-based Access Control (RBAC) within the ShopNow's application to limit access to sensitive health data and functionalities based on user roles and permissions.
# Threat Modelling Process Summary
```mermaid
mindmap
  root((attack))
    STRIDE/MITRE/Kill Chain
      Inherent Risk Assesment
      ::icon(fa fa-book)
      Critical Asset List
        Schedule and Scope Workshop
    Controls Required
      Risks<br/>Mitigations
      Risk Summary
        Redmeiation workflow
            Slack
            JIRA
    Scenarios
      Attack 1
      Attack 2
      Attack 3
      Attack 4