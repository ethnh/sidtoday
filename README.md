# SIDtoday Files converted to Markdown & Json

2006/2006-01-26_SIDToday_-_Top_10_SIDtoday_Articles_of_2005.pdf.md
(U) 'Top 10' SIDtoday Articles of 2005

FROM: the SIDtoday editor
Unknown
Run Date: 01/26/2006
(U) With the year 2005 behind us, SID today thought it might be interesting to determine which articles had the highest readership for the year. As you can see, they are a combination of administrative information, success stories and human interest. Here's the list, in order:

1. (U//FOUO) Redesign of A\&P
2. (U) Well Done! [announcement of the promotions for 2005]
3. (U) Christmas in Iraq
4. (S//SI) NSA Tipoff Leads to Rescue of Serviceman in Afghanistan
5. (S) Saudi Assassination Squelched -- SID Employee Receives FBI Award
6. (U) What Is a J-2?
7. (U) 30 January, Iraq Election Day
8. (S) The Saudi Assassination Plot -- How It Was Thwarted
9. (S) Success Against al-Zarqawi's Group in Northern Iraq
10. (S) New Tactical Collection System Joins the War on Terrorism
"(U//FOUO) SIDtoday articles may not be republished or reposted outside NSANet without the consent of S0121 (DL sid_comms)."

DYNAMIC PAGE -- HIGHEST POSSIBLE CLASSIFICATION IS TOP SECRET // SI / TK // REL TO USA AUS CAN GBR NZL DERIVED FROM: NSA/CSSM 1-52, DATED 08 JAN 2007 DECLASSIFY ON: 20320108

_SIDtoday_ is the internal newsletter for the NSA's most important division, the Signals Intelligence Directorate. _The Intercept_ released four years' worth of newsletters in batches, starting with 2003, after editorial review.

You can read our _SIDtoday_ reporting and browse the documents online [here](https://theintercept.com/snowden-sidtoday).

This repository contains _SIDtoday_ articles released by _The Intercept_, in PDF format and organized by year.

## Downloading and verifying

You can download all of the documents release so far as a zip file [here](https://github.com/firstlookmedia/sidtoday/archive/master.zip).

Every commit in this repository is cryptographically signed using PGP. If you'd like to verify the integrity of the documents, you can either use [GitHub's interface](https://github.com/blog/2144-gpg-signature-verification), or you can manually verify the signatures like this:

```sh
# Download the signing keys
gpg --recv-keys "927F419D7EC82C2F149C1BD1403C2657CD994F73"
gpg --recv-keys "6C577D0B6ABD6AF3D513EF47A72F3B3D3E45FD67"

# Clone the git repository
git clone https://github.com/firstlookmedia/sidtoday.git
cd sidtoday

# Verify the signatures on each commit
git log --show-signature
```
