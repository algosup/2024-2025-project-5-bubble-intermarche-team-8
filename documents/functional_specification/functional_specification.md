# Functional Specification - BiteMatch <!-- omit in toc -->

<details>
<summary> Table of Contents </summary>

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
- [Personas and Use Cases](#personas-and-use-cases)
  - [Personas](#personas)
    - [Persona 1: Hao Huang](#persona-1-hao-huang)
    - [Persona 2: Remi Passereau](#persona-2-remi-passereau)
    - [Persona 3: Maxence Vidal](#persona-3-maxence-vidal)
  - [Use Cases](#use-cases)
    - [Selecting a Wine for a Meal](#selecting-a-wine-for-a-meal)
    - [Selecting a Cheese with Filters](#selecting-a-cheese-with-filters)
- [UI/UX](#uiux)
  - [Wireframes](#wireframes)
  - [Mockups](#mockups)
  - [Color Palette](#color-palette)
  - [Logo](#logo)
  - [Font](#font)
- [Functional Requirements](#functional-requirements)
  - [Languages](#languages)
  - [Data](#data)
    - [Products](#products)
    - [Meals](#meals)
    - [Tags](#tags)
  - [Product Description Page](#product-description-page)
  - [User Workflow](#user-workflow)
- [Non-Functional Requirements](#non-functional-requirements)
  - [Performance](#performance)
  - [Connectivity](#connectivity)
  - [Responsiveness](#responsiveness)
  - [Marketing](#marketing)
- [Glossary](#glossary)

</details>

## Introduction

### Project Overview

---

This project involves creating an application that recommends wine and cheese to users based on the meal they plan to eat.

The client is "Intermarché Saint-Rémy-de-Provence". Our contact points are Célia Moustier and Chrys Cadeau, respectively, the Intermarché's representative and the intern aisle responsible.

---

### Project Definition

---

#### Vision

---

The vision behind this project is to help people choose better wine assortments <sup><a id="1-bis" href="#1">[1]</a></sup> for their meal all day long, even when there is no department expert in the store. This allows newcomers and tourists to try and find new and local products for themselves.

---

#### Objectives

---

- **Helping client find meal assortiment**: The application should allow the user to find wine or cheese without any human help.
- **Bringing discovery to client**: The application should permit the client to discover new and local ingredients/wines. It would allow the client to have a new experience with the French culture.
- **Ease of use**: The application should be totally user-friendly and compatible in many languages. The application should be quick to use no more than 3 pages to navigate through-and accessible without connection.

---

#### Scope

---

This project will be made in Bubble<sup><a id="2-bis" href="#2">[2]</a></sup>, a no-code platform, and should be compatible with every mobile device. If this concept is adapted and should be spread around or scaled, then another language would be used to create the application.

The implementation would mainly concern the front-end, as it is a UX project. A back-end would still be implemented. However, this one would be smaller than the actual database. As it is a proof of concept, quality would be prioritized over quantity.

---

#### Target Audience

---

**Tourist**: People who aren't from the region, wanting to discover more about the culture and culinary habits of its inhabitants. They would use the application in their own language (or the most common one) to discover new wines and cheese quickly during their journey.

**Locals**: People who live annually or partially in the region. They could use the application for recommendations in particular events such as weddings or parties.

**Wine Amateurs**: People who like wines and have knowledge about them. They could use the application to know more about the different tastes of the wine, with what suits it best.

**Cheese Amateurs**: People who like cheeses and have knowlegde about them. They could use the application to know more about the different kind of the cheese and their best assortiment.

---

#### Deliverables

---

The main deliverable of this project is the bubble application/source code. Alongside, five documents would be written:

- The Functional Specification
- The Technical Specification
- The Test Plan
- The User Manual
- Management Planning and Weekly Reports

In addition, a 15-minute-long presentation would be done in front of the client to show this advancement.

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

Launch of a new application to help tourists find good wines/cheeses for their meal by June 20, 2025.

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
- Creating the mock-up<sup><a id="3-bis" href="#3">[3]</a></sup> from April 28 to May 7, 2025.

**Critical Path**:

- Core feature development must be completed before final testing.
- Mock-up must be completed before Implementing Core features.

**Timeline Visualization**:

The Gantt Chart could be found in the [management_artifacts.md file](../management/management_artifacts.md#tasks-and-schedule).

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

- Limited access to real-time inventory from the grocery store may restrict the accuracy of in-stock recommendations.
- The search bar will only be used for cheeses and wines in the Proof of Concept.
- Must comply with local regulations for food labeling, allergens<sup><a id="4-bis" href="#4">[4]</a></sup>, and data privacy (e.g., GDPR).
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

## Personas and Use Cases

### Personas

---

#### Persona 1: Hao Huang

---

**Name**: Hao Huang

**Age Range**: 20-60 years

**Description**: Hao Huang is a tourist who wants to discover new traditional meals from her different trips.

**Frustrations**:

- She can't read the description card in the store because she doesn't speak French.
- She never found traditional dishes from Provence.
- She really liked a wine in her country, but can't find one that tastes the same.

**Goals**:

- She wants to use an application translated into many languages.
- She wants to discover new traditional dishes of the region.
- She wants to find wines that taste the same as those in her hometown.

#### Persona 2: Remi Passereau

---

**Name**: Remi Passereau

**Age Range**: 45-65 years

**Description**: Remi is a wine amateur and loves to discover new wines.

**Frustrations**:

- No application gives enough details about wine tastes in his opinion.
- He would like to filter his search for a more accurate result.
- He never finds the bottle in the store aisle.

**Goals**:

- He wants to select his wine according to the wine's taste description.
- He wants to find the bottle quickly without getting lost in the aisle.
- He wants precise research and not to lose time while searching.

#### Persona 3: Maxence Vidal

---

**Name**: Maxence Vidal

**Age Range**: 18-30 years

**Description**: A young person new to the culinary world and traditions.

**Frustrations**:

- Maxence never tasted a traditional dish of the region.
- Maxence had enough to search for wines and cheeses on different applications.
- Maxence can't use the online application due to its poor quality internet connection.

**Goals**:

- They want to discover the traditional dishes of their heart region.
- They want to save time in their research by searching for both cheeses and wines on the same application.
- They want an application that functions without requiring an internet connection.

### Use Cases

---

#### Selecting a Wine for a Meal

---

**Actor**: user \
**Goal**: Want to select a wine corresponding to a traditional meal of Provence.

**Preconditions**:

- Need to have a phone.
- Need to have access to the application (QR code).

> [!Note]
> If it is the first time the user downloads the application, they would need an internet connection.

**Basic Flow**:

1. Scroll through the predefined meals suggested by the application.
2. Select the desired traditional meal.
3. Select the Wine Tab.
4. Scroll through the suggested list of wine.
5. Click on the desired one.

> [!Warning] Alternate Flows
>
> - The intended meal isn't available on the application.
> - The desired wine isn't in the database.

**Postconditions**:

- The user can find the wine by following the "Where to find" section's instructions.

---

#### Selecting a Cheese with Filters

---

**Actor**: user \
**Goal**: Want to select a cheese with filters for better time management.

**Preconditions**:

- Need to have a phone.
- Need to know a bit about cheese.
- Need to know what kind of cheese they want.
- Need to have access to the application (QR code).

> [!Note]
> If it is the first time the user downloads the application, they would need an internet connection.

**Basic Flow**:

1. Click on the "Add Tags" Button.
2. Select Tags according to the needed cheese by clicking on them.
3. Close the Pop-up.
4. Click the "Search button".
5. Scroll through Cheese options.
6. Click on the desired Cheese.

> [!Warning] Alternate Flows
>
> - None of the cheeses correspond to the filters.
> - None of the cheeses appear.
> - The desired cheeses aren't in the database

**Postconditions**:

- Follow the instructions in the "Where to find" section to find the product within the building.

---

## UI/UX

### Wireframes

---

This project has been in many states and was at first designed as a wireframe<sup><a id="5-bis" href="#5">[5]</a></sup> on Excalidraw. You can find it by clicking on the following link: [Excalidraw, Read only](https://excalidraw.com/#json=CeX56Qg24DF5ZD2TAaS40,9vrUyinyniIOAFH6zy5HQA).

**First Idea**:

The first workflow idea was to enter the name of the meal the user would like to eat, and a recommendation of wines or cheeses would appear underneath the search input.

![First Workflow Idea](./img/design/first_workflow_idea.png)

This idea wasn't retained because the database necessary for its well-being wasn't feasible for this project.

**Second Idea**:

This one was more based on a "menu a la carte" way. The user could choose between many predefined dishes (local culinary specialties), and it would send them to a description page of the meal with recommendations for wine and cheese.

![Second Workflow Idea](./img/design/second_workflow_idea.png)

This idea was not retained due to the lack of possible dishes. The user may want something totally different from what is shown in the cards.

**Third Idea**:

This idea was solely based on a tag system. The user could select in the navigation bar (top bar) if he was searching for a wine or a cheese. Afterward, they could select tags to filter results until they find the expected wine/cheese.

![Third Workflow Idea](./img/design/third_workflow_idea.png)

This idea was rejected for being too specific. Only amateurs of wine and cheese could easily navigate through the different tags to select the desired product.

---

None of those ideas was convenient enough to solve the client's requirement. However, they all have a part that was interesting to dig into. Therefore, a last design was created by merging the three ideas.

**Final Idea**:

![Final Workflow Idea](./img/design/final_workflow_idea.png)

This idea combines the search bar from the first idea, the cards from the second one, and tags from the last one. However, some differences can be spotted.

Firstly, the search bar would be used for wines and cheeses, and not meals anymore. The user would enter the name of a product, and it would appear underneath.

Secondly, in the meal description page, the "both section" has been removed, judged as useless with the two others.

Finally, tags won't be visible on the main screen, since there could be a lot of them at the same time. They would be accessible through the "add tags" button and categorized by type and product (wines, cheeses, accompaniments).

---

### Mockups

---

The mockups were created using Figma and are available in two locations: in the [PDF folder](./pdf/) or via this [read-only Figma link](https://www.figma.com/design/YYSa0BxXfyM5PNkdnCFYeZ/BiteMatch-wine-cheese-application?node-id=0-1&t=jhOQGM6NhjMpkwJ6-1).

BiteMatch's Mockups were made following previously mentioned wireframes and through a try & error process.

**First Version**:

This version was made following the last version of the wireframe. Colors used were Intermarché's one, referred to as choice 1 in [Color Palette](#color-palette).

![Version One Mockup](./img/design/version_one_mockup.png)

This version had some changes, mainly on the sizes of different elements, judged as too big, and feeling like an application for elders, which was not the point.

**Second Version**:

This version was modified according to the first version's feedback.

![Version Two Mockup](./img/design/version_two_mockup.png)

For this version, the cards (wine, cheese, meals) have been reduced as well as the font size and pictures, giving a more recent feeling about the application. \
Also, the brown color has been slightly lightened up to have a more harmonious page. \
The "Home button" has been replaced by the [BiteMatch Logo](#logo). \
Finally, Intermarché's logo has been implemented in the middle of the top bar.

**Arabic Version**:

This application will be translated into many languages to be used by the many people possible. You can find which languages will the application be translated too at the following part, [Languages](#languages).

However, some languages aren't written the same way as Europeans do (up-to-down or right-to-left), as is the case with Arabic. Therefore, another design with a different layout has been designed to avoid issues when creating the application on Bubble.

Here is a picture of the Arabic mockups:

![Version Two Mockup In Arabic](./img/design/version_two_mockup_arabic.png)

---

### Color Palette

---

Many color charts have been defined for this project, but only three choices have been kept. They are the following:

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

Since colors are quite easy and fast to change, the first choice was selected, as it was the same colors as Intermarché's.

---

### Logo

---

As none of the team members are graphic designers and a logo could be quite difficult to design, it was decided to use an AI ([DeepAI](https://deepai.org)) to generate our logo.

The first selection was generated with a prompt containing information about the project and chart colors. DeepAI returned these six:

|                             Logo 1                             |                             Logo 2                             |                              Logo 3                              |                             Logo 4                              |                             Logo 5                              |                             Logo 6                             |
| :------------------------------------------------------------: | :------------------------------------------------------------: | :--------------------------------------------------------------: | :-------------------------------------------------------------: | :-------------------------------------------------------------: | :------------------------------------------------------------: |
| <img alt="Logo 1" src="./img/logo/logo_one.png" width="200px"> | <img alt="Logo 2" src="./img/logo/logo_two.png" width="200px"> | <img alt="Logo 3" src="./img/logo/logo_three.png" width="200px"> | <img alt="Logo 4" src="./img/logo/logo_four.png" width="200px"> | <img alt="Logo 5" src="./img/logo/logo_five.png" width="200px"> | <img alt="Logo 6" src="./img/logo/logo_six.png" width="200px"> |

However, none of them has been considered a good option since they weren't personified enough. Therefore, the team chose a name for the application, and a new prompt was generated with BiteMatch:

|                                           Logo 1                                           |                                           Logo 2                                           |                                            Logo 3                                            |
| :----------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: |
| <img alt="Logo 1 Second Prompt" src="./img/logo/logo_one_second_prompt.png" width="200px"> | <img alt="Logo 2 Second Prompt" src="./img/logo/logo_two_second_prompt.png" width="200px"> | <img alt="Logo 3 Second Prompt" src="./img/logo/logo_three_second_prompt.png" width="200px"> |

This second prompt exceeded our expectations, giving us three good logos. After mindful reflections, the logo chosen was the second one, judged as more adequate with the application colors.

Moreover, the application would also use Intermarché's logo on the main page, as it is a project in collaboration with them. \
This logo would be only displayed on the main page for design purposes. The logo used is the following:

![Intermarché's Logo](img/logo/intermarche_logo.png)

---

### Font

---

This application would be written with the `Inter` font because it is widely used in applications and websites.

---

## Functional Requirements

### Languages

---

Since this application is meant to be used by tourists, it will be translated into many languages.

The two main languages of the application would be French and English, as we are in France, and English is the most spoken language abroad.

However, we decided not to stop to these two languages and to translate the application to other languages, which are:

| Language | Flag | Reason                                                                                                                                    |
| -------- | ---- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Greek    | 🇬🇷   | A team member comes from Greece.                                                                                                          |
| Arabic   | 🇦🇪   | Arabic is a widespread language, it also allows the application to change, since Arabic is written from right to left.                    |
| German   | 🇩🇪   | Germans are the second greatest tourists in France.                                                                                        |
| Spanish  | 🇪🇸   | Spanish is one of the most used languages in France. Moreover, Spain is near France, allowing Spanish people to do tourism quite easily. |
| Chinese  | 🇨🇳   | This is the most spoken language in the world.                                                                                            |

You can find the Mockup in Arabic above, in the [Mockups](#mockups) section.

---

### Data

---

#### Products

---

**Cheeses database**:

The cheese database could be found in the [data folder](./data/cheese_data.md). \
This database could be too heavy for Bubble standards. Therefore, a selection of the most sold cheeses would be displayed according to the data provided by Intermarché. \
The following products would be in the application database:

- Comté 18 mois
- Morbier
- Roquefort société
- Gorgonzola
- St néctaire fermier
- Tomme Tarentaise
- Tomme aux fleurs
- Manchego
- Ossau Iraty
- Tomme de chèvre
- Crottin de Chavignol (piece)
- Banon
- Chèvre de St Rémy (piece)
- Bouyguette (piece)
- Pérail des Bruissières
- St Marcellin (piece)
- Munster
- Brie de Meaux
- Grand morin à la truffe
- Camembert de Bufflonne (piece)

**Wines database**:

The wine database could be found in the [data folder](./data/wine_data.md). \
As for cheeses, wines would have a selection that will be within the database if space constraints are applicable to Bubble. \
The following wines would be:

- IGP VAR GRIS DE ROSE
- LAGOY VIN ROSE IGP ALPILLES BI
- ROSE CUVEE EVIDENCE MAS LANSAC
- GRAND MAS DE LANSAC BLAN
- GRAND MAS LANSAC ROSE
- LANSAC ROSE 5L
- MAS STE BERTHE ROUGE TRADITION
- MAS STE BERTHE ROSE 75 CL
- MAS STE BERTHE BLANC DE BLANC
- COEUR DE CAMARGUE ROSE
- IGP ROSE ETOILE DES ALPILLES
- ETOILE DES ALPILLES IGP BLANC
- VAL DE L OULE ROSE TENDRESSE
- PINOT NOIR 2022 ROUGE
- IGP ALPILLES ROSE TRADITION
- ALPILLES IGP TRADITION BLANC
- LUBERON LES CLAPES
- GRAND MAS DE LANSAC RGE
- AOP FOLIE EN PROVENCE 2023 COT
- LE GRIS MAS MARIGNAN

---

#### Meals

---

For this application, the main page would display meal cards, which would be predefined and regional specialities. You can find the selection hereunder:

|         Meal Name         |                                           Picture                                            |                                                              Meal description                                                               |
| :-----------------------: | :------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
|         Anchoïade         |              <img alt="Anchoïade" src="./img/meal/anchoiade.png" width="200px">              |          A savory dip made from anchovies, garlic, olive oil, and sometimes capers, typically served with raw vegetables or bread.          |
|           Aïoli           |                  <img alt="aioli" src="./img/meal/aioli.png" width="200px">                  |                 A garlic mayonnaise often served with vegetables, fish, or hard-boiled eggs, central to Provençal cuisine.                  |
|  Tomate à la Provençale   | <img alt="Tomate a la Provencale" src="./img/meal/tomate_a_la_provencale.png" width="200px"> |                            Tomatoes baked with herbs, garlic, and breadcrumbs—an aromatic and simple side dish.                             |
|       Bouillabaisse       |          <img alt="Bouillabaisse" src="./img/meal/bouillabaisse.png" width="200px">          | A traditional fish stew from Marseille made with various local fish, shellfish, and a flavorful broth, served with rouille sauce and bread. |
| Ratatouille de Saint-Rémy |     <img alt="Ratatouille de Saint-Remy" src="./img/meal/ratatouille.png" width="200px">     |              A slow-cooked vegetable medley of eggplant, zucchini, peppers, tomatoes, and herbs, originating from Saint-Rémy.               |
|           Socca           |                  <img alt="Socca" src="./img/meal/socca.png" width="200px">                  |                         A thin, crispy chickpea flour pancake from Nice, seasoned with olive oil and black pepper.                          |
|         Broufado          |               <img alt="Broufado" src="./img/meal/broufado.png" width="200px">               |                A hearty Provençal beef stew marinated in red wine and slow-cooked with onions, herbs, and sometimes olives.                 |
|         Crespeou          |               <img alt="Crespeou" src="./img/meal/crespeou.png" width="200px">               |                       A layered savory cake made of different colored omelets with herbs and vegetables, served cold.                       |
|     Tian aux Légumes      |       <img alt="Tian aux Legumes" src="./img/meal/tian_aux_legumes.png" width="200px">       |     A baked dish of sliced vegetables (usually zucchini, tomatoes, and eggplant) arranged in a colorful spiral and roasted with herbs.      |
|       Pissaladière        |           <img alt="Pissaladiere" src="./img/meal/pissaladiere.png" width="200px">           |                    A savory tart from Nice topped with caramelized onions, anchovies, and olives, on a bread-like crust.                    |
|     Daube Provençale      |       <img alt="Daube Provencale" src="./img/meal/daube_provencale.png" width="200px">       |             A rich beef stew braised in red wine with carrots, garlic, and Provençal herbs, often served with pasta or polenta.             |
|         Tapenade          |               <img alt="Tapenade" src="./img/meal/tapenade.png" width="200px">               |                   A spread made of finely chopped olives, capers, anchovies, and olive oil, served on toast or as a dip.                    |

---

#### Tags

---

This application will allow users to search for wine or cheese with a search bar, as explained in the [Mockups](#mockups) section.

Therefore, some tags have been defined and classified into subcategories, which are:

- Wine
- Cheese
- Accompaniment
- Label
- Season
- Allergen

Those tags can be accessed through the "add tags" button. Moreover, every product description page would have tags associated with it. Learn more about it in [Product Description Page](#product-description-page).

Hereunder is a more detailed table for each of those subcategories.

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
| Taste      | Salty     | Rare in wine, but refers to a saline or mineral-like taste.                               |
| Taste      | Round     | A rich, full-bodied mouthfeel, often from high glycerol or alcohol content.               |
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

| Categories | Name      | Definition                                                                                                                                               |
| ---------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Meat       | Red       | Meat from mammals with darker-colored flesh, typically richer in flavor (e.g., beef, lamb).                                                              |
| Meat       | White     | Lighter-colored meat, generally leaner and milder in flavor (e.g., chicken, turkey).                                                                     |
| Meat       | Fish      | Meat from freshwater or saltwater fish, known for being light and high in protein.                                                                       |
| Meat       | Sea       | Edible marine animals other than fish, such as shellfish and crustaceans (e.g., shrimp, scallops).                                                       |
| Meat       | Wild      | Meat from non-domesticated animals hunted in the wild (e.g., venison, boar).                                                                             |
| Dessert    | Cake      | A baked sweet dessert, typically made from flour, sugar, and eggs, often layered or frosted.                                                               |
| Dessert    | Fruit     | Desserts based on fresh or cooked fruits, such as tarts, compotes, or fruit salads.                                                                      |
| Dessert    | Chocolate | Desserts where chocolate is the main ingredient, including mousse, brownies, or truffles.                                                                |
| Dessert    | Ice       | Frozen desserts like ice cream, sorbet, or gelato, served cold and often creamy or fruity.                                                               |
| Aperitif   | Aperitif  | An apéritif is a light pre-meal gathering or course, often featuring drinks and small bites, meant to stimulate the appetite and encourage conversation. |

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

| Name   | Definition                                                                                                                                                     |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Spring | A season for light, fresh wines such as Sauvignon Blanc, Pinot Grigio, and young rosés that pair well with seasonal vegetables and mild weather.               |
| Summer | Ideal for chilled, refreshing wines like rosé, sparkling wines, and crisp whites (e.g., Riesling, Albariño), often paired with light meals and outdoor dining. |
| Autumn | A transitional season favoring fuller whites and lighter reds such as Chardonnay, Pinot Noir, or Grenache, complementing richer harvest foods.                 |
| Winter | Best suited for bold, warming reds like Cabernet Sauvignon, Syrah, or fortified wines such as Port, often served with hearty dishes.                           |

**Allergen**:

| Wine/Cheese | Name      | Definition                                                                                      |
| ----------- | --------- | ----------------------------------------------------------------------------------------------- |
| Cheese      | Milk      | Contains lactose and milk proteins (casein, whey); present in all dairy-based cheeses.          |
| Cheese      | Eggs      | Sometimes used in processed or melted cheeses as emulsifiers or additives.                      |
| Cheese      | Tree Nuts | May be present in flavored cheeses (e.g., walnut cheese); cross-contamination is possible.      |
| Cheese      | Soy       | Rare, but may appear in plant-based or processed cheese products.                               |
| Cheese      | Gluten    | Not naturally present in traditional cheese; may be found in processed or breaded cheeses.      |
| Cheese      | Mustard   | Sometimes found in flavored cheeses or cheese spreads.                                          |
| Cheese      | Sulfites  | Can be used as preservatives in industrial cheeses.                                             |
| Wine        | Sulfites  | Common preservative to prevent oxidation and spoilage; must be labeled if over 10 mg/l.         |
| Wine        | Eggs      | Egg white (albumin) may be used for fining (clarification); must be labeled if detectable.      |
| Wine        | Milk      | Milk proteins (casein) may be used for fining; must be labeled if detectable.                   |
| Wine        | Fish      | Isinglass (fish gelatin) can be used in fining; labeling not always required unless detectable. |

---

### Product Description Page

---

The description page will be separated in seven distinct parts, each of them would describe a partocular thing about the product it is referring to.

**Basic Information**:

This section is composed of:

- The Name of the Product.
- A picture of the Product if provided in the database.
- The Price of the Product.
- The Region it comes from.

And the percentage of alcohol in wines.

**Tags**:

In this section will be a list of all the tags corresponding to the Product. They will be displayed in a row.

**Suggestions**:

As the application should be a recommendation one, two meals will be displayed as suggestions for the product. Allowing users to mix their products better and have the best experience possible. \
The two meals would be displayed only if they are predefined in the database. However, the application is a proof of concept, therefore, some data could be missing. Consequently, this section could be empty. \
In the case of an empty section, the section would be hidden/removed for the product only.

**Taste**:

This section would only be present for wines.

It will be composed of three bars showing the different tastes of the wine. They would be sorted as follows:

- Salty<sup><a id="9-bis" href="#9">[9]</a></sup>/Round<sup><a id="10-bis" href="#10">[10]</a></sup>
- Sweetness<sup><a id="11-bis" href="#11">[11]</a></sup>/Spicy<sup><a id="12-bis" href="#12">[12]</a></sup>
- Bitterness<sup><a id="13-bis" href="#13">[13]</a></sup>/Acidity<sup><a id="14-bis" href="#14">[14]</a></sup>

**Where to find it**:

This section would be a procedure to find the product within the grocery store. This could be done thanks to our client and a system that they already have implemented.

**Labels**:

This section will hold every label the product has. They would also be displayed as tags. However, they would be more descriptive, and the full name would be written, unlike tags.

**Description**:

Finally, the description part is here to give more information about the wine in itself. It couuld be little history, how the wine was made, the year of production.

---

### User Workflow

---

```mermaid
graph TD
 %% BiteMatch Flow
 subgraph BiteMatch Flow
 P1[Loading Page] --> P2[Home Page]

 P2 --> P3[Language Choice Pop-up]
 P2 -->|One for each Meal Card| P4[Meal Description Page]
 P2 -->|body| P5[Search Page]

 P3 -->|Left-to-right Languages| L1[English 'Default', French 'Mandatory', Greek, German, Spanish, Chinese]
 P3 -->|Right-to-left Languages| L2[Arabic]

 P4 -->|By default| S1[Wine Selection]
 P4 --> S2[Cheese Selection]
 S1 --> P6[Wine Description Page]
 S2 --> P7[Cheese Description Page]

 P5 -->|With Results| P9[Result Page]
 P5 -->|No Result| P10[Error Page]
 P5 --> F[Feature]
 F --> F1[Search input for a Product]
 F --> P8[Tags Filter Pop-up]
 F -->|Slider from €0 to most expensive one| F2[Budget Range]

 P8 -->|Category| TC[Wine, Cheese, Accompaniement, Label, Season]

 P9 --> P6
 P9 --> P7
 end
```

> [!note]
> As you might have noticed, BiteMatch is a login-free application, meaning the user doesn't need to log in to use the application.

---

## Non-Functional Requirements

### Performance

---

Our product would be used into the Intermarché grocery store of Saint-Rémy-De-Provence. The loading time should be short and the application intuitive for the users not to lose time.

However, our application still needs to be loaded into the client device at least once, so they can have access to the entire database. The user should not download the application data every time they use the application, but only the first time, so the loading time would be greatly reduced afterwards.

In other words:

- The first time the application is loaded, it should take at most 10 seconds.
- The next usages would take less than a second to load the entire application.

---

### Connectivity

---

The application should be usable without any internet connection. It would avoid losing people who do not possess any connection within the building. \
However, we are forced to use a connection at least once to download all the database into the user's device. \
To avoid this problem, we thought of using the free connection offered by Intermarché.

Once the application is fully loaded, an internet connection won't be necessary anymore.

---

### Responsiveness

---

This application is designed for mobile devices, since it would be used mainly inside Intermarché. We assume people don't go shopping with their laptops.

However, our application should be usable for every operating system and on all main screen sizes. \
Therefore, the application would be developed on the main screensize spread around the world, which is 360x800px. It would also be usable on the range of 350 to 375 pixel width.

---

### Marketing

---

As none of the team members are part of a marketing role or have any marketing experience, this section won't be really enhanced. \
However, the application could be downloaded via a QR code on a basic poster or sign, which could be displayed at the entrance of the building and at both sides of the related departments.

The team also relies on Intermarché's staff and marketing team to promote the application the best they can.

---

## Glossary

| Id                                 | Name        | Definition                                                                                                                                                   |
| ---------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <a id="6" href="#6-bis">[6]</a>    | AOP         | _Appellation d'Origine Protégée_; a French certification guaranteeing that a product is locally grown and produced using traditional methods.                |
| <a id="14" href="#14-bis">[14]</a> | Acidity     | A taste descriptor in both wine and cheese, indicating tartness or sourness, often associated with freshness.                                                |
| <a id="4" href="#4-bis">[4]</a>    | Allergen    | A substance capable of causing an allergic reaction, especially in food products like cheese or wine (e.g., milk, nuts, sulfites).                            |
| <a id="1" href="#1-bis">[1]</a>    | Assortiment | A combination or selection of complementary food items, such as wine and cheese, designed to enhance each other's flavors.                                   |
| <a id="8" href="#8-bis">[8]</a>    | Bio         | In France, “Bio” indicates organic food certified under European regulations, free from synthetic pesticides and GMOs.                                       |
| <a id="13" href="#13-bis">[13]</a> | Bitterness  | A taste characteristic often found in aged cheeses or certain wine varietals, balancing sweetness and acidity.                                               |
| <a id="2" href="#2-bis">[2]</a>    | Bubble      | A no-code development platform used to build web applications through visual programming without traditional coding.                                         |
| <a id="10" href="#10-bis">[10]</a> | Round       | A component of food that affects texture and flavor; in cheese, fat content contributes to richness and mouthfeel.                                           |
| <a id="7" href="#7-bis">[7]</a>    | IGP         | _Indication Géographique Protégée_; a European certification for products that have a specific geographical origin and possess qualities due to that origin. |
| <a id="3" href="#3-bis">[3]</a>    | Mock-up     | A high-fidelity, static representation of a user interface, used for visual design evaluation and client feedback.                                           |
| <a id="9" href="#9-bis">[9]</a>    | Salty       | A basic taste and nutrient, often used in cheese production to influence flavor, texture, and preservation.                                                  |
| <a id="12" href="#12-bis">[12]</a> | Spicy       | A sensory property related to heat or pungency, sometimes present in cheeses or paired with wines to contrast flavors.                                       |
| <a id="11" href="#11-bis">[11]</a> | Sweetness   | A taste quality indicating the presence of sugars; used in wine tasting to describe sugar levels.                                                            |
| <a id="5" href="#5-bis">[5]</a>    | Wireframe   | A basic visual guide used to suggest the layout and structure of a user interface before final design or development.                                        |

---
