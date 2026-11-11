
# E-Commerce & Retail Business Continuity Plan

## Project Overview

This project was completed as part of a group assignment focused on information security and business continuity in the e-commerce and retail industry.

Our goal was to research the major cybersecurity and operational risks that e-commerce businesses face and develop a Business Continuity Plan (BCP) to help organizations prepare for and recover from unexpected disruptions.

The project focused on three main areas:

- **Risk Assessment:** Identifying potential cybersecurity threats, cloud outages, and third-party service failures.
- **Business Impact Analysis (BIA):** Evaluating how system downtime and security incidents affect business operations, revenue, and customer trust.
- **Business Continuity Planning (BCP):** Developing strategies for incident response, communication, backup and disaster recovery, and maintaining critical business operations.

## My Contributions

My responsibilities focused on researching and developing two sections of the Business Continuity Plan: **Backup and Disaster Recovery** and **Redundancy and Failover Strategies**.

### 1. Backup and Disaster Recovery (BDR)

I researched how e-commerce businesses can protect critical systems and recover from cyberattacks, infrastructure failures, and natural disasters.

My work included:

- Developing a proposed backup strategy using incremental backups every 4 hours and full backups every 24 hours.
- Researching encrypted cloud storage across multiple regions and offline backups.
- Establishing Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO) for critical business systems.
- Comparing hot sites, cold sites, and Infrastructure as Code (IaC) for disaster recovery.
- Recommending quarterly backup restoration testing to verify recovery procedures.
- Developing a recovery scenario involving automatic failover to a secondary cloud environment during a regional outage.

### 2. Redundancy and Failover Strategies

I researched how businesses can maintain system availability when critical infrastructure or cloud services experience failures.

My work included:

- Researching multi-region cloud infrastructure to reduce the risk of a single point of failure.
- Examining how load balancers distribute network traffic to maintain availability.
- Exploring automatic failover systems that redirect traffic when primary systems become unavailable.
- Researching redundant servers, network connections, routers, and power systems.
- Comparing Infrastructure as a Service (IaaS), Disaster Recovery as a Service (DRaaS), and Backup as a Service (BaaS).
- Examining how cloud backups and data replication support faster recovery and reduce data loss.
- Outlining team responsibilities, plan maintenance, and regular disaster recovery testing.

## Proposed Backup and Recovery Strategy

As part of my research, I developed the following proposed recovery objectives and procedures for an e-commerce organization.

| Component | Proposed Strategy |
|-----------|-------------------|
| Incremental Backups | Every 4 hours |
| Full Backups | Every 24 hours |
| Backup Storage | Encrypted multi-region cloud storage with an offline copy |
| Backup Recovery Testing | Quarterly |
| Website RTO | 2 hours |
| Website RPO | 15 minutes |
| Regional Cloud Outage | Automatic failover within 60 minutes |
| Disaster Recovery Methods | Hot sites, cold sites, and Infrastructure as Code |

*These strategies were developed as part of an academic research project and were not implemented or tested in a live production environment.*

## Key Concepts Covered

- Business Continuity Planning (BCP)
- Backup and Disaster Recovery (BDR)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Cloud Infrastructure and Redundancy
- High Availability
- Automatic Failover
- Load Balancing
- Data Replication
- Infrastructure as Code (IaC)
- Disaster Recovery Testing

## What I Learned

This project helped me better understand how businesses prepare for unexpected disruptions and why disaster recovery planning is an important part of information security.

One of my biggest takeaways was learning the difference between RTO and RPO and how these objectives help businesses determine acceptable downtime and data loss. I also gained a better understanding of cloud redundancy, automatic failover, and how backup systems help organizations recover from outages.

Overall, the project gave me a better understanding of how IT infrastructure, cybersecurity, and business continuity work together to keep critical systems operational.

## Project Documentation

The complete group project report is included in this repository. It contains our research on Risk Assessment, Business Impact Analysis, and Business Continuity Planning.

## Group Project Acknowledgment

This project was completed with Grant Chang, Trevor St. Don, Jake Warren, and Ethan Fischer. Each member contributed to the overall project, with my primary focus being Backup and Disaster Recovery and Redundancy and Failover Strategies.
