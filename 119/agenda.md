
               Network Management Operations (nmop)
                        Meeting Agenda
                     Monday, March 18, 2024
         Co-Chairs: Benoît Claise & Mohamed Boucadair



| Slot          | Topic              | Presenter      |
|:-------------:|:-----------------:|:----------------|
| 13:00 - 13:05 | Agenda Bashing & Introduction| Chairs    |
| 13:05 - 13:10 | A Word from the AD | Rob    |
| 13:10 - 13:25  | NETCONF/YANG Push Integration | Thomas    |
| 13:25 - 13:55 | Indident Management | Qin/Nigel    |
| 13:55 - 14:25 |  Anomaly Detection | Wanting/Thomas/Alex   |
| 14:25 - 14:40 | Issues Related to Deployment/Usage of YANG Topology Modules | Oscar    |
| 14:40 - 14:55 | Collecting Updated Operator Requirements for IETF Network Management Solutions | Luis    |
| 14:55 - 15:00 | Wrap-up | AD & Chairs    |


# Agenda Bashing & Introduction (Chairs) (5 min)
# A Word from the AD (Rob) (5 min)
   
# NETCONF/YANG Push Integration (15 min)

Goals: 
* Problem space overview (functional perimeter of each involved component)
* Highlight main integration concerns/missing pieces
* Agree on a set of next steps

## An Architecture for YANG Push to Apache Kafka Integration (10 min)

   - I-D: draft-netana-nmop-yang-kafka-integration
   - Presenter: Thomas Graf (onsite)

## Q&A (5 min)

# Indident Management (30 min)

Goals: 
* Clarify the intended scope for this work (network, service, etc.)
* Clarify how this effort fits within the overall ecosystem
* Agree on required actions to ensure this effort is useful for operators + a coordination is in place early in the process
  
## Incident Management for Network Services (10 min)

   - I-D: [draft-feng-nmop-incident-management](https://datatracker.ietf.org/doc/draft-feng-nmop-incident-management/)
   - Presenter: Qin Wu
     
## Common vocabulary for incident management (10 min)

   - I-D: [draft-davis-nmop-incident-terminology](https://datatracker.ietf.org/doc/draft-davis-nmop-incident-terminology/)
   - Presenter: Nigel Davis (onsite)/Adrian Farrel (remote)

## Q&A (10 min)

# Anomaly Detection (30 min)

Goals: 
* Clarify the problem to be solved

## Network Anomaly Detection – Real Time Streaming (10 min)

   - I-D: N/A   
   - Presenter: Wanting Du (remote)

## Semantic Metadata Annotation for Network Anomaly Detection (5 min)

   - I-D: [draft-netana-nmop-network-anomaly-semantics](https://datatracker.ietf.org/doc/draft-netana-nmop-network-anomaly-semantics/)
   - Presenter: Thomas Graf (onsite)

## Rule-based Service Anomaly Detection in Internet Services (5 min), depending on the available time

   - I-D: N/A
   - Presenter: Alex Huang Feng (remote)

## Q&A (10 min)

# Issues Related to Deployment/Usage of YANG Topology Modules (15 min)

Goals: 
* Assess whether there is an issue to be solved.
* If so, is NMOP the right place for this work?

## Modeling of Intermediate System to intermediate System (IS-IS) and OSPF Topologies

  - I-Ds: [draft-ogondio-nmop-isis-topology](https://datatracker.ietf.org/doc/draft-ogondio-nmop-isis-topology/) and draft-ogondio-opsawg-ospf-topology
  - Speaker Oscar Gonzalez de Dios (remote)
  - Slot: 10 min

## Q&A (5 min)

# Collecting Updated Operator Requirements for IETF Network Management Solutions (15 min)

Goals: 
* Explain the rationale for this work
* Identify interested contributors
  
## An Update of Operators Requirements on Network Management Protocols and Modelling (10 min)

   - I-D: [draft-boucadair-nmop-rfc3535-20years-later](https://datatracker.ietf.org/doc/draft-boucadair-nmop-rfc3535-20years-later/)
   - Presenter: Luis Miguel CONTRERAS MURILLO

## Q&A (5 min)
    
# Misc (All)
