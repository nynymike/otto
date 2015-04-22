# Minutes from pre-OTTO organization meeting 4/22/15

## Attending the call:
- Mike Schwartz
- Keith Hazelton
- Judith Bush

## Discussion of Charter

We spent some time updating the charter. Changelog can be review on github:
- https://github.com/nynymike/otto/blob/master/kantara/charter.md

## Potential new members

Mike talked with Prateek Mishra from Oracle, Bob Blakely from Citibank, and Rainer Hörbe.
Prateek may be interested to join. Bob indicated that he'll try to find someone in his group.
Rainer says he is busy until the end of June, but may be interested to join at that point.

## Documentation format

Had a short discussion about [Mkdocs](http://www.mkdocs.org). Its a nice format because it uses markdown, which is viewable
on Github. It can also be rendered to html for improved navigation. Having a nice website may help
encourage developer adoption.

## Discussion of Use Cases

Use cases are narrative descriptions. 

There was some discussion on the dynamic Client registration use case, which would be 
used to achieve something between dynamic registration and manual registration. For example:
"allow any client in the federation to register at an OP".

Judith had some suggestions about standardizing policy discovery and consent. Gluu worked 
on a sample federation site that has a sample partipant agreement, federation agreement, 
data protection policy and user banner [http://ox.gluu.org/tech-info/doku.php](http://ox.gluu.org/tech-info/doku.php)
 
A use case might include how an federation could automate agreement to policies 
when an entity joins, using the OTTO `/join` API. OpenID Connect includes  `policy_uri` and 
`tos_uri` for client registration. Perhaps the federation could leverage these, or define new
parameters to simplify and standardize policy review, and support future standards that 
may automate privacy agreements evaluation by individuals and companies, whether 
expressed in words or machine parsable format.

## Action Items:
- Still need to talk to Don Thibeau. There was a [press release](http://gluu.co/oixnet) this week 
  about a new Registry for "trust frameworks."
- Judith to work on the policy agreement use case
- Mike to work on the client registration use case

## Gotomeeting

This is the new gotomeeting from now just for OTTO. Next week we will change to this one:

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

## Other

Judith committed her [handwritten notes](./003-otto_notes_jeb-4-22-15.pdf)
