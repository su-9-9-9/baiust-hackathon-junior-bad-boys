# baiust-hackathon-junior-bad-boys
baiust computar club hackathon 
# 🛡️ Anti-Kuddus Protocol Portal

A simple and lightweight single-page web application built for the **BAIUST CSE Spring Fest 2026**. This platform integrates a Login/Sign-Up authentication layer with Mission 1 through Mission 6 in a seamless UI flow.

---

## 🛠️ Local Setup Instructions

No server configurations or database setups are required to run this project.

1. Copy the source code and save it as `index.html` on your machine.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, or Safari).
3. **Note:** An active internet connection is required to render the automated ledger graph in Mission 4, as it fetches Chart.js via a public CDN.

---

## 🏗️ Architecture & Core Stack

* **Frontend Framework:** Built entirely using native HTML5, CSS3, and Vanilla JavaScript (No heavy frameworks used).
* **View Routing Engine:** Page shifting is handled programmatically via JavaScript by toggling CSS visibility classes, avoiding bulky external routing libraries.
* **Database State:** Utilizes the web browser's synchronous **localStorage** API. This allows custom parameters, account hashes, and metrics to persist even after reloading the page.
* **External Components:** Integrates **Chart.js** directly to parse dynamic visual charts.

---

## ⚖️ Architectural Trade-Offs

* **Pros:** Exceptionally easy to deploy (zero deployment footprint), highly optimized rendering speed, and zero backend maintenance overhead.
* **Cons:** Data is strictly isolated to the specific browser instance on that local machine. Security mechanisms are restricted to sandbox environments, making it unsuitable for scaled cloud deployment without upgrading to a remote SQL/NoSQL ecosystem.

---

## 🖼️ UI Layout Workflow

The core UI engine functions sequentially through these module blocks:
1. **🔐 Core Access Portal:** The entry terminal where users sign up and log in securely using their Roll Number and Private Password.
2. **📢 M1: The Anonymous Whistleblower:** A secure interface for submitting strikes and monitoring threat levels with a progressive structural warning bar.
3. **🪑 M2: Height Sorted Classroom Grid UI:** An automated workspace sorting student seating arrangements in a grid structure based on height indices.
4. **📚 M3 to M6 Modules:** Features the Syllabus Prompt Negotiator, Corrupt Economy Ledger Dashboard (Data Charting), Local SOS Backup Trigger, and the compliance Rulebook Fact-Checker.
👥Team
Developed for the BAIUST CSE Spring Fest 2026 Hackathon – Junior Segment.By Saif,Abir,Shafayet and Rakin

This project was created solely for educational and hackathon purposes.
