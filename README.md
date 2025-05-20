---
title: 3DGenAI
description: A web-based app that generates 3D visuals from text prompts using generative AI and displays them interactively in a 3D environment.
date: 2025-04-8
image: https://3dgenai.eejay.me/images/banner.png 
category: Development
author:
 name: Juan Carlos de Borja
 role: Developer and 3D artist
 avatar: https://github.com/ttv-voidgg.png  
---

# 3DGenAI

**Prompt-to-3D Model Viewer Powered by AI**

[Live Demo →](https://3dgenai.eejay.me/)

3DGenAI is a web-based app that generates 3D visuals from text prompts using generative AI and displays them interactively in a 3D environment. Built with cutting-edge web technologies, it bridges prompt-based creativity with real-time 3D rendering.

![screenshot](public/preview.png) <!-- Add a real screenshot file here if available -->

---

## 🚀 Features

- 🧠 **Text-to-3D Generation**  
  Input a natural language prompt and generate a 3D visual concept instantly.

- 🎮 **Interactive 3D Viewer**  
  Explore AI-generated content in a WebGL-powered environment (OrbitControls).

- ⚡ **Real-time Updates**  
  See results immediately after submission with seamless rendering.

- 🌐 **Web-based & Responsive**  
  Runs on any modern browser, no installation needed.

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, React, TailwindCSS, Three.js  
- **AI Integration:** Hyper3D.AI
- **3D Rendering:** `@react-three/fiber`, `@react-three/drei`  
- **Deployment:** Vercel

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/eejayme/3dgenai.git
cd 3dgenai

# Install dependencies
npm install

# Start development server
npm run dev
