
# IoT directorate IETF 116 pre-meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keränen


Date: 2023-03-21
Time: 2pm UTC

## Meeting Details 



https://ietf.webex.com/ietf/j.php?MTID=m64155da8302c6bd59df28867bdc25d11
Meeting number: 2436 810 9909
Password: CdmBJEcA683
Join by video system
Dial 24368109909@ietf.webex.com
You can also dial 173.243.2.68 and enter your meeting number.
Join by phone
1-650-479-3208 Call-in toll number (US/Canada)
Access code: 243 681 09909

## Note Well

This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* New/planned IETF/IRTF IoT activities
* Updates on 5G-ACIA (Samita)
* Other IoT SDOs update/activities (if applicable, e.g. IoTSF, etc. )
* AOB. 


Notice that we aim to record the meeting.

# Attendees

* Please add your name here

Marco Tiloca, RISE
Carsten Bormann, Universität Bremen TZI
Erik Kline, Aalyria (~30min only)
Dominique Barthel, self
Carles Gomez, UPC
Emmanuel Baccelli, Inria / FU Berlin
Behcet Sarikaya
Erik Nordmark
János Farkas 
Marco Tiloca
Pascal Thubert
Samita Chakrabarti


# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

WG kept it open in case new work comes up. 
E.g. This might happen once RAW has progressed to the point that it requires interfaces that 6TiSCH can implement in the 802.15.4 TSCH case.
Source: https://mailarchive.ietf.org/arch/msg/6tisch/hOqPVIE3vO31eHLb7inR1-hPqKw/



## 6lo (Carles Gomez / Shwetha Bhandari)

* 6lo will meet in the next IETF

* New RFC: RFC 9354 - IPv6 over PLC

* 5 WG documents (2 recently adopted ones):

  * RFC Editor queue:
	* IPv6 over NFC (draft-ietf-6lo-nfc-22) 

  * IESG evaluation:
    * Use cases draft (draft-ietf-6lo-use-cases-15) 
          - Recently updated, no remaining DISCUSS ballots
            
  * Other WG documents:
    * IPv6 Neighbor Discovery Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-14)
          - Enables a listener to subscribe to an IPv6 multicast or anycast address
          - Adds a new RPL Non-Storing multicast mode and support for anycast
          - Pending shepherd writeup
                   
    * Path-Aware Semantic Addressing (PASA) for Low power and Lossy Networks (draft-ietf-6lo-path-aware-semantic-addressing-00) 
          - Includes stateless forwarding, header compression, for stable topologies

    * Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-ietf-6lo-schc-15dot4-01) 
          
* 2 individual documents:
    * PASA Reliability (draft-li-6lo-pasa-reliability-01)
   
    * IPv6 Neighbor Discovery Prefix Registration (draft-thubert-6lo-prefix-registration-02) 

## ACE (Daniel Migault / Loganaden Velvindron)

## ANIMA (Sheng Jiang / Toerless Eckert)

## ASDF (Michael Richardson / Niklas Widell)
not meeting at IETF116, but will work at hackathon

## CBOR (Barry Leiba / Christian Amsüss)

Slow ongoing activity around expressing details on time, and on packed (which is about using tags from external or ad-hoc dictionaries, while maintaining usability without an uncompression step).

