# IoT directorate IETF 118 pre-meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keranen


Date: 30th October
Time: 5pm UTC

## Note Well 

This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* New/planned IETF/IRTF IoT activities
* Other IoT SDOs update/activities (if applicable, e.g. IoTSF, etc. )
* AOB. 


Notice that we aim to record the meeting.

# Attendees

* Please add your name here
* Ines Robles
* Carsten Bormann
* <del>Christian Amsuss</del> can't join because WebEx apparently once more reduced the set of devices they choose to support. Can we just have future incarnations of this on Meetecho?
* Marco Tiloca
* Carles Gomez
* Michael Richardson
* Erik Kline
* Samita Chakrabarti
* Éric Vyncke (part-time)

# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

6TiSCH is closed


## 6lo (Carles Gomez / Shwetha Bhandari)

6lo will meet in the next IETF

* New RFC: RFC 9453 - 6lo applicability and use cases

* 4 WG documents:

  * Submitted to IESG for publication (AD evaluation):
      * IPv6 Neighbor Discovery Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-15)
                 
  * Other WG documents:
        
     * Path-Aware Semantic Addressing (PASA) for Low power and Lossy Networks (draft-ietf-6lo-path-aware-semantic-addressing-03) 
    
     * Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-ietf-6lo-schc-15dot4-04) 

     * IPv6 Neighbor Discovery Prefix Registration (draft-ietf-6lo-prefix-registration-01)  
          
* 2 individual documents to be presented:

  * Generic Address Assignment Option for 6LowPAN Neighbor Discovery (draft-iannone-6lo-nd-gaao-01)   
    
  * Transmission of IPv6 Packets over Short-Range Optical Wireless Communications (draft-choi-6lo-owc-01)
   

## ACE (Loganaden Velvindron / Tim Hollebeek)

ACE changed chair

## ANIMA (Sheng Jiang / Toerless Eckert)

Many documents in WGLC, coordination with RFC8366bis publication.
Many review comments being addressed.   Will leave WG as a group.

## ASDF (Michael Richardson / Niklas Widell)

Finishing touches on main deliverable asdf-sdf
IETF 118: additional documents -- rechartering?

## CBOR (Barry Leiba / Christian Amsüss)

cbor-time-tag-12 just submitted, all but completed IESG processing
WGLC for cbor-edn-literals and cbor-update-8610-grammar (CBOR "languages" EDN and CDDL), end Mon 2023-11-06
CDDL2 work on modules stable; waiting for implementer feedback; could WGLC soon
cbor-packed under active discussion, lenders-dns-cbor as a use case
complete CDE as a step toward deterministic encoding profiles?

## CoRE (Jaime Jimenez / Marco Tiloca / Carsten Bormann)

* 1 document approved for publication (Informational)
    * -core-target-attr

* 1 document in IESG processing (Proposed Standard)
    * -core-sid

* 1 document in IETF Last Call (Proposed Standard)
    * -core-oscore-edhoc

* Among the WG documents:
    * 2 waiting for Shepherd Write-up (-core-oscore-groupcomm; -core-yang-library)
    * 4 completed WGLC (-core-groupcomm-bis; -core-comi; -core-href; -core-conditional-attributes)

* Selected ongoing activities
    * Major work on the CORECONF documents
        * -core-sid (that came back to the WG) in IESG processing 
        * in parallel with -core-comi, remaining WG work
        * held back by required tools work
    * Addressed AD Review of -core-oscore-edhoc
    * Worked especially on: pub-sub architecture for CoAP; group communication for CoAP; constrained Resource identifiers (HREF); key update for OSCORE (KUDOS)

* New WG documents
    * -core-oscore-capable-proxies

* Since IETF 117
    - Regular biweekly interim meetings
    - Recurring design meetings (HREF & CoRAL)

* CoRE will meet at IETF 118, in a 2-hour session.

* Next interim meetings (alternating with CBOR)
    * 2023-11-22, 15:00-16:30 UTC
    * 2023-12-06, 15:00-16:30 UTC (if need be)
    * 2024-01-17, 15:00-16:30 UTC
    * (then same time, every other Wednesday, ...)
    * 2024-02-28, 15:00-16:30 UTC

## COSE (Matt Miller / Ivaylo Petrov)


## DetNet (Lou Berger / János Farkas)

* RAW WG has been folded to DetNet WG. DetNet charter being updated accordingly. Draft charter https://datatracker.ietf.org/wg/detnet/about/ (on agenda of 2023-11-30 IESG telechat)
* Main RAW work item is draft-ietf-raw-architecture; another WGLC expected.
* Open working meetings on enhanced DetNet data plane are onginig: https://wiki.ietf.org/en/group/detnet/wmosq. Scaling requirements (draft-ietf-detnet-scaling-requirements) are being refined, queuing solution proposals are being evaluated.

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)


## LAKE (Mališa Vučinić / Stephen Farrell)


## LWIG (Mohit Sethi / Zhen Cao)

* Going to close LWIG in Prague
* Only [draft-ietf-lwig-curve-representations](https://datatracker.ietf.org/doc/draft-ietf-lwig-curve-representations/) remains
    * No update from the author since 2022.01
    * Any updates can be handled separately

## RATS (Kathleen/ Nancy / Ned)

MCR: surprise IAB statement regarding the RATS community. Follow-up will be scheduled
    Tommy Pauly <tpauly@apple.com> wrote:
    > We’ve currently slotted this in for our Tuesday morning meeting at
    > 8-9:30am Prague time, in the Florenc 1/2 room. We’d appreciate if
    > people can join us for the discussion there!

## RAW (Rick Taylor / Eve Schooler)
Concluded WG --> DETNET

## ROLL (Dominique Barthel / Ines Robles)

Roll will meet at IETF 118, 1h slot

Submitted to the IESG:
* draft-ietf-roll-aodv-rpl
* draft-ietf-roll-dao-projection

In Progress:

* draft-ietf-roll-enrollment-priority-09
* draft-ietf-roll-mopex-07
* draft-ietf-roll-rnfd-02: Reviews needed. 
* draft-ietf-roll-nsa-extension

Planned Interim Meetings, every two month

## SCHC (Alexander Pelov / Pascal Thubert)

> A lot of work around the [architecture](https://datatracker.ietf.org/doc/draft-ietf-schc-architecture/) and how to transport SCHC over Ethernet or IP.
> [name=éric vyncke]

## SCITT - Supply Chain Integrity, Transparency, and Trust (Hannes Tschofenig/ Jon Geater)

## SUIT (Dave Thaler / David Waltermire / Russ Housley)


## TEEP (Tiru Reddy / Nancy Cam-Winget)


# IRTF

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## T2TRG (Ari Keränen / Carsten Bormann)

Work meeting Fri 2023-11-03 at Prague Hilton, Florenc 1/2.
<https://github.com/t2trg/2023-11-prague>

* Security: 3 active documents, security levels for time, secure discovery
* Foundations: layered self-descriptions; Non-IP nodes

(Note that the discovery/self-description/non-IP points share a theme of naming and identity)

# New/planned IETF/IRTF IoT activities
SPICE BOF at Prague IETF in Nov

# AOB
