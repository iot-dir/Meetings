# IoT directorate IETF 110 pre-meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ari Keränen, Ines Robles


Date: 3 March 2021
Time: 15:00 -16:30 UTC Time.

## Webex:

Meeting Details 
Webex Meeting details:

https://ietf.webex.com/ietf/j.php?MTID=me710fb9fbee85dcfd1e31b238b35f8ca
Wednesday, Mar 3, 2021 7:00 am | 1 hour 30 minutes | (UTC-08:00) Pacific Time (US & Canada)
Meeting number: 185 579 5180
Password: uDMMfPPg883
1553bfdc2a78461e8105fb3efcabd1ef

This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Request for your input
We would like to evaluate the IoT Directorate work at the IETF. Thus, we kindly request your feedback by January 31st through the following form:  

https://www.surveymonkey.com/r/BMVF9WK

## Draft agenda
* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* Report out on OneDM and iotschema



Notice that we aim to record the meeting.

# Attendees

* Please add your name here
* Maria Ines Robles
* Barry Leiba
* Éric Vyncke
* Dominique Barthel
* Ari Keränen
* Dave Thaler
* Erik Nordmark
* Carles Gomez
* Christian Amsüss
* Niklas Widell
* Marco Tiloca
* Henk Birkholz
* Michael Richardson
* Nancy Cam-Winget
* Francesca Palombini
* Erik Nordmark
* Samita Chakrabarti



# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

6TiSCH is dormant but the main RFCs as now being edited by the RFC editor. They were in MISSREF but the ROLL drafts in progress are now available to the deitor as well, see https://www.rfc-editor.org/cluster_info.php?cid=C310.


## 6lo (Carles Gomez / Shwetha Bhandari)
6lo session scheduled at IETF 110.

 Batch of 4 new RFCs:
     - AP-ND --------------> RFC 8928
     - Backbone router   --> RFC 8929
     - Fragment-related  --> RFC 8930, RFC 8931

Most WG documents are at very advanced stages: 

  1 document in RFC Ed queue:
      - Deadline time (State: RFC-EDITOR*R (part of C310))

  2 documents, IESG evaluated:
      - IPv6 over NFC 
      - IPv6 mesh over BLE

  2 other active WG documents:
      - IPv6 over PLC (pre-IESG reviews done)
      - Use cases (2nd WGLC done)    

  In the meeting, also discussion about use of SCHC for header compression in 6lo environments
      - Related individual draft  


Discussion for WG closing ? Eric Vyncke mentioned that the plan was to close soon (but keep mailing list opened as usual) unless anyone has any new work items to keep it going.

## ACE (Daniel Migault / Loganaden Velvindron)




## ASDF (Michael Richardson / Niklas Widell)

The ASDF WG is focused on specification of SDF (Semantic Definition Format), to be used for modelling thing interactions and data in a highly interoperable manner. 

WG has one adopted draft, draft-ietf-asdf-sdf, on Call for Consensus for adoption as Implementation draft, to be intended target for toolchain updates. 

ASDF has will meet at 110. Agenda topics include confirming the consensus call, new features, mapping file format and results from the hackathon. 

AK: for more information about the joint ASDF/WISHI (T2TRG) hackathon, see https://github.com/t2trg/2021-03-hackathon

## CBOR (Francesca Palombini / Christian Amsüss)

* Just leaving WG:
    * Expressing X.660 OIDs in CBOR (-tags-oid)
* Active
    * CBOR with dict-based compression that's usable while compressed (-packed)
    * Matching, building and flagging CDDL parts (-cddl-control) – *and ABNF can stay in*
* Adopted an hour ago:
    * Stating media types for data-at rest (-file-magic)
    * Compact IP address representations (-network-addresses)

Biweekly interims were had, recent ones leading up to the new documents.


## CoRE (Jaime Jimenez / Marco Tiloca)

RFC 8974 published in January, on extended CoAP Tokens and stateless clients.

