# GWC Fabric ERP System 🧵

An advanced, highly responsive Single Page Application (SPA) designed for the garment manufacturing industry to seamlessly manage fabric inventory, order requirements, and outward dispatching.

## 🚀 Live Demo
[Click here to view the Live Live Application](https://mrj23q-tomo.github.io/my-erp/)  
*(Note: Use `admin@gwc.com` and your registered password to access Main Admin features after signing up)*

## 📖 Project Overview
This ERP portal replaces traditional spreadsheet-based fabric tracking with a modern, serverless cloud solution. It allows real-time data entry, instant stock reconciliation, and comprehensive Fabric Closing Reports (FCR) without requiring page reloads.

## ✨ Key Features
* **Modular Dashboard:** Navigate between Requirement, Inward, Outward, and FCR modules instantly.
* **Role-Based Access Control (RBAC):** Secure login system separating 'Main' administrators and 'View-only' users.
* **Real-time Synchronization:** Powered by Firebase Firestore for instant data updates across all clients.
* **Smart Filtering & Dropdowns:** Auto-suggest and multi-select filters for OC Numbers, Fabric types, and Colors.
* **Analytics & Visualization:** Live bar and doughnut charts representing stock availability and dispatch records.
* **Advanced Export Options:** Download tables and reports in multiple formats including **Excel (xlsx)**, **PDF**, and **Images (PNG)**.

## 🛠️ Technology Stack
* **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript (ES6+)
* **Backend & Database:** Google Firebase (Firestore NoSQL DB & Firebase Authentication)
* **Libraries Used:** 
  * `Chart.js` for data visualization
  * `ExcelJS` for dynamic spreadsheet generation
  * `jsPDF` & `html2canvas` for PDF reporting

## ⚙️ How to Run Locally
Since this is a client-side heavy SPA connected to Firebase, running it locally is incredibly simple:
1. Clone this repository or download the ZIP file.
2. Extract the files to your local machine.
3. Simply double-click the `index.html` file to open it in any modern web browser.

---
*Developed as a comprehensive ERP solution for modern garment inventory management.*
