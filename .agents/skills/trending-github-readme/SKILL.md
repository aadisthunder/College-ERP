---
name: trending-github-readme
description: "Guidelines and standardized template for creating trending, aesthetic, professional GitHub README documentation for web applications and open-source projects."
---

# Trending GitHub README Specification & Blueprint

## Objective
Provide an end-to-end framework and canonical template to create modern, high-converting, and visually stunning GitHub `README.md` files for open-source repositories and web projects without emoji clutter.

---

## Core Principles

1. **Clean Professional Typography**:
   - Avoid generic or distracting emojis in headings and body text.
   - Use clean Markdown headers (`#`, `##`, `###`), bold text, and curated shields.io badges.

2. **Top-Level Live Demo Visibility**:
   - Never bury deployment links at the bottom.
   - Place a prominent Live Demo badge and direct URL right below the title within the hero header.

3. **Curated Badges & Tech Stack**:
   - Use `style=for-the-badge` shields.io badges with official brand colors and logos.
   - Group related tech stack items into centered, aesthetic rows.

4. **Visual Proof & Showcases**:
   - Include 2–3 high-resolution UI screenshots or mockups (e.g., Landing Page, Dashboard, Auth Modal).
   - Store all screenshot assets under `assets/` and link using relative markdown paths.

5. **Role-Based Permission Matrix**:
   - For applications with multiple roles (e.g., Faculty vs. Student, Admin vs. User), provide both bulleted capability breakdowns and a comparison table.

6. **Quickstart & Developer Experience**:
   - Provide pre-seeded demo credentials in an easy-to-read table.
   - Provide minimal terminal commands for local execution and cloud deployment (e.g., Firebase, Vercel, Netlify).

---

## Canonical Blueprint

```markdown
<div align="center">

  # [Project Title]

  **[One-sentence high-impact value proposition.]**  
  [Core Feature 1] · [Core Feature 2] · [Core Feature 3] · [Core Feature 4]

  <br />

  <p>
    <a href="[LIVE_URL]" target="_blank">
      <img src="https://img.shields.io/badge/LIVE_DEMO-[DOMAIN]-[COLOR]?style=for-the-badge&logo=[LOGO]&logoColor=white" alt="Live Demo" />
    </a>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/LICENSE-[LICENSE]-[COLOR]?style=for-the-badge" alt="License" />
    </a>
    <a href="[LIVE_URL]">
      <img src="https://img.shields.io/badge/DEPLOYMENT-[PROVIDER]-[COLOR]?style=for-the-badge&logo=[LOGO]&logoColor=white" alt="Deployment" />
    </a>
  </p>

  <p>
    <strong>Live Application URL:</strong> <a href="[LIVE_URL]" target="_blank">[LIVE_URL]</a>
  </p>

  <img src="assets/logo.png" alt="[Project] Emblem" width="90" style="margin-top: 12px; margin-bottom: 8px;" />

</div>

---

<div align="center">

  ### Tech Stack

  <p>
    <img src="https://img.shields.io/badge/[TECH]-[HEX]?style=for-the-badge&logo=[LOGO]&logoColor=white" alt="[TECH]" />
  </p>

</div>

---

## Application Showcase

### 1. [View 1 Name]
![[View 1]](assets/screenshot-1.png)

### 2. [View 2 Name]
![[View 2]](assets/screenshot-2.png)

---

## What is [Project Title]?

[2–3 paragraphs describing architecture, problem solved, client/server model, and state persistence.]

---

## Role-Based Capabilities & Features

### [Role 1]
- **[Feature]**: [Description]

### [Role 2]
- **[Feature]**: [Description]

### Capability Comparison

| Feature / Action | [Role 1] | [Role 2] |
| :--- | :---: | :---: |
| [Permission 1] | Full Access | View Only |
| [Permission 2] | Yes | Yes |

---

## Default Credentials

| Role | Username | Password | Access Level |
| :--- | :--- | :--- | :--- |
| **[Role 1]** | `admin` | `password` | Full Access |
| **[Role 2]** | `user` | `password` | Standard Access |

---

## Project Structure

```text
Project-Name/
├── assets/                  # Logos, banners, screenshots
├── css/                     # Stylesheets
├── js/                      # Scripts and logic
├── index.html               # Main entry point
├── LICENSE                  # Open source license
└── README.md                # Documentation
```

---

## Getting Started

### 1. Clone the Repository
```bash
git clone [REPO_URL]
cd [REPO_DIR]
```

### 2. Run Locally
[Instructions for local execution]

---

## Deployment

[Instructions for deployment]

---

## License

Distributed under the [License Name]. See `LICENSE` for more information.
```

---

## Verification Checklist

- [ ] Header includes title, tagline, shields.io badges, and centered emblem.
- [ ] Live URL is immediately visible in the hero header.
- [ ] No emojis are present in titles, badges, or section headers.
- [ ] Tech stack includes clean, matching badge formats with official logos.
- [ ] 2–3 screenshots are rendered cleanly from `assets/`.
- [ ] Role-based permissions are documented with a clear matrix.
- [ ] Demo credentials are provided with usernames and passwords.
- [ ] Directory tree accurately reflects active project files.
- [ ] Setup and deployment commands are tested and functioning.
