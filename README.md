# The APRS Documentation Project #

It's hard to find good information on APRS.  A web search produces mostly outdated misinformation and little of value.  This is the beginning of a collection of the essential documentation.


## What is APRS? ##

In the words of its creator:


> “**APRS is not a vehicle tracking system**. It is a two-way tactical real-time digital communications system between all assets in a network sharing information about everything going on in the local area. On ham radio, this means if something is happening now, or there is information that could be valuable to you, then it should show up on your APRS radio in your mobile.” 

 -WB4APR (SK)

Read more:  [What-is-APRS.pdf](https://github.com/wb2osz/aprsspec/raw/main/What-is-APRS.pdf)


## The Best APRS Presentations ##

Club meetings and ham conventions are always looking for speakers.  There was nothing about APRS during the 2024 Dayton forums.

Suppose you wanted to give an APRS presentation at a club meeting or ham convention.  But...
It's a big job. You are not sure where to start and would like to use / adapt something already done rather than starting from nothing.

Where can you find suitable presentations?  I’ve tried searching and could not find much that was worthwhile.

I’m throwing this out as a challenge to the APRS community.  Please help to make a list of the best presentations that others could use.  

[The-Best-APRS-Presentations.pdf](https://github.com/wb2osz/aprsspec/raw/main/The-Best-APRS-Presentations.pdf)

## How to Get Started in APRS ##

How can a newcomer get started in APRS?  

A web search produces mostly:

- Very specialized such as the configuration of a specific radio.
- Outdated information.  (e.g.  you must buy a legacy 1980s style TNC or references to software apps abandoned decades ago)
- Only talks about trackers and aprs.fi.
- Leads you to believe that buying a very expensive radio is only way to get started. 
- Overly technical information such as the protocol specification. 
- Very brief description with a link to [aprs.org](http://www.aprs.org/) which would scare a beginner away.


If you search YouTube, the top of the list is “APRS The Most Worthless Mode in Ham Radio”   with APRS = a pile of poo in the picture.  That’s not a good first impression.

There is some very good material out there, but how can the newcomer find it among all the clutter?

[How-to-Get-Started-in-APRS.pdf](https://github.com/wb2osz/aprsspec/raw/main/How-to-Get-Started-in-APRS.pdf)

This is a crowd-sourced list of the best resources for a beginner.  I need YOUR help to find the best resources.




## *** Recommended Reading for all APRS Users *** ##


What does this mean?


    N83MZ>T2TQ5U,WA1PLE-4*:`c.l+@&'/'"G:} KJ6TMS|!:&0'p|!w#f!|3


What is wrong with this packet?


    WA2GUG-15>TQ0V4V,TCPIP,WA2GUG-15,K1EQX-7,N3LLO-3,WIDE2*,RFONLY,NOGATE:}KB1CRN-14>TQ0V4V,WIDE1-1,WIDE2-1,WB2ZII-13,TCPIP,WA2GUG-15*:`e4Tp,Pu/`"4/}Keep on truckin`_1<0x20>

You could try to digest the APRS Protocol Spec but that would probably give you an upset stomach.  And a headache.  A more gentle introduction can be found at:  [Understanding-APRS-Packets.pdf](https://github.com/wb2osz/aprsspec/raw/main/Understanding-APRS-Packets.pdf)

Be sure to read the part about the mistakes that people make.  Read this carefully if you don't want to end up as an example of what not to do.

## APRS Thursday ##

APRS Thursday is a net managed by Michael KC8OWL, held every Thursday with the aim of growing message activity on APRS across the world.  Many manufacturers are now including APRS functionality as a standard feature, making APRS more accessible, and hopefully more popular than ever.

The APRS Thursday net is held each week on Thursday between the hours of 00:00:00UTC to 23:59:59UTC.
Based on your browers locale, you can check into the net each week anytime between and in your local timezone. 

For more information see:  [https://aprsph.net/aprsthursday/](https://aprsph.net/aprsthursday/)   or    [https://aprs.to/events/aprs_thursday/about/](https://aprs.to/events/aprs_thursday/about/) 


## Contact the International Space Station (ISS) with APRS ##

Did you know that the International Space Station (ISS) and some amateur satellites carry APRS digipeaters?  You don’t need fancy equipment to use the ISS digipeater.  I saw a video where someone was successful with an HT and a quarter wave whip antenna.  Of course a better antenna will increase your chances of success.

Details:  [APRS-Digpeaters-in-Space.pdf](https://github.com/wb2osz/aprsspec/raw/main/APRS-Digpeaters-in-Space.pdf)



## Unofficial APRS Protocol Specification 1.2 ##

The APRS Protocol Reference 1.0.1 was developed by the APRS Working Group and published in 2000.   

In 2004, the Working Group approved a list of corrections, clarifications, and new features summarized here:  [http://www.aprs.org/aprs11.html](http://www.aprs.org/aprs11.html). Unfortunately they were never merged back into the original document.
 
Since that time all we have is a bunch of "proposals" from Bob WB4APR (SK) found at [http://www.aprs.org/aprs12.html](http://www.aprs.org/aprs12.html).   Some of the features have been widely implemented, others are just ideas for discussion that never went anywhere.  There is no dividing line.  Some of the links point to places that no longer exist.

APRS is still alive and well a quarter of a century later, with many new products, computer applications, and creative uses.  Implementation is more difficult and error prone with the information scattered around and incomplete.  Some people, trying to implement APRS, might not even know there were any updates since the original.  

This is an independent UNOFFICIAL compilation of the original spec and all of the relevant updates since 2000.  This is not endorsed by the APRS Working Group and should not be considered to be the “official” specification.  The position of the APRS Working group is that the “official” documents are still the original spec and Bob’s version of the errata on his site. 

Naming convention:

[APRS12b.pdf](https://github.com/wb2osz/aprsspec/raw/main/APRS12b.pdf) is DRAFT b of version 1.2.

[APRS12c.pdf](https://github.com/wb2osz/aprsspec/raw/main/APRS12c.pdf) is DRAFT c of version 1.2.  etc.

A release version will drop the letter at the end.


## AX.25 Protocol Specification 2.2, fourth edition ##

APRS is generally transmitted as AX.25 Unnumbered Information (UI) frames. 

[https://www.ax25.net/AX25.2.2-Jul%2098-2.pdf](https://www.ax25.net/AX25.2.2-Jul%2098-2.pdf)

LoRa APRS uses plain text with the TNC-2 monitoring format.



## APRS Digipeater Algorithm ##

The APRS Working Group never produced an APRS digipeater specification.  Probably because existing 1980s style packet radio TNCs were being re-purposed at the time.    Someone wanting to implement a digipeater  had to piece together clues from various places and imitate poorly documented legacy 20th Century TNCs developed long before the advent of the [WIDEn-N paradigm](http://www.aprs.org/fix14439.html).  As a result, we see inconsistent, and sometimes very wrong implementations.

Here is my attempt to clear up the confusion.  [APRS-Digipeater-Algorithm.pdf](https://github.com/wb2osz/aprsspec/raw/main/APRS-Digipeater-Algorithm.pdf)


## APRS IGate Description ##

Information about developing an APRS Internet Gateway ("IGate") exists but it is a little sparse.  For now, see [Successful-APRS-IGate-Operation.pdf](https://github.com/wb2osz/direwolf-doc/raw/main/Successful-APRS-IGate-Operation.pdf)  for supplemental information.  Just ignore the parts mentioning direwolf.  Eventually, I should have a more generic version not revolving around one implementation.




## Feedback ##

The UNOFFICIAL Protocol Specification compilation is a DRAFT version with known issues.  Your feedback is welcome.  Errors and suggestions for improvement should be reported here: [https://github.com/wb2osz/aprsspec/issues](https://github.com/wb2osz/aprsspec/issues)   for tracking.

General discussions about the APRS Protocol should go to the discussion forum  [https://groups.io/g/APRS](https://groups.io/g/APRS)

73, John WB2OSZ