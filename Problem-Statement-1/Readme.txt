# 🛡️ Problem Statement 1 – Product Requirement and Low-Fidelity
 Wireframes

## 📌 Objective

Design a product that helps organizations **scan, identify, and remediate vulnerabilities** in container images deployed within Kubernetes environments, with seamless integration into CI/CD pipelines.

---

## 🧩 Core Features

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 🧾 Image Dashboard        | List of scanned container images with severity breakdown (Critical → Low)   |
| 🪪 Vulnerability Details  | Per-image CVE list with fix availability, severity, and status              |
| 🔍 Filtering & Sorting    | By severity, fix status, image name                                         |
| 🛠️ Fix Recommendations    | Apply available fixes (if supported), or mark CVEs as known                 |
| 🔁 Re-scan Support        | Manually re-trigger scans after image updates                               |
| 🔐 Role-Based Access      | Optional: Admin, Security Analyst, Developer roles                          |

---

## 👥 Target Users

- **DevOps Engineers**: Secure CI/CD pipelines and infrastructure.
- **Security Analysts**: Monitor vulnerabilities across deployed containers.
- **Developers**: Patch and maintain secure base images.

---

## 🧪 User Flow

1. User logs into the system.
2. Views **Dashboard** listing all scanned container images.
3. Applies filters to prioritize high/critical vulnerabilities.
4. Clicks **View** on any image to see CVE details and fix status.
5. Applies fixes and optionally resubmits the image for re-scanning.

---

## 🖼️ Wireframes

Low-fidelity sketches for:
- **Dashboard View** – overview of all scanned images
- **Image Detail View** – CVE-level vulnerability information
- **Fix Apply View** – apply fixes or export reports

📎 See file: `Wireframe.png`

---

## 🧾 Documentation

- 📄 `Product_Requirements_Container_Scanner_pdf.pdf` – complete PRD
- 🖼️ `Wireframe.png` – dashboard + detail UI mockups

---

## 📊 Success Metrics

- Reduction in unresolved **critical/high vulnerabilities**
- Improved **time-to-fix**
- Increased adoption among DevOps and Security teams

---

## 🔧 Developer Notes (Optional)

- Use tools like **Trivy, Grype, or Clair** for image scanning
- API-first backend with **Node.js** or **Python (Flask/FastAPI)**
- Frontend: **React + Tailwind CSS** (or any responsive UI)
- Deploy on **Docker** & **Kubernetes**

---

## 📌 Summary

This scanner product is designed to bridge security and operations, giving teams real-time insight into container vulnerabilities and empowering them to take action directly from a single dashboard.

---
 
