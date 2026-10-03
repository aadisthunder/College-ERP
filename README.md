<div align="center">

  <img src="assets/logo.png" alt="College ERP Logo" width="120" style="border-radius: 14px; margin-bottom: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);" />

  # College ERP

  **A modern, lightweight institutional web portal & academic management dashboard.**  
  Role-Based Access · Attendance Tracking · Timetable Schedules · Notice Board · Exam Records — zero server setup required.

  <p>
    <a href="https://college-erp-aadi.web.app" target="_blank"><img src="https://img.shields.io/badge/LIVE_DEMO-COLLEGE--ERP--AADI.WEB.APP-8b5cf6?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Live Demo" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-22c55e?style=for-the-badge" alt="License" /></a>
    <a href="https://college-erp-aadi.web.app"><img src="https://img.shields.io/badge/DEPLOYMENT-FIREBASE_HOSTING-06b6d4?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase Hosting" /></a>
  </p>

</div>

---

<div align="center">

  ### Tech Stack

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/LOCALSTORAGE-4A154B?style=for-the-badge&logo=databricks&logoColor=white" alt="LocalStorage" />
    <img src="https://img.shields.io/badge/FONTAWESOME-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white" alt="Font Awesome" />
    <img src="https://img.shields.io/badge/JSPDF-FF5722?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="jsPDF" />
    <img src="https://img.shields.io/badge/FIREBASE_HOSTING-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase Hosting" />
  </p>

</div>

---

## What is College ERP?

**College ERP** is a fully client-side academic management portal and college web platform. It eliminates the need for heavyweight backend servers by managing authentication, student profiles, attendance, and administrative records entirely in the browser using `localStorage`.

The platform provides an institutional landing portal alongside an interactive dashboard tailored for both **Students** and **Faculty**.

---

## ✨ Features

- **Institutional Landing Page**: Responsive showcase highlighting academics, admissions, faculty, hostel, and campus facilities.
- **Dual Role-Based Portals**: Separate dashboard contexts for **Faculty** and **Students**.
- **Attendance Management**: Mark, view, and calculate attendance percentages in real time.
- **Interactive Timetable**: Dynamic timetable schedule cards for weekly lecture plans.
- **Notice Board & Announcements**: Centralized announcement hub for institutional updates.
- **Academic Workflow Modules**:
  - Admissions tracking
  - Fee collection & receipts
  - Hostel allocation details
  - Examination records
- **PDF Exporting**: On-the-fly client-side document generation using `jsPDF`.
- **Zero Server Setup**: Out-of-the-box static deployment ready for any hosting provider.

---

## 🔑 Default Credentials

For quick exploration, the following credentials are pre-seeded in the system:

| Role | Username | Password | Access Level |
| :--- | :--- | :--- | :--- |
| **Faculty / Admin** | `admin` | `1234` | Full Faculty & Admin Dashboard Access |
| **Student** | `student` | `1234` | Student Dashboard & Academic Records |

*You can also create new student accounts via the [Registration Form](register.html).*

---

## 📁 Project Structure

```text
College-ERP/
├── assets/                  # Institutional logos, banners, and photography
│   ├── background.png
│   ├── college-bg.jpg
│   ├── college-life.jpg
│   ├── logo.png
│   └── teacher.jpg
├── css/                     # Stylesheets
│   ├── auth.css             # Authentication styling
│   ├── nstyles.css          # Landing page styles
│   └── style2.css           # Dashboard layout & widget styles
├── js/                      # Frontend JavaScript
│   ├── attendance.js        # Attendance computation & UI
│   ├── script.js            # Auth and user session management
│   └── script2.js           # Dashboard routing and state handling
├── auth.html                # Unified modal authentication page
├── dashboard.html           # Student & Faculty ERP Dashboard
├── index.html               # Institutional Landing Page
├── login.html               # Login page
├── register.html            # Registration page
├── .firebaserc              # Firebase project target configuration
├── firebase.json            # Firebase Hosting configuration
├── .gitignore               # Ignored build, cache, and system files
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/aadisthunder/College-ERP.git
cd College-ERP
```

### 2. Run Locally
Because College ERP is built with vanilla web technologies, you can open `index.html` directly in any modern browser:

- Double-click `index.html` or drag it into Chrome/Edge/Firefox.
- Alternatively, serve via any static HTTP server:
```bash
npx serve .
```
Then visit `http://localhost:3000`.

---

## 🔥 Deployment to Firebase Hosting

This project is pre-configured for **Firebase Hosting**.

1. Ensure Firebase CLI is installed and authenticated:
   ```bash
   npm install -g firebase-tools
   firebase login
   ```

2. Deploy hosting:
   ```bash
   firebase deploy --only hosting
   ```

Live site: [https://college-erp-aadi.web.app](https://college-erp-aadi.web.app)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.
