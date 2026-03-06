# 🚀 1Flow: AI-Powered No-Code Website Builder SaaS

**1Flow** is a premium, production-ready SaaS platform that allows users to generate, customize, and deploy professional websites in seconds. Built for developers who want a high-performance stack without third-party overhead.

### 🌐 [Live Demo](https://1flow.1987.ai/) | 📱 [WhatsApp: +254 757 475 299](https://wa.me/254757475299)

---

## 🔥 Why 1Flow?

1Flow eliminates the complexity of website creation. Using a single prompt, the AI builds a structured, styled, and copy-written landing page. 

**The USP (Unique Selling Point):** Your users connect their own **Vercel account** to the platform. This allows them to publish sites directly to their own infrastructure with a single click—no manual exporting required.

### ✨ Key Features
* **AI-Driven Generation:** Transform a text prompt into a high-converting landing page instantly.
* **Native Authentication:** Secure Login/Signup powered by **NextAuth.js** (no Clerk required).
* **High-Performance Database:** Fully integrated with **Neon (Serverless Postgres)** for lightning-fast data fetching.
* **Vercel Auto-Deploy:** Native integration with the Vercel API for automated site publishing.
* **No-Code Visual Editor:** A lightweight drag-and-drop interface for real-time text and image customization.
* **Responsive by Default:** Every generated site is mobile-first and SEO-optimized.

---

## 🛠️ Technical Stack

* **Framework:** Next.js 14+ (App Router)
* **Database:** **Neon** (Serverless PostgreSQL)
* **Authentication:** NextAuth.js (Database Strategy with Neon)
* **Styling:** Tailwind CSS + Shadcn UI
* **Deployment Engine:** Vercel REST API Integration

---

## 🚀 Getting Started (For Buyers)

Setting up your 1Flow instance is straightforward. All you need are your environment variables:

1.  **Neon DB:** Connect your Neon project string to `DATABASE_URL`.
2.  **Authentication:** Configure your `NEXTAUTH_SECRET` for secure sessions.
3.  **Vercel Integration:** Add your Vercel Team/User ID to the dashboard to enable the "Connect & Publish" feature.
4.  **AI Engine:** Plug in your OpenAI or Anthropic API key.

```env
# Environment Configuration
DATABASE_URL="postgresql://user:password@neon-host/1flow?sslmode=require"
NEXTAUTH_SECRET="your_secure_secret"
VERCEL_API_TOKEN="your_vercel_token"
AI_MODEL_KEY="your_ai_api_key"
