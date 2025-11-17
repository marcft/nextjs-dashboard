# Next.js Dashboard - ACME Financial Application

A full-stack financial dashboard built with **Next.js 16** (App Router) as part of the official [Next.js Learn Course](https://nextjs.org/learn). This project demonstrates modern Next.js features and best practices for building production-ready web applications.

## 📋 Overview

ACME is a comprehensive dashboard application that showcases real-world implementation of Next.js features including server components, streaming, authentication, database integration, and optimized rendering strategies.

## ✨ Features

- **🎨 Modern UI**: Responsive design with Tailwind CSS and custom CSS modules
- **⚡ Optimized Performance**: Font and image optimization using Next.js built-in components
- **🔐 Authentication**: Secure login with NextAuth.js and credential-based authentication
- **📊 Dashboard Analytics**: Revenue charts, latest invoices, and customer metrics
- **💾 Database Integration**: PostgreSQL with secure server-side data fetching
- **🔍 Search & Pagination**: Real-time search and paginated data views
- **📝 CRUD Operations**: Create, read, update, and delete invoices using Server Actions
- **⏳ Streaming & Suspense**: Improved loading experience with progressive rendering
- **♿ Accessibility**: Server-side form validation and ARIA-compliant components
- **🚨 Error Handling**: Graceful error boundaries and 404 pages
- **📱 Responsive Design**: Mobile-first approach with adaptive layouts

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS, CSS Modules
- **Authentication**: NextAuth.js
- **Database**: PostgreSQL
- **Validation**: Zod
- **Icons**: Heroicons
- **Deployment**: Vercel-ready
- **Package Manager**: pnpm

## 📁 Project Structure

```text
app/
├── dashboard/          # Protected dashboard routes
│   ├── (overview)/    # Dashboard home with streaming
│   ├── customers/     # Customer management
│   └── invoices/      # Invoice CRUD operations
├── lib/               # Utilities and data functions
│   ├── actions.ts     # Server Actions for mutations
│   ├── data.ts        # Data fetching functions
│   └── definitions.ts # TypeScript types
├── ui/                # Reusable UI components
│   ├── dashboard/     # Dashboard-specific components
│   ├── invoices/      # Invoice-related components
│   └── customers/     # Customer table components
├── login/             # Authentication page
├── layout.tsx         # Root layout
└── page.tsx           # Landing page
```

## 📚 Learning Path

This project covers 16 comprehensive chapters from the Next.js Learn Course:

1. **Getting Started** - Project setup and exploration
2. **CSS Styling** - Tailwind CSS and CSS modules
3. **Optimizing Fonts and Images** - Built-in optimization
4. **Creating Layouts and Pages** - File-based routing
5. **Navigating Between Pages** - `<Link>` component
6. **Setting Up Your Database** - PostgreSQL integration
7. **Fetching Data** - Server Components and data fetching
8. **Static and Dynamic Rendering** - Rendering strategies
9. **Streaming** - Progressive loading with Suspense
10. **Adding Search and Pagination** - URL-based search
11. **Mutating Data** - Server Actions for mutations
12. **Handling Errors** - Error boundaries and 404 pages
13. **Improving Accessibility** - Form validation and ARIA
14. **Adding Authentication** - NextAuth.js integration
15. **Adding Metadata** - SEO optimization

## 🔑 Key Concepts Demonstrated

- **Server Components**: Default server-side rendering for optimal performance
- **Server Actions**: Type-safe server-side mutations without API routes
- **Streaming with Suspense**: Progressive rendering for better UX
- **Route Groups**: Organized routing with `(overview)` pattern
- **Dynamic Routes**: `[id]` segments for dynamic pages
- **Parallel Data Fetching**: Optimized data loading strategies
- **Form Validation**: Zod schemas with server-side validation
- **Middleware**: Route protection and authentication
- **Error Boundaries**: `error.tsx` and `not-found.tsx` files

## 📖 Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js Learn Course](https://nextjs.org/learn)
- [Vercel Deployment Guides](https://vercel.com/guides)
- [TypeScript Documentation](https://www.typescriptlang.org/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

---

Built with ❤️ using Next.js
