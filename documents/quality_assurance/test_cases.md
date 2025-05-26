# BITE MATCH – Test Cases

## Overview

This document outlines the key areas of the BITE MATCH application that will be tested. These tests ensure the app functions correctly, is user-friendly, and can be used in a real production environment without major bugs.

## Criticality

The test cases are defined by a criticality level, indicating the importance of the feature in the system and the inner workings of the device.

| Color | Priority |
| ----- | -------- |
| 🔴     | High     |
| 🟡     | Medium   |
| 🟢     | Low      |

## ✅ Phase 0: Smoke Testing

| Test Case ID | Description                  | Steps                              | Expected Result                                        | Test Critically                                       |
|--------------|------------------------------|------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
| SMK-01       | Verify homepage loads         | Open app URL                       | Homepage loads without errors                          | 🔴              |
| SMK-02       | Check navigation buttons      | Click on **“+Tags”**, **“Search”**, and **“EN”** (language switch button)        | Buttons are visible and clickable                      | 🔴        |
| SMK-03       | Visibility of filters         | Click on **“+Tags”** to open filter section                 | All filter components (Tags, sections) are visible       | 🟡 |


---

## ✅ Phase 1: Functional Testing

| Test Case ID | Description                        | Steps                                         | Expected Result                                          | Test Criticality |
|--------------|------------------------------------|-----------------------------------------------|----------------------------------------------------------|------------------|
| FUNC-01      | Select meal and get suggestions    | Choose a meal                          | Relevant wine and cheese suggestions appear              | 🔴           |
| FUNC-02      | Apply wine filter                  | Select "Red wine"                             | Only red wines are shown                                 | 🔴           |
| FUNC-03      | Apply cheese filter                | Select "Soft cheese"                          | Only soft cheeses are shown                              | 🔴           |
| FUNC-04      | Combine filters                    | Select wine and cheese filters                | Suggestions are updated accordingly                      | 🔴           |
| FUNC-05      | Language switch                    | Change app language to French                 | All labels/text are translated correctly                 | 🟡         |
| FUNC-06      | Scroll long lists                  | Scroll down wine suggestions                  | List scrolls smoothly with no glitches                   | 🟢            |
| FUNC-07      | Switch between views               | Navigate from wine to cheese tab              | View transitions smoothly                                | 🟡         |
| FUNC-08      | Use search bar                     | Type “camembert” in cheese search                  | Matching cheeses are displayed                           | 🔴           |
| FUNC-09      | Use price slider                   | Adjust min/max slider values                  | Suggestions update within price range                    | 🟡         |
| FUNC-10      | Tag logic validation               | Select red & white wine simultaneously        | Selection logic prevents conflict                        | 🟡         |
| FUNC-11      | Unselect a selected tag                    | Click again on a selected tag                               | Tag appears unselected and is removed from the filter logic            | 🔴               |
| FUNC-12      | Search for a specific wine product         | Type exact wine product name in search bar (e.g., "Lansac Rouge") | Matching wine product is displayed                                    | 🔴               |
| FUNC-13      | Search for a non-existent product          | Type a random/nonexistent name in search bar                | "Not found" pop-up message appears                                     | 🟡               |
| FUNC-14      | Click the “go back” arrow                  | Click on the back arrow button                              | User is navigated to the previous page                                 | 🟡               |
| FUNC-15      | Select a suggested meal from product page  | Click on a meal suggestion under a product                  | App navigates to the corresponding meal's page                         | 🔴               |


---

## ✅ Phase 2: UI/UX Testing

| Test Case ID | Description                   | Steps                            | Expected Result                                      | Test Criticality |
|--------------|-------------------------------|----------------------------------|------------------------------------------------------|------------------|
| UI-01        | Layout on different screens   | Resize browser window            | Layout adapts responsively                           | 🔴               |
| UI-02        | Button feedback               | Hover/click on buttons           | Buttons respond with visible feedback                | 🟡               |
| UI-03        | Font readability              | Navigate across pages            | Text is legible and colors contrast well             | 🟡               |
| UI-04        | Visual consistency            | Switch tabs/pages                | Design remains clean and aligned                     | 🟢               |
| UI-05        | Placeholder text visibility         | Check input fields (e.g., search bar)           | Placeholder text is clear and helpful                                 | 🟡               |
| UI-06        | Icon alignment                      | Navigate across all main views                  | Icons are well-aligned and spaced properly                            | 🟢               |
| UI-07        | Tap target size (mobile usability)  | Tap buttons/filters on a mobile screen          | Buttons are large enough to be tapped comfortably                     | 🔴               |
 UI-08        | Match provided UI design             | Compare app with design mockups/screens | App matches provided design in layout, colors, fonts, spacing | 🔴               |

---

## ✅ Phase 3: Edge Case Testing

| Test Case ID | Description                          | Steps                                      | Expected Result                                                  | Test Criticality |
|--------------|--------------------------------------|--------------------------------------------|------------------------------------------------------------------|------------------|
| EDGE-01    | Unsupported input                    | Enter symbols or numbers in search         | "Not found" pop-up message appears                                | 🟡               |


---
## ✅ Phase 4: Regression Testing


After any **updates**, **bug fixes**, or **new feature additions**, **regression testing** will be performed to ensure that **existing functionalities** continue to work as expected. This phase will involve **rerunning selected test cases** from earlier phases — especially **high-priority ones** — to detect any **unintended side effects** introduced by recent changes. We will focus on the homepage, navigation buttons, meal selection flow, and filters to ensure overall app stability.