Most interim and upcoming activity on "CDDL 2", which is currently being dissected into drafts with different compatibility properties. Quoting [the roadmap](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html) document:
* Done before IETF 117: CDDL 1.1: [I-D.bormann-cbor-update-8610-grammar](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html#I-D.bormann-cbor-update-8610-grammar), Grammar fixes: Empty files (enabling CDDL 2), non-literal tags, errata fixes (implemented)
* Done before IETF 117: Parallel to CDDL 1.1: More control operators [I-D.bormann-cbor-cddl-more-control](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html#I-D.bormann-cbor-cddl-more-control): Additional control operators, another iteration like RFC 9165 (implemented)
* Done before IETF 118: CDDL 2.0: [I-D.bormann-cbor-cddl-modules](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html#I-D.bormann-cbor-cddl-modules) (import/include implemented; potentially further directives to be added)
* Done 2024: CDDL 2.5: Section 3 of [the roadmap](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html) ("annotations", plus some functionality enabled by that). The requirements are clear, the specific form this takes needs to be worked out. Enables, e.g., Section 5 of [I-D.bormann-cbor-cddl-freezer](https://www.ietf.org/archive/id/draft-bormann-cbor-cddl-2-draft-02.html#I-D.bormann-cbor-cddl-freezer) (co-occurrence).


## CoRE (Jaime Jiménez / Marco Tiloca / Carsten Bormann)

* 1 document in IESG evaluation
    * -core-sid from the CORECONF cluster

* 1 document submitted to the IESG for publication
    * -core-target-attr

* Among the WG documents:
    * 3 waiting for Shepherd Write-up (-core-comi; -core-yang-library; -core-oscore-groupcomm)
    * 3 past WGLC (-core-groupcomm-bis; -core-conditional-attributes; -core-oscore-edhoc)

* Selected ongoing activities
    * Advancing the CORECONF cluster
    * Constrained Resource Identifiers (HREF)
    * Pub-sub architecture for CoAP
    * Works related to OSCORE (key update KUDOS; optimized workflow for EDHOC; OSCORE at proxies and nested OSCORE protection)
    * Performance measurement for CoAP (building on IPPM work)
    * CoAP over Bluetooth GATT

* Since IETF 115
    - Regular biweekly interim meetings
    - Recurring design meetings (HREF & CoRAL; pub-sub)

* CoRE will meet at IETF 116, in a 2 hour session.

* We plan to resume biweekly interim meetings in April.

## COSE (Matt Miller / Ivaylo Petrov)


## DetNet (Lou Berger / János Farkas)

* OAM framework and MPLS OAM drafts concluded WGLC
* draft-ietf-detnet-scaling-requirements adopted; new requirements for larger networks
* had two interims on queueing for DetNet
* open working meetings on queueing to be conducted after IETF 116 every other week

Samita: applications for scaling draft?
Janos: Service Provider's networks. The proposal was brought to IETF by China Mobile

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)


## LAKE (Mališa Vučinić / Stephen Farrell)


## LWIG (Mohit Sethi / Zhen Cao)

Erik: After Curve registrations going to IESG
intent is to close the WG
Existing work items to move to IOTOPS after charter congruence assured


## LPWAN / SCHC (Alex Pelov / Pascal Thubert)

The LPWAN WG will become the SCHC WG during IETF 116. 
The SCHC WG will continue the active tasks of LPWAN, and then start using SCHC in larger context than just LPWANs.

The WG will work on:

1) Perform SCHC Maintenance, including enabling SCHC mechanisms for Upper layer
Protocols, and providing additional reliability mechanisms such as FEC for
fragments.

2) Produce a Standards Track document to enable Operations, Administration, and
Maintenance (OAM), including support for delayed (as some devices can be
asleep) or proxied (via the gateway) reachability verification.

3) Produce Standard Track documents for SCHC over underlying layers and carried
protocols over SCHC where underlying layers includes but is not limited to IP,
UDP tunnels, PPP, and Ethernet and carried protocols may include IPv4,
ICMPv6-based protocols, TCP, IP tunnels, DLMS, and other protocols over CoAP
such as LwM2M; define and maintain data models for the protocols supported by
SCHC.

4) Produce an informational document describing how a carried protocol can use
SCHC.

5) Define in a Standard Track document the SCHC Protocol Header to convey SCHC
Session Info over IP

6) Produce Standard Track documents for SCHC Rule Discovery and Parameter
Negotiation, including the specification of how work from the IETF security
area is leveraged to secure these operations

7) Produce Standard Track documents for SCHC Rule Provisioning, including the
specification of generic SCHC rules that can be instantiated, e.g., to apply to
a certain node or within a certain network.



