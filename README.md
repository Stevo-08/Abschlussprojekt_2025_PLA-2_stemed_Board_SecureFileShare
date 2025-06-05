# 🔐 Security Toolbox – Webdienst in der Cloud

**Projektarbeit – Abschlussprojekt ZLI Basislehrjahr**  
**Autor**: *[Dein Name]*  
**Firma**: Stevan Solutions  
**Zeitraum**: 12 Tage

---

## 📌 Projektübersicht

Die Security Toolbox ist ein Webdienst, der verschiedene Tools zur IT-Sicherheit bereitstellt. Ziel ist es, eine öffentlich erreichbare Website mit praktischen Security-Tools zu entwickeln, die in der Cloud gehostet wird.

---

## 🧱 Meilensteine

### 🟩 Meilenstein 1 – Setup & Grundlagen (2–3 Tage)
- Cloudserver bereitstellen (z. B. Ubuntu auf Oracle Cloud, Hetzner, Proxmox)
- Webserver einrichten (Apache oder Nginx)
- Domain oder direkte IP erreichbar machen
- Startseite mit Menü (HTML/CSS)

### 🟨 Meilenstein 2 – Tool-Entwicklung (5–6 Tage)
- 🔑 **Passwortgenerator** (JavaScript oder Python Flask)
- 🌐 **IP-Check Tool** (zeigt öffentliche IP + Geo-Daten)
- 🕵️‍♂️ **HTTP-Header-Scanner** (requests/curl)
- Tool-Auswahl über Buttons oder Dropdown-Menü

### 🟥 Meilenstein 3 – Veröffentlichung & Sicherheit (2–3 Tage)
- Webdienst öffentlich zugänglich machen
- HTTPS via Let's Encrypt (Certbot)
- Eingabevalidierung & Logging
- Screenshots und Abschlussbericht erstellen

---

## 🛠️ Technologien

- **Backend**: Python (Flask), Bash, JavaScript
- **Frontend**: HTML, CSS
- **Server**: Ubuntu (Cloud VM)
- **Webserver**: Apache oder Nginx
- **SSL-Zertifikate**: Let's Encrypt / Certbot
- **Sicherheit**: Fail2Ban (optional), OPNsense (für LAN-Restriktion)

---

## 🌍 Zugriff

- 🔗 [http://yourdomain.com](http://yourdomain.com)  
- 📡 Oder direkt via IP: `http://<IP-Adresse>`

---

## 🔒 Sicherheitskonzept

- HTTPS-Verschlüsselung
- Input-Schutz durch Validierung
- Zugriff auf Intranet nur aus LAN-Netz (192.168.x.x)
- Logging aller sensiblen Anfragen

---

## 🖼️ Screenshots

![image](https://github.com/user-attachments/assets/aa7323d5-e83d-4b16-8e83-86554ae18d84)


## 📁 Projektstruktur (Beispiel)

```bash
security-toolbox/
├── index.html
├── style.css
├── js/
│   └── password.js
├── tools/
│   ├── ipcheck.py
│   ├── header_scan.py
├── certbot/
│   └── ssl-setup.sh
└── README.md

