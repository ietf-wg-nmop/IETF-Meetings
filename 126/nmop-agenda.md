# Network Management Operations (nmop) WG Agenda - IETF 126

* Co-Chairs: Benoît Claise & Reshad Rahman

## Current WG's Projects

* P1: NETCONF/YANG Push integration with message brokers & time series databases
* P2: Anomaly detection and incident management
* P3: Issues related to deployment/usage of YANG topology modules
* P4: Consider/plan an approach for updating [RFC 3535](https://datatracker.ietf.org/doc/rfc3535)
* P5: Knowledge Graphs

## Compact Agenda: Session 1

| Slot        | Project | Topic                                              | Presenters       |
| ----------- | ------- | -------------------------------------------------- | ---------------- |
| 09:00-09:10 |         | Agenda Bashing & Introduction                      | Chairs           |
| 09:10-09:25 | P1      | YANG-Push to Message Broker Integration            | Thomas Graf      |
| 09:25-09:35 | P1      | YANG Message Keys for Message Broker Integration   | Ahmed Elhassany  |
| 09:35-09:45 | P2      | YANG data model for Network Incident Management    | Qin Wu           |
| 09:45-09:55 | P2      | Network Anomaly Detection                          | Thomas Graf      |
| 09:55-10:05 | P3      | SIMAP YANG (based on RFC8345)                      | Olga Havel       |
| 10:05-10:15 | P3      | SIMAP YANG (based on RFC8795)                      | Italo Busi       |
| 10:15-10:30 | P3      | SIMAP YANG discussions                             | Chairs/All       |
| 10:30-10:40 |         | NMRG and NMOP                                      | Jeferson Nobre   |
| 10:40-10:50 | P3      | BMP YANG Model for Network Telemetry Messages      | Leonardo Rodoni  |
| 10:50-11:00 |         | Model for distributed authorization policy sharing | Lucia Cabanillas |

## Compact Agenda: Session 2

| Slot        | Project | Topic                                                                  | Presenters          |
| ----------- | ------- | ---------------------------------------------------------------------- | ------------------- |
| 11:30-11:35 |         | Agenda Bashing & Introduction                                          | Chairs              |
| 11:35-11:50 | P2      | Swisscom BGP Routing Loop Network Incident                             | Thomas Graf         |
| 11:50-11:55 |         | AIOPS Side Meeting Logistics and Guidance on AI drafts                 | Mahesh Jethanandani |
| 11:55-12:00 |         | AI based Network Management Agent (NMA)                                | Xing Zhao           |
| 12:00-12:05 |         | Standardizing the northbound Task Interface (NTI) of the NMA           | Bo Wu               |
| 12:05-12:10 |         | Framework and YANG Data Model for the NMA A2U Interface                | Xing Zhao           |
| 12:10-12:15 |         | Framework for AI-Assisted Network Protocol Testing from Specifications | Yunze Wei           |
| 12:15-12:20 | P5      | A Gateway for Network Knowledge Graph Management                       | Mingzhe Xing        |
| 12:20-12:25 |         | Requirements for Network State Exchange in Agent-Assisted Netops       | Mingzhe Xing        |
| 12:25-12:30 |         | Applying the wiki guidance on AI drafts                                | Mahesh Jethanandani |

## Detailed Agenda: Session 1

### 1. Agenda Bashing & Introduction (Chairs) (10 min)

### 2. YANG-Push to Message Broker Integration (15 mins)

* Presenter: Thomas Graf
* Reading Material:
  [draft-ietf-nmop-yang-message-broker-integration](https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration) and
  [draft-ietf-message-broker-telemetry-message](https://datatracker.ietf.org/doc/draft-ietf-nmop-message-broker-telemetry-message)

### 3. YANG Message Keys for Message Broker Integration (10 mins)

* Presenter: Ahmed Elhassany
* Reading Material: [draft-netana-nmop-yang-message-broker-message-key](https://datatracker.ietf.org/doc/draft-netana-nmop-yang-message-broker-message-key/)

### 4. YANG data model for Network Incident Management (10 mins)

* Presenter: Qin Wu
* Reading Material:
  [draft-ietf-nmop-network-incident-yang](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang)

### 5. Network Anomaly Detection (10 mins)

* Presenter: Thomas Graf
* Reading Material:
  [draft-ietf-nmop-network-anomaly-architecture](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-architecture),
  [draft-ietf-nmop-network-anomaly-lifecycle](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-lifecycle) and
  [draft-ietf-nmop-network-anomaly-semantics](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-semantics)

### 6. SIMAP YANG based on RFC8345 (10 mins)

* Presenter: Olga Havel
* Reading Material: [draft-ietf-nmop-simap-concept](https://datatracker.ietf.org/doc/draft-ietf-nmop-simap-concept/)
  [draft-havel-nmop-simap-yang](https://datatracker.ietf.org/doc/draft-havel-nmop-simap-yang/)

### 7. SIMAP YANG based on RFC8795 (10 mins)

* Presenter: Italo Busi
* Reading Material:
  [draft-busi-nmop-simap-rfc8795-applicability](https://datatracker.ietf.org/doc/draft-busi-nmop-simap-rfc8795-applicability)

### 8. SIMAP YANG discussions (15 mins)

* Presenter: Chairs

### 9. NMRG and NMOP (10 mins)

* Presenter: Jéferson Nobre

### 10. BMP YANG Model for Network Telemetry Messages (10 mins)

* Presenter: Leonardo Rodoni
* Reading Material: [draft-netana-nmop-message-broker-bmp-telemetry-msg](https://datatracker.ietf.org/doc/draft-netana-nmop-message-broker-bmp-telemetry-msg/)

### 11. Model for distributed authorization policy sharing (10 mins)

* Presenter: Lucia Cabanillas Rodriguez
* Reading Material:
  [draft-cabanillas-nmop-authz-policy-sharing-model](https://datatracker.ietf.org/doc/draft-cabanillas-nmop-authz-policy-sharing-model)

## Detailed Agenda: Session 2

### 1. Agenda Bashing & Introduction (Chairs) (5 min)

### 2. Swisscom BGP Routing Loop Network Incident (15 mins)

* Presenter: Thomas Graf
* Reading Material: [Swisscom BGP Routing Loop Network Incident](TBD)

### 3. AIOPS Side Meeting Logistics and Guidance on AI drafts (5 mins)

* Presenter: Mahesh Jethanandani
* Reading Material:
  [AI-Driven Network Operations: Evaluation Guidelines](https://wiki.ietf.org/en/group/ops/aiops)

### 4. AI based Network Management Agent (5 mins)

* Presenter: Xing Zhao
* Reading Material:
  [draft-zhao-nmop-network-management-agent](https://datatracker.ietf.org/doc/draft-zhao-nmop-network-management-agent)

### 5. Standardizing the northbound Task Interface (NTI) of the NMA  (5 mins)

* Presenter: Bo Wu
* Reading Material:
  [draft-wu-nmop-nma-nti-problem-statement](https://datatracker.ietf.org/doc/draft-wu-nmop-nma-nti-problem-statement/)

### 6. Framework and YANG Data Model for the NMA A2U Interface (5 mins)

* Presenter: Xing Zhao
* Reading Material:
  [draft-zhao-nmop-nma-a2u-yang](https://datatracker.ietf.org/doc/draft-zhao-nmop-nma-a2u-yang/)

### 7. A Framework for AI-Assisted Network Protocol Testing from Specifications (5 mins)

* Presenter: Yunze Wei
* Reading Material:
  [draft-cui-nmop-auto-test](https://datatracker.ietf.org/doc/draft-cui-nmop-auto-test/)

### 8. A Gateway for Network Knowledge Graph Management (5 mins)

* Presenter: Mingzhe Xing
* Reading Material:
  [draft-nmop-cui-nkg-gateway](https://datatracker.ietf.org/doc/draft-nmop-cui-nkg-gateway/)

### 9. Operational Requirements for Network State Exchange in Agent-Assisted Network Operations (5 mins)

* Presenter: Mingzhe Xing
* Reading Material:
  [draft-cui-nmop-agent-sketch-com](https://datatracker.ietf.org/doc/draft-cui-nmop-agent-sketch-com/)

### 10. Applying the wiki guidance on AI drafts (5 mins)

* Presenter: Mahesh Jethanandani

