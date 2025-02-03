# Serverless config for iran


With [serverless_config_for_iran](https://github.com/patterniha/xray_configs/blob/main/serverless_config_for_iran) all services except telegram are accessible in iran without using any server.

Although websites that have Sanctioned Iran are not accessible with serverless methods.

Using methods:
  * chain-fragment (tlshello + tcp-fragment)
  * noise for UDP
  * uTLS for DOH (DOH domain-fronting)
  * using fallback-addresses for facebook and instagram

Requirements:
  * xray-core >= v25.1.30 (v2rayng >= 1.9.34)
  * Loyalsoldier geoip.dat and geosite.dat, and bootmortis iran-hosted-domains iran.dat:
    - https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geoip.dat
    - https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geosite.dat
    - https://github.com/bootmortis/iran-hosted-domains/releases/latest/download/iran.dat

