# High-Fidelity Prototype Design

## Overview
A React + TypeScript expense tracking application with authentication and group expense management. Originally imported from a Figma design prototype. The app uses Supabase for backend services including authentication, database, and serverless functions.

## Project Architecture
- **Frontend**: React 18 + TypeScript with Vite build system
- **UI Components**: Radix UI primitives with custom styling
- **Styling**: TailwindCSS
- **Backend**: Supabase (authentication, database, serverless functions)
- **State Management**: React Context API
- **Build Tool**: Vite 6.3.5

## Key Features
- User authentication (sign up, sign in, sign out)
- Landing page and main application views
- Dashboard with expense statistics
- Group expense management
- User profiles
- Expense tracking and management

## Project Structure
```
High-Fidelity Prototype Design/
├── src/
│   ├── components/         # React components
│   │   ├── ui/            # Reusable UI components (Radix-based)
│   │   ├── figma/         # Figma-specific components
│   │   ├── AuthPage.tsx   # Authentication page
│   │   ├── Dashboard.tsx  # Main dashboard
│   │   ├── Expenses.tsx   # Expense management
│   │   ├── Groups.tsx     # Group management
│   │   ├── LandingPage.tsx # Landing page
│   │   ├── MainApp.tsx    # Main application wrapper
│   │   └── Profile.tsx    # User profile
│   ├── contexts/          # React contexts
│   │   └── AuthContext.tsx # Authentication context
│   ├── utils/
│   │   └── supabase/      # Supabase client and API utilities
│   ├── styles/            # Global styles
│   └── supabase/functions/ # Supabase Edge Functions
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig.json
├── tailwind.config.js
└── postcss.config.js
```

## Configuration
- **Development Server**: Configured to run on 0.0.0.0:5000 for Replit environment
- **Build Output**: Builds to `/build` directory
- **Deployment**: Configured for autoscale deployment with static file serving

## Setup Complete
- ✅ Node.js environment set up
- ✅ Dependencies installed
- ✅ TypeScript configuration added
- ✅ TailwindCSS configured
- ✅ Vite configured for Replit environment
- ✅ Development workflow running on port 5000
- ✅ Deployment configuration set up

## External Dependencies
- **Supabase Project**: Uses existing Supabase project with ID: rryutxntfvqjtmvtozdh
- **Authentication**: Configured to use Supabase Auth
- **Database**: Uses Supabase PostgreSQL database
- **API**: Custom serverless functions deployed on Supabase

## Recent Changes
- September 7, 2025: Initial project import and Replit environment setup
- Cleaned up duplicate directories from GitHub import
- Configured Vite for Replit environment (host: 0.0.0.0, port: 5000)
- Added TypeScript configuration files
- Installed and configured TailwindCSS
- Set up development workflow and deployment configuration