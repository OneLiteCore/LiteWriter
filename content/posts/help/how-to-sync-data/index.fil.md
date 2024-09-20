---
title: Paano i-sync ang data  
date: 2024-09-20  
ShowToc: true
---

Teknikal na pagsasalita, ang aming app ay hindi sumusuporta sa pag-sync ng data sa pagitan ng mga device. Bagaman maaari mong gamitin ang feature na backup upang ilipat ang iyong data mula sa isang device patungo sa iba, hindi ito maituturing na pag-sync.

Gayunpaman, may ilang mga paraan pa rin upang maisagawa ang pag-sync sa labas ng app.

# Itakda ang isang Imbakan na Folder bilang Home Folder ng App

Maaari mong itakda ang isang folder sa imbakan ng iyong device bilang home folder ng app. Sa setup na ito, ang iyong mga libro at kabanata ay mase-save bilang mga sub-folder at mga text file sa folder ng imbakan.

Dahil naka-save na sila bilang mga file, maaari mong gamitin ang mga panlabas na tool para sa pag-sync ng mga file upang i-sync ang data na ito sa iba't ibang mga device.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Ang Syncthing ay isang malawakang ginagamit, cross-platform na tool para sa pagsasabay ng data. Maaari mo itong gamitin upang i-sync ang data ng iyong app sa pagitan ng mga mobile device, PC, laptop, o home server.

Tingnan ang opisyal na gabay ng Syncthing upang malaman kung paano ito itakda:

[Syncthing - Pagsisimula](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# Network Disks

Ang ilang mga network disk ay nag-aalok ng bi-directional na feature para sa pag-sync ng mga file. Sa pamamagitan ng pagtatakda ng home folder ng iyong app bilang syncing folder, maaari mong i-sync ang data sa iba't ibang mga device. Maaari ring magsilbing add-on na backup server ang network disk sa ganitong sitwasyon.

# Git, SVN, at Rsync

Para sa mga may kaalaman sa programming, ito ang pinakamainam na paraan. Maaari mong gamitin ang mga app tulad ng Termux upang magpatakbo ng mga command-line tools para sa pag-sync ng iyong data.

Kung pamilyar ka sa Git, SVN, o Rsync, ang opsyon na ito ay nagbibigay ng mahusay na kakayahang umangkop. Gayunpaman, kung hindi ka pamilyar sa mga tool na ito, hindi namin ito inirerekomenda, dahil nangangailangan sila ng mas teknikal na kaalaman at hindi ito para sa karaniwang mga gumagamit.

# Buod

Ang pangunahing layunin ng app ay panatilihing ligtas ang data ng mga gumagamit. Dahil ang pag-sync ng data sa pagitan ng dalawang client apps ay hindi laging ligtas, pinili naming hindi bumuo ng built-in na feature para dito. Sa halip, inirerekumenda naming gumamit ng mga maaasahan at propesyonal na tool para sa pag-sync ng data.
