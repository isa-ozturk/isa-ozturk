<h1 align="center">Merhaba, ben İsa Öztürk 👋</h1>

<p align="center">
  <b>IT Manager @ Lenze Turkey</b> · Endüstriyel Otomasyon Mühendisi · Self-Hosted Altyapı Tutkunu
</p>

<p align="center">
  <em>Fabrika zemininden bulut'a; PLC'den Kubernetes'e kadar, tüm teknoloji yığınında çözüm üretiyorum.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/İstanbul-TR-0B1D33?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Odak-Industrial%20Automation-E8A838?style=flat-square" />
  <img src="https://img.shields.io/badge/IEC%2061131--3-Structured%20Text-005F9E?style=flat-square" />
  <img src="https://img.shields.io/badge/Self--Hosted-Enthusiast-1ebe5a?style=flat-square" />
</p>

---

## 🧭 Hakkımda

**Lenze Türkiye**'de **Bilgi İşlem Müdürü** olarak kurumsal IT altyapısı ile endüstriyel otomasyon dünyasının kesişiminde çalışıyorum. İş tanımımın sınırları klasik "IT yöneticisi" rolünün çok ötesinde: aynı gün içinde bir VLAN yapılandırmasını gözden geçirip, ardından 19 klima ünitesini Modbus RTU üzerinden yöneten bir **CODESYS OOP mimarisini** refactor edebiliyorum.

Mühendislik felsefem üç temel ilkeye dayanır:

- 🏗️ **Sağlam temel mimari** — Code & sistemler yıllarca bakım yapılabilir olmalı. Clean Architecture, SOLID, PLCopen standartları benim için tercih değil, gereklilik.
- 🔧 **Alan bilgisi + kod** — Bir PLC fonksiyon bloğu yazıyorsam, sahadaki sensörün nasıl davrandığını da biliyorum. Bir Docker container'ı deploy ediyorsam, arkasındaki network topolojisini de kuruyorum.
- 🧩 **Self-sufficiency** — Vendor lock-in'den uzak, kendi altyapımı kendim yönetirim.

---

## 🛠️ Teknoloji Yetkinlikleri

### 🏭 Endüstriyel Otomasyon & PLC
<p>
  <img src="https://img.shields.io/badge/CODESYS-IEC%2061131--3-005F9E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Structured%20Text-OOP-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Lenze%20PLC-Expert-E8A838?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Modbus%20RTU-Protocol-4A4640?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PLCopen-Standards-00897B?style=for-the-badge" />
</p>

- **CODESYS OOP refactoring** — Function Block hiyerarşileri, interface-based tasarım, State Machine pattern'ları
- **PLCopen uyumlu** FB geliştirme (`xDone`/`xBusy`/`xError` mutually exclusive outputs)
- **Modbus RTU** ile endüstriyel cihaz entegrasyonu (Daikin DIII-Net gateway, EPM-S640/S650 modülleri)
- **HMI geliştirme** — VisiWin, JavaScript optimizasyonu, OPC UA entegrasyonu, MVVM pattern

### 💻 Masaüstü Uygulama Geliştirme
<p>
  <img src="https://img.shields.io/badge/C%23-.NET%208-512BD4?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/WPF-MVVM-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Clean%20Architecture-SOLID-4A4640?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQLite-Local%20DB-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

- Clean Architecture + MVVM ile kurumsal WPF uygulamaları
- SFTP, WMI, RSA hardware-bound licensing, SHA256 password hashing
- INI konfigürasyon yönetimi, sanal klavye, dokunmatik HMI launcher'lar

### 🏗️ Altyapı & DevOps
<p>
  <img src="https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Coolify-Self--Hosted-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Nginx-FPM-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-Tunnel-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Traefik-Reverse%20Proxy-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white" />
  <img src="https://img.shields.io/badge/Authelia-SSO-000000?style=for-the-badge" />
</p>