14 active WG drafts, of which:
- 1 Approved and in Editor Queue (Dev-URN)
- 1 Approved and in AD Followup (Resource Directory)
- 1 Approved and Revised ID Needed (Echo-Request-Tag)
- 2 Last Call (Coreconf documents "yang-cbor" and "sid")
- 2 expected to leave the WG soon (remaining Coreconf documents)

Two documents are post WGLC (Group OSCORE and blockwise for DOTS)
- https://datatracker.ietf.org/doc/draft-ietf-core-oscore-groupcomm/
- https://datatracker.ietf.org/doc/draft-ietf-core-new-block/

We had biweekly virtual Interim meetings mostly about:
- Advancing the work on Dynlink --- https://datatracker.ietf.org/doc/draft-ietf-core-dynlink/
- Advancing the work on cacheable OSCORE --- https://datatracker.ietf.org/doc/draft-amsuess-core-cachable-oscore/
- Discuss new work on cipher limits in OSCORE --- https://datatracker.ietf.org/doc/draft-hoeglund-core-oscore-key-limits/

CoRE will meet at IETF 110. A series of 6 biweekly interim meetings is booked, from April 28.

## COSE (Matt Miller / Ivaylo Petrov)



## DetNet (Lou Berger / János Farkas)
The WG has published the following RFCs:
*	RFC 8557 Deterministic Networking Problem Statement
*	RFC 8578 Deterministic Networking Use Cases
*	RFC 8655 Deterministic Networking Architecture 
*	RFC 8938 Deterministic Networking (DetNet) Data Plane Framework (2020-11)
*	RFC 8939 Deterministic Networking (DetNet) Data Plane: IP (2020-11)
*	RFC 8964 Deterministic Networking (DetNet) Data Plane: MPLS (2021-01)

The following drafts are with the RFC Editor:
*	draft-ietf-detnet-flow-information-model DetNet Flow and Service Information Model
*	draft-ietf-detnet-ip-over-mpls DetNet Data Plane: IP over MPLS
*	draft-ietf-detnet-mpls-over-udp-ip DetNet Data Plane: MPLS over UDP/IP
*	draft-ietf-detnet-ip-over-tsn DetNet Data Plane: IP over IEEE 802.1 Time Sensitive Networking (TSN) 
*	draft-ietf-detnet-mpls-over-tsn DetNet Data Plane: MPLS over IEEE 802.1 Time-Sensitive Networking (TSN) 
*	draft-ietf-detnet-tsn-vpn-over-mpls DetNet Data Plane: IEEE 802.1 Time Sensitive Networking over MPLS

The following draft is under IESG evaluation: 
*	draft-ietf-detnet-security Deterministic Networking (DetNet) Security Considerations
The following draft is at WG Last Call:
*	draft-ietf-detnet-bounded-latency DetNet Bounded Latency
The WG has the following drafts in progress:
*	draft-ietf-detnet-yang Deterministic Networking (DetNet) Configuration YANG Model (getting close to WG Last Call)
*	draft-ietf-detnet-mpls-oam Operations, Administration and Maintenance (OAM) for Deterministic Networks (DetNet) with MPLS Data Plane
*	draft-ietf-detnet-ip-oam Operations, Administration and Maintenance (OAM) for Deterministic Networks (DetNet) with IP Data Plane
*	draft-ietf-detnet-controller-plane-framework Deterministic Networking (DetNet) Controller Plane Framework (recently adopted)

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)

First session next week. Conflicts resolved. Fully packed agenda. Just one hour. We might assess if there's immediate interest for virtual interims to have more mic time. Want to make landing page for non-IETF'ers too. Please have a look at agenda.

> looks like full agenda
> [name=mcr]

## LAKE (Mališa Vučinić / Stephen Farrell)

(Both Mališa and Stephen are unavailable to join the call this afternoon, apologies for that.)
LAKE has held 2 interim meetings since IETF-109. We continued progressing the EDHOC specification by resolving the open issues. 3 online interop events were organized with several independent implementers participating. We have also been discussing the plans on formally analyzing the protocol and verifying one implementation.


