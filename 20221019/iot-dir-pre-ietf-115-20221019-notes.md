# IoT directorate IETF 115 pre-meeting 

Link to video recording: It will be added later

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keränen

* Date: 19th Oct 2022
* Time: 15:00 - 16:30 UTC

## Note Well 

This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* New/planned IETF/IRTF IoT activities
* Other IoT Work: IoTSF, etc.
* Inter-WG coordination requirements for any drafts and reviews
* AOB. 


Notice that we aim to record the meeting.

# Attendees

Please add your name here

* Marco Tiloca, RISE
* Carsten Bormann, TZI
* Barry Leiba, Futurewei
* Éric Vyncke, Cisco
* Carles Gomez
* Dave Thaler
* Janos Farkas
* Michael R
* Pascal T
* Samita C
* Stephen F
* Thomas F
* Toerless E
* Ines Robles

# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)


## 6lo (Carles Gomez / Shwetha Bhandari)

6lo will meet in IETF 115 (90-min session)

RFC Editor queue:
* IPv6 over PLC (draft-ietf-6lo-plc-11)

3 other WG documents:

* 1 document evaluated by the IESG:
     * IPv6 over NFC (draft-ietf-6lo-nfc-17) 
       
* Pre-IESG evaluation:
     * Use cases draft (draft-ietf-6lo-use-cases-13) 
                   
* WG document:
   * IPv6 Neighbor Discovery Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-10)
     * New "Node Uptime Option": extract to a separate draft? (awaiting feedback from 6man)
                   
Individual documents:

  * Native Short Address for Internet Expansion 
         (draft-li-native-short-address-03, draft-li-6lo-nsa-reliability-00)
       * Call for adoption outcome: not adopted, but apparent consensus on how to modify it

  * Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-gomez-6lo-schc-15dot4-03) 
     
  * IPv6 Neighbor Discovery Prefix Registration (draft-thubert-6lo-prefix-registration-01)
   
      


## ACE (Daniel Migault / Loganaden Velvindron)

## ANIMA (Sheng Jiang / Toerless Eckert)

Business as usual. Happy to get more reviewers. Could ask authors to reach out to IoT dir. Change of affiliation for co-chair. Gives more diversity. 


## ASDF (Michael Richardson / Niklas Widell)

ASDF has not met since before IETF114 due to time pressure on the participants.

CB: ASDF is sister group to OneDM (outside of IETF). Working on requirements for the SDF spec. Still ongoing, expect something out of that in IETF 115 time frame, but maybe not early enough for the meeting itself.



## CBOR (Barry Leiba / Christian Amsüss)

BL: CBOR finisihng work on a few docs. Looking at DNS with CBOR. Also CDDL 2.0 work getting started. Will be meeting at 115 Thursday. 


## CoRE (Jaime Jimenez / Marco Tiloca / Carsten Bormann)

* 1 RFC published since July
    * RFC 9254 - yang-cbor from the CORECONF cluster

* 1 document in the Editor's queue (RFC-EDITOR)
    * -core-problem-details - approved in July

* 1 document in IESG evaluation
    * -core-sid from the CORECONF cluster

* Among the WG documents:
    * 1 under Shepherd Write-up (Group OSCORE)
    * 2 in WGLC (-core-groupcomm-bis; -core-conditional-attributes)
    * 1 recently adopted: "DNS over CoAP (DoC)"

* Selected ongoing activities
    * Constrained Resource Identifiers (HREF)
    * Group communication (obsoleting RFC 7390; group communication security with Group OSCORE; support from proxies)
    * Works related to OSCORE (key update procedure KUDOS; optimized combination with EDHOC; OSCORE at proxies and nested OSCORE protection)

* Since IETF 114
    - Regular biweekly interim meetings
    - Recurring design meetings about HREF & CoRAL

CoRE will meet at IETF 115, in a 2 hour session.

## COSE (Matt Miller / Ivaylo Petrov)


## DetNet (Lou Berger / János Farkas)
Updated charter approved: https://datatracker.ietf.org/doc/charter-ietf-detnet/

WG last call concluded on https://datatracker.ietf.org/doc/draft-ietf-detnet-oam-framework/

WG last call ongoing on https://datatracker.ietf.org/doc/draft-ietf-detnet-mpls-oam/

Individual draft on new requirements: https://datatracker.ietf.org/doc/draft-liu-detnet-large-scale-requirements/