More at the [SCHC datatracker page](https://datatracker.ietf.org/doc/charter-ietf-schc/)

## RATS (Kathleen/ Nancy / Ned)


## RAW (Rick Taylor / Eve Schooler)


## ROLL (Dominique Barthel / Ines Robles)
WG charter: extensions and maintenance of RPL (IPv6 Routing Protocol for Low-power and lossy networks).
IETF116: 1h slot on Tuesday.
Status of active drafts
- AODV-RPL (AODV flavour of RPL): was returned to WG from IESG eval, new WGLC just elapsed.
- DAO-Projection (centralized PCE injection of routes into RPL): ready, on rtg directorate review
- MOPEX (extension of Mode of Operation field of RPL): ready for WGLC
- RNFD (Fast border router crash detection in RPL): work on-going
- NSA-Extension (objective function and metric container for path selection based on ancestor list): returned to WG, addressing issues from AD.

Longer term vision: prune original RPL from unused options and combine recent extensions to produce a RPLv2 spec.

## SUIT (Dave Thaler / David Waltermire / Russ Housley)


## TEEP (Tiru Reddy / Nancy Cam-Winget)



# IRTF

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## T2TRG (Ari Keränen / Carsten Bormann)

Various documents in various stages:
* "[IoT edge challenges and functions](https://datatracker.ietf.org/doc/draft-irtf-t2trg-iot-edge/)" draft in IRSG review
* Adopted "[Amplification Attacks Using CoAP](https://datatracker.ietf.org/doc/draft-irtf-t2trg-amplification-attacks/)" and "[A Taxonomy of operational security considerations for manufacturer installed keys and Trust Anchors](https://datatracker.ietf.org/doc/draft-irtf-t2trg-taxonomy-manufacturer-anchors/)" drafts 
* "[Guidance on RESTful Design for Internet of Things Systems](https://datatracker.ietf.org/doc/draft-irtf-t2trg-rest-iot/)" and [Terminology and processes for initial security setup of IoT devices](https://datatracker.ietf.org/doc/draft-irtf-t2trg-secure-bootstrapping/)" drafts slowly getting mature and ready for publication.

Organized [summary interim meeting](https://github.com/t2trg/2022-12-summary) in December with security, data model, and digital twins topics. 

Not meeting at Yokohama. Hackathon [ASDF-focused activity](https://wiki.ietf.org/en/meeting/116/hackathon#:~:text=core%2Dgroupcomm%2Dbis-,ASDF%2DWISHI%2DT2TRG) to progress implementation efforts in the areas of data models for IoT devices and their interactions and to ascertain spec readiness for IESG submission. Early plans for a summary interim in mid-May.

Ines: follow-ups on digital twins work? 
Ari: slow-burner activity to figure out way forward with DTC proposal. Using SDF models for Digital Twins has been discussed many times and also presented at the RG.

Samita: anything written down on digital twins?
Ari: not yet, the presentations at the RG meetings are closest thing. Maybe worth writing something on this use in a draft form too.


# New/planned IETF/IRTF IoT activities


# Update on 5G-ACIA (Samita)

5G-ACIA ( 5G Alliance for Connected Industries & Automation: www.5g-acia.org) is a global association for understanding of 5G applicability on the modern Industrial Networks digitilization. The Industrial Operational Networks have different needs than regular IT communication networks. The smart manufacturing or process industry networks require high reliability, low latency, high security, high bandwidth in their networks. Wireless networks often pose challenges to these type of networks. 5G claims to have many of the properties including ultra-low latency, high bandwidth, in-built security, time synchronization and ability to support ethernet bridging over the 5G network. Samita does not see a direct co-relation between 5G-ACIA and IETF, though there might be some common interests in data modeling such as digital twins. Detnet applicability analysis in the industrial networks have been also analysed at 5G-ACIA. There might be some synergy with detnet upcoming draft on scaling.
Ari mentions SDF and NMRG are looking into Asset Administration Shells for future data modeling. The following document might be a useful reference.
White paper: https://5g-acia.org/whitepapers/using-digital-twins-to-integrate-5g-into-production-networks/

# Other IoT SDOs update/activities 

# AOB

