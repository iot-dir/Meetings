# IoT directorate IETF 113 pre-meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keranen


Date: 9th March 2022
Time: 5pm - 6:30pm (UTC)

## Meeting Details 

This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/


## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* New/planned IETF/IRTF IoT activities
* Other IoT SDOs update/activities (if applicable)
* IIC follow up
* AOB. 


Notice that we aim to record the meeting.

# Attendees

* (Please add your name here)
* Ines Robles
* Ari Keränen
* Michael Richardson
* Marco Tiloca
* Pascal Thubert
* Carsten Bormann
* Henk Birkholz
* Russ Housley
* Eve Schooler
* Dominique Barthel
* Samita Chakrabarti
* Nancy
* Carles Gomez
* Lou Berger


# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert)

On hold, strong relationship with RAW


## 6lo (Carles Gomez / Shwetha Bhandari)

* RFC 9159:
    * IPv6 mesh over BLE (draft-ietf-6lo-blemesh-10)

* 4 WG documents:

  * 2 documents evaluated by the IESG:
      * IPv6 over NFC (draft-ietf-6lo-nfc-17)
      * IPv6 over PLC (draft-ietf-6lo-plc-10)

  * In AD evaluation:
      * Use cases draft (draft-ietf-6lo-use-cases-12) 
            
  * Recently adopted as WG document:
      * IPv6 Neighbor Discovery Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-04)

Most time in IETF 113 will be dedicated to individual documents:

  * 2 drafts focusing on or including header compression functionality:
    * Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-gomez-6lo-schc-15dot4-02)
    * Native Short Address for Internet Expansion (draft-li-native-short-address-02)
        * Includes stateless forwarding
 
  * 1 draft in the area of ND:
    * IPv6 Neighbor Discovery Unicast Lookup (draft-thubert-6lo-unicast-lookup-02)
  * Other ND-related drafts/ideas (for info): 
    * Possible Use of 6LoWPAN ND outside of IoT (draft-thubert-bess-secure-evpn-mac-signaling)
    * Prefix registration 

## ACE (Daniel Migault / Loganaden Velvindron

CB: authorization format (AIF) in telechat tomorrow
as is oauth-authz MQTT profile

* main 4 documents in AUTH48 now (oauth-authz and profiles)

## ANIMA (Sheng Jiang / Toerless Eckert)

* constrained-voucher* going to WGLC.
* RFC8366bis adopted

## ASDF (Michael Richardson / Niklas Widell)

* SDF draft (draft-ietf-asdf-sdf) moving towards WGLC
* Future work includes mapping files (e.g., draft-bormann-asdf-sdf-mapping, draft-kiesewalter-asdf-yang-sdf), SDF compact format (draft-bormann-asdf-sdf-compact), more work on SDF instances and model relationships, etc. 
* 2 interims since 112, no meeting at 113
* increasing comfort with SDF for other SDOs. To be a way to get to/from YANG. Something they have realized they want to do. Good thing for everybody.

## CBOR (Barry Leiba / Christian Amsüss)

CB: have just submitted "file magic"; way to record magic number in stored CBOR items. Down to one WG doc that is CBOR packed. Going to be pretty important when comes out. Also working on CDDL 2.0 and various tag proposals.

## CoRE (Jaime Jimenez / Marco Tiloca / Carsten Bormann)

* RFC 9175 published in February, on two new CoAP options (Echo, Request-Tag) and updating processing steps for the CoAP message token.

* 3 documents in the Editor's queue (AUTH48)
    * senml-data-ct, new-block, resource-directory

* 2 documents in IESG evaluation
    * core-yang-cbor and core-sid from the CORECONF cluster

* 8 more WG documents, of which 1 post WGLC and 3 approaching WGLC

* Selected ongoing activities:
    * Constrained Resource Identifiers (HREF) & RESTful application language CoRAL
    * Group communication (obsoleting RFC 7390, security with Group OSCORE, support from proxies)
    * Works related to OSCORE (key update procedure, optimized combination with EDHOC)
    * Conditional attributes; Transport indication
    * Attacks against CoAP (ongoing WG adoption call)
    * Measurement of CoAP performance (packet loss, delay)

* Since IETF 112
    - 4 biweekly interim meetings
    - Recurring design meetings about HREF & CoRAL

CoRE will meet at IETF 113 (2 hours on Friday 25). Marco will be there.

We will resume with biweekly interim meetings at the end of April.

## COSE (Matt Miller / Ivaylo Petrov)

HB: discussing ; work item on supply chain transparency. Using COSE a lot. Variant of counter signing. Might be interesting to COSE. Presenting in SEC-DISPATCH.

## DetNet (Lou Berger / János Farkas)

LB: Couple of docs in IESG. One on YANG model. Foundational doc for mgmt of detnet nodes. Another on latency for implementations (informational). In the process for extending charter for queuing mechamisms. Discussing if detnet is the right place with INT-area.
Discussions on OAM. Good on MPLS dataplane. For IP dataplane need more work and contribs. Also looking for control plane contribs. Either centralized or hybrid. First taken care of by YANG model, the distributed style out of vogue now. Looking for more interst from WG members.

## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)

