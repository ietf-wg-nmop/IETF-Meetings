# Network Management Operations (nmop) WG Agenda - IETF 120

* When: Friday, July 27, 2024
* Co-Chairs: Benoît Claise & Mohamed Boucadair

## Current WG's priorities

* *P1*: NETCONF/YANG Push integration with message brokers & time series databases
* *P2*: Anomaly detection and incident management
* *P3*: Issues related to deployment/usage of YANG topology modules (e.g., to model a Digital Map)
* *P4*: Consider/plan an approach for updating RFC 3535 (collecting updated operator requirements for IETF network management solutions)

## A Note on Detailed Hackathon Reports

* **Interim** meetings will be scheduled to share detailed hackathon reports
* **Main** findings can be presented in IETF#120 with a preference to share those on the mailing list prior to the session

## Compact Agenda

| Slot          | Priority Label |Topic              | Presenters      |
|:-------------:|:--------:|:----------------:|:----------------|
| 13:00 - 13:10 || Agenda Bashing & Introduction| Chairs    |
| 13:10 - 13:35 |P1| YANG-Push to Message Broker Integration | Thomas    |
| 13:35 - 13:55 |P2| NMOP Terminology | Adrian    |
| 13:55 - 14:10 |P2| Anomaly detection: Experiements & Roadmap | Thomas/Pierre/Vincenzo |
| 14:10- 14:25 |P3| Digital Map Concepts & Requirements | Olga    |
| 14:25 - 14:30 |P4| NEMOPS Workshop  | Chairs    |
| 14:30 - 14:45 |P4| Updates to Operators Requirements | Luis    |
| 14:45 - 15:55 || Knowlegde Graph |  Nacho |
| 14:55 - 15:00 || Wrap-up & Future Meetings |  Chairs |

## Detailed Agenda

### 1. Agenda Bashing & Introduction (Chairs) (10 min)
   
### 2. NETCONF/YANG Push Integration (25 min)

**Goals**: 
* Experiment status update
* Share pending issues
* Next steps

#### 2.1 An Architecture for YANG-Push to Message Broker Integration (20 min)

 * ***Presenter***: Thomas Graf
 * ***Reading Material***: [draft-ietf-nmop-yang-message-broker-integration](https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration/)
 * ***IETF 120 Hackathon***: [YANG-Push Publisher Implementation Tests](https://github.com/network-analytics/ietf-network-analytics-document-status/tree/main/120/Hackathon)

#### 2.2 Q&A (5 min)

### 3. Anomaly Detection and Incident management (35 min)

**Goals**: 
* Sync on the approach/rationale and discuss issues related to NMOP terminology
* Report the outcome of the side meeting on NMOP terminology
* Structure the anomaly detection work & agree on a roadmap for the items to be delivered

#### 3.1 Some Key Terms for Network Incident and Problem Management (20 min)

 * ***Presenters***: Adrian
 * ***Reading Material***: [draft-ietf-nmop-terminology](https://datatracker.ietf.org/doc/draft-ietf-nmop-terminology/)

#### 3.2 Anomaly Detection (15 min)

##### 3.2.2 An Architecture for a Network Anomaly Detection Framework (10 min)

 * ***Presenters***: Thomas Graf, Pierre Francois and Vincenzo Riccobene
 * ***Reading Material***:
    + [draft-netana-nmop-network-anomaly-architecture](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-architecture/)
    + [draft-netana-nmop-network-anomaly-semantics](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-semantics/)
    + [draft-netana-nmop-network-anomaly-lifecycle](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-lifecycle/)
 * ***IETF 120 Hackathon***: [Atagonist Experiment](https://github.com/vriccobene/antagonist)

##### 3.2.3 Q&A (5 min)

### 4. Issues Related to Deployment/Usage of YANG Topology Modules (15 min)

**Goals**: 
* Share status update
* Agree on the next steps

#### 4.1 Digital Map: Concepts & Requirements (10 min)

 * ***Presenters***: Olga Havel
 * ***Reading Material***: [draft-havel-nmop-digital-map-concept](https://datatracker.ietf.org/doc/draft-havel-nmop-digital-map-concept/)
 * ***IETF 120 Hackathon***: [Digital Map for ISIS and OSPF](https://wiki.ietf.org/en/meeting/120/hackathon#digital-map-for-isis-and-ospf)

#### 4.2 Q&A (5 min)

### 5. Collecting Updated Operator Requirements for IETF Network Management Solutions (20 min)

**Goals**: 

* Updates on the NEMOPS IAB Worksop
* Upadates and Plans to meet NMOP-specific charter item, especially the following milestone:

>Sep 2024	Adopt a document on updated operators requirements

#### 5.1 NEMOPS IAB Workshop (5 min)

   - ***Presenter***: Chairs
   - ***Reading material***: [Workshop Proposal](https://github.com/ietf-wg-nmop/Logistic/blob/main/IAB%20Workshop.md)

#### 5.2 An Update of Operators Requirements on Network Management Protocols and Modelling (15 min)

   - ***Presenter***: Luis
   - ***Reading material***: [draft-boucadair-nmop-rfc3535-20years-later](https://datatracker.ietf.org/doc/draft-boucadair-nmop-rfc3535-20years-later/)
   - _Discussion_: Whether this will be submitted as a contribution to NEMOPS or reflect starting point to build NMOP-specific consensus.

### 6. Misc.

##### 6.1 Knowledge Graphs for YANG-based Network Management (10 min)

 * ***Presenter***: Ignacio Dominguez Martinez-Casanueva
 * ***Reading Material***: [draft-marcas-nmop-knowledge-graph-yang](https://datatracker.ietf.org/doc/draft-marcas-nmop-knowledge-graph-yang/)
 * _Discussion_: share plans for experiments, hackathons, link with other items/current WG priorities, etc.

### 7. Next Meetings & Wrap-up (All) (5 min)

 * Next scheduled interim: September 11 (anomaly detection)
 * _Discussion_: Preference to have other interims? Monthly interims dedicated to each items?
