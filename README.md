# 🚢 Balangay

> *A digital barter platform rooted in the Filipino spirit of bayanihan — where value moves through community, not cash.*

---

## 📖 Project Overview

**Balangay** is a full-stack web application built for the **"Pangarap sa Bayan" Hackathon**. It provides a digital barter marketplace where:

- 🏪 **Small businesses** can exchange services, surplus inventory, or storage space
- 👷 **Informal workers** can freely trade their skills
- 🤝 **Communities** can sustain themselves through mutual aid — even when cash runs out

Recognizing that unexpected crises often leave people with no money on hand, Balangay was designed to tackle real-world financial bottlenecks by creating a dedicated space for community-driven trade and market visibility.

---

## ✨ Inspiration

The Philippines has always had a culture of *bayanihan* — but for millions of Filipino small business owners and informal workers, that spirit hits a wall when cash runs out.

We built Balangay to bring that communal spirit into the digital age, where **value doesn't have to move through cash to move at all.**

---

## 🛠️ Technologies & Frameworks

| Technology | Purpose |
|---|---|
| **Next.js** | Core React framework — server-side rendering, routing, and app architecture |
| **React** | Building interactive and reusable UI components |
| **Express.js** | Custom backend REST API routes and server logic |
| **Firebase** | Firestore database management and user authentication |
| **Tailwind CSS** | Utility-first styling for a clean, responsive, modern UI |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm, yarn, pnpm, or bun

### Installation

```bash
# Clone the repository
git clone https://github.com/your-org/balangay.git
cd balangay

# Install dependencies
npm install
```

### Running the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

---

## ⚙️ How It Works

1. **Post** what you have — surplus goods, skills, services, or storage
2. **Browse** what your community needs
3. **Arrange** an exchange — all without a single peso changing hands

Balangay's core loop (posting a listing → browsing offers → initiating an exchange) is **fully functional end to end.**

---

## 🏗️ How We Built It

We used a modern JavaScript stack chosen for speed, scalability, and rapid development:

- **Next.js + React** for a fast, component-driven frontend
- **Express.js** for our custom REST API
- **Firebase** for real-time database management and authentication
- **Tailwind CSS** for a clean, responsive UI

The stack was chosen to let us move quickly while still shipping something polished and production-ready.

---

## 🧱 Challenges We Ran Into

Our biggest challenge was **structuring the project across a multi-layer stack** — aligning how data flows between Next.js, Express, and Firebase took significant coordination. Architectural decisions made early had downstream effects on everything, and we felt that friction throughout the build.

---

## 🏆 Accomplishments We're Proud Of

- ✅ The full core exchange loop is functional end to end
- 🇵🇭 Built something genuinely rooted in Filipino context — not a generic marketplace reskinned for local use

---

## 📚 What We Learned

- **Structure is not a luxury** — hours spent untangling architecture mid-build were hours we could have spent on features
- Our job wasn't to introduce something foreign to Filipino communities; it was to give existing *bayanihan* behavior **a better, digital home**

---

## 🔭 What's Next for Balangay

Our vision is to grow Balangay into an **open source, community-led project** where developers, designers, and organizers across the Philippines can contribute and localize it for their own communities.

> *The best version of Balangay isn't one we build alone — it's one we build together.*

---

## 👥 Team

Built with ❤️ by students for the **Pangarap sa Bayan Hackathon**.

---

## 📄 License

This project is open source. See [LICENSE](LICENSE) for details.
