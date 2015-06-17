# OTTO Meeting minutes 6/17/15

## Attending the call:
- Mike Schwartz
- Janusz Ulanowki
- Judith Bush
- Keith Hazelton
- E. Anwar Reddick
- George Fletcher

## Kantara Process

OTTO wiki page:
*  http://kantarainitiative.org/confluence/display/OTTO/Home

Mailing list:
* http://kantarainitiative.org/mailman/listinfo/wg-otto

Kantara organizational kickoff next weds. We'll discuss quorum, minutes approval,
elections, and IT stuff and more! 

## Discussion of TrustMarks

Anwar gave a summary of GaTech's Trustmark program, which was a previously
awarded NSTIC pilot:

Trustmarks are a statement of conformance to a definition. Currently trustmarks 
are expressed as signed XML, expressing certain conformance criteria. The criteria 
also specifies assessment requirements is included in the trustmark definition. 
Helps to faciliate an apples:apples comparison of trustmarks, or to figure out 
the trust-delta.

See more information on trust marks:
 https://trustmark.gtri.gatech.edu

Keith wonders what are the use cases that are driving the demand for trust level
conformance? Anwar cites the National Identity Exchange federation (NIEF), a US 
federation, connecting law enforcement agencies that need to cooperate with
health care, cyber-security and other domains. Their federation needs a quick legal 
alignment on the rules for access, including terms and compliance assessment. 

There is overlap between trustmarks and the "Vectors of Trust" ad-hoc working group at the 
IETF. The Vectors of Trust effort is to publish values that describe what kind of 
authentication happened (i.e. to replace NIST 800-63, which uses increasingly useless 
1-4 rating). Once developed, these vectors of trust could be indicated in the 
trustmark, perhaps as values for amr, see amr in:
  http://openid.net/specs/openid-connect-core-1_0.html#IDToken

Keith inquired what would be the range of governance models for the issuance of 
trust marks? Mike contends that OTTO should be trust model neutral, and support 
low trust and high trust use cases.

Judith commented on how the federation needs to express "here's how you evaluate someone 
who has one of our trustmarks."

How could applications make decisions based on trustmark participation? Would a trustmark
issued by a federation be published in the OP discovery information? Anwar
clarified that an RP might require a certain trustmark before it trusts an authentication
from an OP; conversely, an OP might require one or more trustmark for dynamic registration? 
Mike pointed out that we had previously discussed a use case for OTTO to restrict
client registration. 

Anwar clariied that trustmarks are issued by a Trustmark provider. A trustmark "tip" 
can help an entity by indicating what trustmarks are required (issued by which providers).

Judith volunteerded that OTTO could help specify: if the federation issues trustmarks, 
they are here... if the federation accepts trustmarks, here they are...

Mike made the point that JSON would be easier to work with, and more developer friendly. 
The GaTech Trustmark NSTIC pilot is proceeding with XML, and may not be able to switch
at this point. Both formats? The substance of the data is the same. But Anwar noted
that others have also requested JSON versus XML.

For more questions on trustmarks, you can email the GTRI Trustmark Team at 
 TrustmarkFeedback@gtri.gatech.edu

## Next week's Gotomeeting Details

Next week's Gotomeeting:

### https://global.gotomeeting.com/join/162399285

- United States: +1 (224) 501-3318
- Australia: +61 2 8355 1039
- Austria: +43 (0) 7 2088 2172
- Belgium: +32 (0) 42 68 0180
- Canada: +1 (647) 497-9379
- Denmark: +45 (0) 89 88 05 39
- Finland: +358 (0) 931 58 4588
- France: +33 (0) 170 950 589
- Germany: +49 (0) 692 5736 7301
- Ireland: +353 (0) 19 036 187
- Italy: +39 0 294 75 15 37
- Netherlands: +31 (0) 108 080 116
- New Zealand: +64 (0) 9 801 0294
- Norway: +47 21 51 81 86
- Spain: +34 911 23 4248
- Sweden: +46 (0) 852 500 516
- Switzerland: +41 (0) 435 0824 41
- United Kingdom: +44 (0) 330 221 0099

- Access Code: 162-399-285