* one hour for 113. Want to have max 3 best presentations. Have been overloaded recently.
* no stable agenda yet
    * will stabilize in a few days
* but we have first request from an external party wrt "is this the landing zone"?
* chair support for I-D authors and steady progression

## LAKE (Mališa Vučinić / Stephen Farrell)


## LWIG (Mohit Sethi / Zhen Cao)


## LPWAN (Alex Pelov / Pascal Thubert)

LPWAN is well-advanced for most of the current topics.
The YANG Model document is under WGLC, ending March 15th
The compound ack document passed WGLC, and is undergoing shepherding by Alexander
New lead author for the SCHC over SigFox document since Juan Carlos joined Cisco.
The SCHC over NBIOT is getting close to WGLC too
Interesting architecture questions (e.g., from Carles on device vs. application roles) as we extend the scope of SCHC from LoRa/Sigfox type of LPWAN to peer to peer (PPP, IEEE 802.15.4)

The next big steps would be:

* complete the architecture document
* document the associated deployment models
* SCHC improvements 
* Progress OAM work (a specifically charter item)

There is probably no need to recharter for these items is we agree that the first 3 fall into thye generic maintenance charter item.

## RATS (Kathleen/ Nancy / Ned)

* Architecture going to IESG
* Network profiling should be done as well
* YANG TPM CHARRA is in IESG eval
* Bunch of other drafts focusing on. Trying to get Entity Attestation Token to publication and move to rest of the work.
* Interest to recharter and broaden the scope. Strong consensus to get rechartering done. A few issues to look into, but minor.

## ROLL (Dominique Barthel / Ines Robles)

* 1 hour slot meeting at IETF 113.
* AODV-RPL needs WG confirmation on the MOP, changed to 4. 
* Open work items: enrolment priority needs input from the WG.
* draft-ietf-roll-nsa-extension submitted to the IESG 
* DAO-Projection in review, next on WGLC
* New Work approved: RNDF-Fast border router crash detection in RPL

PT: for people who don't participate in RPL development: original RPL is distributed protocol running proactive establishment of routes. AODV-RPL is reactive . The DAO-projection is another extreme, completely centralized. To sum up, started with distributed proactive, then distributed reactive, now fully centralized. We now have a nice family.

## SUIT (Dave Thaler / David Waltermire / Russ Housley)

SUIT Manifest Format divided into three documents:
   - draft-ietf-suit-manifest
   - draft-ietf-suit-trust-domains
   - draft-ietf-suit-update-management

Base would be implemented by everyone, other two optional options. Makes core much much simpler.

Firmware Encryption with SUIT Manifests now depends on draft-ietf-cose-hpke:
   - draft-ietf-suit-firmware-encryption

SUIT-related Claims will progress in SUIT (as opposed to RATS):
   - draft-ietf-suit-rats-claims

Secure Reporting of Update Status is using the SUIT-related Claims:
   - draft-ietf-suit-report

Strong Assertions of IoT Network Access Requirements can now progress with the recharter:
   - draft-moran-suit-mud

HB: from RATs, SUIT claims done in SUIT, hard plug here dur to potential misconception that some EAT claim that exixts semantically overrides SUIT claims Have to clear this up. Will not update that draft due to problem. To be discussed in SUIT at Vienna.

RH: discussion started on the mailing list 

## TEEP (Tiru Reddy / Nancy Cam-Winget)

Progressing well; Dave T doing lots of checks. Need to ask how mature the draft is.

## T2TRG (Ari Keränen / Carsten Bormann)

T2TRG is organizing [a summary meeting](https://github.com/t2trg/2022-03-summary) Thursday, March 10th and will not meet during the IETF week.

Starting new activity on Security for Constrained RESTful Environments (SECCORE).

"Guidance for RESTful IoT" and "IoT Edge Challenges and Functions" going towards RGLC.

## COINRG (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)

* interim held in February; several research presentations, plus discussions around RG scope (in general and here specifically)
* much ongoing debate about what aspects of semantic routing are in/out of scope
* New Use cases draft -02 issued 
* I-D expirations being addressed
* agenda for IETF 113 evolving


## RAW (Rick Taylor / Eve Schooler)

* 1 hour slot planned at IETF 113
* LDACS proposed informational RFC wending its way through IESG review; recently received Routing AD review 
* Use Cases I-D completed WGLC and submitted to IESG
* Architecture/Framework docs separated, mimicking the strategy taken in DetNet where the Architecture outlines the general approach and the Framework will provide the specifics
* Technology draft had a thorough review (and several others solicited) in preparation for WGLC

# New/planned IETF/IRTF IoT activities

(Add pointers here about activities you know about)

# Other IoT SDOs update/activities (if applicable)

* OPC UA: Onboarding (taking out of the box) instead provisioning (something that happens in the factory)
* IoTSF: 

* LoRa Alliance: RFC8724/9011 adopted as an adaptation layer for IPv6 over LoRaWAN, spec approved by Technical Committee, now going through Board etc. Expect announcement in a few weeks.

# IIC follow up

AK: Planned WS towards end of Q2. Discussing organization details and agenda in bi-weekly meetings of program committee (also once with IESG/IAB). 

# AOB
