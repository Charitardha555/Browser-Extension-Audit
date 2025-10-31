# Elevate-labs-Cybersecurity-Task-07
A repository for the task 07 from the Elevate labs, Cybersecurity

# 🌐 Cybersecurity Internship Task 7 – Browser Extension Audit

> **Elevate Labs – Task 7: Identify and Remove Suspicious Browser Extensions**

## 🎯 Objective

Canvas a real-world browser, document every extension, evaluate security, and remove suspicious or unnecessary components. The entire journey is visualized in the screenshots folder.

---

## 🖼️ Canvas: Extension Audit Table

| Extension Name                  | Status       | Permissions Review                  | Action Taken  | Screenshot File                |
|---------------------------------|-------------|-------------------------------------|---------------|-------------------------------|
| 2FA Authenticator               | Trusted     | Auth only, no data access           | Kept          | Screenshot-2025-10-31-191041.jpg |
| Adobe Acrobat                   | Trusted     | PDF access, no extra permissions    | Kept          | Screenshot-2025-10-31-191041.jpg |
| Dark Reader                     | Safe        | UI only, no storage/data access     | Kept          | Screenshot-2025-10-31-191041.jpg |
| Email Finder by ContactOut      | Reviewed    | CRM/data access, checked legitimacy | Kept          | Screenshot-2025-10-31-191041.jpg |
| FoxyProxy                       | Reviewed    | Proxy usage, verified developer     | Kept          | Screenshot-2025-10-31-191041.jpg |
| Secure Exam Proctor             | Suspicious  | Disabled, unnecessary for workflow  | Removed       | Screenshot-2025-10-31-191122.jpg |
| Wappalyzer                      | Safe        | Technology profiling, minimal data  | Kept          | Screenshot-2025-10-31-191041.jpg |
| Google Docs Offline             | Trusted     | Docs only, no external data access  | Kept          | Screenshot-2025-10-31-191041.jpg |
| Cookie Editor                   | Reviewed    | Cookie management only              | Kept          | Screenshot-2025-10-31-191041.jpg |

---

## 📝 Task Process Canvas

- **Step 1:** Opened Chrome extension manager: `chrome://extensions`
- **Step 2:** Reviewed extension list, checked each for excessive or suspicious permissions
- **Step 3:** Cross-referenced with user reviews, reputation, and changelogs
- **Step 4:** Disabled 'Secure Exam Proctor' due to no active need and unclear publisher
- **Step 5:** Removed unnecessary extension, restarted browser, validated improved security posture
- **Step 6:** Documented entire process using screenshots (see `/screenshots`)

---

## 💡 Security Insights Canvas

- Malicious extensions can **read browsing history** and **capture sensitive data**
- Review permissions: beware of "Read and change all your data," clipboard access, and background processes
- Always download from proven trusted sources, never from random prompts or ads
- Sandbox activities (separate profiles for work/personal to compartmentalize risk)

---

## 📂 Repo Canvas Structure

/screenshots/
├─ Screenshot-2025-10-31-191041.jpg
├─ Screenshot-2025-10-31-191122.jpg
README.md


---

Task completed as a **visual audit and practical demonstration** – see code, images, and process documentation in this repository.

