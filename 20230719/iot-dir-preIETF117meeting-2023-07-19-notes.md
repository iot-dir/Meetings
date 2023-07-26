# IoT directorate IETF 117 pre-meeting 
Source: https://notes.ietf.org/iot-dir-preIETF117meeting-2023-07-19-notes?both

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keranen
Date: 19-07-2023
Time: 2:00pm UTC

## Meeting Details 
This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

## Recording:
https://www.youtube.com/watch?v=dX7vAivc9nk

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* New/planned IETF/IRTF IoT activities
* Other IoT SDOs update/activities (if applicable, e.g. IoTSF, etc. )
* AOB. 

Notice that we aim to record the meeting.

# Attendees List

Please add your name here
* Ines Robles
* Behcet Sarikaya
* Christian Amsüss
* Erik Kline
* Carsten Bormann
* Marco Tiloca
* Mališa Vučinić
* Matthias Kovatsch
* Samita Chakrabarti
* Dominique Barthel


# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

 The group is terminating
 
## 6lo (Carles Gomez / Shwetha Bhandari)

* 2 WG documents in the RFC Editor queue:

    * IPv6 over NFC (draft-ietf-6lo-nfc-22) -AUTH48-DONE - RFC-to-be 9428
    * 6lo applicability and use cases (draft-ietf-6lo-use-cases-16) - RFC Editor

* 1 WG document - publication requested:

    * IPv6 ND Multicast Address Listener Subscription (draft-ietf-6lo-multicast-registration-15)

* 2 WG documents in earlier stages:

    * Path-Aware Semantic Addressing for LLNs (draft-ietf-6lo-path-aware-semantic-addressing-02)
    * Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-ietf-6lo-schc-15dot4-02)

* Individual documents:
    * IPv6 ND Prefix Registration (draft-thubert-6lo-prefix-registration-03)
        * Call for WG adoption in progress
    * Generic Address Assignment Option for 6LoWPAN ND (draft-iannone-6lo-nd-gaao-00)
        * New
    * Transmission of IPv6 packets over short-range Optical Wireless Communications (draft-choi-6lo-owc-00)
        * New



## ACE (Daniel Migault / Loganaden Velvindron)

## ANIMA (Sheng Jiang / Toerless Eckert)

Toerless: 7 WG drafts around various aspects of the BRSKI zero touch secure bootrap architecture. Strong ongoing work on the top documents via weekly meetings. A bit of constraints against author resources leaving some drafts on the back burner.

Did sort through some huge YANG related blocker around IETF117 (impossibility to spread YANG definitions across multiple documents), resulting in move of all YANG elements of the different drafts into common rfc8995bis, leading to most documents becoming another RFC clusteronce they finish. Now starting to tackle another common aspect of discovery/selection of these protocol variations (DNS/GRASP).

2 ASA (autonomic service agent) related drafts that need more work to progress to WGLC.

(CA's note because I can't access the chat:)
> "If you have similar problems on extending the YANG model, don't replicate our pains" -- too late :-)

## ASDF (Michael Richardson / Niklas Widell)

Not meeting at 117.  Finishing touches at document to do WGLC now, submitted 2023-07-10

A number of items will need rechartering.

## CBOR (Barry Leiba / Christian Amsüss)

