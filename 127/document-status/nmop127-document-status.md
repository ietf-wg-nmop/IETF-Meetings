## NMOP Working Group 

### draft-ietf-nmop-yang-message-broker-integration

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration/
* **State**: Current version **-13** (updated 2026-07-02). Version -13 incorporates feedback from YANG Message Broker Consumer-side implementations. The document is considered ready for  **WG Last Call** .
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-yang-message-broker-integration
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-yang-message-broker-integration
* **Normative references**:
  * RFC2119
  * RFC3552
  * RFC4252
  * RFC6022
  * RFC7950
  * RFC8174
  * RFC8341
  * RFC8446
  * RFC8639
  * RFC8641
  * RFC8792
  * RFC9147
  * RFC9196
  * RFC9887
  * draft-ietf-netconf-notif-envelope
  * draft-ietf-netconf-udp-notif
  * draft-ietf-netconf-yang-library-augmentedby
  * draft-ietf-netconf-yang-notifications-versioning
  * draft-ietf-netconf-yp-transport-capabilities
  * draft-ietf-nmop-message-broker-telemetry-message
* **IETF Session**: At IETF 126, the document was considered ready for WG Last Call. A related ongoing discussion concerns `<span>draft-ietf-idr-bgp-model</span>` and the reuse of YANG groupings from `<span>ietf-bgp-rib-attributes</span>` and `<span>ietf-bgp-rib-tables</span>`. The current discussion is around making these submodules standalone importable modules to support the BMP telemetry/message broker use case. Mahesh suggested that broader conversion of submodules could be considered as part of future -bis/YANG 2.0 work, while Thomas considers standalone modules necessary from a practical implementation perspective.

### draft-ietf-nmop-message-broker-telemetry-message

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-message-broker-telemetry-message/
* **State**: Current version -05 (updated 2026-07-19). YANG validation: 4 errors, 5 warnings. A companion document, `<span>draft-netana-nmop-message-broker-bmp-telemetry-msg</span>`, defines a BMP (RFC 7854) YANG message schema extension for exporting Network Telemetry messages to external systems such as Message Brokers, re-using YANG data modelling from `<span>draft-ietf-idr-bgp-model</span>`. Recent discussion has focused on the interaction between the BMP telemetry model and the Message Key specification. BMP requires message ordering, with partitioning used to ensure that messages from the same network node remain ordered, while the Message Key format differs from the three-field YANG-Push format defined in `<span>draft-ietf-nmop-yang-message-broker-message-key-02</span>`
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-message-broker-telemetry-message
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-message-broker-telemetry-message
* **IETF Session**:
* **Normative references**:
  * RFC2119
  * RFC3688
  * RFC4252
  * RFC6141
  * RFC6991
  * RFC7950
  * RFC8040
  * RFC8174
  * RFC8341
  * RFC8342
  * RFC8446
  * RFC8639
  * RFC8641
  * RFC8791
  * RFC9000
  * RFC9232
  * draft-ietf-nmop-yang-message-broker-integration
  * draft-ietf-netconf-notif-envelope
  * draft-ietf-opsawg-collected-data-manifest
  * draft-ietf-netmod-yang-module-versioning
  * draft-ietf-netmod-yang-semver

### draft-ietf-nmop-yang-message-broker-message-key

draft-ietf-nmop-yang-message-broker-message-key

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-message-key/
* **State**: Current version -02 (updated 2026-07-02). The draft defines the Message Key format for Message Broker integration. Recent review has focused on its applicability beyond YANG-Push, particularly its alignment with the BMP telemetry message draft. The current three-field format is YANG-Push-oriented, while BMP uses a two-line key because it has no subscription ID. The authors clarified that Message Keys depend on the message schema/subject, with different BMP message types using different schemas and keys, and agreed that the BMP draft should update its normative reference to this draft.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-yang-message-broker-message-key
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-yang-message-broker-message-key
* **IETF Session**:
* **Normative references**:
  * RFC2119
  * RFC6241
  * RFC7950
  * RFC8174
  * RFC8342
  * RFC8641
  * RFC8792
  * draft-ietf-nmop-message-broker-telemetry-message
  * draft-ietf-netconf-notif-envelope

### draft-ietf-nmop-network-anomaly-architecture

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-architecture/
* **State**: Current version -08 (updated 2026-07-06). The architecture draft is part of the NMOP network anomaly draft trio, together with the lifecycle and semantics drafts. Recent discussion identified a gap around the evaluation of anomaly detection performance: how to define comparable metrics, build repeatable benchmarks from the Data Storage and Replay component, establish ground truth, and define measurable triggers for the refinement stage. A new individual informational draft, `<span>draft-anjum-nmop-anomaly-detection-evaluation</span>`, has been proposed as a companion to address these aspects. The proposal was welcomed by the authors, with additional discussion around episode-level detection, detection latency, multi-signal evaluation, and applicability beyond ML-based detectors.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-architecture
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-architecture
* **IETF Session**:
* **Normative references**:
  * draft-ietf-nmop-network-anomaly-lifecycle
  * draft-ietf-nmop-network-anomaly-semantics
  * draft-ietf-nmop-terminology
  * RFC2119
  * RFC8174
  * RFC8969
  * RFC9232

