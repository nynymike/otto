# OTTO Use Cases

## Entity Discovery

One of the core features of multi-party federation is the ability to centrally publish who is a member.
A domain may want to discover all the OpenID Providers, Relying Parties, UMA Authorization Servers, 
UMA Resource Servers, and UMA clients in the federation. The federation may vet and include details about 
each entity.

### Considerations:

- Private Discovery: In some cases, authorization may be required to get access to federation member details. Use UMA?
- Leverage Webfinger? RFC 7033. Perhaps OTTO entity discovery is a profile of Webfinger?
- Allows per entity query?
- JOSE signing of metadata? 

