# 🇮🇳 Nivaran Bharat (निवारण भारत)

### A simple gateway to India's public grievance portals

> **Find the right portal. File your grievance. Get heard.**

![Status](https://img.shields.io/badge/Status-Active-success.svg)
![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JavaScript-blue.svg)
![Languages](https://img.shields.io/badge/Languages-22%2B-orange.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 📖 About the Project

Finding the right government website to file a complaint in India can be surprisingly difficult. Different departments have different portals, and every state has its own system. On top of that, language and complicated interfaces can make the process even harder for people who are not comfortable with technology.

**Nivaran Bharat** was built to make that first step easier.

It is a lightweight web application that brings links to major **Central Government, State, and Union Territory grievance portals** together in one place. Instead of searching the internet to figure out where a complaint belongs, users can simply select their state or search for the type of issue they are facing.

The application then takes them directly to the relevant **official government portal**.

---

## ✨ What It Does

### 🏛️ Central & State Portals

Provides a single directory for grievance portals covering Central Government departments, States, and Union Territories.

### 🔎 Quick Search

Users can search by state, department, or type of grievance and instantly find the relevant portal.

### 🌐 Multilingual Interface

The interface supports translation into **22+ Indian languages** using the Google Translate Web Element, making the application more accessible to users across India.

### 📱 Responsive Design

The website is designed to work smoothly on desktops, tablets, and mobile phones, including devices with smaller screens.

### 🛡️ Image Fallback

Regional images have an `onerror` fallback so that a broken external image does not affect the overall user experience.

### 🇮🇳 Simple, Familiar Design

The UI uses a clean "Digital India" inspired design with a tricolour theme, clear sections, simple navigation, and small interactive elements.

---

## 🎯 The Problem

The current grievance system can feel fragmented:

| Problem                                    | How Nivaran Bharat Helps                 |
| ------------------------------------------ | ---------------------------------------- |
| Too many different government portals      | Brings major portals into one directory  |
| Difficult to know where to complain        | Groups portals by state and department   |
| Language barriers                          | Provides 22+ language translations       |
| Searching for official websites takes time | Directly links users to official portals |
| Complex interfaces can be intimidating     | Uses a simple and guided interface       |

Nivaran Bharat **does not replace government grievance systems**. Instead, it works as a starting point that helps citizens find the right one.

---

## 🛠️ Tech Stack

The project intentionally uses a simple frontend stack so that it remains lightweight and easy to deploy.

* **HTML5** – Page structure and semantic markup
* **CSS3** – Responsive layout, animations, and styling
* **JavaScript (ES6+)** – Search, filtering, UI interactions, and DOM manipulation
* **Google Translate Web Element** – Multilingual support
* **Font Awesome 6** – Icons

### No Backend Required

Nivaran Bharat currently runs as a static website. There is no database, server, or build process required.

Everything can run from a single `index.html` file.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/nivaran-bharat.git
```

### 2. Open the project

```bash
cd nivaran-bharat
```

### 3. Run it

Open `index.html` in a modern web browser.

For development, you can also use the **Live Server** extension in VS Code.

---

## 👥 Who Can Use It?

Nivaran Bharat can be useful for:

* 👤 **Citizens** looking for the correct grievance portal
* 🏪 **Common Service Centres (CSCs)** helping people access online government services
* 🤝 **NGOs and social workers** assisting citizens with digital services
* 🎓 **Students and developers** interested in building civic-tech projects

---

## 🛣️ Future Improvements

There are several things that could be added in future versions:

* [ ] **AI-powered grievance routing**
  Let users describe their problem in simple language and suggest the appropriate department or portal.

* [ ] **Grievance tracking**
  Provide a unified place to check complaint status where official APIs are available.

* [ ] **How-to guides**
  Add short guides explaining how to file complaints on commonly used portals.

* [ ] **Progressive Web App (PWA)**
  Allow important directory information to remain accessible even with limited connectivity.

* [ ] **Usage analytics**
  Understand which categories and portals are most frequently accessed while respecting user privacy.

---

## ⚠️ Disclaimer

Nivaran Bharat is an **independent open-source project** created as a civic-technology initiative.

* It is **not affiliated with or endorsed by the Government of India or any State Government**.
* It does not replace any official grievance redressal system.
* It does not collect or store complaint details, Aadhaar information, or other personal grievance data.
* Users are redirected to the respective external government portals to submit their grievances.
* Government portal availability and URLs may change over time, so links should be verified and maintained regularly.

---

## 🤝 Contributing

Contributions and suggestions are welcome.

If you find an incorrect or outdated portal link, notice a UI issue, or have an idea for improving accessibility, feel free to open an issue or submit a pull request.

### Basic workflow

```bash
git checkout -b feature/your-feature
git add .
git commit -m "Add your change"
git push origin feature/your-feature
```

Then open a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

### 🇮🇳 Built with the idea that finding the right government service shouldn't be difficult.

**Nivaran Bharat — Making the first step towards grievance resolution a little easier.**
# Nivaran-Bharat
A simple website meant to help the local folks access the government grievences portal easily. Integrated both central and state government portals. All major regional languages supported.
