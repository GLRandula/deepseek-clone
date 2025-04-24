This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# 🧠 DeepSeek Clone

A full-stack AI-powered chatbot clone built with **Next.js**, authenticated with **Clerk**, data stored in **MongoDB Atlas**, and responses powered by the **DeepSeek API**. The app is deployed on **Vercel** for seamless performance and scalability.

---

## 🚀 Features

- 🔐 Authentication with [Clerk.dev](https://clerk.dev)
- 🌐 Server-side rendered UI with [Next.js](https://nextjs.org)
- 📦 Scalable document database with [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- 🤖 AI-powered responses via [DeepSeek API](https://deepseek.com)
- ⚡ Hosted on [Vercel](https://vercel.com)
- 📄 Chat history & user data saved securely
- ✨ Beautiful, responsive UI

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 14 (App Router)
- **Auth:** Clerk
- **Database:** MongoDB Atlas
- **AI Backend:** DeepSeek API
- **Deployment:** Vercel
- **Styling:** Tailwind CSS
- **Font:** [Geist](https://vercel.com/font) (via `next/font`)

---

## 📦 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/deepseek-clone.git
cd deepseek-clone
npm install
```
Create a `.env.local` file in the root directory with the following environment variables:
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
MONGODB_URI=your_mongodb_atlas_connection_string
DEEPSEEK_API_KEY=your_deepseek_api_key
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

## Project Structure
```bash
.
├── app/                # App directory (Next.js App Router)
│   ├── api/            # API route handlers
│   ├── components/     # Reusable UI components
│   ├── page.tsx        # Main app page
│   └── ...
├── lib/                # Utilities (e.g., MongoDB connection)
├── public/             # Static assets
├── styles/             # Global styles
├── .env.local          # Environment variables
└── ...
```

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
