# Network Management Operations (nmop) WG Agenda - IETF 122

* Co-Chairs: Benoît Claise, Reshad Rahman, & Mohamed Boucadair

## Current WG's Projects

* *P1*: NETCONF/YANG Push integration with message brokers & time series databases
* *P2*: Anomaly detection and incident management
* *P3*: Issues related to deployment/usage of YANG topology modules
* *P4*: Consider/plan an approach for updating RFC 3535


## Compact Agenda

### Session 1

| Slot        | Project |Topic                                                      | Presenters   |
|:-----------:|:-------:|:---------------------------------------------------------:|:-------------|
| 09:30-09:40 |         | Agenda Bashing & Introduction                             | Chairs       |
| 09:40-09:50 |         | Updates from the Terminology Fairy                        | Adrian       |
| 09:50-10:20 |    P3   | SIMAP                                                     | Olga         |
| 10:20-10:35 |    P1   | Message Broker                                            | Ahmed        |
| 10:35-10:55 |    P2   | Incident Management YANG Module                           | Qin          |
| 10:55-11:25 |    P2   | Bring Your Own Outage: Deutsche Telekom                   | Holger       |
| 10:55-11:25 |    P2   | Bring Your Own Outage: Swisscom                           | Thomas       |
| 11:25-11:30 |         | Wrap-up                                                   | Chairs       |

### Session 2  (Hackathon-focused)

| Slot       | Project |Topic                                                      | Presenters |
|:----------:|:-------:|:---------------------------------------------------------:|:-----------|
|15:30-15:35 |         | Agenda Bashing & Introduction                             | Chairs     |
|15:35-15:50 |   P1    | Configured Subscription YANG-Push Publisher               | Thomas     |
|15:50-16:05 |   P3    | SIMAP for SRv6 and Linking Topology to External Data      | Sherif     |
|16:05-16:20 |   P2    | Anomaly Detection Integration Update                      | Vincenzo   |
|16:20-16:30 |         | YANG Configuration Instance Data To Knowledge Graph       | Michael    |

## Session 1: Detailed Agenda

### 1. Agenda Bashing & Introduction (Chairs) (10 min)

### 2. Updates from the Terminology Fairy (10 min)

 * Presenter: Adrian Farrel
 * Reading Material: [draft-ietf-nmop-terminology](https://datatracker.ietf.org/doc/draft-ietf-nmop-terminology/)

### 3. SIMAP (30 min)

 * Presenter: Olga Havel
 * Reading Material: [draft-ietf-nmop-digital-map-concept](https://datatracker.ietf.org/doc/draft-ietf-nmop-digital-map-concept/)
   
### 4. Message Broker: Extensible YANG Model for Network Telemetry Notifications (15 min)

 * Presenter: Ahmed Elhassany
 * Reading Material:
    + [An Architecture for YANG-Push to Message Broker Integration] (https://datatracker.ietf.org/doc/html/draft-ietf-nmop-yang-message-broker-integration-07)
    + [Extensible YANG Model for Network Telemetry Notifications] (https://datatracker.ietf.org/doc/html/draft-netana-message-broker-telemetry-message-00)

### 5. Anomaly Detection & Incident Management (50 min)

#### 5.1. Incident Management YANG Module (20 min)

 * Presenter: Qin Wu
 * Reading Material: [draft-ietf-nmop-network-incident-yang](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang/)

#### 5.2. Bring Your Own Outage ( 30 min)

##### 5.2.1 DT Network Incident (15 min)

* Presenter: Holger Keller

##### 5.2.2 Swisscom Network Incident (15 min)

* Presenter: Thomas Graf
* Reading Material: [Slides](https://datatracker.ietf.org/meeting/122/materials/slides-122-nmop-sessb-swisscom-network-incident-network-analytics-postmortem-00)

### 6. Wrap-up (5 min)

## Session 2: Detailed Agenda (*Hackathon-focused*)

### 1. Agenda Bashing & Introduction (Chairs) (5 min)

### 2. Validate Configured Subscription YANG-Push Publisher Implementations (15 min)

* Presenter: Thomas Graf
* Reading Material:
    + [RFC 8639](https://datatracker.ietf.org/doc/html/rfc8639)
    + [RFC 8641](https://datatracker.ietf.org/doc/html/rfc8641)
    + [RFC 9196](https://datatracker.ietf.org/doc/html/rfc9196)
    + [draft-netana-netconf-notif-envelope](https://datatracker.ietf.org/doc/html/draft-netana-netconf-notif-envelope)
    + [draft-ietf-netconf-yang-notifications-versioning](https://datatracker.ietf.org/doc/html/draft-ietf-netconf-yang-notifications-versioning)
    + [draft-ietf-netconf-udp-notif](https://datatracker.ietf.org/doc/html/draft-ietf-netconf-udp-notif)
    + [draft-ietf-netconf-distributed-notif](https://datatracker.ietf.org/doc/html/draft-ietf-netconf-distributed-notif)
    + [draft-netana-netconf-yp-transport-capabilities](https://datatracker.ietf.org/doc/html/draft-netana-netconf-yp-transport-capabilities)

### 3. SIMAP for SRv6 and Linking Topology to External Data (15 min)

* Presenter: Sherif Mostafa
* Reading Material:
    + [draft-ietf-nmop-simap-concept](https://datatracker.ietf.org/doc/draft-ietf-nmop-simap-concept/)
    + [draft-havel-nmop-digital-map](https://datatracker.ietf.org/doc/draft-havel-nmop-digital-map/)

#### 4. Anomaly Detection Integration Update   (15 min)

 * Presenter: Vincenzo Riccobene
 * Reading Material:
    + [An Experiment: Network Anomaly Lifecycle](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-lifecycle/)
    + [Semantic Metadata Annotation for Network Anomaly Detection](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-semantics/)

### 5. YANG Configuration Instance Data to Knowledge Graph (10 min)

* Presenter: Michael Mackey
* Reading Material: [draft-mackey-nmop-kg-for-netops](https://datatracker.ietf.org/doc/draft-mackey-nmop-kg-for-netops/)

