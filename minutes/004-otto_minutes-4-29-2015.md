# Minutes from pre-OTTO organization meeting 4/22/15

## Attending the call:
- Mike Schwartz
- George Fletcher
- Janusz Ulanowski

## Discussion of Charter

Judith provided some great feedback last week. Please review:
- https://github.com/nynymike/otto/blob/master/kantara/charter.md

## Github files

Note all docs and minutes are located on [Github](https://github.com/nynymike/otto)

## Discussion of Use Cases

We discussed "entity discovery" and the "client registration" use cases.

We consolidate the "op-discovery" and "private-discovery" use cases into "entity-discovery".

Client registration raised some questions. 

At first we considered using 

- During OpenID Connect client registration, how would the client reference itself in the 
context of the federation? Is client ___ ? a member of federation. What is ___ ? In SAML,
the SP and IDP use entityID, which is usually the URL of the metatdata (or a URN). Perhaps 
jwks_uri?

- Will OTTO need to authenticate the client in order to validate that they hold the 
private key associated with the jwks_uri they are registering? Otherwise, the client
could register bogus redirect-uri's. 

- Does OIDC allow extension of dynamic client registration request?

- Could we add a new client parameter to OpenID Connect Client registration, to provide
the OP a hint about to which the client is a member, i.e. "federationID"


## Action Items:
- Research how JOSE standards enable signing of metadata
- Work more on flushing out the use cases. Feel free to submit directly to 
[Github Use Cases](https://github.com/nynymike/otto/tree/master/docs/sources/use-cases)

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

