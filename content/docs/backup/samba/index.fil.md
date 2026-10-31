---
ShowToc: true
date: 2026-10-31
title: Serbisyo ng backup ng Samba
---

Ang Samba ay isang pangkalahatang protocol sa pagbabahagi ng file para sa local area network (LAN), at mahusay itong gumagana sa maraming iba't ibang device at system.

# Pag-unawa sa mga parameter sa pag-login

- **Host name o IP address**: Ang address ng device na nagpapatakbo ng Samba server.
- **Port**: Ang port ng Samba server. Ang default ay **445**.
- **Pangalan ng Samba share**: Maaaring magkaroon ng maraming share configuration ang isang Samba server, kaya kailangan mong tukuyin kung alin ang gagamitin.
- **Path ng storage folder**: Ang storage path sa loob ng share. Maaari itong iwanang walang laman. Itatabi ang mga backup file sa path na ito; kung walang laman, gagamitin ang root directory ng share.
- **Username**: Ang user name, na hindi maaaring walang laman.
- **Password**: Ang password, na hindi maaaring walang laman.
- **Pinaghihigpitang WiFi SSID**: Nililimitahan ang backup sa isang partikular na WiFi network. Iwanang walang laman para payagan ang backup sa anumang WiFi, o maglagay ng SSID para tumakbo lang ang backup kapag nakakonekta sa network na iyon. Ginagamit ang Samba sa pagbabahagi ng file sa lokal na network, kaya pinapanatili nito ang iyong mga backup sa isang pinagkakatiwalaang WiFi.
