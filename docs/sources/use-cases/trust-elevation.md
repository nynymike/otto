# Trust Elevation

OpenID Connect defines acr and amr in the id_token:
  http://openid.net/specs/openid-connect-core-1_0.html#IDToken
  
Clients can also register preferred acr. 

OpenID Connect OP Discovery returns which ACR's are supported.
 "acr_values_supported": ["https://schema.gluu.org/openid/acr/method/duo"]
 
 