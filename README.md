### Hi there, I'm Raflyandi Alviansyah 👋

I am a Computer Science student at BINUS University specializing in **Mobile Application & Technology**. My passion lies at the intersection of **Quantitative Finance, Artificial Intelligence, and Software Engineering.**

I don't just research algorithms; **I build the engines that run them.**

---

### 🚀 **Flagship Ecosystems & Architectures**

#### 1. 🛍️ [World Before Pandemic (WBFP) - Enterprise E-Commerce Architecture](https://github.com/RaflyandiALV/Worldbeforepandemic)
>
> *Status: Live Production | Tech: Next.js 15, React 19, Supabase (PostgreSQL), Cloudflare, Vercel, TailwindCSS*

**High-Performance Headless E-Commerce.** A complete, highly scalable web application engineered completely from scratch for a real-world fashion brand. I bypassed generic monolithic platforms like Shopify to establish raw performance, absolute data ownership, and enterprise-grade security.

* **FortKnox Security Architecture:**
  * **Database Edge:** Secured via rigorous PostgreSQL **Row Level Security (RLS)** isolating public catalog reads from highly-privileged admin mutations. Engineered custom SQL triggers (`on_auth_user_created`) to autonomously serialize user identities and maintain data integrity.
  * **Network Edge:** Proxied via **Cloudflare** utilizing **Strict SSL/TLS (Full Strict)**, active **Bot Fight Mode** heuristically dropping malicious scrapers natively, and built-in DDoS mitigation.
  * **Application Edge:** Hardened Next.js headers enforcing strict MIME sniffing protection (`X-Content-Type-Options: nosniff`), Frame denial for Clickjacking prevention (`X-Frame-Options: DENY`), and robust HTTP Strict Transport Security (`Strict-Transport-Security: HSTS preload`).

* **Zero-Egress Engineering Prowess:**
  * Analyzed massive egress bandwidth drains caused by high-fidelity (1MB+) Lookbook imagery. Strategically re-engineered the asset pipeline by bypassing Vercel's default Next.js Image Optimization (`unoptimized={true}`) and delegating 95% of the payload to Cloudflare's Edge Caching Proxy. This hyper-optimization achieved maximum visual fidelity while reducing database bandwidth costs to near-zero.

* **Autonomous Asynchronous Integrations:**
  * Engineered robust API endpoints natively listening to **Midtrans Webhooks** for real-time cryptographic transaction verification—automatically mutating database order lifecycles from `pending` to `paid` without human intervention.
  * Deeply integrated the **Biteship API** to synchronously generate airway bills (AWB) and dispatch couriers the millisecond a transaction clears.

* **Proprietary Admin CMS & Algorithmic Analytics:**
  * Designed a secure, custom-built internal command center integrating complex mathematical calculations. Features real-time multi-platform revenue analytics (tracking native vs. marketplace sales), dynamic margin tracking, granular inventory control, and automated shipment state management.

* **[Visit Live Site: worldbeforepandemic.com ➔](https://worldbeforepandemic.com)**

#### 2. 🖥️ [QuantWeb: Algorithmic Trading Dashboard](https://github.com/RaflyandiALV/QuantWeb)
>
> *Status: Live Production | Tech: React, FastAPI, Python, PostgreSQL*

**The Command Center.** A full-stack web platform that turns mathematical models into automated trading bots.

* **Features:** Real-time Market Scanner, Backtesting Engine (Grid/Momentum), and Telegram Bot Integration.
* **Engineering:** Built a custom Python API that processes financial data asynchronously and serves it to a responsive React Dashboard.
* **[View Documentation & Screenshots ➔](https://github.com/RaflyandiALV/QuantWeb)**

#### 3. 📱 [QuantIOS: Native Mobile Companion](https://github.com/RaflyandiALV/QuantIOS-MMS)
>
> *Status: Beta | Tech: Swift, SwiftUI, Core Data*

**Trading on the Go.** A native iOS application designed to monitor the QuantWeb ecosystem from anywhere.

* **Features:** Real-time Watchlist synchronization, Native iOS Charts, and Biometric Authentication.
* **Engineering:** Implemented complex data parsing from the Python backend and efficient local storage using JSON/CSV architecture.
* **[View Documentation & Screenshots ➔](https://github.com/RaflyandiALV/QuantIOS-MMS)**

---

### 🤖 **AI & Simulation Projects**

#### 4. 🚦 [AI-Powered Adaptive Traffic Control System](https://github.com/RaflyandiALV/AI-Urban-Traffic-Controller)
>
> *Tech: Python, YOLOv5, PyTorch, Computer Vision*

A smart city solution that uses Computer Vision to solve congestion.

* **Innovation:** Fine-tuned a YOLOv5 model to detect vehicle density in real-time.
* **Impact:** Dynamically adjusts traffic light duration based on weighted volume, reducing congestion by **>20%** in simulations.

#### 5. 🦖 [Open-World Dinosaur VR Experience](https://github.com/RaflyandiALV/Open-World-Dinosaur-VR-Experience)
>
> *Tech: C#, Unity Engine, Oculus SDK*

An immersive Virtual Reality game demonstrating complex AI behaviors.

* **Engineering:** Architected C# State Machines for dinosaur AI (Idle, Chase, Attack) and physics-based interactions for the Oculus headset.

---

### 🛠 **Technical Arsenal**

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Swift](https://img.shields.io/badge/-Swift-F05138?logo=swift&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) ![C#](https://img.shields.io/badge/-C%23-239120?logo=c-sharp&logoColor=white) |
| **Frontend/Mobile** | ![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) ![SwiftUI](https://img.shields.io/badge/-SwiftUI-007AFF?logo=swift&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-38B2AC?logo=tailwind-css&logoColor=white) |
| **Backend/Cloud** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?logo=supabase&logoColor=white) ![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?logo=cloudflare&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white) |
| **Data & AI** | ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![YOLOv5](https://img.shields.io/badge/-YOLOv5-00FFFF?logo=yolo&logoColor=black) |

---

### 📥 **Contact & Professional Info**

* 📄 **[Download Full CV (PDF)](https://drive.google.com/drive/folders/1IAoAhrqgm4lSGZhApImIc5S6uDFDytrj?usp=drive_link)**
* 💼 **[Connect on LinkedIn](https://www.linkedin.com/in/raflyandi-alviansyah05)**
* 📧 **Email:** <Raflyalv@gmail.com>
