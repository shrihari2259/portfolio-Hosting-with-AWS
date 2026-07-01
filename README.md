<div align="center">

# 👋 Shrihari Shinde — Cloud & DevOps Portfolio

**MCA (Cloud Computing) · AWS · DevOps · CI/CD Automation**

[![Live Demo](https://img.shields.io/badge/Live-Demo-4FE0C4?style=for-the-badge)](http://3.110.28.254)
[![Made with HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![Made with CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Hosted on AWS](https://img.shields.io/badge/Hosted%20on-AWS%20EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](#)

A dark, dashboard-styled personal portfolio — built to look like the kind of system I actually work on.

</div>

---

## 🖥️ Live

🔗 **[3.110.28.254](http://3.110.28.254)** — hosted on an AWS EC2 instance running nginx

> A domain + free HTTPS via Let's Encrypt is on the roadmap — see [Deployment](#-deployment) below.

---

## ✨ About this site

This isn't a template — it's built around one idea: **show, don't just tell, that I work with infrastructure.**

- 📊 The hero doubles as a live-style **status dashboard** — real numbers from real work (uptime, deploy-time reduction, API latency).
- 🔁 A **BUILD → TEST → DEPLOY → MONITOR** pipeline strip runs across the page — a nod to the CI/CD pipelines I actually build.
- 🌓 Dark, technical theme (slate + signal-teal + amber) instead of a generic portfolio template.
- 📱 Fully responsive, keyboard-accessible, and respects reduced-motion preferences.
- ⚡ Zero build step — pure HTML/CSS/JS, so it deploys anywhere in seconds.

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Structure | Semantic HTML5 |
| Styling | Hand-written CSS3 (custom properties, CSS Grid, Flexbox) |
| Interactivity | Vanilla JavaScript (no frameworks) |
| Fonts | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) · [Inter](https://fonts.google.com/specimen/Inter) · [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) |
| Hosting | AWS EC2 + nginx |

---

## 📂 Project Structure

```
portfolio/
├── index.html          # All page content & sections
├── style.css           # Design system, layout, responsive rules
├── script.js           # Mobile nav toggle
├── DEPLOY_ON_EC2.md     # Step-by-step EC2 hosting guide
└── README.md            # You are here
```

---

## 🚀 Deployment

This site is designed to be dropped onto any static host with zero configuration.

### Option A — AWS EC2 (current setup)
Full step-by-step instructions, including nginx setup and free HTTPS via Certbot, are in [`DEPLOY_ON_EC2.md`](./DEPLOY_ON_EC2.md).

```bash
# quick version, once nginx is installed:
git clone https://github.com/shrihari2259/portfolio.git
sudo cp portfolio/* /var/www/html/
sudo systemctl restart nginx
```

### Option B — GitHub Pages (free, instant)
1. Go to **Settings → Pages** on this repo
2. Source: `main` branch, `/ (root)` folder → **Save**
3. Live in ~1 minute at `https://shrihari2259.github.io/portfolio/`

### Option C — AWS S3 static website hosting
Just as valid for a fully static site — no server to manage at all. Enable **Static website hosting** on an S3 bucket and upload the three files.

---

## 📈 Highlights featured on the site

- 🏗️ **AWS Cloud & DevOps Internship** — Step Ahead IT (5+ months)
- ⚙️ **CI/CD pipelines** — cut deployment time from ~30 min to under 8 min
- 📦 **ETL Pipeline** — 100,000+ records/run, 99.9% data integrity
- 🔌 **Serverless REST API** — sub-200ms latency, zero server management
- 🌐 **Terraform 3-Tier VPC** — first end-to-end IaC project, S3 + DynamoDB remote state

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-shindeshrihari8%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:shindeshrihari8@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shrihari--shinde-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrihari-shinde-1958aa1a5)
[![GitHub](https://img.shields.io/badge/GitHub-shrihari2259-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shrihari2259)

📍 Pune, Maharashtra, India · Open to relocation · **Available immediately**

</div>

---

<div align="center">
<sub>Built with intent, not a template. ⭐ Star this repo if you found it useful for your own portfolio!</sub>
</div>
