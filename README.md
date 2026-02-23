# Sean Slaughter Portfolio

This is a modern, responsive resume and portfolio website built with **Next.js** and **React**. Designed to showcase professional experience and technical skills in a smooth and elegant interface, the site serves as a live demonstration of full-stack development capabilities.

The project is currently hosted at [seanslaughter.dev](https://www.seanslaughter.dev/).

## 🚀 Features

* **Modern Tech Stack**: Built with Next.js 15, React 19, and TypeScript.
* **Elegant UI/UX**: Utilizes Tailwind CSS and Framer Motion for high-performance animations and a polished design.
* **Optimized Performance**: Configured for static export with optimized image handling.
* **Custom Components**: Includes interactive elements like a word cloud and specialized skill lists.
* **Third-Party Integrations**: Features integrations with the Scryfall API and GitHub for dynamic content.

## 🛠️ Tech Stack

* **Framework**: Next.js (App Router)
* **Styling**: Tailwind CSS
* **Animations**: Framer Motion
* **UI Components**: Radix UI (ShadCN)
* **Language**: TypeScript
* **Icons**: Lucide React & Iconoir

## 🏁 Getting Started

### Prerequisites

* Node.js (Latest LTS recommended)
* npm, yarn, pnpm, or bun

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/stslaug/stslaug.github.io.git
cd stslaug.github.io-main

```


2. **Install dependencies**:
```bash
npm install

```


3. **Run the development server**:
```bash
npm run dev

```


Open [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000) to view the result.

## 📦 Deployment

This project is configured for static site generation (SSG) and is deployed via GitHub Pages.

* **Build command**: `npm run build`
* **Export configuration**: The `next.config.ts` is set to `output: 'export'` with a distribution directory of `build`.
* **Deployment command**: `npm run deploy`

## 📂 Project Structure

* `src/app/`: Contains the main application routes and layouts.
* `src/components/`: Houses reusable UI components and graphical elements like the `ColorGrid` and `WordCloud`.
* `public/assets/`: Stores static assets including images and custom fonts like Noto Sans and Zain.
