<h1 align="center">Hi there, I'm Rudresh Tiwari! 👋</h1>
<p align="center">
  <i>Full Stack Developer | MERN Stack | AI Integrations</i>
</p>
<p align="center">
  🌍 Based in India | 💡 Passionate about building innovative, scalable solutions
</p>



I design and implement full-stack systems with an emphasis on **clean architecture, performance, and maintainability**. My work spans **MERN stack development, Python services, and AI integrations**, creating solutions from **data-intensive web apps and modular CMS platforms** to **real-time analytics engines and intelligent assistant systems**.  

I focus on solving **complex engineering challenges**: optimizing data pipelines, managing concurrency, enforcing robust validations, and architecting systems that scale. I’m interested in **building reliable, testable, and efficient applications** in any domain — whether it’s finance, travel, productivity, or SaaS — and exploring how AI can enhance real-world software solutions.

---

### 🛠️ Technologies & Tools


![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404D59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300000F.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

### 🚀 Featured Projects

#### WelthWest – AI-Driven Stock Market Platform [![Visit Site](https://img.shields.io/badge/Visit-Site-0052CC?style=flat-square&logo=googlechrome&logoColor=white)](https://welthwest.com/)
* **Backtesting Engine:** Fetches raw OHLCV data via yfinance and computes 10+ technical indicators on-the-fly using the ta library. Generates Buy/Sell signals with a custom “voting mechanism” and applies strict risk management (ATR-based stops, drawdown limits). Monte Carlo simulations validate strategies across multiple market conditions.
* **AI Assistant:** FinanceOrchestrator + NextGenAIOrchestrator routes queries via Python-based intent detection (regex + keyword mapping) before sending structured prompts to OpenRouter (Mistral-7B) or Google Gemini APIs. Handles stock quotes, screeners, technical analysis, and news formatting with precise context blocks.
* **Market Regime Management:** CompositeScorer classifies market states into five regimes (e.g., bull_low_vol, bear_high_vol) and adjusts stock scores dynamically using weighted heuristics (RSI, MACD, ROC, volume).
* **Performance & Scaling:** Caching via Redis + Flask-Caching + cachetools. Symbol resolution accelerated with _nse_symbol_cache.json. Disk I/O optimized to prevent EC2 storage issues.
* **Architecture:** Hybrid microservices. Node.js frontend repos separate from monolithic Flask backend. Risk Management runs in an isolated Flask microservice, maintaining independent CORS and middleware logic.

⸻

#### BSG Infra – Full-Stack Equipment Rental Platform [![Visit Site](https://img.shields.io/badge/Visit-Site-FF9900?style=flat-square&logo=googlechrome&logoColor=white)](https://bsginfra.com/)
* **Inventory Management:** Equipment availability tracked via blockedDates arrays and availableUnits counters. Ensures multi-unit booking consistency with rigorous validation (date overlap, units > 0, availability flags). Race conditions theoretically possible due to lack of DB transactions, but mitigated by service-layer logic.
* **Business Logic:** All complex rules abstracted into modular services (availability.service.js, pricing.service.js, geolocation.service.js). Handles dynamic pricing (daily/week/month, regional multipliers), smart discounts, insurance/operator costs, and delivery radius checks.
* **API Design:** Highly structured RESTful MVC architecture with thin controllers and service-oriented design. Standardized responses enable easy client-side integration.
* **Payments:** Database prepared for Stripe/Razorpay/PayU integration with escrow/refunds/event timeline, but live payment processing not yet implemented.

⸻

#### Executive Portfolio – Custom CMS + AI Assistant Platform [![Live Demo](https://img.shields.io/badge/Live-Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://executive-portfolio-sandy.vercel.app/)
* **Messaging System:** Standard REST endpoints (POST /api/messages/submit, GET /api/messages/admin/all) handle user queries; no WebSockets or SSE streaming used.
* **AI Integration:** Backend consumes Google Generative AI via POST /api/ceo-chat, returns full response after completion.
* **CMS:** Strictly structured Mongoose schemas for Blog, AboutSection, Service, and other content types; no unstructured Mixed fields.
* **Auth & Roles:** JWT + bcryptjs with admin and superadmin roles. Middlewares enforce role-based route access.

⸻

#### Explore Indian Islands – Vacation Planning Web App [![Live Demo](https://img.shields.io/badge/Live-Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://exploreindianislands-bn1k1ulvx-rudresh-tiwaris-projects.vercel.app/)
* **Data & Queries:** MERN-based app with structured geo-data stored in MongoDB. Filtering and search executed server-side for performance.
* **UI/UX:** Clean React frontend with intuitive discovery workflows for islands in India.
* **Architecture:** RESTful APIs with Node.js backend and MongoDB; designed for scaling as location dataset grows.
### 🌟 Let's Connect!

I'm always open to collaborating on interesting projects or discussing new ideas. Feel free to reach out to me!

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rudresh-tiwari-99bb57297/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rudraprataptiwari786@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rudreshtiwari10.github.io/Portfolio/)

---

---

### 🎉 Code Persona

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-
class SoftwareEngineer:

    def __init__(self):
        self.name = "Rudresh Tiwari"
        self.role = "Full Stack Developer"
        self.passions = ["MERN", "Python", "AI Integration", "System Design"]

    def build_solution(self):
        return "Turning complex problems into elegant, scalable code! 🚀"

if __name__ == "__main__":
    me = SoftwareEngineer()
    print(me.build_solution())
