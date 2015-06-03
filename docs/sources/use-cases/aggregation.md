# Aggregation of Authorization and User Claims

Could OTTO provide tokens that aggregate authorizations from multiple backend 
OAuth2 servers, both OpenID Connect and UMA?

For exmaple:
```
 { 'iss': 'https://federation.ecosystem.org',
  'scope': 'https://federation.ecosystem.org/scope/authz/2FA',
  'uma_as_list': {'https://authz.acne.com': {'scopes': 'https://scope1'}, 
                  'https//authz.wayne.com': {'scopes': 'https://scope2'}},
  'openid_op_list': {'https://idp.acme.com':{'sub': 'mike@acme.com',
                                              'acr': 'https://duo',
                                              'amr': ['10', 'US', 'duo'}}, 
                      'https://idp.wayne.com': {'sub': '0394398',
                                               'gender': 'M',
                                                'acr': 'https://password',
                                                'amr': ['basic', '31415'}}
 }
```