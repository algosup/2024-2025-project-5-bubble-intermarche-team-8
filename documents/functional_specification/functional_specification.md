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
- [UI/UX](#uiux)
  - [Wireframes](#wireframes)
  - [Mockups](#mockups)
  - [Color Palette](#color-palette)
  - [Logo](#logo)
  - [Font](#font)
- [Funtional Requirements](#funtional-requirements)
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

This project is about creating an application to recommend to user wine and cheese according to the meal they want to eat.

The client is "Intermarché Saint-Rémy-de-Provence". Our contact points are Célia Moustier and Chrys Cadeau, respectively the Intermarché's representative and the intern aisle responsible.

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

## Personas and Use Cases

### Personas

---

<!-- TODO: Create three personas (at least 2) about a professional of wine, a tourist that wants to try cheeses according to regional specialities, someone from the region that wants to have a good wine for their party -->

#### Persona 1: Hao Huang

---

**Name**: Hao Huang

**Age Range**: 20-60 years old

**Description**: Hao Huang is a tourist that want to discover new traditional meals from her different trip.

**Frustrations**:

- She can't read description card in the store because she doesn't speak French.
- She never found traditional dish from Provence.
- She really liked a wine in her country but can't find one that tastes the same.

**Goals**:

- She wants to use an application translated in many languages.
- She wants to discover new traditional dishesof the region.
- She wants to find wines that taste the same as those in her hometown.

#### Persona 2: Remi Passereau

---

**Name**: Remi Passereau

**Age Range**: 45-65

**Description**: Remi is a wine amateurs and love to discover new wines.

**Frustrations**:

- No application gives enough details about wine tastes in its opinion.
- He would like to filter his research for a more accurate result.
- He never find the bottle in the store aisle.

**Goals**:

- He wants to select his wine according to wines tastes description.
- He wants to find the bottle quickly without getting lost in the aisle.
- He wants a precise research and not to lose time while searching.

#### Persona 3: Maxence Vidal

---

**Name**: Maxence Vidal

**Age Range**: 18-30

**Description**: A young person new to culinary word and traditions.

**Frustrations**:

- Maxence never tasted a traditional dish of the region.
- Maxence have nough of searching for wines and cheeses on different applications.
- Maxence can't use online application due to it's poor quality internet connection.

**Goals**:

- They want to discover traditional dishes of their heart region.
- They want to save time in their research by searching for both cheeses and wines on the same application.
- They want a free-connection application to use it even with their connection.

### Use Cases

---

<!-- TODO: Create some use cases formated as in AfterWords documentation. -->

---

## UI/UX

### Wireframes

---

This project has been into many states and was at first designed as a wireframe on Excalidraw. You can find it by clicking on the following link: [Excalidraw, Read only](https://excalidraw.com/#json=CeX56Qg24DF5ZD2TAaS40,9vrUyinyniIOAFH6zy5HQA).

**First Idea**:

The first workflow idea was to enter the name of the meal the user would like to eat and a recomendation of wines or cheeses would appear underneath the search input.

![First Workflow Idea](./img/design/first_workflow_idea.png)

This idea wasn't retained because the database necessary at its well-behavement wasn't feasable for this project.

**Second Idea**:

This one was more based in a menu "a la carte" way. The user could choose between many predefined dishes (local culinary specifities) and it would send them to a description page of the meal with recommendations for wine and cheese.

![Second Workflow Idea](./img/design/second_workflow_idea.png)

This idea was not retained due to the lack of possible dishes. The user could want something totally different from what is shown in the cards.

**Third Idea**:

This idea was solely based on a tag system. The user could select in the navigation bar (top bar) if he was searching for a wine or a cheese. Afterward, they could select tags to filter results until they find the expected wine/cheese.

![Third Workflow Idea](./img/design/third_workflow_idea.png)

This idea was rejected for being too specific. Only amateurs of wine and cheese could easily navigate through the different tags to select the desired product.

---

None of those ideas was convenient enough to solve the client's requirement. However, they all have a part that was interesting to dig in. Therefore, a last design was created by merging the three ideas.

**Final Idea**:

![Final Workflow Idea](./img/design/final_workflow_idea.png)

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

![Version One Mockup](./img/design/version_one_mockup.png)

This version had some changes, mainly on the sizes of different elements, judged as too big, and feeling like an application for elders, which was not the point.

**Second Version**:

This version was modified according to the first version feedback.

![Version Two Mockup](./img/design/version_two_mockup.png)

For this version, the cards (wine, cheese, meals) has been reduced as well as the font size and pictures, giving a more recent feeling about the application. \
Also, the brown color has been slightly lighten up to have a more harmonious page. \
Home button has been replaced by the [BiteMatch Logo](#logo). \
Finally, Intermarché's logo has been implemented in the middle of the top bar.

**Arabic Version**:

This application will be translated in many languages to be used by the most people possible. You can find which languages will the application be translated too at the following part, [Languages](#languages).

However, some languages aren't writting the same way as europeans do (up-to-down or right-to-left) which is the case of Arabic. Therefore, another design with a different layout has been designed to avoid issues when cretaing the application on bubble.

Here is a picture of the arabic Mockups:

![Version Two Mockup In Arabic](./img/design/version_two_mockup_arabic.png)

---

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

|                             Logo 1                             |                             Logo 2                             |                              Logo 3                              |                             Logo 4                              |                             Logo 5                              |                             Logo 6                             |
| :------------------------------------------------------------: | :------------------------------------------------------------: | :--------------------------------------------------------------: | :-------------------------------------------------------------: | :-------------------------------------------------------------: | :------------------------------------------------------------: |
| <img alt="Logo 1" src="./img/logo/logo_one.png" width="200px"> | <img alt="Logo 2" src="./img/logo/logo_two.png" width="200px"> | <img alt="Logo 3" src="./img/logo/logo_three.png" width="200px"> | <img alt="Logo 4" src="./img/logo/logo_four.png" width="200px"> | <img alt="Logo 5" src="./img/logo/logo_five.png" width="200px"> | <img alt="Logo 6" src="./img/logo/logo_six.png" width="200px"> |

However, none of them has been consider as a good option since they weren't personified enough. Therefore, the team chosed a name for the application and a new prompt was generated with BiteMatch:

|                                           Logo 1                                           |                                           Logo 2                                           |                                            Logo 3                                            |
| :----------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: |
| <img alt="Logo 1 Second Prompt" src="./img/logo/logo_one_second_prompt.png" width="200px"> | <img alt="Logo 2 Second Prompt" src="./img/logo/logo_two_second_prompt.png" width="200px"> | <img alt="Logo 3 Second Prompt" src="./img/logo/logo_three_second_prompt.png" width="200px"> |

This second prompt exceeded our expectations giving us three good logos. After mindful reflections, the logo chosed was the second one, judged as more adequate with the application colors.

Moreover, the application would also use Intermarché's logo on the main page as it is a project in collaboration with them. \
This logo would be only displayed on the main page for design purpose. The logo used is the following:

![Intermarché's Logo](img/logo/intermarche_logo.png)

---

### Font

---

This application would be written with the `Inter` font because it is widely used in application and websites.

---

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

#### Products

---

**Cheeses database**:

| Image                                                                                               | Product Name                   | ITM8          | EAN           | Tags | Description | Link                                                                                                               |
| --------------------------------------------------------------------------------------------------- | ------------------------------ | ------------- | ------------- | ---- | ----------- | ------------------------------------------------------------------------------------------------------------------ |
| ![CHEVRE NATURE OU AROMATISE Picture](<img/product/cheeses/CHEVRE NATURE OU AROMATISE.png>)         | CHEVRE NATURE OU AROMATISE     | 0000099006106 | 0205010000000 |      |             | [Link](https://www.intermarche.com/produit/yaourt-au-lait-de-chevre-nature/3250391945993)                          |
| ![YAOURT AUX FRUITS MERE RICHARD Picture](<img/product/cheeses/YAOURT AUX FRUITS MERE RICHARD.png>) | YAOURT AUX FRUITS MERE RICHARD | 0000099064583 | 0000000000198 |      |             | [Link](https://www.intermarche.com/produit/yaourt-onctueux-aux-fruits-mixes-fruits-rouges/3250392046705)           |
| ![P&C ROCAMADOUR AOP NU 35G Picture](<img/product/cheeses/P&C ROCAMADOUR AOP NU 35G.png>)           | P&C ROCAMADOUR AOP NU 35G      | 0000043439167 | 2663702000000 |      |             | [Link](https://www.intermarche.com/produit/rocamadour-aop/2663702000000)                                           |
| ![TOME DE PROVENCE Picture](<img/product/cheeses/TOME DE PROVENCE.png>)                             | TOME DE PROVENCE               | 0000099060048 | 0204410000000 |      |             | [Link](https://www.intermarche.com/produit/tomme-des-pyrenees-igp/3250391594146)                                   |
| ![PELARDON Picture](img/product/cheeses/PELARDON.png)                                               | PELARDON                       | 0000099041865 | 0204510000000 |      |             | Not found                                                                                                          |
| ![ST MARCELLIN MERE RICHARD Picture](<img/product/cheeses/ST MARCELLIN MERE RICHARD.png>)           | ST MARCELLIN MERE RICHARD      | 0000099041874 | 0204600000000 |      |             | [Link](https://www.intermarche.com/produit/saint-marcellin/3250390153344)                                          |
| ![ST FELICIEN MERE RICHARD Picture](<img/product/cheeses/ST FELICIEN MERE RICHARD.png>)             | ST FELICIEN MERE RICHARD       | 0000099041873 | 0204590000000 |      |             | [Link](https://www.intermarche.com/produit/saint-felicien/3250390213994)                                           |
| ![SECHONS DE CHEVRE Picture](<img/product/cheeses/SECHONS DE CHEVRE.png>)                           | SECHONS DE CHEVRE              | 0000099041867 | 0204530000000 |      |             | Not found                                                                                                          |
| ![FE ST FELICIEN ST MARCEL 260G Picture](<img/product/cheeses/FE ST FELICIEN ST MARCEL 260G.png>)   | FE ST FELICIEN ST MARCEL 260G  | 0000019315996 | 3237054005744 |      |             | [Link](https://www.intermarche.com/produit/duo-saint-marcellin-igp-saint-felicien/3237054005744)                   |
| ![CROTTIN DE CHAVIGNOL AOP 60G Picture](<img/product/cheeses/CROTTIN DE CHAVIGNOL AOP 60G.png>)     | CROTTIN DE CHAVIGNOL AOP 60G   | 0000043439418 | 2663716000000 |      |             | [Link](https://www.intermarche.com/produit/crottin-de-chavignol-aop/3250390155478)                                 |
| ![ETOILE QUERCY PAVE DU LOT 180G Picture](<img/product/cheeses/ETOILE QUERCY PAVE DU LOT 180G.png>) | ETOILE QUERCY PAVE DU LOT 180G | 0000019026731 | 2663713000000 |      |             | [Link](https://www.intermarche.com/produit/fromage-de-chevre-rocamadour/3346200101039)                             |
| ![LE VENTOUX Picture](<img/product/cheeses/LE VENTOUX.png>)                                         | LE VENTOUX                     | 0000099060040 | 0204830000000 |      |             | [Link](https://www.intermarche.com/produit/ventoux-vin-rouge/3250391461554)                                        |
| ![BANON FEUILLE Picture](<img/product/cheeses/BANON FEUILLE.png>)                                   | BANON FEUILLE                  | 0000099041863 | 2670978000000 |      |             | [Link](https://www.intermarche.com/produit/banon-aop-cave-25%25-mg/2670978000000)                                  |
| ![ST FELICIEN TENTATION 200G Picture](<img/product/cheeses/ST FELICIEN TENTATION 200G.png>)         | ST FELICIEN TENTATION 200G     | 0000019026713 | 2663532000000 |      |             | [Link](https://www.intermarche.com/produit/fromage-saint-felicien/3237055000724)                                   |
| ![BOUYGUETTE Picture](img/product/cheeses/BOUYGUETTE.png)                                           | BOUYGUETTE                     | 0000099041859 | 0204450000000 |      |             | Not found                                                                                                          |
| ![FE ST FELICIEN AFFINE 150G Picture](<img/product/cheeses/FE ST FELICIEN AFFINE 150G.png>)         | FE ST FELICIEN AFFINE 150G     | 0000019676898 | 3523230034289 |      |             | [Link](https://www.intermarche.com/produit/saint-felicien/3523230034289)                                           |
| ![PICODON AOP MERE RICHARD Picture](<img/product/cheeses/PICODON AOP MERE RICHARD.png>)             | PICODON AOP MERE RICHARD       | 0000099059676 | 0204660000000 |      |             | Not found                                                                                                          |
| ![FE P&C ST MARCELLIN IGP 2X80GR Picture](<img/product/cheeses/FE P&C ST MARCELLIN IGP 2X80GR.png>) | FE P&C ST MARCELLIN IGP 2X80GR | 0000043434119 | 3250391104116 |      |             | [Link](https://www.intermarche.com/produit/st-marcellin-igp/3250391104116)                                         |
| ![MOZZARELLA DI BUFFALA Picture](<img/product/cheeses/MOZZARELLA DI BUFFALA.png>)                   | MOZZARELLA DI BUFFALA          | 0000099006090 | 0204880000000 |      |             | [Link](https://www.intermarche.com/produit/mozzarella-di-bufala/3760056265316)                                     |
| ![XV DU PIC Picture](<img/product/cheeses/XV DU PIC.png>)                                           | XV DU PIC                      | 0000099031468 | 0206360000000 |      |             | Not found                                                                                                          |
| ![FE CHEVRE FRAIS 115G Picture](<img/product/cheeses/FE CHEVRE FRAIS 115G.png>)                     | FE CHEVRE FRAIS 115G           | 0000019278690 | 3358150002120 |      |             | [Link](https://www.intermarche.com/produit/fromage-de-chevre-frais-12%25-mg/3358150002120)                         |
| ![DEMI BRILLAT SAVARIN AFFINE Picture](<img/product/cheeses/DEMI BRILLAT SAVARIN AFFINE.png>)       | DEMI BRILLAT SAVARIN AFFINE    | 0000099041870 | 0204560000000 |      |             | [Link](https://www.intermarche.com/produit/brillat-savarin-moule-a-la-louche-affine-40%25-mg/3296651111937)        |
| ![ST MARCELLIN CERAMIQUE Picture](<img/product/cheeses/ST MARCELLIN CERAMIQUE.png>)                 | ST MARCELLIN CERAMIQUE         | 3266360612018 | 3266360612018 |      |             | Not found                                                                                                          |
| ![RIGOTTE DE CONDRIEU AOP Picture](<img/product/cheeses/RIGOTTE DE CONDRIEU AOP.png>)               | RIGOTTE DE CONDRIEU AOP        | 0000099041876 | 0204620000000 |      |             | Not found                                                                                                          |
| ![QUATRE VENTS Picture](<img/product/cheeses/QUATRE VENTS.png>)                                     | QUATRE VENTS                   | 0000099021317 | 0204650000000 |      |             | [Link](https://www.intermarche.com/produit/languedoc-la-clape-aop-vin-blanc-sec-cuvee-des-4-vents/3760176170156)   |
| ![FE ROCAMADOUR AOP 2X35G Picture](<img/product/cheeses/FE ROCAMADOUR AOP 2X35G.png>)               | FE ROCAMADOUR AOP 2X35G        | 0000019026725 | 3428380002549 |      |             | [Link](https://www.intermarche.com/produit/rocamadour-aop/3428380002549)                                           |
| ![CHEVRE FRAIS AUX FLEURS Picture](<img/product/cheeses/CHEVRE FRAIS AUX FLEURS.png>)               | CHEVRE FRAIS AUX FLEURS        | 0000099041850 | 0204370000000 |      |             | [Link](https://www.intermarche.com/produit/fromage-de-chevre-la-pyramide/3250390749332)                            |
| ![LE CHEVROT NU 200G Picture](<img/product/cheeses/LE CHEVROT NU 200G.png>)                         | LE CHEVROT NU 200G             | 0000043439409 | 2663700000000 |      |             | Not found                                                                                                          |
| ![P&C STE MAURE TOURAINE AOP250G Picture](<img/product/cheeses/P&C STE MAURE TOURAINE AOP250G.png>) | P&C STE MAURE TOURAINE AOP250G | 0000043439400 | 2663715000000 |      |             | [Link](https://www.intermarche.com/produit/sainte-maure-de-touraine-aop-au-lait-cru/3250391420797)                 |
| ![FE VIVALDI BURRATA 200G Picture](<img/product/cheeses/FE VIVALDI BURRATA 200G.png>)               | FE VIVALDI BURRATA 200G        | 0000999211445 | 8002461872419 |      |             | [Link](https://www.intermarche.com/produit/burrata-di-bufala/8002461872525)                                        |
| ![YAOURT NATURE MERE RICHARD     Picture](<img/product/cheeses/YAOURT NATURE MERE RICHARD.png>)     | YAOURT NATURE MERE RICHARD     | 0000099043122 | 0000000000197 |      |             | [Link](https://www.intermarche.com/produit/yaourt-a-la-grecque-nature/3250392060015)                               |
| ![FE MOZZA DI BUFALA BONBON 200G Picture](<img/product/cheeses/FE MOZZA DI BUFALA BONBON 200G.png>) | FE MOZZA DI BUFALA BONBON 200G | 0000019076830 | 2663760000000 |      |             | [Link](https://www.intermarche.com/produit/mozzarella-di-latte-di-bufala/8000430900231)                            |
| ![FE P&C 1/2REBLOCHON AOP LC250G Picture](<img/product/cheeses/FE P&C 1/2REBLOCHON AOP LC250G.png>) | FE P&C 1/2REBLOCHON AOP LC250G | 0000043434095 | 2873981000000 |      |             | [Link](https://www.intermarche.com/produit/reblochon-de-savoie-aop/3294580201019)                                  |
| ![BUCHE DE CHEVRE                Picture](<img/product/cheeses/BUCHE DE CHEVRE.png>)                | BUCHE DE CHEVRE                | 0000099006105 | 0205000000000 |      |             | [Link](https://www.intermarche.com/produit/buche-de-chevre/3250392551407)                                          |
| ![FE BURRATA DE CHEVRE 120G      Picture](<img/product/cheeses/FE BURRATA DE CHEVRE 120G.png>)      | FE BURRATA DE CHEVRE 120G      | 0000019969645 | 3417881210577 |      |             | [Link](https://www.intermarche.com/produit/burrata-cœur-ricotta/3760056266078)                                     |
| ![BRIQUE CENDREE                 Picture](<img/product/cheeses/BRIQUE CENDREE.png>)                 | BRIQUE CENDREE                 | 0000099041298 | 0204040000000 |      |             | Not found                                                                                                          |
| ![FROMAGE DE CHEVRE FERMIER X2   Picture](<img/product/cheeses/FROMAGE DE CHEVRE FERMIER X2.png>)   | FROMAGE DE CHEVRE FERMIER X2   | 0000099090403 | 0000000000176 |      |             | [Link](https://www.intermarche.com/produit/crottin-de-chavignol-fermier/3542430036114)                             |
| ![1/2M ABONDANCE LC AOP 4K5/5KG  Picture](<img/product/cheeses/1/2M ABONDANCE LC AOP 4K5/5KG.png>)  | 1/2M ABONDANCE LC AOP 4K5/5KG  | 0000043439380 | 2663664000000 |      |             | [Link](https://www.intermarche.com/produit/abondance-au-lait-cru-aop/3250391408818)                                |
| ![P&C SELLES/CHER AOP 150G       Picture](<img/product/cheeses/P&C SELLES/CHER AOP 150G.png>)       | P&C SELLES/CHER AOP 150G       | 0000043439405 | 2663704000000 |      |             | [Link](https://www.intermarche.com/produit/fromage-de-chevre-selles-sur-cher-aop/3250391046331)                    |
| ![TOMME AUX FLEURS               Picture](<img/product/cheeses/TOMME AUX FLEURS.png>)               | TOMME AUX FLEURS               | 0000099006095 | 0204930000000 |      |             | Not found                                                                                                          |
| ![MOZZARELLA DI BUFALA TRESSE    Picture](<img/product/cheeses/MOZZARELLA DI BUFALA TRESSE.png>)    | MOZZARELLA DI BUFALA TRESSE    | 0000099006154 | 3770007325617 |      |             | [Link](https://www.intermarche.com/produit/mozzarella-di-bufala-campana-aop/3250391053322)                         |
| ![COMTE EXTRA AOP 18M 1/8 5KG    Picture](<img/product/cheeses/COMTE EXTRA AOP 18M 1/8 5KG.png>)    | COMTE EXTRA AOP 18M 1/8 5KG    | 0000019665927 | 2843295000000 |      |             | [Link](https://www.intermarche.com/produit/comte-aop-fort-des-rousses-18m/3542860952244)                           |
| ![P&C CHABICHOU AOP 150G         Picture](<img/product/cheeses/P&C CHABICHOU AOP 150G.png>)         | P&C CHABICHOU AOP 150G         | 0000043439396 | 2663703000000 |      |             | [Link](https://www.intermarche.com/produit/chabichou-du-poitou-aop/2663703000000)                                  |
| ![FE PLATEAU 3 FROMAGES 190G     Picture](<img/product/cheeses/FE PLATEAU 3 FROMAGES 190G.png>)     | FE PLATEAU 3 FROMAGES 190G     | 0000019453295 | 3492847279003 |      |             | [Link](https://www.intermarche.com/produit/3-fromages-rapes/3250391901746)                                         |
| ![CABECOU PERIGORD CAISSE 12X35G Picture](<img/product/cheeses/CABECOU PERIGORD CAISSE 12X35G.png>) | CABECOU PERIGORD CAISSE 12X35G | 0009919362340 | 2891829000000 |      |             | [Link](https://www.intermarche.com/produit/cabecou-du-perigord-fromage-de-chevre-au-lait-pasteurise/3305510066629) |
| ![APERITIF BQ LAIT CRU VACHE     Picture](<img/product/cheeses/APERITIF BQ LAIT CRU VACHE.png>)     | APERITIF BQ LAIT CRU VACHE     | 0000099026567 | 3760081251155 |      |             | Not found                                                                                                          |
| ![COUPE FROMAGE LS               Picture](<img/product/cheeses/COUPE FROMAGE LS.png>)               | COUPE FROMAGE LS               | 0000000000016 | 0000000000016 |      |             | [Link](https://www.intermarche.com/produit/comte-fromage-a-pate-presse-cuite-affine-9-mois-minimum/2663571000000)  |
| ![GORGONZOLA A LA CUILLERE       Picture](<img/product/cheeses/GORGONZOLA A LA CUILLERE.png>)       | GORGONZOLA A LA CUILLERE       | 0000099006089 | 0204870000000 |      |             | [Link](https://www.intermarche.com/produit/gorgonzola-aop-'a-la-louche'/2843303000000)                             |
| ![FIGOU                          Picture](img/product/cheeses/FIGOU.png)                            | FIGOU                          | 0000099041453 | 0204160000000 |      |             | Not found                                                                                                          |
| ![SAINT DOMNIN A LA LAVANDE      Picture](<img/product/cheeses/SAINT DOMNIN A LA LAVANDE.png>)      | SAINT DOMNIN A LA LAVANDE      | 0000099041858 | 0204440000000 |      |             | Not found                                                                                                          |
| ![BRIE DE MEAUX                  Picture](<img/product/cheeses/BRIE DE MEAUX.png>)                  | BRIE DE MEAUX                  | 0000099041848 | 0204350000000 |      |             | [Link](https://www.intermarche.com/produit/brie-de-meaux-aop/2663500000000)                                        |
| ![FE PARMI REGG AOP COPEAUX 100G Picture](<img/product/cheeses/FE PARMI REGG AOP COPEAUX 100G.png>) | FE PARMI REGG AOP COPEAUX 100G | 0000043434033 | 8001868003129 |      |             | [Link](https://www.intermarche.com/produit/parmigiano-reggiano-aop-en-copeaux/8002461871832)                       |
| ![ENROBE AIRELLES 80G            Picture](<img/product/cheeses/ENROBE AIRELLES 80G.png>)            | ENROBE AIRELLES 80G            | 0000043439092 | 2663695000000 |      |             | [Link](https://www.intermarche.com/produit/l'enrobe-airelles-frais-emballe/3417881212274)                          |
| ![PARMIGIANO REGG AOP 24M 4.5KG  Picture](<img/product/cheeses/PARMIGIANO REGG AOP 24M 4.5KG.png>)  | PARMIGIANO REGG AOP 24M 4.5KG  | 0000019950665 | 2831292000000 |      |             | [Link](https://www.intermarche.com/produit/parmigiano-reggiano-aop/3250391989959)                                  |
| ![MOTHAIS SUR FEUILLE            Picture](<img/product/cheeses/MOTHAIS SUR FEUILLE.png>)            | MOTHAIS SUR FEUILLE            | 0000099041844 | 0204310000000 |      |             | Not found                                                                                                          |
| ![MORBIER AOP 100J 1/2M 3K5      Picture](<img/product/cheeses/MORBIER AOP 100J 1/2M 3K5.png>)      | MORBIER AOP 100J 1/2M 3K5      | 0000019849086 | 2843995000000 |      |             | [Link](https://www.intermarche.com/produit/morbier-aop/2663662000000)                                              |
| ![LOU PERAC PERAIL BREBIS 150G   Picture](<img/product/cheeses/LOU PERAC PERAIL BREBIS 150G.png>)   | LOU PERAC PERAIL BREBIS 150G   | 0000043439450 | 2663709000000 |      |             | [Link](https://www.intermarche.com/produit/la-brique-pur-brebis/3023260031017)                                     |
| ![*MASCARPONE GORGONZOLA 1.2KG  Picture](<img/product/cheeses/MASCARPONE GORGONZOLA 1.2KG.png>)     | \*MASCARPONE GORGONZOLA 1.2KG  | 0000024389388 | 2824730000000 |      |             | [Link](https://www.intermarche.com/produit/torta-gorgonzola-mascarpone/2663725000000)                              |
| ![GALLETOUT                      Picture](img/product/cheeses/GALLETOUT.png)                        | GALLETOUT                      | 0000099041511 | 0204170000000 |      |             | Not found                                                                                                          |
| ![BURRATA                        Picture](img/product/cheeses/BURRATA.png)                          | BURRATA                        | 0000099008081 | 0205070000000 |      |             | [Link](https://www.intermarche.com/produit/burrata/3250392341695)                                                  |
| ![FE CAMEMBERT PYRO ISIGNY 250G  Picture](<img/product/cheeses/FE CAMEMBERT PYRO ISIGNY 250G.png>)  | FE CAMEMBERT PYRO ISIGNY 250G  | 0000019118070 | 3254550030193 |      |             | [Link](https://www.intermarche.com/produit/camembert-au-lait-cru/3254550039639)                                    |
| ![FE CAMEMBERT LAIT CRU AOP 250G Picture](<img/product/cheeses/FE CAMEMBERT LAIT CRU AOP 250G.png>) | FE CAMEMBERT LAIT CRU AOP 250G | 0000043439007 | 2663503000000 |      |             | [Link](https://www.intermarche.com/produit/camembert-de-normandie-au-lait-cru-aop/3252950012016)                   |
| ![RACLETTE                       Picture](img/product/cheeses/RACLETTE.png)                         | RACLETTE                       | 0000099009832 | 0205160000000 |      |             | Not found                                                                                                          |
| ![GRAND MORIN A LA TRUFFE D'ETE  Picture](<img/product/cheeses/GRAND MORIN A LA TRUFFE D'ETE.png>)  | GRAND MORIN A LA TRUFFE D'ETE  | 0000099041288 | 0204030000000 |      |             | Not found                                                                                                          |
| ![ST NECTAIRE FERMIER            Picture](<img/product/cheeses/ST NECTAIRE FERMIER.png>)            | ST NECTAIRE FERMIER            | 0000099041837 | 0204240000000 |      |             | [Link](https://www.intermarche.com/produit/saint-nectaire-fermier-aop-29%25-mg/2829856000000)                      |
| ![EMMENTAL LT CRU 27% 10KG Picture](<img/product/cheeses/EMMENTAL LT CRU 1/8M 27%25 10KG.png>)      | EMMENTAL LT CRU 1/8M 27% 10KG  | 0009919782641 | 2839008000000 |      |             | [Link](https://www.intermarche.com/produit/emmental-francais-est-central-grand-cru-label-cru/0212224000000)        |
| ![GRUYERE FRANCE IGP 5K5         Picture](<img/product/cheeses/GRUYERE FRANCE IGP 5K5.png>)         | GRUYERE FRANCE IGP 5K5         | 0009919667068 | 2843122000000 |      |             | [Link](https://www.intermarche.com/produit/gruyere-rape-igp-france/3250390547372)                                  |
| ![*L'ENROBE ABRICOT 80G         Picture](<img/product/cheeses/L'ENROBE ABRICOT 80G.png>)            | \*L'ENROBE ABRICOT 80G         | 0000024447157 | 2849441000000 |      |             | Not found                                                                                                          |
| ![FE FETA GRECQUE AOP 180G       Picture](<img/product/cheeses/FE FETA GRECQUE AOP 180G.png>)       | FE FETA GRECQUE AOP 180G       | 0000019443461 | 5202425001128 |      |             | [Link](https://www.intermarche.com/produit/feta-grecque-aop/3250391226078)                                         |
| ![LE SAUVAGET                    Picture](<img/product/cheeses/LE SAUVAGET.png>)                    | LE SAUVAGET                    | 0000099006094 | 0204920000000 |      |             | Not found                                                                                                          |
| ![VAGNE COMTE 9/12MOIS 1/8M 5KG  Picture](<img/product/cheeses/VAGNE COMTE 5KG.png>)                | VAGNE COMTE 9/12MOIS 1/8M 5KG  | 0000043439327 | 2663571000000 |      |             | [Link](https://www.intermarche.com/produit/comte-aop-9-mois-d'affinage/2257156000000)                              |
| ![COMTE 12 MOIS                  Picture](<img/product/cheeses/COMTE 12 MOIS.png>)                  | COMTE 12 MOIS                  | 0000099041350 | 0204080000000 |      |             | [Link](https://www.intermarche.com/produit/comte-le-montarlier-aop-affine-12-mois/3228021200156)                   |
| ![BEAUFORT PTPERCE AOP 1/12M 3K5 Picture](<img/product/cheeses/BEAUFORT PTPERCE AOP 3K5.png>)       | BEAUFORT PTPERCE AOP 1/12M 3K5 | 0009943439268 | 2890729000000 |      |             | [Link](https://www.intermarche.com/produit/abondance-au-lait-cru-aop/3250391408818)                                |
| ![COURONNE LOCHOISE              Picture](<img/product/cheeses/COURONNE LOCHOISE.png>)              | COURONNE LOCHOISE              | 0000099041420 | 0204130000000 |      |             | Not found                                                                                                          |
| ![P&C ST NECTAIRE LAITIE AOP 1K7 Picture](<img/product/cheeses/P&C ST NECTAIRE LAITIE AOP 1K7.png>) | P&C ST NECTAIRE LAITIE AOP 1K7 | 0009943439221 | 2890801000000 |      |             | [Link](https://www.intermarche.com/produit/saint-nectaire-laitier-aop/3250392493936)                               |
| ![FE BRILLAT SAVARIN IGP 200G    Picture](<img/product/cheeses/FE BRILLAT SAVARIN IGP 200G.png>)    | FE BRILLAT SAVARIN IGP 200G    | 0000019248513 | 3296651111937 |      |             | [Link](https://www.intermarche.com/produit/brillat-savarin-moule-a-la-louche-affine-40%25-mg/3296651111937)        |
| ![FE HALLOUMI AOP 225G           Picture](<img/product/cheeses/FE HALLOUMI AOP 225G.png>)           | FE HALLOUMI AOP 225G           | 0000024454373 | 3760280680817 |      |             | [Link](https://www.intermarche.com/produit/halloumi-aop/3760280680817)                                             |
| ![*PICODON AOP 60G              Picture](<img/product/cheeses/PICODON AOP 60G.png>)                 | \*PICODON AOP 60G              | 0009919915032 | 2844180000000 |      |             | Not found                                                                                                          |
| ![FE EPOISSES AOP 250G           Picture](<img/product/cheeses/FE EPOISSES AOP 250G.png>)           | FE EPOISSES AOP 250G           | 0000043439171 | 2663495000000 |      |             | [Link](https://www.intermarche.com/produit/epoisses-aop/3250392142032)                                             |
| ![P&C MORBIER AOP LC 6K5         Picture](<img/product/cheeses/P&C MORBIER AOP LC 6K5.png>)         | P&C MORBIER AOP LC 6K5         | 0000043439334 | 2663661000000 |      |             | [Link](https://www.intermarche.com/produit/morbier-au-lait-cru-aop/3250391160785)                                  |
| ![GP CANTAL JEUNE LAIT CRU AOP5K Picture](<img/product/cheeses/GP CANTAL JEUNE LAIT CRU AOP5K.png>) | GP CANTAL JEUNE LAIT CRU AOP5K | 0009919362372 | 2891827000000 |      |             | [Link](https://www.intermarche.com/produit/cantal-jeune-au-lait-cru-aop/2663688000000)                             |
| ![TOMME CAZELLES BREBIS 4.4ENV   Picture](<img/product/cheeses/TOMME CAZELLES BREBIS 4.4ENV.png>)   | TOMME CAZELLES BREBIS 4.4ENV   | 0000019749800 | 2843639000000 |      |             | [Link](https://www.intermarche.com/produit/tomme-du-pays-basque/3023260030515)                                     |
| ![TOMME DE MONTAGNE CHARTREUSE   Picture](<img/product/cheeses/TOMME DE MONTAGNE CHARTREUSE.png>)   | TOMME DE MONTAGNE CHARTREUSE   | 0000099006097 | 0204950000000 |      |             | [Link](https://www.intermarche.com/produit/tomme-fruitee/3176580111546)                                            |
| ![OLIVES DE NYONS                Picture](<img/product/cheeses/OLIVES DE NYONS.png>)                | OLIVES DE NYONS                | 0000099041877 | 0204630000000 |      |             | [Link](https://www.intermarche.com/produit/olives-de-nyons-noires/3250392400927)                                   |
| ![PETIT POT CREME CHOCOLAT       Picture](<img/product/cheeses/PETIT POT CREME CHOCOLAT.png>)       | PETIT POT CREME CHOCOLAT       | 0000099011577 | 3483130046402 |      |             | [Link](https://www.intermarche.com/produit/petit-pot-de-creme-au-chocolat/3250390803409)                           |
| ![P'TIT BASQUE PUR BREBIS 660G   Picture](<img/product/cheeses/P'TIT BASQUE PUR BREBIS 660G.png>)   | P'TIT BASQUE PUR BREBIS 660G   | 0000043439455 | 2663545000000 |      |             | [Link](https://www.intermarche.com/produit/fromage-p'tit-basque-pur-brebis/2663545000000)                          |
| ![REBLOCHON FERMIER AOP          Picture](<img/product/cheeses/REBLOCHON FERMIER AOP.png>)          | REBLOCHON FERMIER AOP          | 0000099041875 | 0204610000000 |      |             | [Link](https://www.intermarche.com/produit/saint-nectaire-fermier-aop-29%25-mg/2829856000000)                      |
| ![ITCHEBAI CHEVRE&BREBIS 4K5     Picture](<img/product/cheeses/ITCHEBAI CHEVRE&BREBIS 4K5.png>)     | ITCHEBAI CHEVRE&BREBIS 4K5     | 0000024105511 | 2831762000000 |      |             | Not found                                                                                                          |
| ![PICHOLINES NATURES             Picture](<img/product/cheeses/PICHOLINES NATURES.png>)             | PICHOLINES NATURES             | 0000099060024 | 0204690000000 |      |             | [Link](https://www.intermarche.com/produit/olives-picholines-vertes/3250391686698)                                 |
| ![FE P&C CHAOURCE AOP 250G       Picture](<img/product/cheeses/FE P&C CHAOURCE AOP 250G.png>)       | FE P&C CHAOURCE AOP 250G       | 0000043434115 | 3250391105335 |      |             | [Link](https://www.intermarche.com/produit/chaource-aop/3250391105335)                                             |
| ![PELISSONNE D'ARDECHE           Picture](<img/product/cheeses/PELISSONNE D'ARDECHE.png>)           | PELISSONNE D'ARDECHE           | 0000099041839 | 0204260000000 |      |             | Not found                                                                                                          |
| ![TOMME DE TARENTAISE            Picture](<img/product/cheeses/TOMME DE TARENTAISE.png>)            | TOMME DE TARENTAISE            | 0000099041838 | 0204250000000 |      |             | [Link](https://www.intermarche.com/produit/tomme-noire-des-pyrenees-igp/3250391231621)                             |
| ![COMTE 24 MOIS                  Picture](<img/product/cheeses/COMTE 24 MOIS.png>)                  | COMTE 24 MOIS                  | 0000099041352 | 0204100000000 |      |             | [Link](https://www.intermarche.com/produit/comte-extra-vieux-24-mois-aop/2843291000000)                            |
| ![COMTE VAGNE AOP 18 MOIS 5KG    Picture](<img/product/cheeses/COMTE VAGNE AOP 18 MOIS 5KG.png>)    | COMTE VAGNE AOP 18 MOIS 5KG    | 0000043439371 | 2663568000000 |      |             | [Link](https://www.intermarche.com/produit/comte-prestige-affinage-18-mois-minimum-aop-35%25-mg/2843637000000)     |
| ![BROCCIU FRAIS FERMIER AOP      Picture](<img/product/cheeses/BROCCIU FRAIS FERMIER AOP.png>)      | BROCCIU FRAIS FERMIER AOP      | 0000099052839 | 3429881511936 |      |             | Not found                                                                                                          |
| ![PETIT POT CREME CAFE           Picture](<img/product/cheeses/PETIT POT CREME CAFE.png>)           | PETIT POT CREME CAFE           | 0000099011579 | 3483130046419 |      |             | [Link](https://www.intermarche.com/produit/petit-pot-de-creme-cafe/3483130046419)                                  |
| ![ROITELET BRIE 3,150KG          Picture](<img/product/cheeses/ROITELET BRIE 3,150KG.png>)          | ROITELET BRIE 3,150KG          | 0000043439010 | 2663499000000 |      |             | [Link](https://www.intermarche.com/produit/petit-brie/3250390344674)                                               |
| ![PAVE DU LARZAC                 Picture](<img/product/cheeses/PAVE DU LARZAC.png>)                 | PAVE DU LARZAC                 | 0000099006092 | 0204900000000 |      |             | [Link](https://www.intermarche.com/produit/pave-daffinois-l'original/3307907100084)                                |
| ![PETIT POT CREME CARAMEL        Picture](<img/product/cheeses/PETIT POT CREME CARAMEL.png>)        | PETIT POT CREME CARAMEL        | 0000099011576 | 3483130046426 |      |             | Not found                                                                                                          |

The database above could be too heavy for Bubble standards. Therefore, a selection for the most selled cheeses would be displayed according to the data provided by Intermarché. \
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

| Image | Product Name                   | ITM8          | EAN           | Tags | Taste | Description | Links |
| ----- | ------------------------------ | ------------- | ------------- | ---- | ----- | ----------- | ----- |
|       | IGP ALPILLES ROSE TRADITION    | 3760076070020 | 0000099056669 |      |       |             |       |
|       | VAL DE L OULE ROSE TENDRESSE   | 3435600000216 | 0000099037387 |      |       |             |       |
|       | GRAND MAS DE LANSAC BLAN       | 3760059140030 | 0000099016142 |      |       |             |       |
|       | IGP VAR GRIS GRIS DE ROSE      | 3760146021815 | 0000099005260 |      |       |             |       |
|       | GRAND MAS LANSAC ROSE          | 3760059140023 | 0000099016143 |      |       |             |       |
|       | AOP FOLIE EN PROVENCE 2023 COT | 3760092070349 | 0000099064698 |      |       |             |       |
|       | LANSAC ROSE 5L                 | 3760059140078 | 0000099016147 |      |       |             |       |
|       | LAGOY VIN ROSE IGP ALPILLES BI | 3760063300321 | 0000099010236 |      |       |             |       |
|       | LE GRIS MAS MARIGNAN           | 3538650074333 | 0000099066408 |      |       |             |       |
|       | LUBERON LES CLAPES             | 3760028200048 | 0000099060230 |      |       |             |       |
|       | ROSE CUVEE EVIDENCE MAS LANSAC | 3760059140184 | 0000099012318 |      |       |             |       |
|       | IGP ROSE ETOILE DES ALPILLES   | 3760251190161 | 0000099035796 |      |       |             |       |
|       | TRADITION 2023 AOP BIO         | 3760025420012 | 0000099016911 |      |       |             |       |
|       | GRAND MAS DE LANSAC RGE        | 3760059140108 | 0000099063709 |      |       |             |       |
|       | AOP BIO PASSE-ROSE 2024 750ML  | 3760025420029 | 0000099016912 |      |       |             |       |
|       | ETOILE DES ALPILLES IGP BLANC  | 3760251190154 | 0000099037189 |      |       |             |       |
|       | ALPILLES IGP TRADITION BLANC   | 3760076070037 | 0000099056670 |      |       |             |       |
|       | IGP TERRE CAMARGUE RS BIO75CL  | 3545440120149 | 0000029500338 |      |       |             |       |
|       | IGP ALPILLES BIO TRADITION 202 | 3760025420036 | 0000099016913 |      |       |             |       |
|       | ALPILLES IGP TRADITION ROUGE   | 3760076070013 | 0000099056662 |      |       |             |       |
|       | MAS GOURGONNIER ROUGE TRADITIO | 3760104593026 | 0000099024947 |      |       |             |       |
|       | COTES DU VENTOUX DOMAINE DE GO | 3760146021914 | 0000099032673 |      |       |             |       |
|       | PROSECCO SPUMANTE DOC BOTTER   | 8008863011081 | 0000099030361 |      |       |             |       |
|       | MAS DE LA DAME RESEVE DU RGE   | 3464725107517 | 0000099016137 |      |       |             |       |
|       | IGP MEDITERRANNEE TERRES DE BO | 3760171263181 | 0000099067489 |      |       |             |       |
|       | MAS DAME LA GOURMANDE ROSE     | 3464722207517 | 0000099028421 |      |       |             |       |
|       | VENTOUX SECRET DE TRUFFE ROUGE | 3700026507640 | 0000099040655 |      |       |             |       |
|       | VCE BLANC VALRIAN 25 CL X 6    | 3250392151645 | 0000052335025 |      |       |             |       |
|       | VIN ESPAGNE BLC VALRIAN3X25CL  | 3250390488828 | 0000052335010 |      |       |             |       |
|       | CUVEE GOURMANDE ROUGE          | 3464721107511 | 0000099024028 |      |       |             |       |
|       | R.MAZET IGPOC RGE MERLOT 75CL  | 3175520018655 | 0000052337510 |      |       |             |       |
|       | LUBERON LES CLAPES             | 3760028200161 | 0000099037518 |      |       |             |       |
|       | IGP CTE TARN BLC MOEL.EC75CL   | 3250390207634 | 0000052338035 |      |       |             |       |
|       | IGP ALPILLES ROSE CUVEE EVIDEN | 3760059140153 | 0000099038691 |      |       |             |       |
|       | VAL DE L OULE ROSE TENDRESSE   | 3435600000216 | 0000099037387 |      |       |             |       |
|       | MAS GOURGONNIER BLANC TRADITIO | 3760104593224 | 0000099024945 |      |       |             |       |
|       | LANSAC ROUGE 5L                | 3760059140061 | 0000099016145 |      |       |             |       |
|       | IGP VAR 100% ROLLE             | 3760146021754 | 0000099012664 |      |       |             |       |
|       | CDR SEGURET VILLAGES 2021      | 3341332013137 | 0000099040700 |      |       |             |       |
|       | IGP TER.MIDI RS GRAINS LISTEL  | 3244081500005 | 0000029499905 |      |       |             |       |
|       | IGP VAR MISS GRIS              | 3760146023659 | 0000099032690 |      |       |             |       |
|       | AOC 2021 LES TROIS ORATOIRES C | 3760012970506 | 0000099041482 |      |       |             |       |
|       | IGP T.CAMARGUE BLC BIO 75CL    | 3545440130148 | 0000029500339 |      |       |             |       |
|       | TERRES ET LUMIeRES VENTOUX BLA | 3760033100081 | 0000099003837 |      |       |             |       |
|       | IGP ROUGE FRISSON VAL DE L'OUL | 3435600000230 | 0000099036806 |      |       |             |       |
|       | VENTOUX ROSE 1911 LEGENDE 75CL | 3760106128462 | 0000099089046 |      |       |             |       |
|       | IGP ROUGE CUVEE ALPILLES BIO 2 | 3760063300628 | 0000099010235 |      |       |             |       |
|       | MAS DE LA DAME ROSE DU MAS     | 3464723207516 | 0000099016135 |      |       |             |       |
|       | LANSAC BLANC 5L                | 3760059140085 | 0000099016148 |      |       |             |       |
|       | VAL DE L'OULE ROUGE EMOTION    | 3435600000209 | 0000099037386 |      |       |             |       |
|       | COTES DE PROVENCE CŒUR ROSE    | 3760057981154 | 0000099020444 |      |       |             |       |
|       | LAGOY VIN ROSE 5L              | 3760063300352 | 0000099051061 |      |       |             |       |
|       | AOP CAB.ANJOU RS EX.CLUB 75CL  | 3250390261735 | 0000052344335 |      |       |             |       |
|       | IGP ROSE ETOILE DES ALPILLES   | 3760251190161 | 0000099035796 |      |       |             |       |
|       | BORDEAUX CHaTEAU MARQUIS DES B | 3259354143001 | 0000099031283 |      |       |             |       |
|       | COTEAUX VAROIS LES RESTANQUES  | 3760146023567 | 0000099013634 |      |       |             |       |
|       | DOMAINE DE LAGOY BIO 2023      | 3760063300024 | 0000099013439 |      |       |             |       |
|       | IGP HERAULT RGE E.CLUB75CL     | 3250390051534 | 0000052337100 |      |       |             |       |
|       | COTES DU RHONE PERRIN ROUGE    | 3296180000160 | 0000099005112 |      |       |             |       |
|       | IGPOC CIN.GRENACH RS R.MAZET75 | 3175520018686 | 0000052339397 |      |       |             |       |
|       | IGP OC CAB SAUV RG CX PIN 75CL | 3250390801078 | 0000052337602 |      |       |             |       |
|       | VAL DE L'OULE BLANC PLAISIR    | 3435600000223 | 0000099037388 |      |       |             |       |
|       | AOP PETIT CHABLIS BL EXP CLUB  | 3250392362898 | 0000017468346 |      |       |             |       |
|       | IGP OC GRIS DES LAUNES         | 3392120003533 | 0000099002256 |      |       |             |       |
|       | COTES DU RHONE RGE GUIGAL      | 3536650501002 | 0000017376801 |      |       |             |       |
|       | VAL DE L'OULE ROSE DESIR       | 3435600000032 | 0000099088812 |      |       |             |       |
|       | IGP OC MERLOT RSE XPIN 75CL    | 3250392336707 | 0000017410880 |      |       |             |       |
|       | IGP OC SAUVIGNON BL CX PIN 75  | 3250390800996 | 0000052338202 |      |       |             |       |
|       | AOP CHABLIS BLC EXPERT CLUB 75 | 3250391594993 | 0000017058346 |      |       |             |       |
|       | AOP CTE RHONE RGE TRADITION 75 | 3410280017815 | 0000052341015 |      |       |             |       |
|       | MAS GOURGONNIER ROSE TRADITION | 3760104593125 | 0000099024946 |      |       |             |       |
|       | IGP VAR DOMAINE DE PELISSE - C | 3760146021358 | 0000099005261 |      |       |             |       |
|       | IGP DES MAURES CUVEE ANE VOLAN | 3760057981192 | 0000099023011 |      |       |             |       |
|       | IGP TERRE CAMARGUE ROUGE 75CL  | 3545440110140 | 0000029500337 |      |       |             |       |
|       | COTES DU RHONE PRESTIGE LE SER | 3700025909339 | 0000099006929 |      |       |             |       |
|       | MAS DE LA DAME LA STELE BLANC  | 3464720001001 | 0000099016133 |      |       |             |       |
|       | AOP CTE RHONE RG JOANNES75     | 3410280017792 | 0000052341010 |      |       |             |       |
|       | IGPOC RG O.CAMBRAS CAB SAUV 75 | 3211203420039 | 0000017110890 |      |       |             |       |
|       | AOP BOURG.ALIGOTE EX.CLUB 75CL | 3250390167075 | 0000052346261 |      |       |             |       |
|       | LE GRIS MAS MARIGNAN PRESTIGE  | 3770016080224 | 0000099020195 |      |       |             |       |
|       | AOP CDR PRESTIGE RG 75CL       | 3179071000978 | 0000052341245 |      |       |             |       |
|       | LE MAS BLANC MARIGNANE         | 3538650007058 | 0000099073088 |      |       |             |       |
|       | COTES DU RHONE PERRIN BLANC    | 3296180000177 | 0000099005113 |      |       |             |       |
|       | IGP MED PLAISIR BLANC          | 3760092070110 | 0000099035255 |      |       |             |       |
|       | VAL DE L'OULE ROUGE SEDUCTION  | 3435600000049 | 0000099088813 |      |       |             |       |
|       | AOP MACON VILL.BL EX.CLUB 75CL | 3250391325245 | 0000052346051 |      |       |             |       |
|       | COTES DE PROVENCE DOMAINE LES  | 3760255430058 | 0000099087646 |      |       |             |       |
|       | COTES DU RHONE SAINTE ROCHE    | 3344392118408 | 0000099003282 |      |       |             |       |
|       | MAS DAME LA GOURMANDE BLANC    | 3464724307512 | 0000099016136 |      |       |             |       |
|       | VCE ROUGE VALRIAN 12 1,5L      | 3250391786909 | 0000052334210 |      |       |             |       |
|       | IGP HERAULT ROSE 75CL          | 3250390145349 | 0000052339100 |      |       |             |       |
|       | AOP CTE PROV. BERNE GD RECOLTE | 3760033590028 | 0000017410177 |      |       |             |       |
|       | AOC VENTOUX MOT DEXCUSE 2020 R | 3760028200314 | 0000099035453 |      |       |             |       |
|       | AOC CDR RESERVE ROUGE GRAND CH | 3365385001545 | 0000099066251 |      |       |             |       |
|       | MAS DE LA DAMELA STELE RGE     | 3464726107516 | 0000099016138 |      |       |             |       |
|       | BANDOL DOMAINE L'OLIVETTE ROSE | 3458301571120 | 0000099032689 |      |       |             |       |
|       | AOP COST.NIME.RG.E.CLUB 75CL   | 3250390261797 | 0000052340033 |      |       |             |       |
|       | IGP MED ROSE STUD MIRAVAL      | 3296180007794 | 0000999221454 |      |       |             |       |
|       | BIB ROSE TERRE DE CAMARGUE REY | 3545441020417 | 0000099022053 |      |       |             |       |
|       | MAS SAINTE BERTHE LA CHAPELLE  | 1212121212121 | 1212121212121 |      |       |             |       |

---

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

#### Meals

---

For this application, the main page would display meal cards which would be predefined and regional specialities. You can find the selection hereunder:

|         Meal Name         |                                           Picture                                            |                                                              Meal description                                                               |
| :-----------------------: | :------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
|         Anchoïade         |              <img alt="Anchoiade" src="./img/meal/anchoiade.png" width="200px">              |          A savory dip made from anchovies, garlic, olive oil, and sometimes capers, typically served with raw vegetables or bread.          |
|           Aïoli           |                  <img alt="aioli" src="./img/meal/aioli.png" width="200px">                  |                 A garlic mayonnaise often served with vegetables, fish, or hard-boiled eggs, central to Provençal cuisine.                  |
|  Tomate à la Provençale   | <img alt="Tomate a la Provencale" src="./img/meal/tomate_a_la_provencale.png" width="200px"> |                            Tomatoes baked with herbs, garlic, and breadcrumbs—an aromatic and simple side dish.                             |
|       Bouillabaisse       |          <img alt="Bouillabaisse" src="./img/meal/bouillabaisse.png" width="200px">          | A traditional fish stew from Marseille made with various local fish, shellfish, and a flavorful broth, served with rouille sauce and bread. |
| Ratatouille de Saint-Rémy |     <img alt="Ratatuoille de Saint-Remy" src="./img/meal/ratatouille.png" width="200px">     |              A slow-cooked vegetable medley of eggplant, zucchini, peppers, tomatoes, and herbs, originating from Saint-Rémy.               |
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

This application will allow user to search for wine or cheese with a search bar, as explained in the [Mockups](#mockups) section.

Therefore, some tags have been defined and classified into subcategories which are:

- Wine
- Cheese
- Accompaniement
- Label
- Season

Those tags can be access within the "add tags" button. Moreover, every product description page would have tags associated with them. Learn more about it in [Product Description Page](#product-description-page).

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

| Name   | Definition                                                                                                                                                     |
| ------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Spring | A season for light, fresh wines such as Sauvignon Blanc, Pinot Grigio, and young rosés that pair well with seasonal vegetables and mild weather.               |
| Summer | Ideal for chilled, refreshing wines like rosé, sparkling wines, and crisp whites (e.g., Riesling, Albariño), often paired with light meals and outdoor dining. |
| Autumn | A transitional season favoring fuller whites and lighter reds such as Chardonnay, Pinot Noir, or Grenache, complementing richer harvest foods.                 |
| Winter | Best suited for bold, warming reds like Cabernet Sauvignon, Syrah, or fortified wines such as Port, often served with hearty dishes.                           |

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

And the percentage of alcohol for wines.

**Tags**:

In this section will be a list of all the tags corresponding to the Product. They will be displayed in a row.

**Suggestions**:

As the application should be a recommemdation one, two meals will be displayed as suggestion for the product. Allowing users to mix their product better and have the best experience possible. \
The two meals would be displayed only if they are predifined in the database. However, the application is a proof of concept, therefore, some data could be missing. Consequently, this section could be empty. \
In the case of an empty section, the section would be hidden/removed for the product only.

**Taste**:

This section would only be present for wines.

It will be composed of three bars showing the different taste of the wine. They would be sorted like following:

- Salt/Fat
- Sweetness/Spice
- Bitterness/Acidity

**Where to find it**:

This section would be a procedure to find the product within the grocery store. This could be done thanks to our client and a system that they already have implemented.

**Labels**:

This section will hold every labels the product have. They would also be displayed as tags. However, they would be more described and the full name would be written, unlike tags.

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
> As you might have noticed, BiteMatch is a login-free application, meaning the user doesn't need to login to use the application.

---

## Non-Functional Requirements

### Performance

---

Our product would be used into the Intermarché grocery store of Saint-Rémy-De-Provence. The loading time should be short and the application intuitive for the users not to lose time.

However, our application still need to be loaded into the client device, at least once, so they could have access to the entire database. The user should not download the application data everytime they use the application but only the forst time, so the loading time would be greatly reduced afterwards.

In other words:

- The first time the application is loaded, it should take at most 10 sec.
- The next usages would take less than a second to load the entire application.

---

### Connectivity

---

The application should be usable without any internet connection. It would avoid losing people who do not possessed any connection within the building. \
However, we are forced to used connection at least once to download all the database into the users' device. \
To avoid this problem we thought of using the free connection offered by Intermarché.

Once the application would be fully loaded, an internet connection won't be necessary anymore.

---

### Responsiveness

---

This application is designed for mobile devices, since it would be used mainly inside Intermarché. We assume people don't go shopping with their laptop.

However, our application should be usable for every operating system and on the main screen sizes. \
Therefore, th epllication would be developed on the main screensize spread sround the world which is 360x800px. It would also be usable on the range of 350 to 375 pixel width.

---

### Marketing

---

As none of the team members are part of a marketing role or had any marketing experience, this section won't be really enhanced. \
However, the application could be downloaded via a QRcode on a basic poster or sign, that could be displayed at the entrance of the building and at both sides of the related departments.

The team also rely on Intermarché's staff and marketing team to promote the application the best they could.

---

## Glossary

<!-- TODO: Find all the words that could be missinterpreted or unknown by the most common one. Create a table gathering all of them. Create html tags for every one of them and link them so you can go back and forth the glossary in one click. -->

---
