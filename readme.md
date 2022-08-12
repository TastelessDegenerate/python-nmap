# Python NMAP using Kali Rolling 
> https://pypi.org/project/python-nmap/




```json
{'addresses': {'ipv4': '127.0.0.1'},
  'hostnames': [],
  'osmatch': [{'accuracy': '98',
              'line': '36241',
              'name': 'Juniper SA4000 SSL VPN gateway (IVE OS 7.0)',
              'osclass': [{'accuracy': '98',
                            'cpe': ['cpe:/h:juniper:sa4000',
                                    'cpe:/o:juniper:ive_os:7'],
                            'osfamily': 'IVE OS',
                            'osgen': '7.X',
                            'type': 'firewall',
                            'vendor': 'Juniper'}]},
              {'accuracy': '91',
              'line': '17374',
              'name': 'Citrix Access Gateway VPN gateway',
              'osclass': [{'accuracy': '91',
                            'cpe': [],
                            'osfamily': 'embedded',
                            'osgen': None,
                            'type': 'proxy server',
                            'vendor': 'Citrix'}]}],
  'portused': [{'portid': '443', 'proto': 'tcp', 'state': 'open'},
              {'portid': '113', 'proto': 'tcp', 'state': 'closed'}],
  'status': {'reason': 'syn-ack', 'state': 'up'},
  'tcp': {113: {'conf': '3',
                'cpe': '',
                'extrainfo': '',
                'name': 'ident',
                'product': '',
                'reason': 'conn-refused',
                'state': 'closed',
                'version': ''},
          443: {'conf': '10',
                'cpe': '',
                'extrainfo': '',
                'name': 'http',
                'product': 'Juniper SA2000 or SA4000 VPN gateway http config',
                'reason': 'syn-ack',
                'state': 'open',
                'version': ''}},
  'vendor': {}}

```


## TroubleShoot 

https://www.maketecheasier.com/change-console-fonts-in-ubuntu/

## References

https://www.freecodecamp.org/news/enhance-nmap-with-python/
