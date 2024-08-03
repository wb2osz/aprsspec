# Unofficial APRS Protocol Specification 1.2 #

The APRS Protocol Reference 1.0.1 was developed by the APRS Working Group and published in 2000.   

In 2004, the Working Group approved a list of corrections, clarifications, and new features summarized here:  [http://www.aprs.org/aprs11.html](http://www.aprs.org/aprs11.html). Unfortunately they were never merged back into the original document.
 
Since that time all we have is a bunch of "proposals" from Bob WB4APR (SK) found at [http://www.aprs.org/aprs12.html](http://www.aprs.org/aprs12.html).   Some of the features have been widely implemented, others are just ideas for discussion that never went anywhere.  There is no dividing line.  Some of the links point to places that no longer exist.

APRS is still alive and well a quarter of a century later, with many new products, computer applications, and creative uses.  Implementation is more difficult and error prone with the information scattered around and incomplete.  Some people, trying to implement APRS, might not even know there were any updates since the original.  

This is an independent UNOFFICIAL compilation of the original spec and all of the relevant updates since 2000.  This is not endorsed by the APRS Working Group and should not be considered to be the “official” specification.  The position of the APRS Working group is that the “official” documents are still the original spec and Bob’s version of the errata on his site. 

Naming convention:

APRS12b.pdf is DRAFT b of version 1.2.

APRS12c.pdf is DRAFT c of version 1.2.  etc.


## APRS Digipeater Algorithm ##

Anyone wanting to understand how an APRS digipeater works faces a similar problem.  There was not a good definition.  It had to be pieced together from various places and reverse engineering poorly documented legacy 20th Century TNCs.  As a result, we see inconsistent, and sometimes very wrong implementations.

Here is my attempt to clear up the confusion.


## APRS IGate Description ##

Information about developing an APRS Internet Gateway ("IGate") exists but it is a little sparse.  For now, see [https://github.com/wb2osz/direwolf-doc/blob/main/Successful-APRS-IGate-Operation.pdf](https://github.com/wb2osz/direwolf-doc/blob/main/Successful-APRS-IGate-Operation.pdf)  for supplemental information.  Just ignore the parts mentioning direwolf.  Eventually, I should have a more generic version not revolving around one implementation.


## Recommended Reading for all APRS Users ##

The protocol specification can be confusing and difficult to digest.  A more gentle introduction can be found at:  [https://github.com/wb2osz/direwolf-doc/blob/main/Understanding-APRS-Packets.pdf](https://github.com/wb2osz/direwolf-doc/blob/main/Understanding-APRS-Packets.pdf)


## How to Get Started in APRS ##

How can a newcomer get started in APRS?  
A web search produces mostly:

- Overly technical information such as the protocol specification. 
- Has outdated information.  (e.g,  you must buy a discontinued 1980s style TNC)
- Only talks about trackers and aprs.fi.
- Leads you to believe that buying a very expensive radio is only way to get started. 
- Very brief description with a link to [aprs.org](http://www.aprs.org/) which would scare a beginner away.


If you search YouTube, the top of the list is “APRS The Most Worthless Mode in Ham Radio”   with APRS = a pile of poo in the picture.  That’s not a good first impression.

There are many interesting videos, but where does the newcomer start?  How would the newcomer know which were outdated or giving bad advice?

This is a crowd-sourced list of the best resources for a beginner.


## Feedback ##

The UNOFFICIAL Protocol Specification compilation is a DRAFT version with known issues.  Your feedback is welcome.  Errors and suggestions for improvement should be reported here: [https://github.com/wb2osz/aprsspec/issues](https://github.com/wb2osz/aprsspec/issues)   for tracking.

General discussions about the APRS Protocol should go to the discussion forum  [https://groups.io/g/APRS](https://groups.io/g/APRS)

73, John WB2OSZ