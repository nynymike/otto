# Minutes from pre-OTTO organization meeting 5/20/15

## Attending the call:
- Mike Schwartz
- Judith Bush
- George Fletcher

## Apologies
- Janusz Ulanowski

## Discussion of Charter

Charter has been subnmitted by the Kantara Leadership Council.

## Discussion of Use Cases

Discussion of SAML v. OpenID Connect discovery. 

George mentioned that Webfinger allows queries, and could be useful as a base. 
But any discovery mechanism would need to include security. For more info on user 
discovery with good auditing, privacy, and user controls, attend George's talk
at CIS or watch it when its hopefully online! 

Discussion of how members of federations trust other members can vary. Hopefully 
OTTO would facilitate an entity using either algorithmic rules or one-by-one 
specification for trust.

Judith has been reviewing SAML and OpenID Connect discovery, and provided these links: 
Jones, Paul, Joseph Smarr, Gonzalo Salgueiro, and Michael Jones. RFC 7033: 
WebFinger. PROPOSED STANDARD. IETF. Accessed May 18, 2015. http://tools.ietf.org/html/rfc7033.

Sakimura, Nat, John Bradley, Michael B. Jones, and Edmund Jay. OpenID Connect 
Discovery 1.0 Incorporating Errata Set 1. Spec. OIDF, November 8, 2014. 
http://openid.net/specs/openid-connect-discovery-1_0.html.

George described the query features of Webfinger. Is the discovery endpoint of 
OTTO a profile of WebFinger? 

Mike pointed out that the OpenID Connect perhaps envisions federations to define values
For example, the definition of 'arm' in the Core Spec:
  http://openid.net/specs/openid-connect-core-1_0.html#IDToken
It says "The definition of particular values to be used in the amr Claim is beyond the 
scope of this specification." The federation metadata may contain identifiers and human 
understandable documentation about what the values mean.

Justin Richer recently outlined an idea on an UMA WG Binding Obligations subgroup call 
where federations may not be needed with the proper application of Trustmarks--a way to 
point back from the OP to which federation it belongs. A trust framework may not publish 
a list of memberships. George pointed out that a while back, MitreID was awarded a 
loa-1 trustmark by Kantara:
  https://kantarainitiative.org/mitreid-awarded-loa-1-csp-kantara-trustmark-grant

What exactly is a trustmark? Just a link back to the federation? Or is it some kind of 
encrypted text that can be validated.

## Threat Sharing Use Case

Mike feels that sharing threat information between domains is a compelling
use case for OTTO. There might be mechanisms or schema that we want to consider in 
the design of OTTO. 

Mike has reached out to Threatconnect, a software firnm for inter-domain 
security collaboration http://www.threatconnect.com

ThreatConnect has announced a free version of their software if you are a threat 
information sharing organization (ISAO): http://gluu.co/free-isac-isao

Other efforts exists at sharing threat information. OpenID Connect has a working group 
called RISK that is working to create collaboration around account state changes.
Facebook has a threat exchange: https://threatexchange.fb.com

Although not specifically aimed at threat sharing, OASIS has announced a 
"Cyber Threat Intelligence" (CTI) Technical Committee
  http://gluu.co/oasis-cti
  
## Action Items:

- Continue to work on use cases.

- We need a logo? Any ideas?

## Gotomeeting

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

