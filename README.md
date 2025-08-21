# ✨ Video Calling Interview Platform

A full-stack video interview platform enabling real-time communication, secure authentication, and a smooth user experience.

---

## 🚀 Tech Stack

- **Next.js** (App Router, Server Components, Server Actions)
- **TypeScript**
- **Stream** (for video calling, screen sharing, recording)
- **Convex** (serverless functions and storage)
- **Clerk** (authentication and user management)
- **Tailwind CSS** + **Shadcn UI**

---

## 🔑 Features

- 🎥 Video Calling
- 🖥️ Screen Sharing
- 🎬 Screen Recording
- 🔒 Authentication & Authorization (via Clerk)
- 💻 Full support for Client & Server Components
- 🛣️ Dynamic & Static Routing
- 🎨 Modern UI with Tailwind CSS & Shadcn
- ✨ Server Actions for backend operations

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/iamsufiyan560/Video-Calling-Interview-Platform.git
cd video-interview-platform
```

### 2. Install Dependencies

```bash
npm install
```

---

## 🛠️ Environment Setup

Create a `.env.local` file at the project root and add the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
```

> ⚠️ Do **not** commit your environment file.

---

## 🧪 Running the App

```bash
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
video-interview-platform/
├── app/                  # App Router pages & layouts
├── components/           # Shared React components
├── convex/               # Convex serverless functions
├── lib/                  # Utility functions
├── public/               # Static assets
├── styles/               # Global styles
└── .env.local            # Environment variables (not committed)
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Author

Built with ❤️ by SUFIYAN.
