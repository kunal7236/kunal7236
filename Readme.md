# Kunal Kashyap

**Software Engineer at [Zluri](https://www.zluri.com/)** · Computer Science & Engineering at BIT Mesra, Class of '26

[![Portfolio](https://img.shields.io/badge/Portfolio-kunalka.me-0d1117?style=flat-square&logo=googlechrome&logoColor=white)](https://www.kunalka.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kunal--kashyap-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kunal-kashyap-bitmesra)
[![Email](https://img.shields.io/badge/Email-kunalkashyap277@gmail.com-333333?style=flat-square&logo=gmail&logoColor=white)](mailto:kunalkashyap277@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-1761-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/kunal7236/)

I build enterprise frontend at Zluri and self-hosted backends in my spare time. Interested in problems that span the whole stack — React and TypeScript at work, Python data pipelines and APIs on my own hardware.

---

## What I'm working on

- 🏢 **Zluri** — owned the frontend for a drag-and-drop email template builder (GrapesJS) that lets enterprise admins brand every product notification, plus custom sender-domain support so organisations send from their own email domain. Also shipped JSONata-computed custom fields (full-stack) and an SLA-breach tracker.
- 🍓 **JanAushadhi Data Engine** — a weekly GitHub Actions pipeline that parses government PDFs into indexed SQLite, feeding a FastAPI service I run on a Raspberry Pi at [jan-api.kunalka.me](https://jan-api.kunalka.me/docs).
- 📈 Solved **1000+** DSA and SQL problems across LeetCode, GeeksforGeeks and Code360.

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Mobile & Tooling**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Projects

### JanAushadhi Sarthak

Making India's generic-medicine data usable, end to end — pipeline, API and app.

- **[kendra-data-engine](https://github.com/kunal7236/kendra-data-engine)** — authenticates with the official JanAushadhi portal, streams government PDFs in-memory and parses their tables with `pdfplumber`, producing clean datasets of **20,700+ store locations** and **2,400+ medicines** with drug codes and MRP. Syncs weekly via GitHub Actions, rebuilds indexed SQLite + CSV snapshots, and reports each run through a Telegram bot.
- **[jan-api.kunalka.me](https://jan-api.kunalka.me/docs)** — a FastAPI service I self-host on a Raspberry Pi, serving medicine search by drug code or generic name and Kendra lookup by pincode, state, district or Kendra code. Indexes tuned for sub-second queries on low-power hardware.
- **[jan_aushadhi_sarthak](https://github.com/kunal7236/jan_aushadhi_sarthak)** — the Flutter client: store discovery, colour-coded availability and pricing, one-tap calling and Maps navigation, and a persistent cart. Signed APKs published to Releases by CI.

`Python` `FastAPI` `SQLite` `Flutter` `Raspberry Pi` `GitHub Actions`

### Others

| Project | What it does | Stack | Links |
| :--- | :--- | :--- | :--- |
| **IPTV Player** | 150 live TV channels via real-time M3U8 parsing, with a custom player supporting 5 aspect ratios, rotation, auto-hiding controls and a tap-to-unlock overlay. | Flutter, Dart, HLS | [Code](https://github.com/kunal7236/iptv_player) · [Demo](https://youtube.com/shorts/LNQ2E4kYZsk?feature=share) |
| **Musify** | Music streaming and downloading — background playback, lock-screen controls, 320 kbps offline downloads, synced lyrics. | Flutter, audio_service | [Code](https://github.com/kunal7236/Musify) · [Demo](https://youtube.com/shorts/NpMFO8_OAzg?feature=share) |
| **Easy Rail** | Real-time train information in one place: seat availability, PNR status and live train tracking. | Flutter, REST APIs | [Code](https://github.com/kunal7236/easy_rail_app) · [Demo](https://www.youtube.com/shorts/q-T9eZis8eU) |
| **Weather App** | Real-time weather for any city, built on Material Design 3 with a dark-first theme. | Flutter, OpenWeather API | [Code](https://github.com/kunal7236/Weather-App) · [Demo](https://youtube.com/shorts/tHZVERkG7b4?feature=share) |

---

## GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kunal7236&show_icons=true&count_private=true&hide_border=true&theme=github_dark&title_color=4a8cff&icon_color=4a8cff&bg_color=0d1117&text_color=9aa5b1" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kunal7236&layout=compact&langs_count=8&hide_border=true&theme=github_dark&title_color=4a8cff&bg_color=0d1117&text_color=9aa5b1" alt="Top languages" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kunal7236&hide_border=true&theme=github-dark&ring=4a8cff&fire=4a8cff&currStreakLabel=9aa5b1&background=0d1117" alt="Contribution streak" height="165" />
</p>

---

## Elsewhere

[![LeetCode](https://img.shields.io/badge/LeetCode-1761-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/kunal7236/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2021-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/user/kunal7236/)
[![Code360](https://img.shields.io/badge/Code360-therealkunal-FF6B00?style=flat-square&logo=codingninjas&logoColor=white)](https://www.naukri.com/code360/profile/therealkunal)
[![X](https://img.shields.io/badge/X-@KashyapK257-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/KashyapK257)
[![Telegram](https://img.shields.io/badge/Telegram-@NinjaApache-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/NinjaApache)
