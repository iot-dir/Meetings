
# IoT directorate IETF 114 pre-meeting 

Source: https://notes.ietf.org/iot-dir-preIETF114meeting-2022-06-22-notes?both

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keränen


Date: 22th June
Time: 4pm - 5:30pm UTC

## Meeting Details 




This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* Other IoT Work: IoTSF, etc.
* How to facilitate the input of other IoT SDOs into the IETF?
* AOB. 


Notice that we aim to record the meeting.

# Attendees

Please add your name here

* Ines Robles
* Carsten Bromann
* Marco Tiloca
* Janos Farkas
* Samita Chakrabarti
* Dominique Barthel
* Emmanuel Baccelli
* Malisa Vucinic
* Hannes Tschofenig
* Russ Housley
* Janos Farkas
* Eric V.
* Thomas F.



# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)


## 6lo (Carles Gomez / Shwetha Bhandari)

* 6lo will meet in the next IETF (1 hour)

* 4 WG documents:

  * 2 documents evaluated by the IESG:
      - IPv6 over NFC (draft-ietf-6lo-nfc-17)
      - IPv6 over PLC (draft-ietf-6lo-plc-11)

  * Pre-IESG evaluation:
      - Use cases draft (draft-ietf-6lo-use-cases-12) --> will be updated before IETF 114
            
  * Progressing:
      - IPv6 Neighbor Discovery Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-07)
            - Enables a listener to subscribe to an IPv6 multicast or anycast address
            - Adds a new RPL Non-Storing multicast mode and support for anycast
            - Will be presented at IETF 114 in 6lo, ROLL and 6MAN

* Individual documents:

  * 2 drafts focusing on or including header compression functionality:
    - Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-gomez-6lo-schc-15dot4-02) --> will be updated before IETF 114
    - Native Short Address for Internet Expansion (draft-li-native-short-address-03) 
          - Includes stateless forwarding
      Companion document will also be discussed:
          - draft-li-nsa-reliability-00

## ACE (Daniel Migault / Loganaden Velvindron)

## ANIMA (Sheng Jiang / Toeless Eckert)


## ASDF (Michael Richardson / Niklas Widell)

## CBOR (Barry Leiba / Christian Amsüss)


## CoRE (Jaime Jiménez / Marco Tiloca / Carsten Bormann)

* 3 RFCs published since March
    * RFC 9176 - CoRE Resource Directory
    * RFC 9177 - CoAP block-wise transfer for robust transmission
    * RFC 9193 - SenML Data Content-Format Indication

* 1 document in the Editor's queue (RFC-EDITOR)
    * yang-cbor from the CORECONF cluster (approved in April)

* 2 documents in IESG evaluation
    * core-sid from the CORECONF cluster
    * problem-details

* 11 more WG documents, of which
    * 1 under Shepherd Write-up (Group OSCORE)
    * 2 in WGLC (Groupcomm-bis for CoAP; conditional-attributes)
    * 2 recently adopted (transport-indication, attacks-on-coap)

* Selected ongoing activities
    * Lot of intense and focused work on concise problem details as needed by 3GPP
    * Constrained Resource Identifiers (HREF) & RESTful application language CoRAL
    * Group communication (obsoleting RFC 7390, security with Group OSCORE, support from proxies)
    * Works related to OSCORE (key update procedure KUDOS, optimized combination with EDHOC)

* Since IETF 113
    - Regular biweekly interim meetings
    - Recurring design meetings about HREF & CoRAL and problem-details

CoRE will meet at IETF 114, in a 2 hour session.

We plan to resume with biweekly interim meetings after summer.

## COSE (Matt Miller / Ivaylo Petrov)


## DetNet (Lou Berger / János Farkas)
Charter extension for enhanced data plane solutions pending approval.
Draft charter: https://datatracker.ietf.org/doc/charter-ietf-detnet/
Updated milestones: https://datatracker.ietf.org/wg/detnet/about/

Samita: OPC-UA running on DETNET, no need of TSN ?
Janos: TSN is one option but detnet is deisgned to run without running TSN underneath. The new charter extension to follow.

## IOTOPS (IoT Operations) (Alexey Melnikov, Henk Birkholz)


## LAKE (Mališa Vučinić / Stephen Farrell)

* EDHOC under formal review by the academic community
    * Spec was frozen until mid-May
    * New version (-14) of EDHOC includes substantial changes, includes first feedback from the formal analysis
* 1-hour meeting at IETF 114

## LWIG (Mohit Sethi / Zhen Cao)

7228bis on WG adoption: comments needed

## LPWAN (Alex Pelov / Pascal Thubert)

* SCHC YANG data model
* SCHC compound ACK: an extension to the protocol
* SCHC over sigfox
* SCHC over NB-IoT
* new topic: IP protocol number for SCHC

## RATS (Kathleen/ Nancy / Ned)


## RAW (Rick Taylor / Eve Schooler)
Two interim meetings before IETF 114 to work on the architecture document ( Comment from Janos). The LDACS document provides roadmap for aeronautical technologies that are defined outside IETFS


## ROLL (Dominique Barthel / Ines Robles)
Interim meeting on 27th June  
Requested 1 hour slot in IETF 114
DAO Projection in WGLC
AODV-RPL needs feedback from WG, please review 
In Progress: enrollment-priority; draft-ietf-roll-rnfd
Addressing feedback of IESG: draft-ietf-roll-nsa-extension
Joint meeting with MANET, ANIMA in multicast



## SUIT (Dave Thaler / David Waltermire / Russ Housley)

Recharter is complete, which will allow the SUIT WG to include support for MUD.  See draft-ietf-suit-mud-00.

Progress is slow on breaking the manifest document into a base document and several ones that are needed to address various optional features.

## TEEP (Tiru Reddy / Nancy Cam-Winget)



# IRTF

## COIN (Jeffrey He / Eve Schooler / Marie-José Montpetit)


## T2TRG (Ari Keränen / Carsten Bormann)

Not planning to meet at the IETF 114 but planning to have a summary meeting after the IETF meeting.

The "IoT Edge Challenges and Functions" [draft](https://www.ietf.org/archive/id/draft-irtf-t2trg-iot-edge-06.html) RG last call ended June 13th (TBD).

The "Guidance on RESTful Design for Internet of Things Systems" [draft](https://www.ietf.org/archive/id/draft-irtf-t2trg-rest-iot-09.html) is being [updated](https://github.com/t2trg/t2trg-rest-iot/pulls) to address the chair review comments (and a detailed review by authors).

Arranged [work meeting on Digital Twins and IETF IoT technologies](https://github.com/t2trg/2022-05-digital-twins) where we explored the state of applicability of IETF technologies in building Digital Twins, with a view to identifying gaps for further standardization development at the IETF and research opportunities at the IRTF.

Arranged WISHI meeting to discuss "IoT Information-Model Standards Description" [work](https://github.com/t2trg/semantic-landscape) and started two new activities: documenting learnings from data model versioning and collecting proposals for relation information design for SDF.


# New/planned IETF/IRTF IoT activities

## SCITT

Bof: SCITT- Supply Chain integrity Transparency(?)-transparent description of items of supply chains. 

Hannes Tschofenig: Mailing list is here: https://www.ietf.org/mailman/listinfo/scitt

Hannes Tschofenig: Slides and recordings have been posted, in case you missed it: https://mailarchive.ietf.org/arch/msg/scitt/Kd_npgmv7BS0P-TBi8ZJ1t1p8d4/


# Other IoT Work: IoTSF, etc.

# How to facilitate the input of other IoT SDOs into the IETF?

# AOB
