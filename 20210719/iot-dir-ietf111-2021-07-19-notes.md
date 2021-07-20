Source: https://codimd.ietf.org/iot-dir-ietf111-2021-07-19-notes

# IoT directorate Pre-IETF 111 meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keranen


Date: 19 July 2021
Time: 16:00 -17:30 UTC Time.

## Webex:

Meeting Details 
Webex Meeting details:

https://ietf.webex.com/ietf/j.php?MTID=m78ab78badcf7ebc1904faf2f09439996
Monday, Jul 19, 2021 9:00 am | 1 hour 30 minutes | (UTC-07:00) Pacific Time (US & Canada)
Meeting number: 161 186 6167
Password: JegvKmNj753

Join by video system
Dial 1611866167@ietf.webex.com
You can also dial 173.243.2.68 and enter your meeting number.

Join by phone
1-650-479-3208 Call-in toll number (US/Canada)
Access code: 161 186 6167



This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* AOB. 


Notice that we aim to record the meeting.

# Attendees

* Barry Leiba
* Ines Robles
* Carsten Bormann
* Marco Tiloca
* Russ Housley
* Henk Birkholz
* Toerless 
* Dave Thaler 
* Francesca Palombini
* Carles Gomez
* Alexey Melnikov
* Samita Chakrabarti




# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

MCR thinks that all documents are finally processed through the RFC-editor.

## 6lo (Carles Gomez / Shwetha Bhandari)

6lo session scheduled for IETF 111

1 new RFC (RFC 9034):
      - Packet Delivery Deadline Time in 6LoWPAN Routing Header

The (4) WG documents are in advanced stages:

  2 documents (IESG evaluated):
      - IPv6 over NFC 
      - IPv6 mesh over BLE

  2 other active WG documents:
      - IPv6 over PLC (pre-IESG reviews addressed)
      - Use cases (2nd WGLC almost passed)

For the first time in several years, most time in the next meeting will be dedicated to new work:
    - Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-gomez-6lo-schc-15dot4-00)
    - Native Short Address for Internet Expansion (draft-li-native-short-address-00)
    - Fragment forwarding and FEC (draft to be uploaded)
    



## ACE (Daniel Migault / Loganaden Velvindron)

Framework and DTLS Profile "almost done"

## ANIMA (Sheng Jiang / Toeless Eckert)

Charter round 1 completed after IETF110, 8 RFC total, ca. 450 pages.
- ANI - Autonomic Networking Infrastructure (ACP, BRSKI/Voucher, GRASP)
- RFC8366, RFC8368
- RFC8990, RFC8991, RFC8992, RFC8993, RFC8994, RFC8995 (May 2021)

Ongoing / proposed WG work items
- Extensions to ANI and its components including adaptations for constrained deployments
- Autonomic Service Agents (ASA) - Network and Security automation using ANI
- Weekly meeting for work on constrained Bootstrap (BRSKI)
- 7 WG drafts, 10 new drafts

Hackathon in constrained BRSKI this week (before IEF111)
- for details, visit: https://docs.google.com/document/d/1T8Rtfk1zia_p05_6eb_WQA2Mmid-eP1-cAgnwdpF9Xk/edit?usp=sharing

Adjacency to NMRG Intent Based Networking work
- Intent as target highest layer in network automation (RFC7575/RFC8993)

## ASDF (Michael Richardson / Niklas Widell)

There are [hackathon efforts][asdfhack] this week.
An implementation draft, called "SDF 1.1" was declared at a virtual interim a few months ago.
No meeting is planned for ASDF at IETF 111.

[asdfhack]: https://codimd.ietf.org/hackathon-2021-t2trg-111-monday

## CBOR (Barry Leiba / Christian Amsüss)

Published RFC 9090 (CBOR Tags for Object Identifiers).

Three documents about to leave the working group:
- draft-ietf-cbor-cddl-control
- draft-ietf-cbor-file-magic (in WGLC)
- draft-ietf-cbor-network-addresses (in WGLC)

Regular progress in bi-weekly conference calls.
This is a happy, friendly working group.  :-)

## CoRE (Jaime Jimenez / Marco Tiloca)

RFC 9039 published in June, on Uniform Resource Names for Device Identifiers.

16 WG document, of which:
- 3 approved and in Editor's Queue (new-block, resource-directory, senml-versions)
- 1 approved and in AD Followup (echo-request-tag)
- 2 in IESG evaluation (Coreconf documents "yang-cbor" and "sid")
- 1 with publication requested (senml-data-ct)
- 2 expected to leave the WG soon (remaining Coreconf documents)

