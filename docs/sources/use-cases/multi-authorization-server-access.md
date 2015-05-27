# Access to more than one UMA authorization server

Could OTTO provide tokens that represent authorizations from multiple backend 
OAuth2 servers, both OpenID Connect and UMA. 

For exmaple, 
 { 'iss': 'https://federation.ecosystem.org',
  'scope': 'https://federation.ecosystem.org/scope/authz/2FA',
  'uma_as_list': ['https://as1.example.com': {'scopes': 'https://scope1'}, 
                  'https//as2.example.com': {'scopes': 'https://scope2'}],
  'openid_op_list': [{'https://idp.acme.com':{'sub': 'mike@acme.com'}}, 
                      'https://idp.acme.com': {'sub': '0394398',
                                               'gender': 'M'}],
  .
  .
  .
 }
 
 