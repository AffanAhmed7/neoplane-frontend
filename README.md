# NeoPlane Frontend

This is the frontend repository for the **NeoPlane** real-time chat platform.

**Live Demo:** [https://neoplane-frontend.vercel.app/](https://neoplane-frontend.vercel.app/)  
**Backend Repository:** [https://github.com/AffanAhmed7/Neoplane-Backend](https://github.com/AffanAhmed7/Neoplane-Backend)

## 📌 Project Overview
NeoPlane is a robust, production-ready real-time communication platform designed to mimic the core functionalities of industry-leading chat applications like Discord and Slack. Built with a modern, high-performance tech stack, it supports seamless real-time messaging, sophisticated user presence, multimedia file sharing, and complex channel/group management.

## 🚀 Frontend Features
- **Real-Time Client:** Integrated `socket.io-client` for persistent, low-latency WebSocket connections enabling live messaging, typing indicators, and presence updates.
- **State Management:** **Zustand** for lightweight global state (managing active chats, user status) and **React Query** for caching, background synchronization, and server-state management.
- **Responsive UI & Animations:** Built with **Tailwind CSS v4** for a highly responsive, utility-first design system, paired with **Framer Motion** for fluid micro-animations and page transitions.
- **Hybrid Authentication:** Secure user authentication utilizing both **Firebase Auth** (OAuth/Google) and custom JWT-based email/password flows.
- **Cloud Media Handling:** Upload and display AWS S3-hosted media including avatars, channel banners, and message attachments.

## 🛠️ Tech Stack
- **Framework:** React 19 + TypeScript + Vite
- **Styling:** Tailwind CSS v4, clsx, tailwind-merge
- **State & Data Fetching:** Zustand, @tanstack/react-query, Axios
- **Real-Time Engine:** Socket.io-client
- **Authentication:** Firebase Auth
- **Animations:** Framer Motion
- **Icons:** Lucide React

## 🚀 Setup Instructions
1. Clone this repository.
2. Ensure you have `Node.js` installed.
3. Install dependencies: `npm install`
4. Set up the environment variables (e.g., Firebase config, API endpoints).
5. Start the development server: `npm run dev`
6. Build for production: `npm run build`

## 💡 Architecture Highlights
- React Query is utilized strategically to minimize backend database hits and optimize loading states.
- Reusable UI components styled comprehensively using modern Tailwind v4 practices.
- Strict TypeScript adoption for runtime safety and error reduction across the entire codebase.
