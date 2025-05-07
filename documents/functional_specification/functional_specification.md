# Functional Specification - BiteMatch <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
  - [Project Overview](#project-overview)
  - [Project Definition](#project-definition)
    - [Vision](#vision)
    - [Objectives](#objectives)
    - [Scope](#scope)
    - [Target Audience](#target-audience)
    - [Deliverables](#deliverables)
  - [Project Organisation](#project-organisation)
    - [Project Representatives](#project-representatives)
    - [Stakeholders](#stakeholders)
    - [Project Reviewers](#project-reviewers)
  - [Project Plan](#project-plan)
    - [Retroplanning](#retroplanning)
    - [Milestones](#milestones)
    - [Dependencies](#dependencies)
    - [Assumptions/Constraints](#assumptionsconstraints)
    - [Risks/Mitigation](#risksmitigation)
- [UI/UX](#uiux)
  - [Wireframes](#wireframes)
  - [Mockups](#mockups)
  - [Color Palette](#color-palette)
  - [Logo](#logo)
  - [Font](#font)
- [Funtional Requirements](#funtional-requirements)
  - [Languages](#languages)
  - [Data](#data)
    - [Meals](#meals)
    - [Tags](#tags)
  - [Product Description](#product-description)
  - [Personas](#personas)
  - [User Workflow](#user-workflow)
- [Non-Functional Requirements](#non-functional-requirements)
  - [Performance](#performance)
  - [Connectivity](#connectivity)
  - [Responsiveness](#responsiveness)
  - [Marketing](#marketing)
  - [Technical Requirements](#technical-requirements)
- [Glossary](#glossary)

## Introduction

### Project Overview

---

This project is about creating an application to recommend to user wine and cheese according to the meal they want to eat.

The client is "Intermarché Saint-Rémy-de-Provence". <!-- Our contact point is ___, the --> <!-- TODO: add name & role. -->

---

### Project Definition

---

#### Vision

---

The vision behind this project is to help people chose better wine assortiment for their meal all day long, even when there is no department expert in the store. Allowing new commers and tourist to try and find by themselves new and local product.

---

#### Objectives

---

- **Helping client finding meal assortiment**: The application should allow user to find wine, or cheese without any human help.
- **Bringing discovery to client**: The application should permit client to discover new and local ingredients/wine. It would allow client to have a new experience with the French culture.
- **Ease of use**: The application should be totally user-friendly and compatible in many languages. The application should be quick to use-no more than 3 pages to navigate through-and accessible without connection.

---

#### Scope

---

This peoject will be made in bubble, a no-code platform, and should be compatible with every mobile device. If this concept is adapted and should be spread around or scaled, then another language would be used to create the application.

The implementation would mainly concern the front-end as it is a UX project. A back-end would still be implemented. However, this one would be smaller than the actual database. As it is a proof of concept, quality would be prioritize as quantity.

---

#### Target Audience

---

**Tourist**: People that aren't from the region, wanting to discover more about the culture and culinary habits of its inhabitants. They would use the application in their own language (or most common one) to discover new wines and cheese quickly during their journey.

**Locals**: People that live annually or partially in the region. They could use the application for recommendation in particular events such as weddings or party.

**Wine Amateurs**: People that likes wines and have knowlegde about them. They could use the application to know more about the different tastes of the wine, with what it suits best.

**Cheese Amateurs**: People that likes cheeses and have knowlegde about them. They could use the application to know more about the different kind of the cheese and their best assortiment.

---

#### Deliverables

---

The main deliverable of this project is the bubble application/source code. Alongside, five documents would be written:

- The Functional Specification
- The Technical Specification
- The Test Plan
- The User Manual
- Management Planning and Weekly Reports

In addition, a 15-minute long presentation would be done in front of the client to show this advancement.

---

### Project Organisation

---

#### Project Representatives

---

| Name            | Role              | Responsibilities                                                                                                                     | Links                                                             |
| --------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| Antoine PREVOST | Project Manager   | Managment (time, resources)<br>Workload distribution<br> Report to stakeholders<br>Risk anticipation and mitigation                  | [LinkedIn](https://www.linkedin.com/in/antoine-prevost-dev/)      |
| Maxime THIZEAU  | Program Manager   | Mock-ups and general design of the software<br>Communication with the client<br>Functional specification delivery<br>Risk management | [LinkedIn](https://www.linkedin.com/in/maxime-thizeau-0b311a293/) |
| Antoine PREVOST | Technical Leader  | Define coding conventions<br>Choose technical tools used<br>Technical specification delivery<br>Manages developer tasks              | [LinkedIn](https://www.linkedin.com/in/antoine-prevost-dev/)      |
| Pavlo PRENDI    | Software engineer | Write the code<br>Fix bugs<br>Document the code<br>Create the tests if needed for the code                                           | [LinkedIn](https://www.linkedin.com/in/pavlo-prendi/)             |
| MARIEM ZAIANE   | Quality assurance | Verify documents<br>Test the program<br>Confirm we match the client expectations<br>Test plan delivery                               | [LinkedIn](https://www.linkedin.com/in/mariem-zaiane/)            |

---

#### Stakeholders

---

| Role            | Representative              | Expectation                                                            |
| --------------- | --------------------------- | ---------------------------------------------------------------------- |
| Client          | Célia & Dylan (Intermarché) | Finished project while meeting requirements and proof-tested prototype |
| School director | Franck JEANNIN (ALGOSUP)    | Clear documentation and management based on the skills learnt in class |

---

#### Project Reviewers

---

External project reviewers have been appointed by the project owner to review our specifications and provide us with feedback.

---

### Project Plan

---

#### Retroplanning

---

**End Goal and Deadline**:

Launch of a new application to help tourist find good wines/cheeses for their meal by June 20, 2025.

**Key Milestones**:

- Final Testing completed by June 16, 2025.
- Final Product codebase completed by June 14, 2025.
- Functional Specification completed by May 16, 2025.

**Task Breakdown**:

- Correcting codebase product from June 11 to June 13, 2025.
- Testing codebase product from June 11 to June 13, 2025.
- Implementing Nice-to-have features from June 4 to June 11, 2025.
- Implementing core features from May 22 to June 2, 2025.
- Reviewing Functional Specification from May 14 to May 16, 2025.
- Defining Functional Specification from May 7 to May 14, 2025.
- Creating the mock-up from April 28 to May 7, 2025.

**Critical Path**:

- Core feature development must be completed before final testing.
- Mock-up must be completed before Implementing Core features.

**Timeline Visualization**:

<!-- TODO: Wainting for PM Gantt Chart -->

---

#### Milestones

---

| Date       | Time   | Milestones                        |
| ---------- | ------ | --------------------------------- |
| 04/22/2025 | 9 A.M. | Project kick-off with the client  |
| 05/16/2025 | 5 P.M. | Functional Specification delivery |
| 05/28/2025 | 5 P.M. | Technical Specification delivery  |
| 06/06/2025 | 5 P.M. | Test Plan delivery                |
| 06/16/2025 | 5 P.M. | Final product codebase delivery   |
| 06/16/2025 | 5 P.M. | User Manual Delivery              |
| 06/20/2025 | 9 A.M. | Final Presentation Pitch          |

---

#### Dependencies

---

**Task Dependencies**:

- The Final Testing cannot start until Core Features are developed.
- The Nice-to-have Feature Development cannot start until Core Features are developed.
- The Core Feature Development cannot start until the mockup is approved.

**Resource Dependencies**:

- QA must be available for the testing phase from June 2 to June 13, 2025.
- Tech Lead must be available for code review from June 11 to June 13, 2025.

---

#### Assumptions/Constraints

---

**Assumptions**:

- Tourists have access to smartphones with internet connectivity while shopping, at least to download the application.
- Intermarché will allow application usage in-store and possibly promote it.
- The application will run on both iOS and Android platforms.
- The application will use a simple and intuitive interface to accommodate casual or non-tech-savvy users.

**Constraints**:

- Limited access to real-time inventory from the grocery store may restrict accuracy of in-stock recommendations.
- The search bar will only be used for cheeses and wines in the Proof Of Concept.
- Must comply with local regulations for food labeling, allergens, and data privacy (e.g., GDPR).
- The application must function offline or with limited connectivity, at least for basic features.
- UI must accommodate quick usage in a shopping setting.

---

#### Risks/Mitigation

---

| Type                                     | Description                                                                                                                | Likelihood | Impact                  | Mitigation                                                     |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------------------- | -------------------------------------------------------------- |
| New requirements                         | The client might request some changes at any time, forcing us to change our specifications and potentially creating delays | Medium     | Varies from low to high | Avoidance                                                      |
| Wrong interpretation of the requirements | We might forget a key point in our solution or misinterpret a requirement                                                  | Medium     | High                    | Regular communications about what's being done with the client |

---

## UI/UX

### Wireframes

---

This project has been into many states and was at first designed as a wireframe on Excalidraw. You can find it by clicking on the following link: [Excalidraw, Read only](https://excalidraw.com/#json=CeX56Qg24DF5ZD2TAaS40,9vrUyinyniIOAFH6zy5HQA).

**First Idea**:

The first workflow idea was to enter the name of the meal the user would like to eat and a recomendation of wines or cheeses would appear underneath the search input.

![First Workflow Idea](./img/first_workflow_idea.png)

This idea wasn't retained because the database necessary at its well-behavement wasn't feasable for this project.

**Second Idea**:

This one was more based in a menu "a la carte" way. The user could choose between many predefined dishes (local culinary specifities) and it would send them to a description page of the meal with recommendations for wine and cheese.

![Second Workflow Idea](./img/second_workflow_idea.png)

This idea was not retained due to the lack of possible dishes. The user could want something totally different from what is shown in the cards.

**Third Idea**:

This idea was solely based on a tag system. The user could select in the navigation bar (top bar) if he was searching for a wine or a cheese. Afterward, they could select tags to filter results until they find the expected wine/cheese.

![Third Workflow Idea](./img/third_workflow_idea.png)

This idea was rejected for being too specific. Only amateurs of wine and cheese could easily navigate through the different tags to select the desired product.

---

None of those ideas was convenient enough to solve the client's requirement. However, they all have a part that was interesting to dig in. Therefore, a last design was created by merging the three ideas.

**Final Idea**:

![Final Workflow Idea](./img/final_workflow_idea.png)

This idea combines the search bar from the first idea, the cards from the second one, and tags from the last one. However some differences can be spotten.

Firstly, the search bar would be used for wines and cheeses, and not meals anymore. The user would enter the name of a product and they would apear underneath.

Secondly, in the meal description page, the "both section" has been removed, judged as useless with the two others.

Finally, tags won't be visible on the main screen, since there could be a lot of them at the same time. They would be accessible through the "add tags" button and categorized by type and product (wines, cheeses, accompaniement).

---

### Mockups

---

The Mockups have been made on Figma and can be found in two places, either as a [pdf file]() or with this link: [Figma, Read only](https://www.figma.com/design/YYSa0BxXfyM5PNkdnCFYeZ/BiteMatch-wine-cheese-application?node-id=0-1&t=jhOQGM6NhjMpkwJ6-1).

<!-- TODO: add link to pdf file -->

BiteMatch's Mockups were made following previously mentionned wireframes and through a try & error process.

**First Version**:

This version was made following the last version of the wireframe. Colors used was Intermarché's one, referred as choice 1 in [Color Palette](#color-palette).

![Version One Mockup](./img/version_one_mockup.png)

This version had some changes, mainly on the sizes of different elements, judged as too big, and feeling like an application for elders, which was not the point.

**Second Version**:

This version was modified according to the first version feedback.

![Version Two Mockup](./img/version_two_mockup.png)

For this version, the cards (wine, cheese, meals) has been reduced as well as the font size and pictures, giving a more recent feeling about the application. \
Also, the brown color has been slightly lighten up to have a more harmonious page. \
Home button has been replaced by the [BiteMatch Logo](#logo). \
Finally, Intermarché's logo has been implemented in the middle of the top bar.

**Arabic Version**:

This application will be translated in many languages to be used by the most people possible. You can find which languages will the application be translated too at the following part, [Languages](#languages).

However, some languages aren't writting the same way as europeans do (up-to-down or right-to-left) which is the case of Arabic. Therefore, another design with a different layout has been designed to avoid issues when cretaing the application on bubble.

Here is a picture of the arabic Mockups:

![Version Two Mockup In Arabic](./img/version_two_mockup_arabic.png)

---

<!--
### Unique UI Feature

---

TODO

--- -->

### Color Palette

---

Many color charts has been defined for this project, but only three choices have been kept. They are the following:

| Colors           | Choice 1 | Choice 2 | Choice 3 |
| ---------------- | -------- | -------- | -------- |
| Primary          | #E00E1F  | #DD1717  | #590031  |
| Primary Contrast | #DECE9C  | #F4460B  | #FCFCEA  |
| Text             | #000000  | #940B0B  | #88A895  |
| Surface          | #F1F1F2  | #67140B  | #E5B355  |
| Background       | #FFFFFF  | #E5951A  | #442C42  |
| Destructive      | #B0200C  | #B0200C  | #B0200C  |
| Success          | #1E6C30  | #1E6C30  | #1E6C30  |
| Alert            | #DCA114  | #DCA114  | #DCA114  |

Since colors are quite easy and fast to change, the first choice was selected, as it was the same colors as Intermarché's ones.

---

### Logo

---

As none of the team members are graphic designers and that a logo could be quite difficult to design, it was decided to use an AI ([DeepAI](https://deepai.org)) to generate our logo.

The first selection was generated with a prompt containing information about the project and chart colors. DeepAI returned these six:

|                          Logo 1                           |                          Logo 2                           |                           Logo 3                            |                           Logo 4                           |                           Logo 5                           |                          Logo 6                           |
| :-------------------------------------------------------: | :-------------------------------------------------------: | :---------------------------------------------------------: | :--------------------------------------------------------: | :--------------------------------------------------------: | :-------------------------------------------------------: |
| <img alt="Logo 1" src="./img/logo_one.png" width="200px"> | <img alt="Logo 2" src="./img/logo_two.png" width="200px"> | <img alt="Logo 3" src="./img/logo_three.png" width="200px"> | <img alt="Logo 4" src="./img/logo_four.png" width="200px"> | <img alt="Logo 5" src="./img/logo_five.png" width="200px"> | <img alt="Logo 6" src="./img/logo_six.png" width="200px"> |

However, none of them has been consider as a good option since they weren't personified enough. Therefore, the team chosed a name for the application and a new prompt was generated with BiteMatch:

|                                        Logo 1                                         |                                        Logo 2                                         |                                         Logo 3                                          |
| :-----------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: |
| <img alt="Logo 1 Second Prompt" src="./img/logo_one_second_prompt.png" width="200px"> | <img alt="Logo 2 Second Prompt" src="./img/logo_two_second_prompt.png" width="200px"> | <img alt="Logo 3 Second Prompt" src="./img/logo_three_second_prompt.png" width="200px"> |

This second prompt exceeded our expectations giving us three good logos. After mindful reflections, the logo chosed was the second one, judged as more adequate with the application colors.

---

### Font

---

This application would be written with the `Inter` font because it is widely used in application and websites.

---

<!-- ### Image Assets

---

TODO

--- -->

## Funtional Requirements

### Languages

---

Since this appliaction is meant to be used by tourist, it will be translated in many languages.

The two main languages of the application would be French and English, as we are in France and that English is most spoken language abroad.

However, we decided not to stop to these two languages and to implant other languages which are:

| Language | Flag | Reason                                                                                                                                    |
| -------- | ---- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Greek    | 🇬🇷   | A team member comes from Greece.                                                                                                          |
| Arabic   | 🇦🇪   | Arabic is a widespread language, it also allows the application to change, since Arabic is written from right to left.                    |
| German   | 🇩🇪   | Germans are the second greatest tourist in France.                                                                                        |
| Spanish  | 🇪🇸   | Spanish are one of the most used languages in France. Moreover, Spain is near France, allowing Spanish people to do tourism quite easily. |
| Chinese  | 🇨🇳   | This is the most spoken language in the world.                                                                                            |

You can find the Mockup in Arabic above, in the [Mockups](#mockups) section.

---

### Data

---

#### Meals

---

For this application, the main page would display meal cards which would be predefined and regional specialities. You can find the selection hereunder:

|         Meal Name         |                                         Picture                                         |                                                              Meal description                                                               |
| :-----------------------: | :-------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
|         Anchoïade         |              <img alt="Anchoiade" src="./img/anchoiade.png" width="200px">              |          A savory dip made from anchovies, garlic, olive oil, and sometimes capers, typically served with raw vegetables or bread.          |
|           Aïoli           |                  <img alt="aioli" src="./img/aioli.png" width="200px">                  |                 A garlic mayonnaise often served with vegetables, fish, or hard-boiled eggs, central to Provençal cuisine.                  |
|  Tomate à la Provençale   | <img alt="Tomate a la Provencale" src="./img/tomate_a_la_provencale.png" width="200px"> |                            Tomatoes baked with herbs, garlic, and breadcrumbs—an aromatic and simple side dish.                             |
|       Bouillabaisse       |          <img alt="Bouillabaisse" src="./img/bouillabaisse.png" width="200px">          | A traditional fish stew from Marseille made with various local fish, shellfish, and a flavorful broth, served with rouille sauce and bread. |
| Ratatouille de Saint-Rémy |     <img alt="Ratatuoille de Saint-Remy" src="./img/ratatouille.png" width="200px">     |              A slow-cooked vegetable medley of eggplant, zucchini, peppers, tomatoes, and herbs, originating from Saint-Rémy.               |
|           Socca           |                  <img alt="Socca" src="./img/socca.png" width="200px">                  |                         A thin, crispy chickpea flour pancake from Nice, seasoned with olive oil and black pepper.                          |
|         Broufado          |               <img alt="Broufado" src="./img/broufado.png" width="200px">               |                A hearty Provençal beef stew marinated in red wine and slow-cooked with onions, herbs, and sometimes olives.                 |
|         Crespeou          |               <img alt="Crespeou" src="./img/crespeou.png" width="200px">               |                       A layered savory cake made of different colored omelets with herbs and vegetables, served cold.                       |
|     Tian aux Légumes      |       <img alt="Tian aux Legumes" src="./img/tian_aux_legumes.png" width="200px">       |     A baked dish of sliced vegetables (usually zucchini, tomatoes, and eggplant) arranged in a colorful spiral and roasted with herbs.      |
|       Pissaladière        |           <img alt="Pissaladiere" src="./img/pissaladiere.png" width="200px">           |                    A savory tart from Nice topped with caramelized onions, anchovies, and olives, on a bread-like crust.                    |
|     Daube Provençale      |       <img alt="Daube Provencale" src="./img/daube_provencale.png" width="200px">       |             A rich beef stew braised in red wine with carrots, garlic, and Provençal herbs, often served with pasta or polenta.             |
|         Tapenade          |               <img alt="Tapenade" src="./img/tapenade.png" width="200px">               |                   A spread made of finely chopped olives, capers, anchovies, and olive oil, served on toast or as a dip.                    |

---

#### Tags

---

This application will allow user to search for wine or cheese with a search bar, as explained in the [Mockups](#mockups) section.

Therefore, some tags have been defined and classified into subcategories which are:

- Wine
- Cheese
- Accompaniement
- Label
- Season

Hereunder are a more detailed table for each of those subcategories.

**Wine**:

| Categories | Name      | Definition                                                                                |
| ---------- | --------- | ----------------------------------------------------------------------------------------- |
| Type       | Red       | Wine made primarily from dark-colored grape varieties; typically bold and rich in flavor. |
| Type       | White     | Wine made from green or yellowish grapes; usually light and crisp.                        |
| Type       | Sparkling | Wine containing significant levels of carbon dioxide, making it fizzy or bubbly.          |
| Type       | Rosé      | Wine with a pink hue, made from red grapes with limited skin contact during fermentation. |
| Alcohol%   | Natural   | Wine with no added alcohol; alcohol content arises solely from natural fermentation.      |
| Alcohol%   | 0%        | Non-alcoholic wine with 0% alcohol by volume (ABV).                                       |
| Alcohol%   | <8%       | Wine with a low alcohol content, typically light and often sweet.                         |
| Alcohol%   | <14%      | Standard table wine with moderate alcohol content.                                        |
| Alcohol%   | <23%      | Fortified wine with higher alcohol content, often due to added spirits.                   |
| Alcohol%   | 23+%      | Very high-alcohol content, typically liqueur-style or for cooking use.                    |
| Taste      | Spicy     | Flavor profile with notes similar to spices like pepper, clove, or cinnamon.              |
| Taste      | Bitter    | Sharp, slightly harsh taste often found in tannins or certain grape skins.                |
| Taste      | Salt      | Rare in wine, but refers to a saline or mineral-like taste.                               |
| Taste      | Fat       | A rich, full-bodied mouthfeel, often from high glycerol or alcohol content.               |
| Taste      | Sweet     | Noticeable sugar content, ranging from off-dry to dessert-level sweetness.                |
| Taste      | Acid      | Tart, tangy sensation that gives wine its freshness and balance.                          |

**Cheese**:

| Categories   | Name        | Definition                                                                                                                       |
| ------------ | ----------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Animal Milk  | Goat        | Milk from goats, often used for cheeses with a tangy flavor and softer texture.                                                  |
| Animal Milk  | Cow         | The most common milk source for cheese, offering a wide variety of textures and flavors.                                         |
| Animal Milk  | Sheep       | Rich, fatty milk that yields creamy and tangy cheeses like Roquefort and Manchego.                                               |
| Animal Milk  | Buffalo     | High-fat milk known for producing rich, creamy cheeses like mozzarella di bufala.                                                |
| Vegetal Milk | Nut         | Plant-based milk made from nuts (e.g., almond, cashew), used in vegan cheese alternatives.                                       |
| Vegetal Milk | Soy         | Milk from soybeans, commonly used in dairy-free cheese products due to its high protein content.                                 |
| Vegetal Milk | Coconut     | Creamy, plant-based milk from coconuts, adding a mild sweetness to vegan cheeses.                                                |
| Vegetal Milk | Oat         | Dairy-free milk from oats, often used in plant-based cheese for its creamy texture.                                              |
| Vegetal Milk | Hemp        | Nutrient-rich milk from hemp seeds, used in alternative cheeses for its earthy flavor.                                           |
| Vegetal Milk | Rice        | Mild-flavored milk from rice, typically used in lighter vegan cheese products.                                                   |
| Vegetal Milk | Pea Protein | Plant-based milk derived from yellow peas, rich in protein and used in vegan cheese products.                                    |
| Type         | Fresh       | Cheese that is not aged, with a soft texture and high moisture content (e.g., ricotta).                                          |
| Type         | Soft        | Slightly aged cheese with a creamy interior and edible rind (e.g., Brie, Camembert).                                             |
| Type         | Semi-hard   | Firm cheese with lower moisture, aged longer for fuller flavor (e.g., Gouda, Edam).                                              |
| Type         | Hard        | Aged for extended periods, with a crumbly or firm texture (e.g., Parmesan, Pecorino).                                            |
| Type         | Blue        | Cheese inoculated with mold cultures, resulting in blue or green veins and a strong, tangy flavor (e.g., Gorgonzola, Roquefort). |

**Accompaniement**:

| Categories | Name      | Definition                                                                                         |
| ---------- | --------- | -------------------------------------------------------------------------------------------------- |
| Meat       | Red       | Meat from mammals with darker-colored flesh, typically richer in flavor (e.g., beef, lamb).        |
| Meat       | White     | Lighter-colored meat, generally leaner and milder in flavor (e.g., chicken, turkey).               |
| Meat       | Fish      | Meat from freshwater or saltwater fish, known for being light and high in protein.                 |
| Meat       | Sea       | Edible marine animals other than fish, such as shellfish and crustaceans (e.g., shrimp, scallops). |
| Meat       | Wild      | Meat from non-domesticated animals hunted in the wild (e.g., venison, boar).                       |
| Dessert    | Cake      | Baked sweet dessert, typically made from flour, sugar, and eggs, often layered or frosted.         |
| Dessert    | Fruit     | Desserts based on fresh or cooked fruits, such as tarts, compotes, or fruit salads.                |
| Dessert    | Chocolate | Desserts where chocolate is the main ingredient, including mousse, brownies, or truffles.          |
| Dessert    | Ice       | Frozen desserts like ice cream, sorbet, or gelato, served cold and often creamy or fruity.         |

**Label**:

| Name                                     | Definition                                                                                                                  |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Local                                    | Products sourced from a specific nearby region, often highlighting freshness and reduced transport.                         |
| AOP (Appellation d'Origine Protégée)     | EU certification guaranteeing that products are made entirely in a specific region using traditional methods.               |
| AOC (Appellation d'Origine Contrôlée)    | French certification for origin and quality, often a precursor to AOP, ensuring strict geographic and production standards. |
| IGP (Indication Géographique Protégée)   | Indicates that at least one stage of production, processing, or preparation takes place in the designated area.             |
| Label Rouge                              | French quality label awarded to products that have superior taste and production standards compared to regular products.    |
| STG (Spécialité Traditionnelle Garantie) | EU label highlighting traditional character, either in composition or means of production, without linking to a region.     |
| Bio (AB)                                 | French organic certification ("Agriculture Biologique") ensuring the product is made without synthetic chemicals or GMOs.   |

**Season**:

| Name   | Definition                                                                                                                                                                                                                                    |
| ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Spring | A season for light, fresh wines such as Sauvignon Blanc, Pinot Grigio, and young rosés that pair well with seasonal vegetables and mild weather. |
| Summer | Ideal for chilled, refreshing wines like rosé, sparkling wines, and crisp whites (e.g., Riesling, Albariño), often paired with light meals and outdoor dining. |
| Autumn | A transitional season favoring fuller whites and lighter reds such as Chardonnay, Pinot Noir, or Grenache, complementing richer harvest foods. |
| Winter | Best suited for bold, warming reds like Cabernet Sauvignon, Syrah, or fortified wines such as Port, often served with hearty dishes.                        |

---

### Product Description

---

<!-- TODO: Say the different parts of the description page, how they are useful and so on -->

---

### Personas

---

<!-- TODO: Create three personas (at least 2) about a professional of wine, a tourist that wants to try cheeses according to regional specialities, someone from the region that wants to have a good wine for their party -->

---

### User Workflow

---

<!-- TODO: Create a mermaid about the application workflow, meaning from wich page to start to wich page it goes, ect -->

---

## Non-Functional Requirements

### Performance

---

<!-- TODO: The application should run quickly without long loading time. -->

---

### Connectivity

---

<!-- TODO: The application should only use internet (4G, 5G, wifi) to install the application and the application should be usable without any internet access. -->

---

### Responsiveness

---

<!-- TODO: The application should be compatible to mainly used phones. They could be iOS or Android. -->

---

### Marketing

---

<!-- TODO: Explain how users will know about the application, maybe "etiquettes" with QR code or something else. -->

---

### Technical Requirements

---

<!-- TODO: Explain the technical requirement needed to complete the project in time. -->

---

## Glossary

<!-- TODO: Find all the words that could be missinterpreted or unknown by the most common one. Create a table gathering all of them. Create html tags for every one of them and link them so you can go back and forth the glossary in one click. -->

---
