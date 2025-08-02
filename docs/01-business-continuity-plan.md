# Business Continuity Plan (BCP)

## Organization: SecureTech  
## Date: January 2025  
## Focus Area: Cloud Services Hosting Payment and User Data  

---

## 1. Business Impact Analysis

- **Critical Systems**: Cloud server infrastructure, database, authentication, and payment gateway
- **Recovery Time Objective (RTO)**: 6 hours
- **Recovery Point Objective (RPO)**: 30 minutes

---

## 2. Risk Scenarios

| Scenario | Impact | Likelihood | RTO Breach Risk |
|---------|--------|------------|----------------|
| Cloud outage (Azure) | High | Medium | High |
| Cyberattack (Ransomware) | Very High | Medium | Very High |
| Insider misuse | Medium | Low | Medium |

---

## 3. Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| BCP Coordinator | Trigger plan, notify stakeholders |
| IT Recovery Team | Restore systems |
| Comms Lead | Internal and external updates |

---

## 4. Contingency Measures

- **Backups**: Hourly encrypted snapshots on separate cloud
- **Alternate Workspace**: Remote failover environment via VPN
- **Customer Comms**: Pre-approved downtime messaging via email and status page

---

## 5. Test & Review

- Tabletop simulation every 6 months
- Update plan annually or after major incidents
