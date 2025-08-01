# Hamza Malik - Personal Portfolio

A modern, responsive personal portfolio website built with Next.js 14, showcasing my work experience, skills, and projects.

## 🚀 Live Demo

[View Portfolio](https://hamza-malik.com)

## ✨ Features

- **Modern Design**: Clean, responsive design with smooth animations using Framer Motion
- **Dark/Light Mode**: Built-in theme switching with next-themes
- **Blog Support**: MDX-based blog with syntax highlighting
- **Performance Optimized**: Built with Next.js 14 App Router for optimal performance
- **TypeScript**: Fully typed for better development experience
- **Responsive**: Works perfectly on all devices
- **SEO Optimized**: Built-in SEO features with Next.js

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui + Radix UI
- **Animations**: Framer Motion
- **Content**: MDX with react-markdown
- **Deployment**: Vercel
- **Icons**: Lucide React
- **Theme**: next-themes

## 📦 Installation & Setup

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hamxa003/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start the development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎨 Customization

### Personal Information
Edit `src/data/resume.tsx` to update:
- Personal details (name, description, avatar)
- Work experience
- Education
- Skills
- Contact information
- Social links

### Styling
- Modify `tailwind.config.ts` for theme customization
- Update `src/app/globals.css` for global styles
- Customize components in `src/components/`

### Content
- Add blog posts in `content/` directory
- Update images in `public/` directory
- Modify pages in `src/app/`

## 📁 Project Structure

```
├── src/
│   ├── app/                 # Next.js App Router pages
│   ├── components/          # Reusable UI components
│   │   ├── ui/             # shadcn/ui components
│   │   └── magicui/        # Custom animation components
│   ├── data/               # Data configuration
│   └── lib/                # Utility functions
├── content/                # MDX blog posts
├── public/                 # Static assets
└── components.json         # shadcn/ui configuration
```

## 🚀 Deployment

This portfolio is optimized for deployment on Vercel:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

