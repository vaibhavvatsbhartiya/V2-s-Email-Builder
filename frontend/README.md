```
frontend/
├── public/
│   ├── index.html         # Main HTML file
│   └── assets/            # Static assets (images, icons, etc.)
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── Navbar.js      # Navigation bar
│   │   ├── Footer.js      # Footer for all pages
│   │   ├── ProtectedRoute.js # Route guard for authenticated pages
│   │   └── ImageUploader.js
│   ├── pages/             # Pages for routing
│   │   ├── LandingPage.js # Public landing page
│   │   ├── Login.js       # Login page
│   │   ├── Signup.js      # Signup page
│   │   └── Dashboard.js   # Main dashboard with the email builder
│   ├── features/          # Feature-specific submodules
│   │   └── emailBuilder/
│   │       ├── Editor.js  # Core email editor
│   │       ├── Preview.js # Email preview component
│   │       └── Config.js  # Email configuration logic
│   ├── services/          # API logic
│   │   ├── authService.js # Auth API services
│   │   └── api.js         # Email-related API services
│   ├── styles/            # CSS/SCSS styles
│   ├── context/           # React Context for global state
│   │   └── AuthContext.js # Authentication state management
│   ├── App.js             # Main React component
│   ├── index.js           # React entry point
│   └── constants.js       # Global constants (e.g., API base URL)
├── package.json           # Frontend dependencies
└── vite.config.js         # Configuration file (if using Vite)
```