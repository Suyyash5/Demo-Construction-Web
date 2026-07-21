# BNK Construction — Premium Architecture & Portfolio Portal

🚀 **Live Demo:** [bnk-construction-web.vercel.app](https://bnk-construction-web.vercel.app/)

A modern, highly interactive React and Vite web application built for a premium construction and architecture firm. The platform features an elegant public showcase portfolio and a secure passcode-protected administrative dashboard for dynamic content management.

---

## 🚀 Key Features

* **🎨 Modern Minimalist Visuals**: Uses custom CSS variables, balanced contrast, and a dark/light mode switcher tailored for architectural layouts.
* **✨ Smooth Motion & Micro-interactions**: Integrates `lenis` for inertial smooth scrolling, along with custom cubic-bezier animations for fluid transitions.
* **📷 Dual-Mode Project Carousels**: Toggleable project details carousel showing both high-res photographs and technical architectural blueprints, complete with full-screen zoom lightbox and touch-swipe support.
* **🔒 Passcode-Protected Admin Portal**: A secure dashboard (`/admin`) where administrators can add new construction projects, delete old listings, and check incoming client inquiries.
* **💾 Client-Side Storage & Image Compression**: Utilizes `localStorage` for serverless data persistence, incorporating custom HTML5 Canvas compression to shrink uploaded device images (from ~5MB to <80KB) to fit browser storage quotas.
* **🗺️ Theme-Responsive Map**: An interactive Google Map on the contact page that automatically shifts its styling (inverted colors in dark mode, grayscale in light mode) to fit the active theme.
* **📨 Inbox & Email Alerts Setup**: A message inbox for admins to view client queries, alongside commented guidelines inside the contact page for integrating EmailJS live alerts.

---

## 🛠️ Technology Stack

* **Frontend Framework**: React.js (v18)
* **Routing**: React Router DOM (v6)
* **Build System**: Vite (v5)
* **Styling**: Vanilla CSS3 (utilizing custom properties/variables for the theme engine)
* **Smooth Scrolling**: Lenis
* **Icons**: Lucide React
* **Data Storage**: Web Storage API (`localStorage` & `sessionStorage`)
* **Image Processing**: HTML5 Canvas API (for real-time image resizing and JPEG compression)
* **Map Integration**: Google Maps Embed API (with custom theme-responsive CSS filters)

---

## ⚙️ Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Suyyash5/BNK-Construction-Web.git
   ```

2. Navigate to the project folder:
   ```bash
   cd BNK-Construction-Web
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Project

Start the local development server:
```bash
npm run dev
```

The application will run locally at **[http://localhost:5173/](http://localhost:5173/)**.

---

## 🔐 Administrative Access

To access the portfolio manager and message inbox:
1. Navigate to: **[http://localhost:5173/admin](http://localhost:5173/admin)**
2. Enter the administrative passcode: `admin123`
