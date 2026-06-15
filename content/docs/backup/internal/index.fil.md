---
ShowToc: true
copy_mark: copied
date: 2026-06-14
title: Internal backup service
---

May internal backup mechanism ang app na pana-panahong kino-compress ang data ng iyong mga kabanata sa isang .zip file.

# Mawawala ang mga internal backup file kapag na-uninstall ang app

Iniimbak ng built-in na mekanismo ang mga backup na .zip file sa isang pribadong folder ng app. Mabubura ang folder na ito kasama ng iba pang data ng app kapag na-uninstall ang app.

Kaya huwag lamang dito umasa para mapanatiling ligtas ang iyong data. Hindi ito ginawa upang maging tanging paraan mo ng pag-backup.

# Paano ito gumagana

Kapag umalis ka sa app, o sa nakatakdang oras bawat araw, titingnan ng app kung may mga pagbabagong hindi pa na-back up. Kung mayroon, sisimulan ang proseso ng backup. Bilang default, may hindi bababa sa 8 oras na pagitan sa pagitan ng dalawang proseso ng backup.

Kapag nakagawa na ng bagong zip file, susuriin ng app ang mga lumang backup data at buburahin ang mga ito kung kinakailangan. Bilang default, pinapanatili ng app ang pinakabagong 20 backup file, kaya hindi mo kailangang mag-alala na masyadong maraming storage ang kakainin ng mga backup.

Kung nakapag-set up ka na ng ibang backup service, gaya ng Google Drive o backup ng storage ng device, ia-upload din doon ang pinakabagong zip file.
