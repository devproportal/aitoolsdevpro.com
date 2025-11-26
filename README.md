# 🛠️ AIToolsDevPro.com - The AI Tool Directory & Review Platform

## 🎯 Project Goal
This is the **revenue core** site of the DevPro network. Our goal is to provide a highly optimized, data-driven directory of AI tools for developers and creators. The structure is designed to maximize Google AdSense and affiliate revenue by focusing on high-commercial-intent keywords (tools, reviews, pricing).

---

## 🛠️ Technology Stack (Mobile-First)
* **Framework:** Hugo (Static Site Generator) - *Essential for lightning-fast loading on mobile devices.*
* **Data Management:** YAML Files (`data/tools.yaml`)
* **Styling:** Tailwind CSS (or your chosen framework) - *For responsive, mobile-first design.*
* **Deployment:** Cloudflare Pages / Vercel

## 📁 Core Data Structure
All tool listings are managed via the **Data Files** approach.

### **Data Update Guide (Focus on Commercial Data)**
To add or modify a tool, edit the `data/tools.yaml` file. Key fields to maintain for high AdSense RPM:

| Field (Key) | Example Value | Description |
| :--- | :--- | :--- |
| `name` | GitHub Copilot | The product name |
| `slug` | github-copilot | Used to generate review URLs (`/reviews/slug/`) |
| `url` | Official Link | **Official or Affiliate Link (High monetization value)** |
| `category` | coding-assistants | Primary functional category (for navigation) |
| `price_tier` | Subscription | Pricing model (Freemium, Paid) |
| `rating` | 4.9 | Your personal review rating |

### **Local Development**
```bash
hugo server -D
