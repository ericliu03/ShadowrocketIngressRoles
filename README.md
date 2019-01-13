# Shadowsocks ingress rules


## Setup Guide

### for macOS: ShadowsocksX-NG-R: 
https://github.com/qinyuhang/ShadowsocksX-NG-R
 - Hit paper plane 
 - Advance Preference, change `ACL White List URL` to the follow url
 - `https://raw.githubusercontent.com/ericliu03/ShadowrocketIngressRoles/master/ssr_ingress_rules.acl`
 - Hit paper plane again -> `White List Mode`

###for iOS: shadow rocket: 
https://liguangming.com/Shadowrocket
 - use following url as rule source
 - `https://raw.githubusercontent.com/ericliu03/ShadowrocketIngressRoles/master/sr_ingress_rules.conf`

### for Windows: shadowsocks
https://github.com/shadowsocks/shadowsocks-windows/releases
- right click paper plane
- PAC -> use online PAC
- edit online pac url to 
- `https://raw.githubusercontent.com/ericliu03/ShadowrocketIngressRoles/master/ss_ingress_pac.pac`


## Reference Rules:
1. ACL rules for SSR-NG-R: https://github.com/ACL4SSR/ACL4SSR
1. PAC rules for shadowrockets: https://github.com/h2y/Shadowrocket-ADBlock-Rules


