# Schema 

The federation can publish a list of supported schema including:

1. *User Claims*
2. *OpenID Connect Scopes*
3. *OpenID Connect Scopes: User Claim Mapping"
4. *UMA Scopes*
5. *ACR URI's* Example: https://federation.org/schema/acr/duo
6. *AMR identifiers*: 
OpenID Connect defines 'amr' in the id_token: http://openid.net/specs/openid-connect-core-1_0.html#IDToken
The values used for amr can be defined by the federation. An example AMR values could be:
  Example: ['duo', '10', 'https://federation.org/schema/acr/duo', 'silver']
7. *Resource:Policy Mapping* Example: {'federation/over21': ['https://federation.org/schema/uma/releaseAge'],
                                       'library/inter-library-loan': [https://federation.org/schema/uma/isMember']'}
8. Contain naming system to allow distinct, non-reassignable identification of a person, like
edupersonUniqueID.