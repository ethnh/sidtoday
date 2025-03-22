![img-0.jpeg](img-0.jpeg)
(TS//SI) GSM Temporary Selectors - Breakthroughs in Automated Identification

FROM:
Target Analysis Center (S2S1)
Run Date: 07/27/2005
(TS//SI) Since the dawn of GSM ${ }^{1}$ in the early 1990's, NSA analysts working GSM have struggled whenever cellular networks implement TMSIs (Temporary Mobile Subscriber Identities) to address mobile subscribers. TMSIs obscure the true identities of the cellular subscribers being referenced in call records, location events, and SMS (text messaging). TMSIs can change every few hours or even with every phone call. Few NSA analysts working GSM have had both the expertise and the time needed to maintain continuity on TMSIs. Thus, TMSIs came to be regarded as an unsolvable problem, just one of the unavoidable obstacles that came with working GSM.
(TS//SI) As GSM metadata collection, processing, and storage matured over the years, it became possible to use a series of individual metadata records to manually trace a TMSI backwards through time to the corresponding permanent IMSI 2 or IMEI ${ }^{3}$. The ASSOCIATION team was given the challenge to automate the process, to run the sequential series of queries quickly enough to produce the result within an acceptable response time.
(TS//SI) The ASSOCIATION improvements had already quietly begun when the Iraqna (Central Iraq) and Asiacell (Northern Iraq) GSM networks implemented TMSIs in March and May 2005 respectively. As GSM cellular phones are popular communications devices with Iraq insurgents, these network changes had negative effects on NSA's ability to monitor and locate terrorist targets operating within Iraq.
(TS//SI) ASSOCIATION incorporated the first-ever automated TMSI identification tool into its June 2005 version 7.0 release. If an analyst enters the TMSI, the network, and the date and time observed, ASSOCIATION examines a sequential series of event records to try to find the corresponding IMSI or IMEI.
(TS//SI) Metadata volume is the key to successful TMSI identification. It only takes only one unobserved TMSI reallocation from one uncollected cell to lose TMSI continuity. The success of the new TMSI identification utility is largely because all GSM collection systems (in the case of Iraq to include SCS, tactical military, and Overhead) are feeding into a common metadata repository (FASCIA), allowing ASSOCIATION to use separate events from multiple sites to make a single TMSI identification.
(TS//SI) Additional Capabilities - The next release of ASSOCIATION will improve the TMSI identification algorithms, and will also attempt to automate the enhancement of TMSI identifications in ASSOCIATION queries and results (Currently, an analyst who encounters a TMSI in ASSOCIATION query results has to run a second ASSOCIATION query to identify the TMSI. Goal will be to make it a one-step process). Also related to the subject of automated identification of temporary subscriber addresses, the current version of ASSOCIATION introduced the first-ever automated MSRN ${ }^{4}$ identification utility, and a future ASSOCIATION version will support automated LMSI ${ }^{5}$ identification.
(U//FOUO) POC: Target Analysis Center/S2S1; Qnsa, 2005

# *(U) Notes: 

1. (U) GSM, or Global System for Mobile Communications, is the dominant 2d generation digital cell phone technology. Approximately 75\% of the world's cell phone subscriptions are GSM.
2. (U) IMSI, or International Mobile Subscriber Identity, is the 15-digit account number that is a subscriber's primary address within a GSM network.
3. (U) IMEI, or International Mobile Equipment Identification, is the 14-digit serial number of a GSM handset.
4. (S//SI) MSRN, or Mobile Station Roaming Number, is a dynamically-assigned telephone number used to route an incoming GSM call to the Mobile Switching Center currently serving the called subscriber. MSRNs can appear as the Called Number in a contact chaining record.
5. (S//SI) LMSI, or Local Mobile Subscriber Identity, is a temporary address assigned by the Visitor Location Register (VLR) only for so long as the subscriber remains registered in that VLR. SIGINT processing had been able to safely ignore LMSIs for years, but now LMSIs are increasingly being used as the only address to identify the recipient of an SMS within the GSM core network.

# "(U//FOUO) SIDtoday articles may not be republished or reposted outside NSANet without the consent of S0121 (DL sid_comms)."
