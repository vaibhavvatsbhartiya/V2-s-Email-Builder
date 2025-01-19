```
backend/
├── controllers/
│   ├── emailController.js  # Business logic
├── routes/
│   ├── emailRoutes.js      # API routes
├── models/
│   ├── EmailTemplate.js    # MongoDB schema
├── views/
│   └── layout.html         # Base email template
├── uploads/                # Uploaded images
├── app.js                  # Main app file
├── package.json            # Backend dependencies
└── config/
    ├── db.js               # MongoDB connection
    └── constants.js        # App constants
```

### Setup Backend:

**Node.js: Initialize the project and install dependencies:**
```bash
npm init -y
npm install express mongoose multer body-parser cors ejs
```