### draft-ietf-nmop-network-anomaly-lifecycle

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-lifecycle/
* **State**: Current version -07 (updated 2026-09-06). Recent review by Mateen Ali raised concerns about the evaluation criteria in Section 5.1, noting that false-positive/false-negative targets can be misleading for rare symptoms and should be evaluated against a trivial baseline (e.g., an always-alarm detector). He also suggested ensuring that symptom prevalence is kept consistent when comparing results across replay/refinement cycles, or using metrics that are not sensitive to prevalence. Mateen additionally offered to provide guidance on ground-truth requirements, including versioning and provenance, to ensure replay results remain comparable across lifecycle iterations.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-lifecycle
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-lifecycle
* **IETF Session**:
* **Normative references**:
  * Antagonist
  * draft-ietf-nmop-network-anomaly-architecture
  * draft-ietf-nmop-network-anomaly-semantics
  * draft-ietf-nmop-terminology
  * draft-ietf-nmop-yang-message-broker-integration
  * RFC2119
  * RFC3688
  * RFC4252
  * RFC6141
  * RFC8040
  * RFC8174
  * RFC8340
  * RFC8341
  * RFC8446
  * RFC9000
  * RFC9232
  * RFC9417
  * RFC9418
  * RFC9543
  * RFC9911

### draft-ietf-nmop-network-anomaly-semantics

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-semantics/
* **State**: Current version -06 (updated 2026-07-06). The authors incorporated Reshad Rahman's review comments into -06, including simplification of the abstract, terminology and editorial fixes, removal of the implementation-specific `<span>cbl</span>` naming from the YANG module and groupings, clarification of the rationale for the dedicated L2VPN/L3VPN service and network groupings, and correction of the NETCONF reference to RFC 6241. The authors also agreed to include an example with annotation metadata. Reshad confirmed on 2026-08-31 that the comments had been addressed and indicated that he would request a YANG Doctors review. The remaining focus is therefore on the upcoming YANG Doctors review and any resulting feedback.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-semantics
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-semantics
* **IETF Session**:
* **Normative references**:
  * Antagonist
  * draft-ietf-nmop-network-anomaly-architecture
  * draft-ietf-nmop-network-anomaly-lifecycle
  * draft-ietf-nmop-terminology
  * RFC3688
  * RFC4252
  * RFC6241
  * RFC8040
  * RFC8340
  * RFC8341
  * RFC8446
  * RFC8969
  * RFC9000

### draft-ietf-nmop-network-incident-yang

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang/
* **State**: Current version -17 (updated 2026-09-24). The draft has addressed the YANG Doctors review and subsequent comments from Paul Aitken, including reference/downref cleanup, RPC and incident-key descriptions, security requirements, notification references, and YANG formatting issues. Saumya Dikshit also raised Last Call comments on probable-cause identity, support for multiple causes per node/resource, and the handling of anomaly confidence; the authors accepted the first two points and clarified that the incident model should remain independent of the anomaly detection lifecycle, with no normative dependency on the experimental anomaly work. The WGLC is now being closed, while recent discussion on multi-step diagnosis and Network Management Agents has been framed as potential future extension work building on the base incident model.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-incident-yang
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-incident-yang
* **IETF Session**:
* **Normative references**:
  * RFC2119
  * RFC3688
  * RFC4252
  * RFC4253
  * RFC6020
  * RFC6241
  * RFC7950
  * RFC8040
  * RFC8174
  * RFC8340
  * RFC8341
  * RFC8345
  * RFC8632
  * RFC8791
  * RFC9000
  * RFC9375
  * RFC9846
  * RFC9911

### draft-ietf-nmop-rfc3535-20years-later

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-rfc3535-20years-later/
* **State**: Current version -04 (updated 2026-05-05). 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-rfc3535-20years-later
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-rfc3535-20years-later
* **IETF Session**:
* **Normative references**:
  - RFC3535

### draft-ietf-nmop-simap-concept

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-simap-concept/
* **State**: Current version  **-14** , published  **2026-10-02**. The -14 revision addressed the TSVART Last Call review, including the addition of the **REQ-CONGESTION** requirement. Mahesh has sent the document for IESG review.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-simap-concept
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-simap-concept
* **IETF Session**:
