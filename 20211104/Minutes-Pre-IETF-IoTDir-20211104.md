Source: https://notes.ietf.org/iot-dir-ietf112-2021-11-04-notes

# IoT directorate IETF 112 pre-meeting 

IoT-DIR Chairs: Samita Chakrabarti, Ines Robles, Ari Keranen


Date: 2021-11-04
Time: 3:30pm - 5pm UTC

## Meeting Details 
This meeting is aligned with the IETF Note Well: https://www.ietf.org/about/note-well/

NEW WEBEX LINK:
Pre-IETF 112
Hosted by IoT Directorate

https://ietf.webex.com/ietf/j.php?MTID=mb8344dfa05129161730be21867ce4e5f
Thursday, Nov 4, 2021 8:30 am | 1 hour 30 minutes | (UTC-07:00) Pacific Time (US & Canada)
Meeting number: 2435 772 4034
Password: yJdA8B3JsA3

Join by video system
Dial 24357724034@ietf.webex.com
You can also dial 173.243.2.68 and enter your meeting number.

Join by phone
1-650-479-3208 Call-in toll number (US/Canada)
Access code: 243 577 24034

## Draft agenda

* Overview of the IETF/IRTF IoT groups (WG/RG chairs; 1-2 minutes per group)
* IIC/IETF collaboration feedback
* AOB. 


Notice that we aim to record the meeting.

# Attendees

Please add your name here
1. Ines Robles
1. Ari Keränen
1. Carsten Bormann
1. Marco Tiloca
1. Mališa Vučinić
1. Erik Nordmark
1. Barry Leiba
1. Carles Gomez
1. Erik Kline
1. Éric Vyncke (part-time)
2. Samita Chakrabarti
3. Christian Amsüss
4. Toerless Eckert
5. Bruce Nordman
6. Hannes Tschofenig


# Overview of the IETF/IRTF IoT groups

## 6TiSCH (Thomas Watteyne / Pascal Thubert): CLOSE

MCR: closed; but mailing list open
Erik: not closed yet

## 6lo (Carles Gomez / Shwetha Bhandari)
1-hour session scheduled for IETF 112

* 1 document in RFC editor queue:
    * IPv6 mesh over BLE (draft-ietf-6lo-blemesh-10)

* 4 other WG documents:
  * 2 documents evaluated by the IESG:
      - IPv6 over NFC (draft-ietf-6lo-nfc-17)
      - IPv6 over PLC (draft-ietf-6lo-plc-06)
  * Passed WGLC:
      - Use cases draft (draft-ietf-6lo-use-cases-11) 
  * New WG document:
      - IPv6 ND Multicast Address Listener Registration (draft-ietf-6lo-multicast-registration-01)
            - Includes a new RPL Non-Storing multicast mode and support for anycast

* Several individual documents:
  * Header compression:
    - Transmission of SCHC-compressed packets over IEEE 802.15.4 networks (draft-gomez-6lo-schc-15dot4-01)
    - Native Short Address for Internet Expansion (draft-li-native-short-address-00) 
    - Short Hierarchical IP Addresses at Edge Networks (draft-song-ship-edge-02)
  * Neighbor Discovery:
    - IPv6 Neighbor Discovery Unicast Lookup (draft-thubert-6lo-unicast-lookup-01)

Erik: the two IESG docs locked on me; will get to that soon

## ACE (Daniel Migault / Loganaden Velvindron)

## ANIMA (Sheng Jiang / Toerless Eckert)
Next week meeting
Hackaton activity on BRSKI. Restructuring doc; many encoding and procol options. How many combinations we need? 
First erratas coming in. Wrote good overview article on what ANIMA is today and what we'd like to see it used for. Internet protocol journal: https://ipj.dreamhosters.com/wp-content/uploads/2021/10/243-ipj.pdf


## ASDF (Michael Richardson / Niklas Widell)

* ASDF had been very active leading up to IETF111, resulting in an implementation (1.1) draft for IETF110. 
    * Less active since IETF111, but many smaller issues resolved.
    * Recently, mostly just editorial changes
* Now looking at new work involving additional work in protocol mapping.

Carsten: writing a draft right now.

Ari: also lots of activity in the Github issues / PRs. And discussions in the WISHI meetings that go beyond current charter of ASDF. Will be brought to ASDF meeting next week.

## CBOR (Barry Leiba / Christian Amsüss)

Fields:

* Extension point maintenance
  * RFC 9090 on OIDs ("this byte string is a {absolute,relative,relative-to-private-enterprise}" OID) in CBOR
  * network-addresses ("this is an IPv{4,6} {address, address and accompanying subnet, subnet}") in RFC editor queue
  * file-magic ("if you save your files to disk, get a tag indicating your complete format, and do it like that") has an open point but is almost ready
  * time-tag is adopted \[now mostly waiting for SEDATE to come up to speed]
  * WG interims also serve as venue for expert to solicit feedback on third-party registrations

* Language maintenance
  * at RFC editor: cddl-control (new opt-in features for CDDL (think ABNF for CBOR), eg. regexp and ABNF support)

* Large things inbetween
  * in WG: cbor-packed ("how to use, and how to set up, compression that is usable in-place") growing with interactio from CoRAL (in CoRE)

Bi-weekly interims in September and October, resuming in December

## CoRE (Jaime Jimenez / Marco Tiloca)

RFC 9100 published in August, on indicating features and versions for SenML.

4 documents in the Editor's queue
- senml-data-ct, echo-request-tag (recently approved)
- new-block, resource-directory (were waiting for echo-request-tag)

2 documents in IESG evaluation
- core-yang-cbor and core-sid from the CORECONF cluster

8 more WG documents, of which 3 are approaching WGLC

Overall ongoing activities:
- Constrained Resource Identifiers (HREF)
- The RESTful application language CoRAL
- Resource Linking and Transport Indication
- Group communication, its security with Group OSCORE, support for it from proxies
- New methods related to OSCORE (key update, optimized combination with EDHOC, cacheability of responses)

Since IETF 111
- 4 biweekly interim meetings
- Recurring design meetings about HREF & CoRAL and CORECONF

CoRE will meet at IETF 112 (2 hours)

We will have an interim meeting on December 8th, and then a series of 4 biweekly interim meetings is scheduled starting from January 19th.

## COSE (Matt Miller / Ivaylo Petrov)


## DetNet (Lou Berger / János Farkas)

First set of DetNet specs are ready:
1. RFCs:
* RFC 8557 DetNet Problem Statement
* RFC 8578 DetNet Use Cases
* RFC 8655 DetNet Architecture
* RFC 9055 DetNet Security Considerations
* RFC 8938 DetNet Data Plane Framework 
* RFC 8939 DetNet Data Plane: IP 
* RFC 8964 DetNet Data Plane: MPLS 
* RFC 9056 DetNet Data Plane: IP over MPLS 
* RFC 9025 DetNet Data Plane: MPLS over UDP/IP
* RFC 9023 IP over TSN
* RFC 9037 MPLS over TSN
* RFC 9024 TSN VPN over MPLS
* RFC 9016 DetNet Flow Information Model

2. Publication requested:
* DetNet Bounded Latency: draft-ietf-detnet-bounded-latency
* DetNet YANG: draft-ietf-detnet-yang

OAM is the primary focus of ongoing WG work:
* draft-ietf-detnet-oam-framework
* draft-ietf-detnet-mpls-oam
* draft-ietf-detnet-ip-oam

Controller Plane is upcoming WG work:
* draft-ietf-detnet-controller-plane-framework

Recent interim focusing on reaching agreement on the problem statement related to potential DetNet queueing mechanism: https://datatracker.ietf.org/meeting/interim-2021-detnet-01/materials/minutes-interim-2021-detnet-01-202109131300-00.html



## IOTOPS (IOT Operations) (Alexey Melnikov, Henk Birkholz)

(later when Henk joins)

## IPWAVE (Carlos Bernardos, Russ Housley)

All documents are in the RFC Editor queue.  The WG will close soon.

## LAKE (Mališa Vučinić / Stephen Farrell)
LAKE will meet on Friday of the IETF week at 1430 UTC.

The EDHOC draft is considered stable and is in the "pre-WGLC" stage. We are expecting early reviews by EOW that will be discussed during the IETF 112 meeting. We are in the process of launching a call for formal analysis with the target submission date of the EDHOC spec in April 2022.

The WG adopted a new draft gathering EDHOC test vectors, previously part of the main EDHOC spec. The exact scope of the draft and the eventual publication as an RFC will be further discussed during the IETF 112 meeting.

## LWIG (Mohit Sethi / Zhen Cao)


## LPWAN (Alex Pelov / Pascal Thubert)

> Mainly YANG data model
> Progress on Sigfox & NB-IoT
> [name=Éric Vyncke]

Pascal: progress on LPWAN arch stalled; draft that pushed to int-area: SCHC over PPP. Work on data model; optimistic on this one. Next tech we'll ship: Sigfox. LoRA alreay shipped will get some feedback on that from LoRA alliance. Sigfox people proposed additions. 


## RAW (Eve Schooler, Rick Taylor)

Pascal: 3 mature docs: LDACS is in IESG review. It is a new L2 tech for radio that is redesigned for limited distance; ground to airplane, could be used between planes. Similar to Wi-Fi6 and 5G. Optimized for plane communication.
Technology draft is an overview on where RAW expected to work on. Close to ready; LC going on. RAW architecture stalled since last IETF. Waiting for changes from DetNet side. Will see how progress goes on that. 
Eve: Additionally, the Industrial Requirements draft is ready for WG adoption.

## RATS (Kathleen/ Nancy / Ned)



## ROLL (Dominique Barthel / Ines Robles)

- One hour meeting on IET112 - 1hr
- AODV-RPL: Adressing DISCUSS open issues on the IESG Evaluation
- Items close to WGLC: Mopex, Capabilities, DAO-Projection, enrollment-priority
- Reviews required
- Submitted to the IESG: draft-ietf-roll-nsa-extension
- Item to be evaluated for Adoption RNFD (Fast border router crash detection in RPL), Root-ACK (RPL Storing Root-ACK)


## SUIT (Dave Thaler / David Waltermire / Russ Housley)

Hannes: manifest was cut down on functionality. Spec only contains core pieces. Extensions to separate doc. Done to make the whole spec simpler to read. Had hackathon this week. Will see if people like the cleaned-up version.

Russ: Progress on firmware encryption mechanism; turned out to be more complicated than thought. Have published a basic COSE HPKE mechanism (Russ will talk about next week in COSE), and the SUIT firmware encryption makes use of that COSE HPKE mechanism (Hannes will talk.

## TEEP (Tiru Reddy / Nancy Cam-Winget)


## T2TRG (Ari Keränen / Carsten Bormann)

Done:

* [Summary interim meeting](https://github.com/t2trg/2021-10-summary) last week
  * Research talk on "Data centric CoAP transport"
  * Introduction on "Matter Security & Privacy for Security & Privacy Experts"
  * [Recording](https://youtu.be/rm4H2UuClz0) and [slides](https://datatracker.ietf.org/meeting/interim-2021-t2trg-02/session/t2trg)
* Not planning to meet during IETF 112, some isolated Hackathon activity
* Since last IETF, had two [WISHI meetings](https://github.com/t2trg/wishi/wiki/Agenda-items#past-events) on [SDF](https://ietf-wg-asdf.github.io/SDF/sdf.html) architectural topics and [Azure DTDL](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md) — SDF interwork topic

Next:

* RG [draft](https://datatracker.ietf.org/doc/html/draft-irtf-t2trg-iot-edge-03) on "IoT Edge Challenges and functions" going soon for RG LC
* 2021-12-07: [DAI-SNAC21] workshop at ACM CoNEXT21: Descriptive Approaches to IoT Security, Network, and Application Configuration

[DAI-SNAC21]: https://dai-snac21.hotcrp.com

## COIN (Jeffrey He / Eve Schooler / Marie-Jose Montpetit)


# New/planned IETF/IRTF IoT activities


# IoTSF

The IoT Security Foundation is holding their annual conference Wed/Thu (Nov 3/4: i.e., right now).  There is a new version of the Security Compliance Framework, with a slightly new name.  The IoTSF's Manysecured.net SUIB effort is on the agenda for IOTOPS.  Last year's videos: https://www.iotsecurityfoundation.org/iot-security-foundation-virtual-conference-2020-applied-security/
Manysecured D3 effort is looking at MUD extensions, with third-party assertions.


# IIC/IETF Meeting - Feedback

See recording: https://youtu.be/ZiePfQCHBAk

Introduction meeting given by IIC Industrial IoT Consortium, 
Dave Thaler: Very useful. Let's continue the external  SDO presentation effort. Other examples could be OPCF, ZigBee Alliance

SDOs Presentation at the IETF: 

Dave: think it's really useful. Would like to see continue. Thanks for setting up. Have had joint meetings with e.g. OCF earlier. But there are others where we don't have direct contacts they would be good. Like OPC and Zigbee alliance. 

Carsten: interesting symptom. Had just event with Zigbee; may not have noticed. In the summary meeting Steve Hanna talked about Matter that is from CSA which is what Zigbee has become. We need to be more accessible inside IETF. 

Dave: who organized that?

Carsten: T2TRG. Also IoTops doing this kind of work. We should devise a way to make this information more available. Would be good to have channel where people notice these.

Toerless: would love to see IETF calendars. Would be obvious way to catch these. 

Dave: want to +1 Carsten; if have presentation from IIC. Who is the audience? Directorate or IETF people in general? Value for IETF people in general. More we want cross org collab the more will benefit us. Would be useful for IoT dir, T2tRG, etc, should be open to anyone at IETF open. If there's calendar or other way to announce these -- would help IETF in general.

Toerless: useful to have at least public stream if not interactive

MCR: didn't notice was happening. Will save later the youtube. Missed the announcement. Know we have problems putting IoT dir meeting to our calendars. I'm very enthusiastic on this kind of work. Important to bring what we are doing to their meetings too. Have heard comments from cloistered British academics that Internet was designed in UK...

Carsten: actually French invention :-)

Hannes: Austrian!

MCR: want to do more of these things. But not just to us but also like how is IPv6 used in Matter would be great for v6ops session.

Toerless: have been talking with Wael at IIC; one thing directorate can do is to work through the bloody buraucracy and how to get to good tech discussion. 

Ari: 

Toerless: any existing toolk we could use? 
MCR: suggest that since IOT-DIR can't book virtual interims (due to DT tooling), that we just have IOTOPS do the button pushing so that it will show up in the upcoming.ics

Ari: way forward with IIC

Dave: I was there. Was peripheraly familiar with IIC but not in detail. IIC is not SDO but more like marketin org. Does frameworks and marketing. If try to schedule joint meeting; didn't have a meeting with OCF and WoT? Since not SDO but work with other SDOs; if have informational chat on IETF topics should have joint meeting with other SDOs like OPC? Should be 2 or 3 way meeting?

MCR: works for me if you can herd all those cats (and coordinate a time zone)

Toerless: not sure of designation of SDO

Dave: IIC says they are not SDO. OPC or other org does spec and IIC takes use of that.

Toerless: important to understand the benefit of the exchange. They do testbeds and validate solutions. Could include IETF standards. Have been looking for interactions from those goals perspective.

Hannes: at hackathon very few people at gathertown. How many are doing hacking at this event? Or some fatigue on online hacking events?

MCR: there, fixing things. But there is fatigue. 

Hannes: so many concurrent meetings happening. Impossible to make progress. 

MCR: events this week similar to prev hackathons, but in 111 was lots of enthusiasm. If compare to that, terrible. But compared to 110 similar.

Carsten: around SDF some implementation work and spec example generation work is ongoing. Didn't bother to announce.

Hannes: working with guys you work previously? Trying to get new people; contacted and setup tutorials.

Ari: back to IIC;

Dave: webinar style / interim / workshop. Style of preso IIC made; would call workshop or meeting? Would suggest that they're not SDO, if do just to them, we do same way as webinar style. Things we have they could use. For a full WS pulling another SDO to the mix might be useful.

Toerless: if start with overview of IETF stuff could be overwhelming. Could be useful to have one round to find what is interesting.

Dave: carsten has done that talk; has done to OCF. Think that was great.

Carsten: worked with OCF. We have great working relationship with them.
Difference with IIC is that they have marketing department that generates structured messages. Doing summary of IETF is work; need to update for every IETF meeting. Not easy to keep up. Would be nice to have a way to get input for that.

Hannes: have participated in IIC and they are very broad. Telling them about the stuff we work on can be very useful as amplification / marketing. 

Toerless: for example next test bed; maybe not the work we do now but rather the work we did few years ago could be intersting.

Hannes: could be difficult. Many groups with different focus. 

Toerless: part of investigation. Ultimately we should have idea of where things fit. Now idea to have tech tutorials. Bit of marketing from IETF side. That type of stuff would be great. Material for interst to other orgs.

Erik: When they presented; did they indicate next set of problems where would make sense for us to target? 

Ari: makes sense to give overview from IETF

Toerless: annoying that what currently working on is not public. That's why they have liaison in process. Could be one of the steps to take. To define the liaison relationship.

Dave: IAB will ask what you would do with that. Given they're not SDO, they do docs but not something implementor can conform to. Will have to figure out are the docs unpublished relevant to IETF. If yes, could make a case for IAB on the liaison. 

Toerless: we don't know what we don't know

Dave: could look what have done previously. Could see if could have done something different if we've had liaison.

Toerless: now looking at detnet. IIC could be good branch to get more interest for detnet output. Could push forward prolifirating the work we've done. Maybe same line of work could apply to other IETF work.

Ari: (chair hat off) makes sense for us to engage more with IIC.

Toerless: good to have people from both sides engaged. 

Next Steps: Forming a Task Force? Volunteers?


# AOB

