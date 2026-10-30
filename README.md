<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:302b63,100:24243e&height=230&section=header&text=Aditya%20Pagare&fontSize=64&fontColor=ffffff&fontAlignY=42&desc=Full%20Stack%20Developer%20%E2%80%A2%20Backend%20Focused&descSize=20&descAlignY=64&animation=fadeIn" width="100%"/>

<a href="https://adipagare-portfolio.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Java+%7C+Spring+Boot+%7C+Node.js+%7C+Next.js;I+build+billing+%26+business+tools+shops+actually+use;Clean+Code+%7C+Clean+Architecture+%7C+REST+APIs;Open+to+Remote+%26+Freelance+Roles+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/><br/>

[![Profile Views](https://komarev.com/ghpvc/?username=AdityaPagare&label=Profile%20Views&color=7c3aed&style=flat-square)](https://github.com/AdityaPagare)
![Open to Work](https://img.shields.io/badge/%F0%9F%9F%A2-Open%20to%20Work-16a34a?style=flat-square)
![Location](https://img.shields.io/badge/%F0%9F%93%8D-Aurangabad%2C%20India-f59e0b?style=flat-square)
![Experience](https://img.shields.io/badge/%E2%8C%9B-1%2B%20Year%20Experience-6366f1?style=flat-square)
[![Portfolio](https://img.shields.io/badge/%F0%9F%8C%90-Portfolio-FF5722?style=flat-square)](https://adipagare-portfolio.netlify.app/)

<br/>

**[Projects](#-featured-projects) · [Tech stack](#%EF%B8%8F-tech-stack) · [GitHub stats](#-github-analytics) · [Certifications](#-certifications) · [Contact](#-lets-connect)**

</div>

---

## 👋 About me

I'm a **full stack developer who leans backend**: APIs, databases, auth and the boring-but-important parts that make software dependable. I like shipping tools a real business uses every day, not demos. My latest work is a complete **billing and staff system for a cycle shop**, built end to end: invoices, GST, PDF bills, WhatsApp and email, attendance and payroll.

```java
public class AdityaPagare extends Developer {

    String name     = "Aditya Pagare";
    String role     = "Full Stack Developer (Backend Focused)";
    String location = "Aurangabad, Maharashtra, India";
    String edu      = "MCA — Maharashtra Institute of Technology (2022–2024)";

    String[] stack = { "Java", "Spring Boot", "Node.js", "Next.js", "React", "Angular" };

    Map<String, String> currentlyBuilding = Map.of(
        "Cycle Wala Billing", "Invoices, GST, PDF bills, payroll — built for a real shop",
        "REST APIs",          "Spring Boot & Node.js services",
        "Admin Dashboards",   "Full-stack CRUD with React & Angular"
    );

    String[] interests = {
        "Clean Backend Architecture",
        "API Design & Integrations",
        "System Design",
        "Open Source"
    };

    String greeting() {
        return "I build practical, high-impact systems. Let's create something great.";
    }
}
```

---

## 🚀 Featured Projects

### 🚲 Cycle Wala Billing — billing & staff system *(flagship)*

<table>
<tr>
<td width="62%" valign="top">

A complete back-office built for a real cycle shop. The bill is a PDF in the shop's own layout, and it can reach the customer on WhatsApp or email in one tap.

- 🧾 **Sales invoices, quotations and purchase bills** with GST (CGST / SGST / IGST), HSN and frame / serial numbers
- 📄 **PDF bills** in the shop's exact layout, with Hindi support, plus a public link customers can open
- 💬 **WhatsApp and email sending**, including automatic send through the WhatsApp Cloud API
- 👥 **Parties, stock and payments** with ledgers, balances shown as *Udhaar baaki / Dene hain*, reminders and CSV import
- 🧑‍🤝‍🧑 **Staff attendance and payroll**: staff log in on their phones to check in and out; salary slips and advances
- 📊 **Reports** with CSV export, a dashboard, **dark mode**, and a layout that works on phones
- 🔐 Signed HttpOnly sessions, rate-limited sign-in, and a data layer that runs on MongoDB or plain files

</td>
<td width="38%" valign="top" align="center">

`Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `MongoDB` `pdf-lib` `WhatsApp Cloud API` `Nodemailer` `Vercel`

<br/><br/>

[![Live demo](https://img.shields.io/badge/Live-cyclewala--billing.vercel.app-4a3ccf?style=for-the-badge&logo=vercel&logoColor=white)](https://cyclewala-billing.vercel.app/)

[![Source](https://img.shields.io/badge/GitHub-Source%20code-181717?style=for-the-badge&logo=github)](https://github.com/AdityaPagare/cyclewala-billing)

</td>
</tr>
</table>

### 🛒 Cycle Wala — shop website & online store

<table>
<tr>
<td width="62%" valign="top">

The public website for the same shop: a catalogue of cycles with photos, a cart and orders, service bookings, customer accounts with wishlists, and an owner admin to manage it all.

- 🛍️ **Online catalogue, cart and orders**, with new orders emailed to the owner
- 🔧 **Service booking** and customer accounts with wishlists
- 🛠️ **Admin area** to edit the catalogue, photos, orders and bookings, with Excel export
- ✨ Smooth, animated front end (GSAP, Lenis, Three.js)
- 💾 Storage that adapts to where it is hosted: MongoDB, Netlify Blobs, Vercel Blob or plain files

</td>
<td width="38%" valign="top" align="center">

`Next.js` `React 19` `GSAP` `Three.js` `MongoDB` `ExcelJS` `Nodemailer`

<br/><br/>

[![Live site](https://img.shields.io/badge/Live-cyclewala--ten.vercel.app-FF5722?style=for-the-badge&logo=vercel&logoColor=white)](https://cyclewala-ten.vercel.app/)

[![Source](https://img.shields.io/badge/GitHub-Source%20code-181717?style=for-the-badge&logo=github)](https://github.com/pagareadi0/cyclewala)

</td>
</tr>
</table>

### 📦 More projects

<div align="center">

| 🏷️ Project | 📋 Description | 🔧 Stack | 🔗 Link |
|:---:|:---|:---:|:---:|
| ⚙️ **HRMS** | Feature-rich dashboard with full CRUD operations | `Spring Boot` `MySQL` | [![Repo](https://img.shields.io/badge/GitHub-View-181717?style=flat-square&logo=github)](https://github.com/REPL-IT-Intern/ui-eob) |
| ☕ **Coffee Cafe** | Full-stack online coffee ordering system with cart & order flow | `React` `MySQL` | [![Repo](https://img.shields.io/badge/GitHub-View-181717?style=flat-square&logo=github)](https://github.com/AdityaPagare/CoffeeCore) |
| 🖐️ **GSAP Butterfly** | Real-time MediaPipe hand tracking with Verlet physics ropes | `React` `MediaPipe` `Canvas` | [![Repo](https://img.shields.io/badge/GitHub-View-181717?style=flat-square&logo=github)](https://github.com/AdityaPagare/gsap-butterfly-animation) |
| 🌐 **Portfolio** | Personal developer portfolio with project showcase | `React` `Netlify` | [![Live](https://img.shields.io/badge/Live-Visit-orange?style=flat-square&logo=netlify)](https://adipagare-portfolio.netlify.app/) |

</div>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,nodejs,express,nextjs,react,angular,ts,js,tailwind,mongodb,mysql,docker,git,linux,vercel,netlify,postman,vscode&perline=10" alt="Tech stack icons" />

<br/><br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![ERPNext](https://img.shields.io/badge/ERPNext-0089FF?style=for-the-badge&logo=frappe&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=AdityaPagare&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&cache_seconds=1800"/>
  &nbsp;
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaPagare&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=1800"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AdityaPagare&theme=tokyo-night&hide_border=true&area=true" width="95%"/>
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AdityaPagare&theme=tokyonight" width="95%"/>
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AdityaPagare&theme=tokyonight"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AdityaPagare&theme=tokyonight"/>
</div>

---

## 📜 Certifications

<div align="center">

| 🏅 Certification | 🏢 Issuer |
|:---|:---:|
| 🔴 **RHCSA** — Red Hat Certified System Administrator | Red Hat |
| 🐧 **Tools of the Trade: Linux and SQL** | Google / Coursera |
| 📊 **Data Analysis with Python** | IBM / Coursera |
| 🔐 **Foundations of Cybersecurity** | Google / Coursera |

</div>

---

## 🤝 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adityappagare358@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-pagare/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdityaPagare)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://adipagare-portfolio.netlify.app/)

<br/>

> 💼 **Open to:** Full-time roles · Remote opportunities · Freelance projects · Open-source collaborations
>
> 📬 **Response time:** Within 24 hours

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

*"First, solve the problem. Then, write the code."* — John Johnson

⭐ **If you find my work useful, consider starring my repositories!**

</div>
