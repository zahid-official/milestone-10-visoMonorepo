<div align="center">

<img src="https://viso-official.surge.sh/assets/2.logo.svg" alt="Viso Logo" width="50" />

# Viso - Visa Application Companion

A full-stack monorepo web application for seamless visa discovery, application management, and progress tracking — powered by React, Node.js, Express, and MongoDB.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-viso--official.surge.sh-00C853?style=for-the-badge&logo=netlify&logoColor=white)](https://viso-official.surge.sh/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official/milestone-10-visoMonorepo)
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge" alt="DaisyUI" />

</div>

<br/>

## 🔍 Overview

**Viso** is a full-stack visa application companion built as a monorepo with separate client and server workspaces. Users can browse visa types, view detailed requirements, submit applications, track their progress, and manage their added visas — all within a clean, responsive interface backed by a RESTful API and MongoDB persistence.

> _Where every application brings your travel dreams closer to reality._

<br/>

## ✨ Key Features

### 🌍 Visa Discovery & Management

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Browse All Visas</b></td><td>Explore a comprehensive catalog of visa types with filtering by category</td></tr>
<tr><td><b>Visa Details</b></td><td>View in-depth visa information including requirements, fees, processing time, and application method</td></tr>
<tr><td><b>Add New Visa</b></td><td>Authenticated users can contribute new visa entries to the platform database</td></tr>
<tr><td><b>Update & Delete</b></td><td>Full CRUD operations — edit visa details or remove entries you've added</td></tr>
<tr><td><b>Type Filtering</b></td><td>Filter visas by type (Tourist, Student, Business, etc.) for quick discovery</td></tr>
</tbody>
</table>

### 🔐 Authentication & Security

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Multi-Method Auth</b></td><td>Register, sign in, and sign out with email/password — plus Google OAuth via Firebase</td></tr>
<tr><td><b>Protected Routes</b></td><td>Add Visa, My Visas, and My Applications pages are secured behind authenticated private routes</td></tr>
<tr><td><b>User-Scoped Data</b></td><td>Each user sees only their own added visas and submitted applications</td></tr>
</tbody>
</table>

### 🎨 User Interface

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Responsive Design</b></td><td>Fully optimized for mobile, tablet, and desktop viewports</td></tr>
<tr><td><b>Reveal Animations</b></td><td>Smooth scroll-triggered animations powered by <code>react-awesome-reveal</code></td></tr>
<tr><td><b>Interactive Sliders</b></td><td>Swiper-based carousels for dynamic banner and content presentation</td></tr>
<tr><td><b>Typewriter Effects</b></td><td>Engaging text animations via <code>react-simple-typewriter</code></td></tr>
<tr><td><b>Toast Notifications</b></td><td>User-friendly feedback through <code>react-toastify</code> alerts</td></tr>
<tr><td><b>SweetAlert2 Modals</b></td><td>Beautiful confirmation dialogs for delete and update operations</td></tr>
<tr><td><b>Application Search</b></td><td>Search submitted applications by country name with real-time results</td></tr>
</tbody>
</table>

<br/>

## 🛠️ Tech Stack

<table align="center">
<thead>
<tr><th align="left">Technology</th><th align="center">Version</th><th align="left">Purpose</th></tr>
</thead>
<tbody>
<tr><td><b>React</b></td><td align="center"><code>^18.3.1</code></td><td>Component-based UI development</td></tr>
<tr><td><b>JavaScript</b></td><td align="center"><code>ES6+</code></td><td>Application logic and interactivity</td></tr>
<tr><td><b>Vite</b></td><td align="center"><code>^6.0.1</code></td><td>Lightning-fast dev server and build tooling</td></tr>
<tr><td><b>Firebase</b></td><td align="center"><code>^11.0.2</code></td><td>Authentication and user management</td></tr>
<tr><td><b>React Router DOM</b></td><td align="center"><code>^7.0.2</code></td><td>Declarative client-side routing</td></tr>
<tr><td><b>Tailwind CSS</b></td><td align="center"><code>^3.4.16</code></td><td>Utility-first CSS framework</td></tr>
<tr><td><b>DaisyUI</b></td><td align="center"><code>^4.12.14</code></td><td>Tailwind-based UI component library</td></tr>
<tr><td><b>Node.js</b></td><td align="center"><code>v18+</code></td><td>Server-side JavaScript runtime</td></tr>
<tr><td><b>Express</b></td><td align="center"><code>^4.21.2</code></td><td>Minimalist web framework for REST API</td></tr>
<tr><td><b>MongoDB</b></td><td align="center"><code>^6.11.0</code></td><td>NoSQL database for data persistence</td></tr>
<tr><td><b>CORS</b></td><td align="center"><code>^2.8.5</code></td><td>Cross-origin resource sharing middleware</td></tr>
<tr><td><b>dotenv</b></td><td align="center"><code>^16.4.7</code></td><td>Environment variable management</td></tr>
<tr><td><b>Swiper</b></td><td align="center"><code>^11.1.15</code></td><td>Touch-enabled slider and carousel</td></tr>
<tr><td><b>React Awesome Reveal</b></td><td align="center"><code>^4.2.14</code></td><td>Scroll-triggered reveal animations</td></tr>
<tr><td><b>React Simple Typewriter</b></td><td align="center"><code>^5.0.1</code></td><td>Typewriter text animation effect</td></tr>
<tr><td><b>React Toastify</b></td><td align="center"><code>^10.0.6</code></td><td>Toast notification system</td></tr>
<tr><td><b>SweetAlert2</b></td><td align="center"><code>^11.14.5</code></td><td>Beautiful alert and confirmation dialogs</td></tr>
<tr><td><b>React Icons</b></td><td align="center"><code>^5.4.0</code></td><td>Popular icon sets as React components</td></tr>
</tbody>
</table>

<br/>

## 🏗️ Architecture

<div align="center">
<pre>
┌─────────────────────────────────────────────────────────────────────┐
│                           Browser                                   │
├─────────────────────────────────────────────────────────────────────┤
│  React Client (Vite)                                                │
│  ┌───────────┐  ┌──────────────┐  ┌──────────────────────────────┐  │
│  │  Layout   │  │  React       │  │  Auth Provider               │  │
│  │  (Navbar+ │◄─┤  Router      │  │  (Firebase Context)          │  │
│  │   Footer) │  │  (Public +   │  │                              │  │
│  │           │  │   Private)   │  │  • Login / Register          │  │
│  └───────────┘  └──────┬───────┘  │  • Google OAuth              │  │
│                        │          └──────────────────────────────┘  │
│               ┌────────▼────────┐                                   │
│               │     Pages       │                                   │
│               │  Home │AllVisas │                                   │
│               │  AddVisa│MyVisas│                                   │
│               │  MyApplications │                                   │
│               └────────┬────────┘                                   │
│                        │                                            │
│               ┌────────▼────────┐                                   │
│               │   Components    │                                   │
│               │  Cards │ Banner │                                   │
│               │  Slider│ Forms  │                                   │
│               └────────┬────────┘                                   │
│                        │  HTTP Requests (fetch)                     │
├────────────────────────┼────────────────────────────────────────────┤
│                        ▼                                            │
│  Express Server (Node.js)                                           │
│  ┌─────────────────────────────────────────────────────────────┐    │
│  │  REST API Endpoints                                         │    │
│  │  GET  /          — Latest visas (home)                      │    │
│  │  GET  /visa      — All visas                                │    │
│  │  POST /visa      — Create visa                              │    │
│  │  PUT  /update/:id — Update visa                             │    │
│  │  DEL  /visaDetails/:id — Delete visa                        │    │
│  │  POST /applications    — Submit application                 │    │
│  │  GET  /applications/:email — User applications              │    │
│  │  DEL  /applicationDetails/:id — Cancel application          │    │
│  │  GET  /filters/:visaType — Filter by type                   │    │
│  │  GET  /search?searchQuery= — Search applications            │    │
│  └───────────────────────────┬─────────────────────────────────┘    │
│                              │                                      │
│                    ┌─────────▼──────────┐                           │
│                    │   MongoDB Atlas    │                           │
│                    │  visasDB           │                           │
│                    │  ├── visas         │                           │
│                    │  └── applications  │                           │
│                    └────────────────────┘                           │
└─────────────────────────────────────────────────────────────────────┘
</pre>
</div>

## 📂 Project Structure

```
milestone-10-visoMonorepo/
│
├── README.md                          # Project documentation
│
├── client/                            # Frontend — React + Vite
│   ├── index.html                     # HTML entry point
│   ├── package.json                   # Client dependencies and scripts
│   ├── vite.config.js                 # Vite configuration
│   ├── tailwind.config.js             # Tailwind CSS configuration
│   ├── postcss.config.js              # PostCSS configuration
│   │
│   ├── public/                        # Static assets
│   │   └── assets/                    # Images, banners, icons, and logos
│   │
│   └── src/
│       ├── main.jsx                   # React DOM entry point
│       ├── App.jsx                    # Root application wrapper
│       ├── index.css                  # Global styles
│       │
│       ├── Layout/                    # Shared layout (Navbar + Footer)
│       ├── Routes/                    # Route config and private route guard
│       │
│       └── Components/
│           ├── Auth/                  # Firebase authentication (Login, Register, OAuth)
│           ├── Home/                  # Landing page sections (Banner, Cards, Extras)
│           ├── AllVisas/              # Visa catalog and individual visa details
│           ├── AddVisa/               # Add new visa form
│           ├── MyVisas/               # User's added visas (edit/delete)
│           └── MyApplications/        # User's submitted applications (search/cancel)
│
└── server/                            # Backend — Node.js + Express
    ├── index.js                       # Server entry point and API routes
    ├── package.json                   # Server dependencies
    └── vercel.json                    # Vercel deployment configuration
```

<br/>

## 🚀 Getting Started

### Prerequisites

<table align="center">
<thead>
<tr><th align="left">Requirement</th><th align="left">Details</th></tr>
</thead>
<tbody>
<tr><td><b>Node.js</b></td><td>v18 or higher recommended</td></tr>
<tr><td><b>npm</b></td><td>Comes bundled with Node.js</td></tr>
<tr><td><b>MongoDB Atlas</b></td><td>Required for database — create a free cluster</td></tr>
<tr><td><b>Firebase Project</b></td><td>Required for authentication features</td></tr>
<tr><td><b>Modern Browser</b></td><td>Chrome, Firefox, Safari, or Edge</td></tr>
</tbody>
</table>

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/zahid-official/milestone-10-visoMonorepo.git

# 2. Navigate to the project directory
cd milestone-10-visoMonorepo

# ── Client Setup ──

# 3. Navigate to the client directory
cd client

# 4. Install client dependencies
npm install

# 5. Set up client environment variables (see section below)

# 6. Start the client development server
npm run dev

# ── Server Setup (in a new terminal) ──

# 7. Navigate to the server directory
cd server

# 8. Install server dependencies
npm install

# 9. Set up server environment variables (see section below)

# 10. Start the server
npm start
```

The client will be available at `http://localhost:5173` and the server at `http://localhost:3000` by default.

<br/>

## 🔑 Environment Variables

### Client (`client/.env.local`)

Create a `.env.local` file inside the `client/` directory with the following Firebase credentials:

```env
VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_project.firebaseapp.com
VITE_projectId=your_project_id
VITE_storageBucket=your_project.appspot.com
VITE_messagingSenderId=your_sender_id
VITE_appId=your_app_id
```

### Server (`server/.env`)

Create a `.env` file inside the `server/` directory with the following MongoDB credentials:

```env
DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

> **Note:** Client variables must be prefixed with `VITE_` for Vite to expose them to the client bundle. Never commit `.env.local` or `.env` to version control.

<br/>

## 📜 Available Scripts

### Client Scripts

<table align="center">
<thead>
<tr><th align="left">Command</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><code>npm run dev</code></td><td>Start the Vite development server with HMR</td></tr>
<tr><td><code>npm run build</code></td><td>Create an optimized production build</td></tr>
<tr><td><code>npm run preview</code></td><td>Preview the production build locally</td></tr>
<tr><td><code>npm run lint</code></td><td>Run ESLint to check for code quality issues</td></tr>
</tbody>
</table>

### Server Scripts

<table align="center">
<thead>
<tr><th align="left">Command</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><code>npm start</code></td><td>Start the Express server with Node.js</td></tr>
</tbody>
</table>

<br/>

## ⚙️ How It Works

<div align="center">
<pre>
User lands on Home ──► Browses Latest Visas ──► Views All Visas
                                                      │
                              ┌───────────────────────┘
                              ▼
                    Selects a Visa Card
                              │
                              ▼
                    View Visa Details ──► Apply for Visa
                                               │
                          ┌────────────────────┘
                          ▼
                Route requires auth?
                 ┌──── Yes ────┐
                 ▼             ▼
            Not logged in   Logged in
                 │             │
                 ▼             ▼
            Redirect to    Submit Application
            Login Page     (saved to MongoDB)
                 │             │
                 ▼             ▼
            Authenticate   Track in
            (Email/Google) My Applications
                 │             │
                 ▼             ▼
            Return to ────► Manage My Visas
            Previous Page    (Add / Edit / Delete)
</pre>
</div>

1. **Landing** — Users explore the platform overview, latest visa offerings, and extra sections on the home page.
2. **Visa Browsing** — All visa types are fetched from the Express API and displayed with filtering options.
3. **Visa Details** — Each visa card links to a detailed view showing requirements, fees, and processing time.
4. **Authenticated Actions** — Adding visas, applying, and managing entries require Firebase authentication via private routes.
5. **Application Management** — Users can search, view, and cancel their submitted applications through a dedicated dashboard.

<br/>

## 🌟 Author

<div align="center">
  <a href="https://github.com/zahid-official">
    <img src="https://github.com/zahid-official.png" width="100" height="100" style="border-radius: 50%;" alt="Zahid Official" />
  </a>

  <h3>Zahid Official</h3>
  <p><b>Web Developer | Tech Enthusiast</b></p>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zahid-web)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zahid.official8@gmail.com)

  <p>Creating impactful digital experiences with passion and purposeful design</p>
</div>

<br/>

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how you can help improve **Viso**:

```bash
# 1. Fork the repository

# 2. Create a feature branch
git checkout -b feature/your-feature-name

# 3. Make your changes and commit
git commit -m "feat: add your feature description"

# 4. Push to your fork
git push origin feature/your-feature-name

# 5. Open a Pull Request against the main branch
```

<p align="center"><b>Viso</b> — <i>Where every application brings your travel dreams closer to reality.</i></p>
