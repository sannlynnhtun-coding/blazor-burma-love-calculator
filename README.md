# ❤️ Love Calculator | Premium Red Edition

A state-of-the-art, high-performance **Love Resonance Engine** built with **Blazor WebAssembly** and **.NET 10**. This application combines modern design aesthetics with a robust calculation algorithm to determine name compatibility.

![Premium Red Theme](https://img.shields.io/badge/Theme-Premium%20Red-DC2626?style=for-the-badge)
![Built with .NET 10](https://img.shields.io/badge/.NET-10.0-512BD4?style=for-the-badge&logo=dotnet)
![Tailwind CSS 4](https://img.shields.io/badge/Styling-Tailwind%204-06B6D4?style=for-the-badge&logo=tailwindcss)
![Vercel Deploy](https://img.shields.io/badge/Deploy-Vercel-000000?style=for-the-badge&logo=vercel)

## 🌟 Overview

The **Burma Love Calculator Pro** is a modern reimagining of the classic name-matching logic, optimized for speed and visual excellence. It features a "Premium Red" interface inspired by **shadcn/ui** and **glassmorphism** principles.

## 🚀 Key Features

- **Resonance Algorithm**: A deterministic name reduction engine that calculates deep compatibility scores.
- **Trace Visualization**: View every mathematical step of the calculation to see how the "spirits of the names" align.
- **Micro-Animations**: Experience a "Heart Burst" particle effect upon calculation and premium "breathing" aura glows for high scores.
- **Fast-as-Light Loading**: Custom CSS loader and optimized WASM runtime ensures a "no-wait" experience.
- **Responsive Design**: Mobile-first architecture that looks stunning on everything from an iPhone to a 4K display.

## 🛠️ Tech Stack

- **Framework**: .NET 10.0 (Blazor WebAssembly)
- **Styling**: Tailwind CSS v4.2.4 (using the edge-compatible `@tailwindcss/cli`)
- **Icons**: Custom Premium SVG Brand Icons
- **Deployment**: Automated via GitHub Actions to Vercel
- **Build Pipeline**: Custom MSBuild targets for synchronized Tailwind CSS compilation

## 💻 Local Development

### Prerequisites
- .NET 10 SDK
- Node.js (for Tailwind CLI)

### Running the App
1. Clone the repository
2. Restore dependencies:
   ```bash
   npm install
   dotnet restore
   ```
3. Run with hot reload:
   ```bash
   dotnet watch
   ```

## 🚢 Deployment

The project is configured for automated deployment via **GitHub Actions** to **Vercel**.

### Configuration Highlights:
- **CI/CD**: Builds the .NET project, compiles Tailwind CSS, and prepares static assets with a fingerprinting fix for Vercel's edge network.
- **Vercel Routing**: Configured via `vercel.json` to handle SPA routing and serve Brotli/Gzip compressed assets with correct headers.

## 📜 License

Created for fun and demonstration. Not a scientific relationship metric.

---
*Built with ❤️ by Antigravity*
