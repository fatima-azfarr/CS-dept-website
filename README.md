# 🎓 CS Department — COMSATS University Islamabad, Lahore Campus

A fully static, multi-page departmental website for the **Department of Computer Science** at COMSATS University Islamabad, Lahore Campus. Built with plain HTML, CSS, and vanilla JavaScript — containerised with Docker, served via Nginx, and deployed through a full CI/CD pipeline using GitHub Actions.

---

## ✨ Pages

| Page | What it covers |
|---|---|
| **Home** | Department overview, mission, highlights, announcements, and degree programs |
| **Courses** | Full course catalogue filterable by semester |
| **Faculty** | Faculty directory with rank filters and live search |
| **Admissions** | Programs, eligibility criteria, application steps, scholarships, and FAQ |
| **Contact** | Contact form, office info, campus map, and departmental office directory |

---

## 🎨 Design

Dark navy theme with blue and gold accents. Every page shares the same glassmorphism navbar, animated hero section, and card-based layout — giving the site a cohesive, modern feel throughout. Built with **Syne** for headings and **DM Sans** for body text.

---

## ⚙️ DevOps Pipeline

This project follows a full **three-environment CI/CD workflow**:

| Workflow | Trigger | Purpose |
|---|---|---|
| `ci.yml` | Every push / PR | HTML linting via `.htmlhintrc` |
| `cd-dev.yml` | Push to `dev` | Deploy to development environment |
| `cd-staging.yml` | Push to `staging` | Deploy to staging for QA |
| `cd-production.yml` | Push to `main` | Deploy to production |

The site runs inside a **Docker** container served by **Nginx** (`nginx.conf`), making it fully portable and environment-agnostic.

---

## 🛠️ Built With

`HTML5` &nbsp;·&nbsp; `CSS3` &nbsp;·&nbsp; `Vanilla JavaScript` &nbsp;·&nbsp; `Docker` &nbsp;·&nbsp; `Nginx` &nbsp;·&nbsp; `GitHub Actions` &nbsp;·&nbsp; `HTMLHint`

---

> Department of Computer Science, COMSATS University Islamabad — Lahore Campus &nbsp;·&nbsp; © 2025