Good for others beyond the group to take a look. If have other cases in mind that are not addressed, good to add. Gist for new requirements is having bigger networks and admin domains. Addressing issues with long cables and large number of nodes. Coming from telco environ.
TE: wide area reqs, and TSN was assuming time synch is easy to do. Links being perfectly well and no jitter. Don't apply in metro networks. 


## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)


## LAKE (Mališa Vučinić / Stephen Farrell)

* EDHOC is now in working group last call
    * comments deadline 4 November 2022
* LAKE @ IETF 115 meeting is on Tuesday of the IETF week


## LWIG (Mohit Sethi / Zhen Cao)

CB: LWIG has number of projects but not making progress now. Wonder if need to find new home for remaining work items. Maybe IoTops the place or some other group?

IR: Have discussed with Henk?

CB: not yet

SC: could discuss here?

CB: AD thoughts?

EV: Erik Kline, INT AD, is responsible AD for LWIG

## LPWAN (Alex Pelov / Pascal Thubert)

Two docs well progressed in queue: YANG data model and SCHC over NB-IoT well advanced. For the nb-iot I-D, issued a [liaison statement](https://datatracker.ietf.org/liaison/1796/) with 3GPP; standard tracks for one part and informational for the 3GPP parts (this is clearly marked in the I-D). Now working on architecture, how to generalize SCHC for media where media is not based on point-to-point. If do over mesh, need to notify who is who, etc.

SC: liaison to 3GPP possible to share?

PT: Published at IETF site. Can copy link here.

EV: https://datatracker.ietf.org/liaison/1796/


## RATS (Kathleen/ Nancy / Ned)

* Monday 2h slot at IETF 115
* Arch draft and CHARRA (format for refence values) draft submitted to IESG, now in RFC editor Q
* EAT in WGLC
* EAT media types and CORIM went through calls for adoption

## RAW (Rick Taylor / Eve Schooler)


JF: (reporting on behalf of chairs

) one doc in IESG, couple of comments left. Following: use cases draft, submitted to IESG. Hot topic in WG is arch document. Very good draft by Pascal. Comments and updates needed to be addressed.

PT: replied to Lou on good comments; believe we're very close to agreement. In-line with comments and converging on what the doc shoul be.

## ROLL (Dominique Barthel / Ines Robles)

* Requested 1h timeslot at IETF 115
* DAO Projection ready, waiting for Shepherd document
* AODV-RPL new version addressing last comments
* RNFD - Fast border router crash detection in RPL - active, needs review 


## SUIT (Dave Thaler / David Waltermire / Russ Housley)

* Meeting WED 13:00-14:30 at IETF 115
* Manifest spec went through LC and close to IESG submission
* Some parts previously split into separate docs to allow main spec to progress
* Discussion thus focusing on the extensions
* Incorporating feedback from TEEP WG

## TEEP (Tiru Reddy / Nancy Cam-Winget)

* Uses RATS (EAT) and SUIT (manifest) to manage/remediate TEEs
* Meeting WED 15:00-16:30 at IETF 115, right after SUIThttps://datatracker.ietf.org/doc/draft-wallace-rats-concise-ta-stores/
* Architecture draft went through IESG, updating to address ballot comments
* HTTP transport doc waiting for protocol doc but addressed GENART, ARTART review comments
* Protocol doc addressing implementation comments
* Expect to have another active hackathon discussion at 115

# IRTF

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## T2TRG (Ari Keränen / Carsten Bormann)

Not meeting at IETF 115; planning for a summary meeting later (details TBD).
IoT Edge: shepherd TBD
RESTful IoT: last updates TBD before RGLC


# New/planned IETF/IRTF IoT activities

Stub Network Auto Configuration for IPv6 [SNAC](https://datatracker.ietf.org/wg/snac/about/) new WG about stub networks (e.g., IEEE 802.15.4) connecting to 'normal' home network (e.g., IEEE 802.11). With some links to Matter.



# Other IoT Work: IoTSF, etc.

IoTSF: Conference last week


AK: Matter has published [1.0 spec](https://csa-iot.org/developer-resource/specifications-download-request/)

MR: issues in the Matter spec, like not not using TLS (at least earlier spec). Inventing their own security. No guard against bid-down attack. Only way to go for stronger sec is replacing all devices

CB: re-inventing seems to be at play



# Inter-WG coordination requirements for any drafts and reviews

https://datatracker.ietf.org/doc/draft-wallace-rats-concise-ta-stores/
being adopted in RATS and draft contains some RATS specific language, but really is not RATS specific.
Any WG that relies on having some trust anchor store should review.


# AOB
