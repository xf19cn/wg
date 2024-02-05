# wg
Wire guard setting 
Name: WG Client
Public key: PhUlUqYrkgIWQM1vREmK/QXh+uWmfTTaOTIZhdeiaVw=
[Interface]
PrivateKey = SGRF0ZWU3wojJwHFX+hTTKEn7BVHClf0VwmeugMqL00= 
Address = 192.168.100.2/24
DNS = 8.8.8.8,1.1.1.1
[Peer]
Publickey = oirThrs+dkuUvb0Mep6NU3LIQnpAPCvMDuHvXQOOgC8= 
AllowedIPs = 0.0.0.0/0
Endpoint = netvn 51820

Name: WG Server
[Interface]
PrivateKey = WGTLX4FxZIMgHq3qfrET yuT+1HVIDqRWQgekZnrz5FB=
ListenPort = 51820
Address = 192.168.100.1/24
[Peer]
PublicKey = PhulUqYrkg/WQMIvREmK/QXh+uWmfTTa0TZhdeiaVw=
AllowedIPs = 192.160.100.2/12
