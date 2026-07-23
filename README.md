# A. MANGUKIYA Real Estate

A modern, premium real estate portfolio and lead management web application. This project features a stunning user-facing website to showcase luxury properties, a dynamic lead-generation system, and a secure backend dashboard powered entirely by Firebase.

## 🚀 Features

- **Premium UI/UX:** Built with Tailwind CSS, featuring glassmorphism, smooth animations, and responsive layouts tailored for high-end real estate.
- **Dynamic Property Listings:** Display properties directly from the database with seamless filtering and elegant property detail views.
- **Real-Time Lead Generation:** Contact forms on the live site automatically push customer inquiries directly to the secure dashboard in real-time.
- **Admin Control Panel:** 
  - Create, Edit, and Delete property listings instantly.
  - Changes reflect on the live site without requiring a rebuild.
- **Database Dashboard:**
  - View real-time analytics and charts of daily lead generation.
  - Manage leads (Update statuses, bulk delete, inspect client details).
  - Export leads directly to CSV format.

## 🛠️ Technology Stack

This project was built to be fast, lightweight, and serverless.

- **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)
- **Database & Backend:** Firebase Firestore (NoSQL, Real-Time)
- **Hosting / Deployment:** Designed for Vercel, Netlify, or any static hosting provider.

## 📂 Project Structure

```
├── index.html               # Main landing page & live app
├── admin-panel.html         # Portal to publish and manage property listings
├── dashboard.html           # Real-time dashboard for managing client leads
├── property-details.html    # Detailed view for individual properties
├── user-dashboard.html      # (Optional) Portal for registered clients
├── login.html & signup.html # Authentication pages
└── README.md                # Project documentation
```

## ⚙️ Setup & Local Development

Because this project is entirely static and serverless, no local backend setup is required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/RealEstate.git
   cd RealEstate
   ```

2. **Open locally:**
   You can simply open `index.html` in your browser. For the best development experience, use a local server like the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VSCode.

3. **Firebase Configuration:**
   The Firebase SDK configuration is already embedded within the `<script type="module">` tags inside `index.html`, `dashboard.html`, and `admin-panel.html`. 

## 🌐 Deployment (Vercel)

Deploying this project is incredibly easy since it requires no backend servers (like Python or Node.js). 

**Method 1: Drag and Drop (No Git required)**
1. Log in to [Vercel](https://vercel.com).
2. Click **Add New...** > **Project**.
3. Drag and drop the entire project folder into the upload area.
4. Vercel will instantly build and provide a live URL.

**Method 2: Via GitHub**
1. Push your code to a GitHub repository.
2. In Vercel, click **Add New...** > **Project**.
3. Import your GitHub repository.
4. Click **Deploy**. Vercel will automatically detect it as a static site.

---
*Designed for Excellence. Built for Performance.*
