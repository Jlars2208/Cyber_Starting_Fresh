# Cyber_Starting_Fresh

# GitHub Copilot - Your AI peer programmer

**[GitHub Copilot](https://code.visualstudio.com/docs/copilot/overview)** is an AI peer programming tool that helps you write code faster and smarter.


# Hi, I'm {{Joel Larson}} 👋

[![GitHub followers](https://img.shields.io/github/followers/Jlars2208?label=follow&style=social)](https://github.com/Jlars2208)
[![Top Language](https://img.shields.io/github/languages/top/Jlars2208?color=blue)](https://github.com/Jlars2208)
[![Profile Views](https://komarev.com/ghpvc/?username=Jlars2208&color=brightgreen)](https://github.com/Jlars2208)

A quick, professional intro: I'm a [CyberSecurity/Contruction worker tech y] who loves building practical, and user-centered CyberSecurity activities. I focus on functionality, simplicity, learning continuously, helping teams grow, an also have fun doing it!


---

## 🚀 About Me
- 🔭 Current focus: {{going back to school for higher learning, and finding a Tech carrer. Been getting more into coding}}
- 🌱 Learning: {{LEARNING_GOAL}} (learning more about pen testing and furthering my knowledge to become a sscp, cism, and maybe CEH)
- 👯 Open to: Collaborations on {{COLLABORATION_AREAS}} (open-source tooling, DevOps automations, tips and pointers)
- 💼 Available for: {{AVAILABILITY}} (Full-time, Contract, Open to opportunities)
- 💬 Pronouns: {{he\him}}
- 📍 Location: {{Colorado}}

---

## 💡 Key Skills
- Languages: {{LANGUAGES}} (e.g., JavaScript, TypeScript, Python, Go)
- Frameworks & Tools: {{FRAMEWORKS}} (e.g., React, Node.js, Docker, Kubernetes)
- Testing & CI: {{TESTING_CI}} (e.g., Jest, Playwright, GitHub Actions)
- Cloud & Infra: {{CLOUD_INFRA}} (e.g., AWS, GCP, Terraform)

---

## 🔧 Tech Stack
```
Primary:     {{PRIMARY_STACK}} 
Databases:   {{DATABASES}}
Caching/Msg: {{CACHING_OR_MQ}}
Infrastructure: {{INFRASTRUCTURE}}
```

---

## 📂 Selected Projects
### [Project One name](PROJECT_ONE_URL) — short tagline
A 1–2 sentence description highlighting impact, tech used, and results (e.g., reduced latency by 40%, served 100k users).

### [Project Two name](PROJECT_TWO_URL) — short tagline
A 1–2 sentence description focusing on architecture, role, and notable learnings.

### [Project Three name](PROJECT_THREE_URL) — short tagline
Describe the project and include any measurable outcomes (performance, adoption, revenue, etc).

(Replace above entries with your top 3–6 projects, each with a short description and link.)

---

## 📈 GitHub Stats (optional)
[![Jlars2208's GitHub stats](https://github-readme-stats.vercel.app/api?username=Jlars2208&show_icons=true&theme=github_dark)](https://github.com/Jlars2208)

(If you'd like these, I can add or customize them—colors, hide total stars, show streaks, etc.)

---

## 🎯 Highlights & Achievements
- {{ACHIEVEMENT_1}} (e.g., Speaker at XYZ conference, published article)
- {{ACHIEVEMENT_2}} (e.g., Contributor to popular OSS package)
- {{CERTIFICATIONS}} (e.g., AWS Certified Solutions Architect)

---

## 🤝 How to Work With Me
- Preferred communication: {{COMM_PREF}} (e.g., Email, LinkedIn, Slack)
- Best times: {{AVAILABILITY_HOURS}} (optional)
- Hiring: {{HIRING_STATUS}} (e.g., Open to opportunities / Not looking)

---

## 📫 Contact & Socials
- Website/Portfolio: [{{WEBSITE}}]({{WEBSITE}})
- Email: {{EMAIL}}
- LinkedIn: [{{LINKEDIN_USERNAME}}]({{LINKEDIN_URL}})
- X / Twitter: [@{{TWITTER_USERNAME}}]({{TWITTER_URL}})
- Resume: [Download]({{RESUME_URL}})

---

## 🧾 Want to know more?
If you'd like, I can:
- Turn this into a polished README for your repo (fill in all placeholders).
- Add dynamic GitHub cards (top languages, streaks, trophies).
- Produce alternate tones: concise professional, warm personal, or technical resume-style.

Thanks for visiting — let's build something great! ✨

--------------------------------------------------------------


                  🛡️ Network Guardian SIEM

Network Guardian is a custom-built Security Information and Event Management (SIEM) tool. It provides real-time visibility into network traffic, performs deep packet inspection (DPI) for sensitive keywords, and visualizes data through an interactive web dashboard.

                    📋 Table of Contents
Features
Architecture
Installation
Usage
Security & Compliance

                       ✨ Features
Live Traffic Analysis: Real-time monitoring of TCP/UDP packets using Scapy.
Geographical Tracking: Integration with IPinfo to identify the physical location and Organization (ISP) of source IPs.
Deep Packet Inspection: Scans raw payloads for unencrypted sensitive keywords (e.g., "password", "admin").
Desktop Alerts: Cross-platform system notifications for high-risk traffic.
Interactive Dashboard: Built with Streamlit to show traffic "heartbeats," service distribution, and alert logs.
Audit Reporting: One-click CSV export for security forensics and compliance.

                     🏗️ Architecture
The tool uses a multi-threaded approach to ensure no packets are dropped during UI rendering:
The Engine (Scapy): Sniffs raw traffic and extracts metadata.
The Logic (Python/Pandas): Filters duplicates and matches keywords.
The UI (Streamlit): Consumes the processed data for live visualization.

                     🚀 Installation
1. Prerequisites
Ensure you have Python 3.8+ installed. You will also need libpcap installed on your system (standard on Linux/Mac; use Npcap for Windows).
2. Install Dependencies

pip install streamlit scapy plyer ipinfo pandas

                        💻 Usage
Obtain an API Token: Sign up for a free token at ipinfo.io.
Configure the Script: Replace your_ipinfo_token_here in the script with your actual token.
Run as Administrator: Since network sniffing requires raw socket access, you must run the tool with elevated privileges.
<!-- end list -->

                      # Linux / macOS
sudo streamlit run guardian.py

                         # Windows
streamlit run guardian.py
         # Run your terminal as Administrator, then:

                🔒 Security & Compliance
Privacy: This tool does not store packet data permanently unless the "Export" button is clicked. All data is stored in a rolling RAM buffer.
Resource Impact: Utilizes Berkeley Packet Filters (BPF) to minimize CPU overhead.
Encryption: The tool respects TLS/SSL boundaries and does not attempt to decrypt secure payloads, ensuring privacy for encrypted communications.
Final Project Status: Complete
You have successfully moved from a single-line command to a professional security application.