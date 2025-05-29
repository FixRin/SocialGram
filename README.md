# SocialGram

[![Vercel](https://img.shields.io/badge/deployed%20on-Vercel-000000?logo=vercel)](https://socialgram.vercel.app)  
Live Demo: https://socialgram.vercel.app

A modern social networking web application for sharing photos, following users, and engaging through comments and likes—built with Next.js, Tailwind CSS, and Convex.

---

## 📝 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Environment Variables](#-environment-variables)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## ✨ Features

- **User Authentication:** Sign up, sign in, and secure sessions using Clerk.  
- **Profile Management:** Update avatar, bio, and personal details.  
- **Image Uploads:** Upload and display photos with Cloudinary integration.  
- **Feed & Explore:** View posts from followed users and discover popular content.  
- **Interactions:** Like posts, add comments, and follow/unfollow other users.  
- **Real-time Updates:** Live feed refresh powered by Convex edge functions.  
- **Responsive Design:** Optimized for mobile and desktop with Tailwind CSS.

---

## 🛠 Tech Stack

- **Framework:** Next.js (App Router)  
- **Language:** TypeScript  
- **Styling:** Tailwind CSS  
- **Authentication:** Clerk  
- **Database & Edge Functions:** Convex  
- **Image Storage:** Cloudinary  
- **Deployment:** Vercel

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 18  
- npm or yarn  
- A Convex project & deployment token  
- Clerk account & API keys  
- Cloudinary account & API credentials

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/FixRin/SocialGram.git
   cd SocialGram
   ```
2. **Install dependencies**  
   ```bash
   npm install
   # or
   yarn
   ```
3. **Copy environment example**  
   ```bash
   cp .env.example .env.local
   ```

### Running Locally

- **Development mode**  
  ```bash
  npm run dev
  ```  
  Open at http://localhost:3000

- **Build & Preview**  
  ```bash
  npm run build
  npm run start
  ```

---

## 🔒 Environment Variables

```dotenv
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_live_...
CLERK_SECRET_KEY=sk_live_...

# Convex
NEXT_PUBLIC_CONVEX_URL=your_convex_url
CONVEX_SECRET=your_convex_secret

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---
