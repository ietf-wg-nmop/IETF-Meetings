# Network Management Operations (nmop) WG Agenda - IETF 119

* When: Monday, March 18, 2024
* Co-Chairs: Benoît Claise & Mohamed Boucadair

## Compact Agenda


| Slot          | Topic              | Presenter      |
|:-------------:|:-----------------:|:----------------|
| 13:00 - 13:05 | Agenda Bashing & Introduction| Chairs    |
| 13:05 - 13:10 | A Word from the AD | Rob    |
| 13:10 - 13:25 | NETCONF/YANG Push Integration | Thomas    |
| 13:25 - 13:50 | Anomaly Detection | Thomas/Vincenzo   |
| 13:50 - 14:15 | Incident Management | Qin/Nigel    |
| 14:15 - 14:40 | Issues Related to Deployment/Usage of YANG Topology Modules | Oscar/Olga    |
| 14:40 - 14:55 | Collecting Updated Operator Requirements for IETF Network Management Solutions | Luis    |
| 14:55 - 15:00 | Wrap-up|     |

## Detailed Agenda

### Agenda Bashing & Introduction (Chairs) (5 min)
### A Word from the AD (Rob) (5 min)
   
### NETCONF/YANG Push Integration (15 min)

Goals: 
* Clarify the problem to be solved (Highlight main integration concerns/missing pieces)
* Describe the dependencies, status, and next steps

#### An Architecture for YANG Push to Apache Kafka Integration (10 min)

   - I-D: [draft-netana-nmop-yang-kafka-integration](https://datatracker.ietf.org/doc/draft-netana-nmop-yang-kafka-integration/)
   - Presenter: Thomas Graf (onsite)

#### Q&A (5 min)

### Anomaly Detection (25 min)

Goal: 
* Clarify the problem to be solved

#### Experiment Semantic Metadata Annotation for Network Anomaly Detection + Network Anomaly Postmortem Lifecycle (15 min)

   - I-Ds: [draft-netana-nmop-network-anomaly-semantics](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-semantics/) & [draft-netana-nmop-network-anomaly-lifecycle](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-lifecycle/)
   - Presenters: Thomas Graf (onsite) and/or Vincenzo Riccobene (remote)

#### Q&A (10 min)

### Incident Management (25 min)

Goals: 
* Clarify the problem to be solved (network, service, etc.)
* Clarify how this effort fits within the overall SDO ecosystem
* Agree on required actions to ensure this effort is useful for operators + a SDO coordination is in place early in the process
  
#### Incident Management for Network Services (10 min)

   - I-D: [draft-feng-nmop-network-incident-yang](https://datatracker.ietf.org/doc/draft-feng-nmop-network-incident-yang/)
   - Presenter: Qin Wu
     
#### Common vocabulary for incident management (5 min)

   - I-D: [draft-davis-nmop-incident-terminology](https://datatracker.ietf.org/doc/draft-davis-nmop-incident-terminology/)
   - Presenter: Nigel Davis (onsite)/Adrian Farrel (remote)

#### Q&A (10 min)


### Issues Related to Deployment/Usage of YANG Topology Modules (25 min)

Goals: 
* Clarify the problem to be solved
* Next step: how to structure this work?

#### Problem Space and Modeling Issue of the Digital Space (15 min)
  
  - I-Ds: [draft-ogondio-nmop-isis-topology](https://datatracker.ietf.org/doc/draft-ogondio-nmop-isis-topology/) & [draft-havel-nmop-digital-map](https://datatracker.ietf.org/doc/draft-havel-nmop-digital-map/)
  - Presenters: Oscar Gonzalez de Dios (remote) & Olga Havel (remote)
  - Slot: 15 min

#### Q&A (10 min)

### Collecting Updated Operator Requirements for IETF Network Management Solutions (15 min)

Goals: 
* Explain the rationale for this work
* How to collect operator requirements?
  
#### An Update of Operators Requirements on Network Management Protocols and Modelling (10 min)

   - I-D: [draft-boucadair-nmop-rfc3535-20years-later](https://datatracker.ietf.org/doc/draft-boucadair-nmop-rfc3535-20years-later/)
   - Presenter: Luis Miguel CONTRERAS MURILLO

#### Q&A (5 min)
    
### Misc (All) (5 min)
