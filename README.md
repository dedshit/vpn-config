# vpn-config

 ### Another random shit, here i will upload free & premium either in ovpn or conf file format from this apk.You can use openvpn to access these this files

  ## VPN Indonesia-Unlimited VPN
   
  ## LINK: https://play.google.com/store/apps/details?id=free.vpn.secure.turbo.proxy.hotspot.vpnindonesia
  
  ![](https://user-images.githubusercontent.com/62318734/226526269-b808d28e-4ab8-432f-b553-312b7f771eaa.png)
  
  # Ukraine-{Kiev-1} (premium) [**SAMPLE**]
   
   ## Config for OpenVPN 2.x
## Enables connection to GUI/TERMINAL

```management /data/user/0/free.vpn.secure.turbo.proxy.hotspot.vpnindonesia/cache/mgmtsocket unix
management-client
management-query-passwords
management-hold

setenv IV_GUI_VER "free.vpn.secure.turbo.proxy.hotspot.vpnindonesia 1.8.4.9" 
setenv IV_SSO openurl,crtext
setenv IV_PLAT_VER "29 10 armeabi-v7a samsung msm8937 SM-J610F"
machine-readable-output
allow-recursive-routing
ifconfig-nowarn
client
verb 0
connect-retry 2 300
resolv-retry 60
dev tun
remote 95.85.72.172 1194 udp
explicit-exit-notify 

<ca>
-----BEGIN CERTIFICATE-----
MIIB1zCCAX2gAwIBAgIURi9vY9DCjZc2L7eXlCvjDZ7gIcEwCgYIKoZIzj0EAwIw
HjEcMBoGA1UEAwwTY25fY3p4eTl4cjBZbFpsV0M1YzAeFw0yMjA1MTUxMjE0NDJa
Fw0zMjA1MTIxMjE0NDJaMB4xHDAaBgNVBAMME2NuX2N6eHk5eHIwWWxabFdDNWMw
WTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAATy9icWjIX/QJ++JT1cKEbr/s5CCw4H
qeNtqDt6eMGPi/S3GD0Ka3YW/Rd7INd3IszA4FnV3ZkTlIt+FREc+cpwo4GYMIGV
MB0GA1UdDgQWBBQnT2wHfzZ65J4lSrphmpbhl/VohTBZBgNVHSMEUjBQgBQnT2wH
fzZ65J4lSrphmpbhl/VohaEipCAwHjEcMBoGA1UEAwwTY25fY3p4eTl4cjBZbFps
V0M1Y4IURi9vY9DCjZc2L7eXlCvjDZ7gIcEwDAYDVR0TBAUwAwEB/zALBgNVHQ8E
BAMCAQYwCgYIKoZIzj0EAwIDSAAwRQIhAKQF1SnWuhA6cf8H8McM6wgfr73d0ekC
i9lrFdBqwrLvAiAJXq5BLpHcTRMJp6wchjbqIdXMH8Jprd36Nn/v5X+sxA==
-----END CERTIFICATE-----
</ca>
<key>
-----BEGIN PRIVATE KEY-----
MIGHAgEAMBMGByqGSM49AgEGCCqGSM49AwEHBG0wawIBAQQgafn7cAgsSgs4Hha3
PibJwO2uJz+dWraQDw75voeCQ7OhRANCAARDC+W14H7YQQeIFpvNk8cIp8AB63XT
xCnJZ5GUOdhPY3IpQ7z/RlFdrXPsYp6DmkeSPZXSI3Pgw4Ct8PqKRQIZ
-----END PRIVATE KEY-----
</key>
<cert>
-----BEGIN CERTIFICATE-----
MIIB4TCCAYegAwIBAgIRAJWl/hDOgf6XbAam+zbVAagwCgYIKoZIzj0EAwIwHjEc
MBoGA1UEAwwTY25fY3p4eTl4cjBZbFpsV0M1YzAeFw0yMjA1MTUxMjE0NDlaFw0y
NDA4MTcxMjE0NDlaMBkxFzAVBgNVBAMMDmdjb3JlX3VrcmFpbmU2MFkwEwYHKoZI
zj0CAQYIKoZIzj0DAQcDQgAEQwvlteB+2EEHiBabzZPHCKfAAet108QpyWeRlDnY
T2NyKUO8/0ZRXa1z7GKeg5pHkj2V0iNz4MOArfD6ikUCGaOBqjCBpzAJBgNVHRME
AjAAMB0GA1UdDgQWBBQel3z5l6Np5dHvG3gvilnjZ58rdDBZBgNVHSMEUjBQgBQn
T2wHfzZ65J4lSrphmpbhl/VohaEipCAwHjEcMBoGA1UEAwwTY25fY3p4eTl4cjBZ
bFpsV0M1Y4IURi9vY9DCjZc2L7eXlCvjDZ7gIcEwEwYDVR0lBAwwCgYIKwYBBQUH
AwIwCwYDVR0PBAQDAgeAMAoGCCqGSM49BAMCA0gAMEUCIEa193YpXa1RWy4qHpui
IFEMm9dMBOEIq1wV6n5BDmsvAiEAzy+SY1+FGWWVcgAzNApPlNnrPYmZ5RycJFrA
I+z3r84=
-----END CERTIFICATE-----
</cert>
<tls-crypt>
#
# 2048 bit OpenVPN static key
#
-----BEGIN OpenVPN Static key V1-----
b854e9b845e6360e6fe042fa46c4f21e
93f7545685732b5f17b87cad3630c883
ac851b43ce635108d8c41d40f848ece1
4a0a08f297b4e505edc1e058856101c5
b987e72881d9613543b3d459154164e0
f9b49e2665eb4563c9ba4f653a2d3d62
c0c7ee8ed19e0e97fe37a46d95acbefb
b86b2b2e0357f67b8fa037ad313ccc06
3a2e07d14543d565ca058b0f8dfaadd9
6d0ecf382b5992f8122e860f37150964
f748c5eaa106e2ca89afd912bbb19dcc
f42a0b3b14d2fdc89b19e844f4d7485d
e4ab17ad2220c22ccab16322a99c664a
f81af7ac1a89ef9c723c5315711aa0ab
e79e2e6f94c4913f5f4488ea56e0b201
73c9b4a8bbd9c0561a571f82cc474d10
-----END OpenVPN Static key V1-----
</tls-crypt>
dhcp-option DNS 8.8.8.8
dhcp-option DNS 8.8.4.4
dhcp-option DOMAIN blinkt.de
nobind
verify-x509-name server_UhWUoNjeHCviFP7p name
remote-cert-tls server
cipher AES-128-GCM
auth SHA256
persist-tun
# persist-tun also enables pre resolving to avoid DNS resolve problem
preresolve
# Use system proxy setting
management-query-proxy
# Custom configuration options
# You are on your on own here :)
# These options found in the config file do not map to config settings:
setenv opt block-outside-dns 
resolv-retry infinite 
tls-cipher TLS-ECDHE-ECDSA-WITH-AES-128-GCM-SHA256 
ignore-unknown-option block-outside-dns 
tls-version-min 1.2
```

[NewZealand-[Auckland#1].conf](https://github.com/dedshit/vpn-config/files/11025412/NewZealand-.Auckland.1.conf.txt)  - **IP: 154.26.156.204**

[Australia-[Adelaide#1].conf](https://github.com/dedshit/vpn-config/files/11025430/Australia-.Adelaide.1.conf.txt)  -  **IP: 154.26.157.50**

[Romaina-[Bucharest#1].conf](https://github.com/dedshit/vpn-config/files/11025461/Romaina-.Bucharest.1.conf.txt)   -   **IP: 213.156.142.191**
