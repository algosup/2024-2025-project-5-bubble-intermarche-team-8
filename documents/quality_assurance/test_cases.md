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

| Test Case ID | Description                  | Steps                              | Expected Result                                        | Test Criticality                                       |
|--------------|------------------------------|------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
| SMK-01       | Verify homepage loads         | Open app URL                       | Homepage loads without errors<br>[see expected result here](images/homepage.png)                          | 🔴              |
| SMK-02       | Check navigation buttons      | Click on **“+Tags”**, **“Search”**, and **“EN”** (language switch button)        | Buttons are visible and clickable<br>[see expected result here](images/buttons_smk02.png)                      | 🔴        |
| SMK-03       | Visibility of filters         | Click on **“+Tags”** to open filter section                 | All filter components (Tags, sections) are visible<br>[see expected result here](images/tags.png)       | 🟡 |


---

## ✅ Phase 1: Functional Testing

| Test Case ID | Description                        | Steps                                         | Expected Result                                          | Test Criticality |
|--------------|------------------------------------|-----------------------------------------------|----------------------------------------------------------|------------------|
| FUNC-01      | Select meal and get suggestions    | Step 1: Open the BITE MATCH app. <br> Step 2: From the home page, select a meal.                          | Relevant wine and cheese suggestions appear <br>[see expected result here](images/meal_selected.png)               | 🔴           |
| FUNC-02      | Apply wine filter                  | Step 1: Open the BITE MATCH app.<br>  Step 2: On the home page, click the **+Tags** button. <br> Step 3: From the tag list, select the tag that indicates **"White"**.                             | Only white wines are shown <br>[see expected result here](images/wines_page.png)                                 | 🔴           |
| FUNC-03      | Apply cheese filter                | Step 1: Open the BITE MATCH app.<br>  Step 2: On the home page, click the **+Tags** button. <br> Step 3: From the tag list, select the tag that indicates **"Soft"**.                          | Only soft cheeses are shown <br>[see expected result here](images/cheese_page.png)                              | 🔴           |
| FUNC-04      | Combine filters                    | Step 1: Open the BITE MATCH app.<br> Step 2: On the home page, click the **+Tags** button.<br> Step 3: From the wine tags section, select the tag that indicates **"Red"**.<br> Step 4: From the cheese tags section, select the tag that indicates **"Blue"**.               | Suggestions are updated accordingly                      | 🔴           |
| FUNC-05      | Language switch                    | Step 1: Open the BITE MATCH app.<br> Step 2: Click on the **Language** button (default is **EN**).<br> Step 3: From the popup of available languages, select **"French"**. | All labels/text are translated correctly                 | 🟡         |
| FUNC-06      | Scroll long lists                  | Step 1: Open the BITE MATCH app.<br>Step 2: Click on the **+Tags** button.<br>Step 3: From the wine tags section, select a **wine type** (e.g., "Red").<br>Step 4: Click **outside the popup** to close it.<br>Step 5: **Scroll down** to view all the available wines of the selected type.| List scrolls smoothly with no glitches                   | 🟢            |
| FUNC-07      | Switch between views               | Step 1: Open the BITE MATCH app.<br>Step 2: Select a meal from the home page.<br>Step 3: Click on the **"Cheese"** button.<br>Step 4: Click on the **"Wine"** button.              | View transitions smoothly                                | 🟡         |
| FUNC-08      | Use search bar                     | Step 1: Open the BITE MATCH app.<br>Step 2: Type **"camembert"** in the **search bar**.<br>Step 3: Click on the **"Search"** button.                  | Matching cheeses are displayed                           | 🔴           |
| FUNC-09      | Use price slider                   | Step 1: Open the BITE MATCH app.<br>Step 2: Slide the **maximum part** of the **slider** until it reaches **50 euros**.                  | Suggestions update within price range                    | 🟡         |
| FUNC-10      | Tag logic validation               | Step 1: Open the BITE MATCH app.<br> Step 2: On the home page, click the **+Tags** button.<br> Step 3: From the wine tags section, select the tag that indicates **"Red"**.<br> Step 4: From the wine tags section, select the tag that indicates **"White"**.          | Selection logic prevents conflict                        | 🟡         |
| FUNC-11      | Unselect a selected tag                    | Step 1: Open the BITE MATCH app.<br>Step 2: Click on the **+Tags** button.<br>Step 3: **Select** a tag by clicking on it.<br>Step 4: **Unselect** the same tag by clicking on it again.                               | Tag appears unselected and is removed from the filter logic            | 🔴               |
| FUNC-12      | Search for a specific wine product         | Step 1: Open the BITE MATCH app.<br>Step 2: Type the exact wine product name (e.g., **"Lansac Rouge"**) in the **search bar**.<br>Step 3: Click on the **"Search"** button. | Matching wine product is displayed                                    | 🔴               |
| FUNC-13      | Search for a non-existent product          | Step 1: Open the BITE MATCH app.<br>Step 2: Type a **random or nonexistent name** (e.g., **"xyz123"**) in the **search bar**.<br>Step 3: Click on the **"Search"** button.| "Not found" pop-up message appears <br>[see expected result here](images/not_found.png)                                     | 🟡               |
| FUNC-14      | Click the “go back” arrow                  | Step 1: Open the BITE MATCH app.<br>Step 2: Select a meal from the **home page**.<br>Step 3: Click on the **back arrow** button located at the **top left** of the page.                              | User is navigated to the previous page                                 | 🟡               |
| FUNC-15      | Select a suggested meal from product page  | Step 1: Open the BITE MATCH app.<br>Step 2: Search for **rosé wine** in the **search bar**.<br>Step 3: Click on the **"Search"** button.<br>Step 4: Click on the first suggested product.<br>Step 5: **Scroll down**, then click on one of the **suggested meals** under the product.                  | App navigates to the corresponding meal's page                         | 🔴               |


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
| EDGE-01    | Unsupported input                    | Step 1: Open the BITE MATCH app.<br>Step 2: Type an **unsupported input** (e.g., unvalid names, symbols) in the **search bar**.<br>Step 3: Click on the **"Search"** button.         | "Not found" pop-up message appears <br>[see expected result here](images/not_found.png)                                | 🟡               |


---
## ✅ Phase 4: Regression Testing


After any **updates**, **bug fixes**, or **new feature additions**, **regression testing** will be performed to ensure that **existing functionalities** continue to work as expected. This phase will involve **rerunning selected test cases** from earlier phases — especially **high-priority ones** — to detect any **unintended side effects** introduced by recent changes. We will focus on the homepage, navigation buttons, meal selection flow, and filters to ensure overall app stability.
