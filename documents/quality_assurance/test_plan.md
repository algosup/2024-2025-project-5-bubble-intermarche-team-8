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
  - [5. Test Strategy](#5-test-strategy)
    - [5.1 Test Methodology](#51-test-methodology)
      - [Phase 0: Smoke Testing](#phase-0-smoke-testing)
      - [Phase 1: Functional Testing](#phase-1-functional-testing)
      - [Phase 2: UI/UX Testing on Desktop](#phase-2-uiux-testing-on-desktop)
      - [Phase 3: Edge Case \& Data Behavior Testing](#phase-3-edge-case--data-behavior-testing)
      - [Phase 4: Regression Testing (Post-Changes)](#phase-4-regression-testing-post-changes)
  - [5.2 Test Cases](#52-test-cases)
    - [Key Test Case Categories:](#key-test-case-categories)
  - [5.3 Test Reports](#53-test-reports)
  - [5.4 Bug Lifecycle](#54-bug-lifecycle)
  - [6. Entry \& Exit Criteria](#6-entry--exit-criteria)
    - [6.1. Entry Criteria](#61-entry-criteria)
    - [6.2. Exit Criteria](#62-exit-criteria)
    - [6.3. Suspension Criteria](#63-suspension-criteria)
    - [6.4. Resumption Criteria](#64-resumption-criteria)

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


---

## 5. Test Strategy

As **BITE MATCH** is currently an MVP developed with **Bubble.io**, the focus is on testing the app on **desktop browsers only**. The app will not be tested in-store or on mobile devices at this stage.

The goal is to make sure everything works smoothly for first-time users: clean navigation, accurate recommendations, and bug-free filters.

Testing will be done manually using real user interactions. We’ll check if the app responds properly to typical inputs and behaves well in edge cases.

Basic design consistency and user clarity will also be part of the checks to ensure a professional-looking and intuitive experience.

The test phase will follow a structured timeline:

1. **Smoke Testing** – To confirm app launches and major flows are reachable.
2. **Functional Testing** – To validate the main user journey from input to results.
3. **UI Testing** – To check layout, responsiveness, and readability.
4. **Edge Case Testing** – To simulate unexpected or missing inputs.
5. **Regression Testing** – To confirm nothing breaks after changes or updates.

### 5.1 Test Methodology

#### Phase 0: Smoke Testing

Before diving into deeper test phases, a quick **smoke test** will be performed to verify that the app **loads correctly** and that **core features are accessible**. This step helps catch any major blockers early, such as:

- The homepage loads without errors.
- Main navigation buttons are visible and clickable.
- The meal selection interface opens properly.
- Filters and search bars are visible.

This phase ensures the foundation is stable enough to proceed with more detailed testing.

#### Phase 1: Functional Testing

This testing method will allow the team to validate if the features work as expected based on the client’s requirements and initial design.  
The primary goal is to ensure that users can complete their journey smoothly — from selecting a meal to receiving accurate suggestions — without running into logic errors or broken flows.

The following aspects will be verified:

- Meal selection flow: check that the user can choose a meat dish and proceed.
- Recommendation engine: validate that relevant cheese and wine suggestions appear based on the chosen meal.
- Filter logic: ensure that each filter (wine color, cheese type, etc.) works individually and in combination.
- Language switching: confirm that all visible text updates correctly when the language is changed.

Additional functional checks include:

- Scroll behavior: verify that users can scroll through long lists of suggestions without glitches.
- Page switching: test the transition between wine and cheese recommendation views.
- Search bar: ensure that entering keywords filters the results correctly.
- Price slider: test minimum and maximum values and confirm that product lists update accordingly.
- Tag system: validate that filters like wine color or cheese family behave logically (e.g., red and white wine cannot be selected at the same time).

#### Phase 2: UI/UX Testing on Desktop
- Confirm layout consistency on different screen resolutions.
- Test button click areas, label alignment, and feedback (e.g., hover/click).
- Ensure text is legible and color contrast is adequate.
- Validate the app remains user-friendly and visually clean across flows.

#### Phase 3: Edge Case & Data Behavior Testing
- Input: no meal selected, unsupported options, special characters.
- Filters: combine, reset, or apply without selecting a meal.
- Database: verify correct loading of texts, images, and descriptions.

#### Phase 4: Regression Testing (Post-Changes)
- After any change or bug fix, re-test the main flow:
  - Meal input → Filters → Suggestions → Reset
- Check that language and UI behavior remain consistent after updates.


## 5.2 Test Cases

Test cases will be created for each feature and user interaction described in the scope of testing. These cases will be updated iteratively as new features are added or bugs are discovered. Each test case will include an **ID**, **description**, **test steps**, **expected result**, **actual result**, and a **status** that tracks multiple test iterations. Testing will continue through successive iterations until the feature passes all relevant test cases.

Test cases will be managed via GitHub Issues for efficient tracking and version control, and documented in the `TestCases.md` file to ensure traceability and team visibility.

Test coverage will focus on the main user journey (meal selection → filtering → recommendation), edge cases, and interface behavior.

### Key Test Case Categories:
- **Meal Input & Selection**: Verifying the user can choose their meal easily and that the app responds accordingly.
- **Recommendation Logic**: Ensuring relevant wine and cheese suggestions appear based on selected inputs.
- **Filter Functionality**: Testing the behavior of filters such as wine color, cheese category, price range, and tags.
- **Search & UI Components**: Validating smooth scrolling, keyword filtering via search bar, and intuitive tag-based selection.
- **Navigation & Transitions**: Confirming that switching between wine and cheese views is smooth and does not reset the user's flow.
- **Multilingual Support**: Ensuring that switching between languages updates content without breaking logic or layout.
- **Data Accuracy**: Verifying that the content displayed (text, images, prices) matches what’s stored in the database.

Each category will include typical user scenarios and edge cases. Regression checks will be performed after every major change or bug fix to ensure ongoing app stability.

---
## 5.3 Test Reports

Test reports will be generated throughout the testing process to document progress, identify issues, and track feature readiness. These reports provide visibility into the app’s quality and stability, and help guide further development and prioritization.

Each test report will include:

- A summary of test cases executed during the testing session
- Pass/fail status for each test case and test iteration
- Notes on any bugs, inconsistencies, or unexpected behavior
- Screenshots or recordings to illustrate issues
- Recommendations or next steps for unresolved problems

Reports will be created after each major testing round and shared with stakeholders via GitHub.

---
## 5.4 Bug Lifecycle
To ensure efficient handling of bugs, we follow a clear and repeatable lifecycle. The diagram below illustrates the key steps from detection to resolution:

<img src="bug_lifecycle.png" alt="Bug Lifecycle Diagram" width="300"/>


---


## 6. Entry & Exit Criteria

### 6.1. Entry Criteria
To ensure relevant test reports and provide insights on the development progression, the following points need to be validated:
- All the necessary documentation and requirement information should be available in the repository to ensure consistent testing. It will also allow testers to operate the system correctly.
- All the core features defined for the MVP in the functional specifications have been implemented.
- Test environment is stable and accessible.
- The test scenarios, test cases and testing suite have been reviewed.
- Necessary test data has been prepared.
- No high-priority open bugs blocking core functionalities.

### 6.2. Exit Criteria
In order to consider the test phase as completed, the following points should have been validated:
- All major bugs are resolved.
- Test case execution shows ≥95% pass rate.
- All planned test cases have been executed.

- All critical and major bugs are fixed and re-tested.

- Regression testing is completed with no unexpected failures.

- All acceptance criteria for the tested features are met.

- Test reports and documentation are finalized and approved.

### 6.3. Suspension Criteria

In case of a critical issue that impacts the integrity or feasibility of the testing process, the testing phase may be temporarily suspended. The suspension ensures that time and resources are not wasted on blocked or invalid test efforts.

The following situations can trigger a suspension:

- A critical bug that blocks core functionality and prevents further testing.  
- Unavailability of key testing resources (e.g., QA team members, development support).  
- Major changes in requirements or scope requested by the client.  
- The application or environment contains severe defects that limit or entirely prevent meaningful testing.


---

### 6.4. Resumption Criteria

To resume the testing phase, the cause of the suspension should have been identified, addressed and resolved.

---