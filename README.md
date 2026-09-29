# ⚛️ ElementExplorer — Interactive Periodic Table

An interactive, responsive, web-based Periodic Table web application built with single-file HTML5, Tailwind CSS, and plain JavaScript. 

It enables seamless switching between the **Standard Periodic Table Grid Layout** and **Property Sorting Modes** (such as Electronegativity, Discovery Year, Thermal/Electrical Conductivity, Density, and Melting Point) using relative HSL heatmap color gradients.

---

## ✨ Features

* **Complete 118 Elements Dataset:** Contains structural, chemical, thermal, and electrical metrics for all 118 elements.
* **Top-Right Property Dropdown:** Rearrange elements dynamically based on:
  * Standard Periodic Grid Position
  * Year of Discovery
  * Electronegativity (Pauling Scale)
  * Density ($g/cm^3$)
  * Melting Point ($K$)
  * Thermal Conductivity ($W/(m·K)$)
  * Electrical Conductivity ($S/m$)
  * Atomic Mass
* **Relative Heatmap Color Coding:** Dynamically calculates color gradients using HSL color scales based on normalized min-to-max values across selected properties.
* **Live Search & Category Filtering:** Search by name, symbol, or atomic number, or filter by chemical categories (Alkali Metals, Noble Gases, Lanthanides, Actinides, etc.).
* **Detailed Inspection Modal:** Click any element tile to open a modal window displaying comprehensive metrics, water solubility characteristics, and descriptions.
* **Mobile-Optimized PWA:** Designed to run seamlessly on Android devices (such as Samsung Galaxy phones) and install directly to your home screen.

---

## 🛠️ Tech Stack

* **HTML5** — Semantic layout structure.
* **Tailwind CSS** — Modern dark-mode UI styling and grid layouts.
* **JavaScript (ES6)** — Dynamic DOM rendering, sorting logic, and state management.
* **Lucide Icons** — Lightweight icon rendering.

---

## 🚀 How to Run Locally

1. Download or clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/periodic-table.git