- **Coolify** üzerinde container orchestration (Node-RED, MongoDB, Nextcloud, Technitium DNS)
- **Traefik + Cloudflare Tunnel + Authelia** ile Zero-Trust self-hosted setup
- **Nginx + PHP-FPM** migration (120 GB'lık büyük dosya uploadları için optimizasyon)
- **Active Directory** Fine-Grained Password Policy yönetimi

### 🔌 IoT & Monitoring
<p>
  <img src="https://img.shields.io/badge/Node--RED-Low%20Code-8F0000?style=for-the-badge&logo=node-red&logoColor=white" />
  <img src="https://img.shields.io/badge/unified--red-Dashboard-E8A838?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-NoSQL-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/SNMP-Protocol-4A4640?style=for-the-badge" />
</p>

- Node-RED ile profesyonel alarm yönetim sistemleri
- SNMP ile UPS monitoring (Megatec NetAgentA, 3-fazlı sistemler)
- TeslaMate entegrasyonu ve araç telemetri monitoring

### 🌐 Web & Entegrasyon
<p>
  <img src="https://img.shields.io/badge/PHP-Nextcloud%20Apps-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare%20Workers-Edge-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white" />
</p>

---

## 🔬 Odaklandığım Projeler

### 🏢 Lenze Türkiye — Tesis Otomasyonu
**5 katmanlı sıcaklık izleme mimarisi** geliştirdim. `FB_PT100Reader` sensör okumadan başlayıp `FB_OutdoorTemperatureAnalyzer` ve `FB_ServerRoomMonitor`'a kadar hiyerarşik bir FB ağı. 4 seviyeli parametrik alarm sistemi, startup rate-of-change false alarm debug'ı, gerçek PLC I/O ile canlı test.

Kapsamlı subsystem portföyü:
- **FB_ShutterControl** — Cold-start/clean-all init, sensör bazlı state priority chain, RETAIN vs PVL depolama
- **FB_BarrierControl** — Photocell güvenlik, mid-travel reversal, split error recovery
- **FB_SecurityAlarmMonitor** — Pronet panel analog input, debounce, state-change instability detection
- **FB_GeneratorMonitor** — PLCopen outputs, TIME overflow fix, RETAIN istatistikler
- **FB_MagneticDoorLock** — Gece yarısını aşan time-window logic, manuel/otomatik mod
- **FB_DaikinClimateController** — 19 AC ünite için queueing, pre-heat logic, adaptive setpoint, history ring buffer, Node-RED notification output

### 🏠 Self-Hosted Infrastructure Stack
- **Nextcloud** custom app geliştirme (`foldertemplate` — "+ Yeni" menüsüne template folder copy butonu enjekte)
- **DNS Cluster** mimarisi — iki Coolify node'u üzerinde Technitium
- **Snipe-IT** tabanlı IT asset inventory (Microsoft Lists vs custom değerlendirmesi sonrası tercih)
- **Teslamate** + Traefik + Cloudflare Tunnel + Authelia ile Zero-Trust araç telemetri

### 🔐 Kurumsal Uygulamalar
- **Lenze i950 SD Card Tool** — License/credit workflow, WMI drive enumeration, safe ejection, 6 projeli Clean Architecture
- **Lenze AuditTrack** — WPF/.NET 8, SQLite, SFTP, RSA tabanlı hardware licensing
- **HMI Launcher** — Windows 10 IoT touchscreen, dual operating modes, SHA256 password

---

## 📌 Öne Çıkan Repolar

<p>
  <a href="https://github.com/isa-ozturk/nzymuhendislik-web">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=isa-ozturk&repo=nzymuhendislik-web&theme=default" />
  </a>
  <a href="https://github.com/isa-ozturk/isaozturk-web">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=isa-ozturk&repo=isaozturk-web&theme=default" />
  </a>
</p>

---

## 📊 GitHub İstatistikleri

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=isa-ozturk&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=isa-ozturk&layout=compact&theme=default&hide_border=true" />
</p>

---

## 🧠 Felsefem

> *"Bir PLC programını yazmak kolaydır. Üç yıl sonra, gece yarısı bir arıza çağrısında onu okuyabilmek — işte mühendislik budur."*

Her yazdığım kod; **mimarisel temizlik**, **alan bilgisi** ve **operasyonel gerçeklik** üçgeninin kesişiminde durur. Over-engineering'den de kaçınırım, quick-and-dirty kod'dan da. Doğru soru şudur: *"Bu sistemi, iki yıl sonra, yarı uykulu bir teknisyen anlayabilecek mi?"*

---

## 📫 İletişim

<p>
  <a href="mailto:isa@ozturk.dev"><img src="https://img.shields.io/badge/E--mail-Contact-E8A838?style=for-the-badge&logo=protonmail&logoColor=white" /></a>
  <a href="https://github.com/isa-ozturk"><img src="https://img.shields.io/badge/GitHub-isa--ozturk-0B1D33?style=for-the-badge&logo=github" /></a>
</p>

---

<p align="center">
  <sub>
    ⚙️ <strong>Fabrika zemininden bulut'a kadar, her katmanda.</strong><br>
    <em>Built with care in İstanbul, Türkiye.</em>
  </sub>
</p>
