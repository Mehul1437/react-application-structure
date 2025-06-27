```
src/
├── assets/                # Static assets (images, fonts)
│   ├── fonts/
│   ├── images/
│
├── components/            # UI components following Atomic Design
│   ├── atoms/             # Basic reusable elements (Button, Input, Label)
│   ├── molecules/         # Grouped atoms with logic (e.g., FormField)
│   ├── organisms/         # Complex UI sections (e.g., Header, Sidebar)
│   ├── templates/         # Page layouts (e.g., AuthLayout, DashboardLayout)
│
├── lib/                   # Business logic and utilities
│   ├── constants/         # Application-wide constants
│   ├── helpers/           # Reusable utility functions
│   ├── hooks/             # Custom React hooks
│   ├── store/             # State management (e.g., Redux, Zustand)
│   └── types/             # Shared TypeScript types and interfaces
│       └── types.ts
│
├── pages/                 # Page-level components (e.g., LoginPage, DashboardPage)
│   └── App.tsx            # Main application entry point
│
├── routes/                # Centralized routing logic
│   └── routes.tsx
│
├── services/              # API service layer (organized by domain)
│   └── products/
│       ├── api.ts         # API calls
│       ├── queries.ts     # React Query fetch functions
│       ├── mutations.ts   # React Query mutation functions
│       └── keys.ts        # Query keys for caching
│
├── styles/                # Global styles and theme config
│   └── globals.css
│
├── index.tsx              # React DOM root
├── .env.local             # Local environment variables
├── .gitignore
├── package.json

```