* "CDDL 2.0" efforts are ongoing, with first drafts adopted (from [small fixes](https://datatracker.ietf.org/doc/draft-ietf-cbor-update-8610-grammar/) to [regular operator maintenance](https://datatracker.ietf.org/doc/draft-ietf-cbor-cddl-more-control/) up to [module structure](https://datatracker.ietf.org/doc/draft-ietf-cbor-cddl-modules/))

* The [Gordian efforts](https://datatracker.ietf.org/doc/draft-mcnally-envelope/) had their [determinstic CBOR](https://datatracker.ietf.org/doc/draft-mcnally-deterministic-cbor/) dispatched to us; has been taken up to be probably an information model that is more flexible on numbers.

  Some controversy on tag frugality is happening related to Gordian.

* [Packed CBOR](https://datatracker.ietf.org/doc/draft-ietf-cbor-packed/) is moving on again, expecting completion before 118.

* Some tag work ongoing as always (with [time-tag](https://datatracker.ietf.org/doc/draft-ietf-cbor-time-tag/) now going forward without further waiting for SEDATE)

## CoRE (Jaime Jiménez / Marco Tiloca / Carsten Bormann)

* 1 document in AD Evaluation
    * -core-target-attr

* Among the WG documents:
    * 3 waiting for Shepherd Write-up (-core-oscore-groupcomm; -core-oscore-edhoc; -core-yang-library)
    * 2 completed WGLC (-core-groupcomm-bis; -core-conditional-attributes)

* In WG Last Call
    *  Constrained Resource Identifiers (HREF)

* Selected ongoing activities
    * Major work on the CORECONF documents
        * -core-sid (back to the WG) in parallel with -core-comi, soon expected WGLC for both, then -core-yang-library will follow
    * Addressed Shepherd review of -core-oscore-groupcomm
    * Works related to OSCORE (key update KUDOS; OSCORE at proxies and nested OSCORE protection)

* New WG documents
    * Performance measurement for CoAP (building on IPPM work)
    * OSCORE key limits (split out from the KUDOS document)

* Since IETF 116
    - Regular biweekly interim meetings
    - Recurring design meetings (HREF & CoRAL)

* CoRE will meet at IETF 117, in a 2-hour session.

* CoRE will have a 90-minutes side meeting at IETF 117, for informal hallway discussions on topics related to:
    * Non-traditional responses; corrections and clarifications to CoAP; locally significant URIs
    * https://wiki.ietf.org/en/meeting/117/sidemeetings

* We plan to resume biweekly interim meetings on the 30th of August.


## COSE (Matt Miller / Ivaylo Petrov)

CB: Has a packed agenda, have a look. Glue work, that but that glue needs to be there for thigns to work.

Agenda:
13:00-13:05 Opening remarks - the chairs (5 minutes)
13:05-13:25 Post-Quantum Signatures draft-ietf-cose-{dilithium,sphincs,falcon} (20 minutes) - Mike Prorock and Orie Steele
13:25-13:35 draft-birkholz-cose-tsa-tst-header-parameter (10 minutes) - Henk Birkholz
13:35-13:45 draft-ietf-cose-cbor-encoded-cert (10 minutes) - Göran Selander or John Mattsson
13:45-13:55 draft-steele-cose-merkle-tree-proofs (10 minutes) - Orie Steele
13:55-14:05 draft-birkholz-cose-cometre-ccf-profile (10 minutes) - Henk Birkholz
14:05-14:15 draft-isobe-cose-key-thumbprint (10 minutes) - Hannes Tschofenig
14:15-14:25 draft-jones-cose-typ-header-parameter (10 minutes) - Orie Steele and Mike Jones
14:25-14:40 Summary of contentious issues in HPKE (15 minutes) - Orie Steele
14:40-14:55 draft-ietf-cose-hpke (15 minutes) - Hannes Tschofenig
14:55-15:00 AOB (5 minutes)

Also:
COSE-HPKE and the Single Algorithm Discussion (https://mailarchive.ietf.org/arch/msg/cose/_GQXXpltAgXNozXIFC9z1yY1CCM/)

## DetNet (Lou Berger / János Farkas)

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)


## LAKE (Mališa Vučinić / Stephen Farrell)

* Status
    * The WG received AD reviews for `draft-ietf-lake-edhoc` and `draft-ietf-lake-traces`
    * `draft-ietf-lake-edhoc-20` published incorporating the comments from the AD review
    * One change affects the implementations
    * IETF Last Call triggered for `draft-ietf-lake-edhoc-20`
        * Last Call ends on 4 August 2023
    * `draft-ietf-lake-traces `under revision
        * Significant change to the traces after the implementation update following `draft-ietf-lake-edhoc-20`
    * Rechartering of the WG in progress
* IETF 117
    * Joint session with ACE on Monday, 24 July 2023
    * 16:30-18:30 UTC


## LWIG (Mohit Sethi / Zhen Cao)

Last document awaiting update ([draft-ietf-lwig-curve-representations](https://datatracker.ietf.org/doc/draft-ietf-lwig-curve-representations/)); then over to RFC Editor and will close the group.

## LPWAN (Alex Pelov / Pascal Thubert)

LPWAN is transmogrifying into SCHC.
The last RFCs 9441-to-be & 9442-to-be are being completed with the RFC editor, in AUTH48. 
They relate SigFox thought the compound ack RFC 9441 is more general.
Please create an entry for SCHC now


## RATS (Kathleen/ Nancy / Ned)


## RAW (Rick Taylor / Eve Schooler)

RAW architecture in WGLC. spining back in DetNet

PT: usecase document is mostly done. What's left is the raw-framework and raw-oem(?), presumably to be completed within detnet.
TE: Planned timeline?
PT: Chairs have explained they will not continue the activity, thus hastening the merge (accepted by detnet chairs). Already have raw/detnet meeting this week.

## ROLL (Dominique Barthel / Ines Robles)

Will not meet at IETF 117. Planning to have interim in September.

Documents:
* [draft-ietf-roll-dao-projection](https://datatracker.ietf.org/doc/draft-ietf-roll-dao-projection/)
   * Ready, waiting for routing directorate review, which should be done soon. 
* [draft-ietf-roll-aodv-rpl-17](https://datatracker.ietf.org/doc/draft-ietf-roll-aodv-rpl/)
   * ready, waiting for shepherd document
* [draft-ietf-roll-nsa-extension-11](https://datatracker.ietf.org/doc/draft-ietf-roll-nsa-extension/)
  * almost all issues addressed, 1 open issue
  * requested rtg and security directorate early review
* [enrollment-priority](https://datatracker.ietf.org/doc/draft-ietf-roll-enrollment-priority/)
  * in progress


## SCHC (Alex Pelov / Pascal Thubert)

newly created to generalize RFC 8724 ad 8824 over FOO (and under BAR)
LPWAN drafts like architecture and OAM are migrated to SCHC

PT: This is the next step for LPWAN; realized its applicability is wider (just like 6lo was from 6lowpan)

## SUIT (Dave Thaler / David Waltermire / Russ Housley)


## TEEP (Tiru Reddy / Nancy Cam-Winget)



# IRTF

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


## T2TRG (Ari Keränen / Carsten Bormann)

Will not meet at IETF 117.

Has five documents at various stages of completion.
New documents submitted for post-117 interims.
https://datatracker.ietf.org/group/t2trg/documents/



# New/planned IETF/IRTF IoT activities


# AOB

(Nothing came up.)