Ongoing work and new proposals on:
- Constrained Resource Identifiers
- Resource Linking and Transport Indication
- Group communication and its security with Group OSCORE
- Methods related to using Proxies, OSCORE and EDHOC

We had 6 biweekly virtual Interim meetings since IETF 110, plus design meetings especially on Constrained Resource Identifiers.

CoRE will meet at IETF 111. A series of 4 biweekly interim meetings is planned starting from mid-September.

## COSE (Matt Miller / Ivaylo Petrov)

9052-to-be and 9053-to-be (8152bis) in AUTH48 🎉

## DetNet (Lou Berger / János Farkas)

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)

* moved to a conflict with secdispatch (blame Henk)
* ~75min of agenda are set up already (5 presentations on prelim agenda)
* 3 native I-Ds now related via DT (plus a recent one that does not fit regex)

## LAKE (Mališa Vučinić / Stephen Farrell)


## LWIG (Mohit Sethi / Zhen Cao)


## LPWAN (Alex Pelov / Pascal Thubert)


## RATS (Kathleen/ Nancy / Ned)


## ROLL (Dominique Barthel / Ines Robles)

* ROLL will not meet at IETF 111
* Interim meeting will happen on 31th August
* Authors working on draft-ietf-roll-aodv-rpl after IESG evaluation 
* Submitted to IESG: nsa-extension
* New work to be considered:  draft-iwanicki-roll-rnfd (Fast border router crash detection in RPL)
* **Looking for reviewers for dao-projection, enrollment-priority, mopex**


## SUIT (Dave Thaler / David Waltermire / Russ Housley)

* SUIT architecture is now RFC 9019
* SUIT information model in RFC Editor queue: draft-ietf-suit-information-model-13
* SUIT manifest just about ready for WGLC: draft-ietf-suit-manifest-14
* Adopted reporting document as separate doc, to not delay main mainfest doc
* Just adopted firmware encryption extension as separate doc for same reason
* Working on recharter text so can adopt MUD document (draft-moran-suit-mud-02)
* Hackathon 111 working on integrating SUIT + TEEP


## TEEP (Tiru Reddy / Nancy Cam-Winget)

Architecture (draft-ietf-teep-architecture-15) & transport (draft-ietf-teep-otrp-over-http-11) documents waiting for doc shepherd to submit to IESG
Protocol document (draft-ietf-teep-protocol-06) collecting implementation experience
Hackathon 111 working on integrating TEEP + SUIT + RATS

## T2TRG (Ari Keränen / Carsten Bormann)

T2TRG already had its summer meeting on June 21st, before summer solstice.

Interaction is ongoing with and reports were received from OneDM One Data Model, W3C WoT, as well as from two research group documents: [IoT Edge Challenges and Functions][Edge] is nearing completion, and Initial Security Setup (was security bootstrapping) is awaiting a late-stage restructuring.

[Edge]: https://datatracker.ietf.org/doc/draft-irtf-t2trg-iot-edge/

WISHI is keeping contact with ecosystems that could interact with ASDF's SDF, including Azure DTDL.

SDF conversion and processing will be a subject for a 111 Hackathon project, which kicked off at 1400Z today.

An academic workshop on **Descriptive Approaches to IoT Security, Network, and Application Configuration** (DAI-SNAC 2021) is being organized by T2TRG and W3C WoT people at ACM CoNEXT 2021, December 6.  More at <https://dai-snac21.hotcrp.com/>.
 

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## RAW (Rick Taylor / Eve Schooler)


## IotSF ManySecured WG

MCR: Created new mailing list, web site https://manysecured.net live now.  After Secure Useable Intranet Browser (SUIB) effort, next work item resolves around IoT device identity.

# New/planned IETF/IRTF IoT activities



# AOB

Request(Dave T, Toreless, Carsten): Add a list of SDOs in the IoT wiki, include SDOs that we are not familiar. If possible, associate the contact information for the particular SDO. This list is separate from the official IETF liaison list.
T2Trg also invites other SDO presentations time to time, but they don't have a standing list - only meeting minutes. 
Thought (Samita): IOT-DIR can co-ordinate with T2Trg and point to their SDO presentations/contact in addition to IoT-DIR SDO list

Survey Results: https://github.com/iot-dir/SurveyResults
