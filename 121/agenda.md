# Network Management Operations (nmop) WG Agenda - IETF 121

* When: Tue, Nov 05, 2024
* Co-Chairs: Benoît Claise & Mohamed Boucadair

## Current WG's priorities

* *P1*: NETCONF/YANG Push integration with message brokers & time series databases
* *P2*: Anomaly detection and incident management
* *P3*: Issues related to deployment/usage of YANG topology modules (e.g., to model a Digital Map)
* *P4*: Consider/plan an approach for updating RFC 3535 (collecting updated operator requirements for IETF network management solutions)

> For P4 items: We propose to submit those for the forthcoming NEMOPS Workshop. Will discuss in future whether we keep this item in the charter or remove it
> after the NEMOPS Workshop takes place.

## Compact Agenda

### Session 1

| Slot          | Priority Label |Topic                                    | Presenters            |
|:-------------:|:--------------:|:---------------------------------------:|:----------------------|
| 09:30 - 09:40 |                | Agenda Bashing & Introduction           | Chairs                |
| 09:40 - 10:10 |P3              | Digital Map: Concepts & Requirements    | Olga                  |
| 10:10 - 10:40 |P1              | YANG-Push to Message Broker Integration | Thomas                |
| 10:40 - 10:45 |P2              | Next Steps for the terminology draft    | Chairs                |
| 10:45 - 11:00 |P2              | Incident Management YANG Module         | Qin                   |
| 11:00 - 11:20 |P2              | Follow up to the Anomaly Interim        | Thomas/Vincenzo       |
| 11:20 - 11:30 |                | Flash Teasers                           | Robert/Rob/Xing/Diego |

### Session 2

| Slot          | Priority Label |Topic                                    | Presenters |
|:-------------:|:--------------:|:---------------------------------------:|:-----------|
| 18:00 - 18:05 |                | Introduction                            | Chairs     |
| 18:05 - 18:20 |P1              | Validate Configured Subscription YANG-Push Publisher Implementations | Yannick     |
| 18:20 - 18:40 |P3              | Digital Map Hackathons | Sherif/Olga/Italo     |
| 18:40 - 18:50 |P2              | Network Anomaly Lifecycle Hackathon | Vincenzo      |
| 18:50 - 18:55 |                | Knowlege Graph for Network Operations Hackathon | Mike     |
| 18:55 - 19:00 |                | Open Mic  | All     |


## Session 1: Detailed Agenda

### 1. Agenda Bashing & Introduction (Chairs) (10 min)

### 2. Digital Map: Concepts & Requirements (30 min)

 * Presenters: Olga Havel
 * Reading Material: [draft-ietf-nmop-digital-map-concept](https://datatracker.ietf.org/doc/draft-ietf-nmop-digital-map-concept/)
   
### 3. YANG-Push to Message Broker Integration (30 min)

#### 3.1 An Architecture for YANG-Push to Message Broker Integration (20 min)

 * Presenter: Thomas Graf
 * Reading Material: [draft-ietf-nmop-yang-message-broker-integration](https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration/)

#### 3.2. Operator/Implementer Contribution: YANG-Push Next Steps  (10 min)

 * Presenter: Thomas Graf
 * Reading Material: In over 4 workshop iterations we collected from IETF YANG-Push implementers and operators feedback on how IETF YANG-Push is being used, what they liked, what could be improved and what never will be used or implemented.

### 4. Anomaly Detection and Incident Management (40 min)

#### 4.1 Next Steps for the terminology draft (Chairs, 5 min)

#### 4.2 Incident Management YANG Module (15 min)

 * Presenter: Qin Wu
 * Reading Material: [draft-ietf-nmop-network-incident-yang](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang/)

#### 4.3. Follow up to the Anomaly Interim  (20 min)

 * Presenter: Thomas Graf/Vincenzo Riccobene
 * Reading Material:
   + [slides-interim-2024-nmop-03-sessa-chairs-questions](https://datatracker.ietf.org/meeting/interim-2024-nmop-03/materials/slides-interim-2024-nmop-03-sessa-chairs-questions-00)
   + [draft-ietf-nmop-network-anomaly-architecture](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-architecture/)
   + [draft-netana-opsawg-nmrg-network-anomaly-semantics](https://datatracker.ietf.org/doc/draft-netana-opsawg-nmrg-network-anomaly-semantics/)
   + [draft-netana-nmop-network-anomaly-lifecycle](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-lifecycle/)

### 5. Flash Prez: 1-slide Teasers (10 min)

#### 5.1. YANG Template Framework (Robert Peschi)
#### 5.2. AI based Network Management Agent (NMA): Concepts & Architecture (Xing Zhao)
#### 5.3. NETCONF YANG-Push Observability (Rob Wilton)
#### 5.4. ETSI TC DATA (Diego Lopez)


## Session 2: Detailed Agenda (Hackathon-focused)

### 1. Agenda Bashing & Introduction (Chairs) (5 min)

### 2. Validate Configured Subscription YANG-Push Publisher Implementations ( 15 min)

* Presenter: Yannick Buchs
* Reading Material: [draft-ietf-nmop-yang-message-broker-integration](https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration/)

### 3. Digital Map Hackathons (20 min)

 * Presenter: Olga/Sherif/Italo
  * Reading Material:
     + [draft-ietf-nmop-digital-map-concept](https://datatracker.ietf.org/doc/draft-ietf-nmop-digital-map-concept/) 
     + [draft-havel-nmop-digital-map](https://datatracker.ietf.org/doc/draft-havel-nmop-digital-map/)
     + TE Models

### 4. Network Anomaly Lifecycle (Hackathon) (10 min)

 * Presenter: Vincenzo Riccobene
  * Reading Material: [draft-netana-nmop-network-anomaly-lifecycle](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-lifecycle/)


### 5. Knowlege Graph for Network Operations (Hackathon) (5 min)

 * Presenter: Michael Mackey
  * Reading Material: [draft-mackey-nmop-kg-for-netops](https://datatracker.ietf.org/doc/draft-mackey-nmop-kg-for-netops/)

### 6. Misc (5 min)

