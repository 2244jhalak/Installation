# React + TypeScript + Redux Toolkit + Tailwind CSS (Vite Setup)

This project uses **Vite** to scaffold a modern React app using TypeScript, Redux Toolkit for state management, and Tailwind CSS for styling.

---

## 🛠️ Installation & Setup Guide

Follow the steps below to create and run your project:

### 1️⃣ Create Project Using Vite

```bash
npm create vite@latest my-app -- --template react-ts
cd my-app
# Installation
```
```bash
npm install
npm install @reduxjs/toolkit react-redux
npm install tailwindcss @tailwindcss/vite
# Installation
```
```bash
// vite.config.ts
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';
import tailwindcss from '@tailwindcss/vite';

export default defineConfig({
  plugins: [react(), tailwindcss()],
});

# vite.config.ts
```
```bash
@import "tailwindcss";
# app.css
```bash
npm run dev


