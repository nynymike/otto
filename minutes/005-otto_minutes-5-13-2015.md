# Minutes from pre-OTTO organization meeting 5/13/15

## Attending the call:
- Mike Schwartz
- Judith Bush
- Janusz Ulanowski

## Discussion of Charter

Charter was submitted to the Kantara Leadership council for review:
- https://github.com/nynymike/otto/blob/master/kantara/charter.md
Hope to hear back in a week or so. 

## Discussion of Use Cases

Most of the session was devoted to discussing use cases. 

* A person uses his state issued drivers license to perform a transaction in a different state. 
* Buying alcohol from an out-of-state vendor that requires proof that you are older than 21, but
  to whom you don't want to release the DOB.
* Inter-library loans: every library could perhaps standardize APIs. 
* Threat information sharing between members
* Security incident response between members

Several schema use cases were discussed:

1. Certainly user claim schema will need to be published by the federation, as it is in SAML
2. OpenID Connect scopes, and scopes-to-claim mapping may be published by the federation.
3. ACR and AMR -- details needed for cross domain authentication. For example, how can one
   domain send a person to be authenticated in another domain by a specific method (i.e. duo auth)?
4. Resources: What if domains have certain API's in common. For example, if the vendor selling
   alcohol needs to know the person is over 21, but not their DOB. Perhaps the federation could
   define a standard API endpoint (and respective policy) that makes this information available,
   perhaps only with the user's consent to release. We talked about if the federation might 
   be a convenient place to list these APIs.

## Action Items:
- Work on / think about use cases! 
[Github Use Cases](https://github.com/nynymike/otto/tree/master/docs/sources/use-cases)
- Follow up with ThreatConnect to see if they might want to be a guest on a call to help
  us understand if including any threat sharing schema might be useful 
  http://www.threatconnect.com/

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

