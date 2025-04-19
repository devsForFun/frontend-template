# Frontend Template - Next.js 15 + Tailwind CSS v4 + Supabase

A modern SaaS template built with Next.js 15, Tailwind CSS v4, Shadcn UI v2, and Supabase.

## Features

- ⚡️ **Next.js 15** - The React framework for production
- 💨 **Tailwind CSS v4** - A utility-first CSS framework
- 🔥 **Shadcn UI v2** - Beautifully designed components
- 🔐 **Supabase** - For authentication and database
- 📝 **TypeScript** - Static type checking
- 📱 **Responsive Design** - Mobile-first approach
- 🌓 **Dark Mode** - Light and dark theme support
- 🧩 **React Hook Form** - Flexible form validation
- ⚙️ **Zod** - Schema validation

## Prerequisites

- Node.js 18+ (recommended: 20+)
- npm or yarn or pnpm

## Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/frontend-template.git
cd frontend-template
```

### Install dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### Set up environment variables

1. Copy the `.env.example` file to `.env.local`:

```bash
cp .env.example .env.local
```

2. Update the environment variables in `.env.local` with your Supabase credentials:

```
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
NEXT_PUBLIC_SITE_URL=http://localhost:3000
```

### Run the development server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Your application should now be running at [http://localhost:3000](http://localhost:3000).

## Project Structure

```
/
├── app/                    # Next.js App Router
│   ├── (auth)/             # Authentication routes
│   ├── (public)/           # Public routes
│   └── (authenticated)/    # Protected routes
├── components/             # React components
├── hooks/                  # Custom React hooks
├── lib/                    # Utility functions and libraries
├── public/                 # Static assets
└── utils/                  # Helper functions
```

## Deployment

The application can be deployed to any platform that supports Next.js, such as Vercel, Netlify, or a custom server.

```bash
# Build the application
npm run build
# or
yarn build
# or
pnpm build

# Start the production server
npm start
# or
yarn start
# or
pnpm start
```

## Available Scripts

- `npm run dev` - Run the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm run clean:dotfiles` - Clean up dotfiles
- `npm run clean:node_modules` - Remove node_modules
- `npm run clean:cache` - Clear Next.js cache

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.