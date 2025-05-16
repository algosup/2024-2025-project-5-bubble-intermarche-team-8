# 🧪 Test Plan

## 📑 Table of Contents
- [🧪 Test Plan](#-test-plan)
  - [📑 Table of Contents](#-table-of-contents)
  - [1. Introduction](#1-introduction)
  - [2. Test Environment](#2-test-environment)
    - [📦 Platform \& Tools](#-platform--tools)
    - [🖥️ Devices \& Browsers](#️-devices--browsers)
    - [🌐 Network Conditions](#-network-conditions)
    - [🔐 Data \& Configuration](#-data--configuration)
  - [3. Scope of Testing](#3-scope-of-testing)
    - [✅ In Scope](#-in-scope)
    - [🚫 Out of Scope](#-out-of-scope)
  - [4. Test Objectives](#4-test-objectives)
    - [✅ Validate Requirements – Core Functionalities](#-validate-requirements--core-functionalities)
    - [🌟 Validate Objectives – Nice-to-Have Features](#-validate-objectives--nice-to-have-features)
    - [🧪 Test Data Accuracy \& System Behavior](#-test-data-accuracy--system-behavior)

---

## 1. Introduction
This document outlines the test plan for the recommendation app developed for **Intermarché Saint-Rémy-de-Provence**. The app provides personalized **cheese and wine suggestions** based on the user's chosen **meal**. The goal of this test plan is to ensure the application is functionally stable, user-friendly, and ready for in-store usage.

---

## 2. Test Environment

The test environment includes all the hardware, software, and configurations required to execute and validate the test cases. It is designed to reflect the real conditions under which the app will be used in Intermarché Saint-Rémy-de-Provence.

### 📦 Platform & Tools
- **Bubble.io**: Main development platform (no-code).
- **Bubble Debugger**: For real-time behavior inspection and issue tracking.
- **Browser Dev Tools**: For layout testing, console logs, and network monitoring.
- **Google Chrome / Safari / Firefox**: For cross-browser compatibility checks. NOTSURE!!!
- **Postman / Bubble API Connector**: For testing plugin/API responses (if applicable). NOTSURE!!!
- **Google Sheets**: For logging test cases and tracking bugs.
- **Screenshot/Screen Recording Tools**: For documenting UI/UX issues.

### 🖥️ Devices & Browsers
Testing will be performed on the following devices to ensure proper functionality and responsiveness:

- **Smartphones**:
  - Android (Samsung)
  - iPhone (iOS 15+)
- **Desktop Browsers** (for initial development tests):
  - Google Chrome (latest)
  - Brave (latest)
  - Safari (latest on macOS)

### 🌐 Network Conditions
- **Standard Wi-Fi**: In-store Wi-Fi as used by employees/customers
- **4G Mobile Data**: To simulate users accessing the app outside the store (if permitted) NOTSURE!!!

### 🔐 Data & Configuration
- **Test database**: A duplicate of the live database used to validate data accuracy without affecting real entries.
- **Languages**: English, French..

---

## 3. Scope of Testing

The scope of testing of our recommendation app encompasses all key requirements pointed out by the client and mentioned in the specifications. It will ensure that the application functions correctly, provides relevant suggestions based on the user’s input, and delivers a smooth user experience across all supported devices.

### ✅ In Scope
- Verification of the meal input and selection interface to ensure ease of use and functional correctness.
- Validation of the recommendation engine for wine and cheese, ensuring relevant and accurate suggestions.
- Testing of all available filters and sorting options (e.g., wine color, cheese category), including combined usage scenarios.
- Full walkthrough of the user journey to assess navigation flow, UI consistency, and responsiveness across supported devices.
- Performance testing focused on load time and fluidity of interactions.
- Language support testing to ensure that all labels, buttons, messages, and content are correctly translated and function seamlessly when switching between languages.
- Verification that all third-party plugins and APIs are correctly implemented and return the expected results.

### 🚫 Out of Scope
- Real-time availability of store products
- Back-office or admin-side content management
- AI-generated meal suggestions 
- Advanced analytics or user behavior tracking


---

## 4. Test Objectives

The objective of the testing phase of the recommendation app is to thoroughly evaluate whether the application meets the functional and non-functional requirements specified in the client brief and specifications document. This includes core expected functionalities as well as additional features that enhance user experience.

### ✅ Validate Requirements – Core Functionalities

These are the minimum viable product (MVP) requirements that must be fully functional for the app to be considered acceptable by the client:

- The user must be able to input their meal using a clean and responsive interface.
- The app must provide accurate wine and cheese suggestions based on the selected meal.
- All filters (such as wine type, cheese type, dietary preferences) must function correctly and update results accordingly.
- The application must be fully responsive and usable on tablets and mobile devices typically used in-store.
- Multilingual support must work correctly: changing the language should update all interface elements without breaking layout or logic.
- All plugins and APIs integrated into the app (e.g., filtering, display components) must work as intended and return the expected data.

### 🌟 Validate Objectives – Nice-to-Have Features

These features are not mandatory but contribute significantly to the overall quality and user-friendliness of the app:

- Smooth transition animations and feedback when selecting meals or applying filters.
- Visually appealing layout and icons tailored for the Intermarché brand.
- Smart auto-suggestions based on previous user selections.

### 🧪 Test Data Accuracy & System Behavior

As the app will be used in a live retail environment, its accuracy and reliability are essential. The following aspects will also be evaluated:

- All content retrieved from the database (e.g., wine/cheese descriptions, images) must load correctly and correspond to the correct meal mappings.
- Data must be properly stored, retrieved, and updated within the Bubble.io database.
- Filters must not cause display or data inconsistencies when combined or reset.
- The app must respond quickly (with minimal lag).
- Edge cases such as no input, unsupported combinations, or invalid characters must be handled gracefully.
