![img-0.jpeg](img-0.jpeg)
(S//SI) Click ... Click ... Click ... What's the Number?

FROM: Adolf Cusmariu
Technical Director, Operational Technologies (S202B11)
Run Date: 09/21/2006
(S//SI) Attention, collectors and SIGDEV analysts: a new analog-dialing extraction capability will soon be available for your use via BABBLEQUEST.
(S//SI) What if SIGINT collects an acoustical signature from the old analog rotary telephone system, full of simple clicks as the mechanical dial opens and closes the circuit on its way around? Is there any way of determining what number was dialed? The MENA target office covering the Levant (S2E33) had just such a problem when they came across intercepts from what appeared to be an internal communications link.

# (S//SI) Background: Each Number Has a Unique Frequency 

(S//SI) Dialed Number Recognition (DNR) in our modern digital age has become a problem in frequency (or spectral) estimation; each dialed digit, regardless of standard, is uniquely represented by a frequency doublet. For example, in the DTMF system used in the US, the digit "5" is represented by the doublet ( $770 \mathrm{~Hz}, 1,336 \mathrm{~Hz}$ ). Estimate the doublet sequence and you get the dialed number. The somewhat older pulsed dialing systems again yield to spectral DNR because the pulse stream is typically carried by line-supervision tones used by phone companies to charge for line usage; once an appropriate pulse counter is devised the dialed number can be estimated. Of course, dialed number databases provide critical intelligence on all targets, helping to define social networks, patterns of communication, call origination and destination, and tasking guidance.
(S//SI) The image below shows an example of MENA's analog dialing intercept, in the spectral and acoustical domains.
(S//SI) The spectrogram in the top tier shows the sequence: a dial tone, then a 3-digit analog number, ring-back, and finally voice indicating the call got through. The click sequence produced by the dial rotation is worth examining in more detail:

## (U) The New Capability

(S//SI) DNR in this case amounts to careful retention of very short pulses, as a given dialed digit corresponds to exactly two such pulses. S202B11 (HLT Operational Technologies) has developed an algorithm to break out the numbers. Full details about this DNR algorithm may be found at

## MENA DNR webpage

...which also contains algorithm code in MATLAB.

## (S//SI) About BABBLEQUEST

(S//SI) For nearly a decade BABBLEQUEST has been a workhorse architecture processing millions of intercepts each month, to provide DNR of several types, Facsimile Activity Detection, and extensive speech technical exploitation using many and varied state-of-the-art algorithms of both internal and external origin.
(U) POCs:
(U//FOUO) If you have special needs regarding these services, please contact one of the below:

- Adolf Cusmariu (Technical Director, HLT Operational Technologies), at
![img-1.jpeg](img-1.jpeg)
(Speech Services Project Manager), at
(SASBLEQUEST Project Manager), at
(Customer Representative), at

"(U//FOUO) SIDtoday articles may not be republished or reposted outside NSANet without the consent of S0121 (DL sid_comms)."
