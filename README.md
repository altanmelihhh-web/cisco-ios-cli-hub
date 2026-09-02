# Cisco CLI Hub

*[English](README.en.md)*

Cisco IOS / IOS-XE / NX-OS komut referansı — routing, switching, VPN, QoS.

**→ [Canlı: altanmelihhh-web.github.io/cisco-ios-cli-hub/](https://altanmelihhh-web.github.io/cisco-ios-cli-hub/)**

Sahada tekrar tekrar ihtiyaç duyulan komutları tek bir aranabilir sayfada
toplayan bir referans. Her kayıt komutun kendisini, ne işe yaradığını ve ne
zaman kullanılacağını içerir — arama sonucunu tarayıp doğru olanı bulmak yerine
doğrudan çalıştırılabilir olanı verir.

| | |
|---|---|
| Komut | 873 |
| Kategori | 34 |
| Senaryo | 10 |
| Bağımlılık | yok — tek sayfa, tamamen istemci tarafında |
| Ağ çağrısı | yok |

## Kapsam

- ACL
- BFD
- BGP
- DAI
- DHCP
- DHCP Snooping
- Debug
- Device Mgmt
- EEM
- EIGRP
- EtherChannel
- HSRP
- IP SLA
- IPsec VPN
- Interface
- MPLS
- Monitoring
- Multicast
- NAT
- NX-OS
- OSPF
- Ping/Trace
- Port Security
- QoS
- Route-Map
- SNMP/Syslog/NTP
- SPAN
- STP
- Security
- Static Route
- Storm Control
- Track
- VLAN
- VRF

## Kullanım

Sayfayı açın ve arayın. Filtreleme anlık; kategori başlıklarından da
gezinebilirsiniz. Komutlar tek tıkla kopyalanır.

Yerelde çalıştırmak için ekstra bir şey gerekmez:

```bash
git clone https://github.com/altanmelihhh-web/cisco-ios-cli-hub.git
cd cisco-ios-cli-hub
python3 -m http.server 8000    # ya da index.html'i doğrudan açın
```

Derleme adımı, paket yöneticisi veya arka uç yoktur — `index.html`, `app.js`,
`style.css`.

## Not

Tüm örneklerdeki adresler dokümantasyon içindir (RFC 5737 / RFC 1918) ve
kurgusaldır. Komutları kendi ortamınızda uygulamadan önce etkisini
değerlendirin; bazıları yapılandırmayı değiştirir veya trafiği etkiler.

## Lisans

MIT — bkz. [LICENSE](LICENSE).