## LWIG (Mohit Sethi / Zhen Cao)
Since last IETF:
* The IESG meeting on 3rd March will discuss the draft on Alternative Elliptic Curve Representations (draft-ietf-lwig-curve-representations). Hopefully, we can reach some reasonable consensus on how to proceed with the document. 
* Minimal ESP (draft-ietf-lwig-minimal-esp) finished the working group last call and is now waiting for shepherd writeup. 
* TCP Usage Guidance in the Internet of Things (IoT) (draft-ietf-lwig-tcp-constrained-node-networks-13) approved by IESG and with RFC editor.
* draft-ietf-lwig-cellular-06 in RFCed queue for 1884 days :(
* Several working group adopted documents not seeing any activity and expired. Milestones:
    * "Submit the CoAP security comparison document to the IESG for publication as an Information RFC" for review, due December 2018
    * "Submit the neighbor management guidance document to IESG for publication as an Informational RFC" for review, due March 2019
    * "Submit the lwig virtual assembly guidance document to IESG for publication as an Informational RFC" for review, due March 2019
    lwig-cellular draft is dependent on CORE resource directory draft. The Resource directory draft should be ready soon and it is in final review stage (Christian).

## LPWAN (Alex Pelov / Pascal Thubert)

LPWAN deliver SCHC over LoraWAn that is being edited by the RFC editor.
The work on YANG model has started. 
The SCHC-COAP draft is held by a DISCUSS from Ben Kaduk, we hope this is solved soon.
> SCHC-CoAP DISCUSS has been cleared by Ben. Ana to upload a revised I-D fixing the latest comments when the window opens again and Éric will then approve it to go to the RFC Editor Queue
> [name=Éric Vyncke]

> SCHC over Sigfox and SCHC over NB-IoT are also progressing
> [name=Carles]

## RATS (Kathleen/ Nancy / Ned)

Architecture draft should be ready for WGLC.
Remote Integrity Verification draft is done waiting for AD approval (as it has many dependencies on other RATs drafts still in construction) to move to IESG
EAT draft continues to evolve.
TPM/Yang based draft is maturing
Interaction models was adopted and under construction.
There are still several other drafts that may come into adoption to address SUIT interconnect, using unprotected CWT claims, time based unidirectional attestations and extensions for handling CoSWID integrity measurements.

## ROLL (Dominique Barthel / Ines Robles)

* ROLL will have one hour meeting on IETF 110.
* Interim meetings between IETFs.
* RFC Editor: draft-ietf-roll-useofrplinfo-44, draft-ietf-roll-unaware-leaves-30, draft-ietf-roll-turnon-rfc8138-18, draft-ietf-roll-efficient-npdao-18
* Work In progress: draft-ietf-roll-dao-projection-16, draft-ietf-roll-enrollment-priority-04, draft-ietf-roll-mopex-02, draft-ietf-roll-capabilities-07


## SUIT (Dave Thaler / David Waltermire / Russ Housley)
* Hackathon this week has TEEP project using SUIT (and RATS)
* SUIT Architecture is in RFC editor queue
* Information model/threat model is in IESG
* Manifest format is getting close to WGLC
* Call for adoption in progress on "Secure Reporting of Update Status"
* MUD (Strong Assertions of IoT Network Access Requirements) also proposed for adoption but needs charter update

## TEEP (Tiru Reddy / Nancy Cam-Winget)

TEEP Architecture draft should be close to done.
TEEP Protocol draft is maturing as implementations are forcing clarifications and improvements.


## T2TRG (Ari Keränen / Carsten Bormann)

Recent work on three documents (all on agenda for the 2-hour summary meeting at IETF 110):
* [IoT Edge Challenges and Functions](https://tools.ietf.org/html/draft-irtf-t2trg-iot-edge-01) draft that is getting ready for publication
* [Secure Bootstrapping](https://tools.ietf.org/html/draft-sarikaya-t2trg-sbootstrapping-11) draft that is getting mature for adoption
* [A Taxonomy of operational security considerations for manufacturer installed keys and Trust Anchors](https://www.ietf.org/archive/id/draft-richardson-t2trg-idevid-considerations-03.html); new document that will be presented at summary meeting

Good to synch with RATS, ANIMA, IOTOPS on the security docs.

Other recently submitted documents:

* Low End-to-End Latency Content Caching in Wireless Network Clouds
* Proactive energy management for smart city with edge computing using meta-reinforcement learning scheme
* Resource Allocation Strategy for Latency Sensitive IoT Traffic
* Resource Sharing in Virtualized Wireless Networks: A Two-Layer Game Approach
* User Centric Assignment and Partial Task Offloading for Mobile Edge Computing in Ultra-Dense Networks

Recent [WISHI](https://github.com/t2trg/wishi) work has been focusing on supporting OneDM/ASDF. One WISHI online meeting (yesterday).
 
Ongoing hackathon together with ASDF WG.


## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## RAW (Rick Taylor / Eve Schooler)
3 documents were adopted and publised as draft IETF. 
These are:

*   The technologies draft
*   the Use cases draft
*   the LDACS draft 
 
LDACS is a radio that was designed for airplane communication


# New/planned IETF/IRTF IoT activities


# Updates from other IoT groups

## IoTSF

(IoT Security Foundation)

IoTSF has started  new WG called "ManySecured", which deals with security in the home between IoT devices and owners.  The problem of how to do HTTPS (or equivalent) is specifically in scope as the first work item.   draft-richardson-homerouter-provisioning-00 deals with a similiar problem.

## OneDM 
https://onedm.org/

Goal: 
- Normalize IoT information models across industry in multiple verticals

Progress: 
- Stable working draft of SDF language (precondition)
- 200 models [contributed](https://github.com/one-data-model/playground) from 4 different SDOs: IPSO/LWM2M, OCF, Bluetooth Mesh, and Zigbee/CHIP

Next steps:
- Drive a process of model convergence and publication of consensus-based models and definitions
- Expand the scope of information models – electronic datasheets, textile manufacturing equipment
- Provide use case requirements for SDF extensions 

## iotschema
http://iotschema.org/

Goal: 
- Provide an extension to schema.org for IoT categories

Progress: 
- Small set of 20-30 common example models
- Aligned with OneDM and industry ontologies
- Used in W3C WoT plugfests 

Next steps:
- Deploy the extension point in schema.org, working with danb
- Extend the models and convert models from e.g. OneDM

## W3C WoT

Get your W3C WoT update at the T2TRG summary meeting @IETF110, Thu 1600Z Mar 11

# AOB

Ted: two drafts -- connecting Thread meshes to IP networks in scalable way. Wasn't available tech to do that. Wrote [stub document](https://datatracker.ietf.org/doc/draft-lemon-stub-networks-ps/) on the problem and [solutions](https://datatracker.ietf.org/doc/draft-lemon-stub-networks/) explored. Posted a doc about solution. Might be general interest. Largely operational practice. Not cast in stone; helpful if folks interest to problem of connecting IoT networks to infra networks could have a look at the doc. IoT networks are not usually transit networks. Fairly restricted usecase that gives you ways to simplify things. Base use case: Thread accessory that needs to be discoverable in home network. How to make happen. Use number of IETF protocols. 

Koster: anyone can report to Zigbee / PCHIP? They will likely go on another route to solve these things. Could try to do that.

Ted: good to get involved. This is work presented to Thread already. Code is running in home pod mini. Also independent implementation by Google. For CHIP/Thread members more participation would be good.

Eric: two drafts on Homenet?

Ted: yes. Also service discovery discussed in the same timeslot with DNSSD. Can make visible and usable in Wifi network.

