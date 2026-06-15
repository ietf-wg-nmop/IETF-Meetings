## NMOP Working Group

### draft-ietf-nmop-yang-message-broker-integration

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-integration/
* **State**: Current version -12 (updated 2026-05-13). Authors addressed Reshad's comments and added operational, security and IANA considerations sections. Reviews are requested, particularly on the operational and security considerations sections. Authors have requested WG last call. IETF 126 hackathon already in preparation, focusing on: YANG instance data validation against YANG schema, feature differences among open-source YANG library implementations, unit tests, follow-up on open items from IETF 124, and enhancements in the YANG-Push Receiver.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-yang-message-broker-integration
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-yang-message-broker-integration
* **IETF Session**:


### draft-ietf-nmop-message-broker-telemetry-message

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-message-broker-telemetry-message/
* **State**: Current version -04 (updated 2026-01-18). YANG validation: 0 errors, 5 warnings. A companion document has been published: draft-netana-nmop-message-broker-bmp-telemetry-msg, which defines a BMP (RFC 7854) message schema extension in YANG to transform Network Telemetry messages into external systems such as Message Brokers, re-using existing work from draft-ietf-idr-bgp-model. It also describes a message broker addressing scheme and message keys based on draft-ietf-nmop-yang-message-broker-message-key. Active discussion on BMP message ordering in Message Brokers has started on the mailing list: key open question is how to preserve BMP message ordering across partitions and topics, with proposals ranging from a single-topic approach (ordering guaranteed at the cost of parallelism) to separating control messages (init, term, peer up/down) into a dedicated control-topic while routing other BMP messages to different topics, acknowledging that BMP station implementations would need to handle residual ordering issues through internal state.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-message-broker-telemetry-message
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-message-broker-telemetry-message
* **IETF Session**:


### draft-ietf-nmop-yang-message-broker-message-key

~draft-netana-nmop-yang-message-broker-message-key~ → draft-ietf-nmop-yang-message-broker-message-key

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-yang-message-broker-message-key/
* **State**: Current version -01, draft-netana has been adopted by the WG and replaced by draft-ietf-nmop-yang-message-broker-message-key-01 (updated 2026-03-02). 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-yang-message-broker-message-key
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-yang-message-broker-message-key
* **IETF Session**:


### draft-ietf-nmop-network-anomaly-architecture

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-architecture/
* **State**: Current version -07 (updated 2026-01-21). 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-architecture
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-architecture
* **IETF Session**:


### draft-ietf-nmop-network-anomaly-lifecycle

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-lifecycle/
* **State**: Current version -05 (updated 2026-02-12). YANG validation: 0 errors, 0 warnings. Reshad provided comments on -05 (2026-03-13) still pending to be addressed: abstract considered too verbose (seeking WG feedback), open question on false positive/false negative trade-offs in the introduction, state machine diagram in Section 7 lacks explanatory text for state transitions and has a rendering nit (missing top line on "Problem Confirmed" box), Section 8.2 has several issues: 6991-bis reference needs updating to RFC9911, inconsistent terminology across leaf descriptions (mixing "relevant state", "relevant-state", "problem" and "fault" — should all use "Relevant State"), leaf nodes topic-name and subject-name incorrectly using "host-name" type, and a typo ("is in" → "A problem is in")
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-lifecycle
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-lifecycle
* **IETF Session**:


### draft-ietf-nmop-network-anomaly-semantics

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-semantics/
* **State**: Current version -05 (updated 2026-01-19), with -06 pending submission. YANG validation: 0 errors, 1 warning. Reshad Rahman reviewed -05 (2026-03-13) with the following comments: abstract unclear on what the annotations are for, wrong use of "uniforms" (should be "standardizes" or "unifies"), ambiguous use of "vendors", nit in introduction ("the system need" → "the system needs"), question on whether Table 1 in Section 3 aligns with draft-ietf-opsawg-discardmodel, clarification needed on whether Tables 1-3 are exhaustive or illustrative, meaning of "cbl" in 'ietf-network-anomaly-symptom-cbl' unexplained, unclear rationale for including L2VPN/L3VPN service models in Section 4.3, wrong RFC reference in Section 6 (RFC6141 should be RFC6241 for NETCONF), and a request for an example with annotation metadata. Authors responded (2026-05-25): nits and abstract simplification already merged into -06 (diff available), remaining comments addressed inline. New version -06 expected to be submitted shortly. 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-anomaly-semantics
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-anomaly-semantics
* **IETF Session**:


### draft-ietf-nmop-network-incident-yang

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang/
* **State**: Current version -08 (updated 2026-02-13), which addressed comments from Reshad, Daniel and Benoît. YANG validation: 0 errors, 0 warnings. Adrian Farrel raised the question of next steps on the mailing list (2026-05-11), noting the overdue December 2025 milestone and asking whether anything remains to advance the document. Multiple WG members responded in support of moving to WGLC: Dan (2026-05-11), Sai Han(2026-05-21), Cheng Zhou (2026-05-22) and Shailesh (2026-05-22) all consider the document stable and ready for WGLC. WGLC expected to be called soon. 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-network-incident-yang
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-network-incident-yang
* **IETF Session**:


### draft-ietf-nmop-rfc3535-20years-later

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-rfc3535-20years-later/
* **State**: Current version -04 (updated 2026-05-05). Version -03 (2026-03-20) removed the assessment appendices to focus on new requirements, with historical background/discussion available in the NEMOPS report. Version -04 is a minor revision fixing nits and references, and authors consider it ready for WGLC. The consolidated requirements presented at IETF 125 in Shenzhen include an item about implementations and running code; Job Snijders has agreed to lead a discussion on implementation policy in OPS at IETF 126. 
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-rfc3535-20years-later
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-rfc3535-20years-later
* **IETF Session**:


### draft-ietf-nmop-simap-concept

* **URL**: https://datatracker.ietf.org/doc/draft-ietf-nmop-simap-concept/
* **State**: Current version -11 (submitted 2026-06-03). Publication requested by Reshad Rahman on 2026-03-31 as Informational on behalf of the WG. AD Mahesh Jethanandani completed his review of -10 (2026-05-04), noting thorough WG process (49 issues resolved during WGLC) and broad WG support, but raising two MAJOR and several MINOR comments. Authors opened 10 issues on GitHub and addressed them all in -11. All MAJOR comments resolved: ETSI ZSM 019 reference properly added (Section 8.2) and Security Considerations significantly expanded. All MINOR comments resolved in -11. A further revision (-12) is expected shortly to formally incorporate the -11 changes confirmed by Mahesh.
* **Mailinglist**: https://mailarchive.ietf.org/arch/browse/nmop/?q=draft-ietf-nmop-simap-concept
* **Diff**: https://author-tools.ietf.org/diff?doc_1=draft-ietf-nmop-simap-concept
* **IETF Session**:
