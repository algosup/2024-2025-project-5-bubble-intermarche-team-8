# BiteMatch - README <!-- omit in toc -->

This repository contains every document about BiteMatch, an application suggesting Cheeses and Wines.

---

## Definition <!-- omit in toc -->

BiteMatch is a mobile application created on Bubble. It was requested by Intermarché Saint-Rémy-de-Provence, France. \
This application allows the consumer to search for a specific wine/cheese directly from the application. It also allows them to test new traditional meals via predefined meal cards on the home page. Each of them is linked to 2 or 3 wines and cheeses.

> **Technical Architecture**: The app is built with [Bubble](https://bubble.io) and wrapped for mobile using [MobiLoud Canvas](https://mobiloud.com), making it compatible with Android 13+ and iOS 17+.

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Status](#status)
- [Usage](#usage)
  - [How to Find a Specific Wine/Cheese](#how-to-find-a-specific-winecheese)
  - [How to Find the Perfect Match for a Traditional Meal](#how-to-find-the-perfect-match-for-a-traditional-meal)
- [Installing/Getting Started](#installinggetting-started)
- [Roadmap](#roadmap)
- [Documentation of the Project](#documentation-of-the-project)
- [Development](#development)
  - [Built With](#built-with)
  - [Prerequisites](#prerequisites)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License \& Copyrights](#license--copyrights)
- [Contacts](#contacts)
- [Credits and Acknowledgement](#credits-and-acknowledgement)

---

## Status

This project is currently evolving and will be improved regularly until June 20. After this date, updates will be less frequent.

However, we invite you to help us contribute to this project! \
If you are interested, please refer to the [Contributing](#contributing) part.

---

## Usage

### How to Find a Specific Wine/Cheese

1. Open the application
2. Write the name of your product in the Searchbar.
3. Scroll until you find the intended references.

You have found your wine/cheese, you can now look for more detailed information or find it in store.

> [!NOTE]
>
> - On the main page, you can filter your research with Tags and by budget.
> - On the description page, you can find information about:
>
>   - Tags.
>   - Location.
>   - Origin.
>   - Price.
>   - Taste (for wine).
>   - Labels.

> [!NOTE]
>
> - The search bar supports tag-based filtering (e.g., by taste, occasion, dietary constraints).
> - The recommendation engine uses metadata stored in a structured Bubble database and is executed via Bubble Workflows.

---

### How to Find the Perfect Match for a Traditional Meal

1. Open the application.
2. Click on the Meal card of your choice.
3. Click on the wine tab for wines.
4. Click on the wine you want.

You are now on the description page of the wine you want to buy.

> [!NOTE]
> The user can click on the cheese tab to select a cheese.

> [!NOTE]
> Matches are generated dynamically based on dish tags using visual workflows in Bubble (Workflow D: Tag-Based Pairing).

---

## Installing/Getting Started

1. Clone the repository.

   ```bash
   git clone https://github.com/algosup/2024-2025-project-5-bubble-intermarche-team-8
   ```

2. Navigate to the directory.

   ```bash
   cd 2024-2025-project-5-bubble-intermarche-team-8
   ```

3. Navigate to the src folder.

   ```bash
   cd src
   ```

4. Access the application.

<!-- ---

The application is available with the following code:

E-mail: <> \
Password: \ -->

> [!NOTE]
> Bubble applications are web-hosted. Installation for local development is not applicable. The repository mainly contains documentation and assets.

---

## Roadmap

The Roadmap of this project can be find in the [Management Atrifacts](./documents/management/management_artifacts.md#tasks-and-schedule). \
This Roadmap is an estimation of the time that will take the project to be accomplished. The team will fit to it as much as possible. However, in case delays happen, please refer to the Actual Schedule in the same document to see the actual schedule.

---

## Documentation of the Project

**[Functional Specifications](./documents/functional_specification/functional_specification.md)**: Describes what the software does by outlining user requirements and expected functionalities.

**[Technical Specifications](./documents/technical_specification/technical_specification.md)**: Details how the software will be built, including architecture, design, and technology choices.

**[Project Charter](./documents/management/project_charter.md)**: Officially initiates the project by defining its scope, objectives, stakeholders, and overall framework.

**[Test Plan](./documents/quality_assurance/test_plan.md)**: Outlines the strategy, procedures, and criteria for verifying that the system meets its requirements.

---

## Development

### Built With

This project was built with [Bubble.io](https://bubble.io), a no-code visual development platform. It combines frontend UI design, backend workflows, and database management in a unified environment.

> - **Frontend**: Bubble UI Builder (drag-and-drop)
> - **Logic**: Bubble Workflow Engine (conditional and sequential logic)
> - **Database**: Bubble DB (non-relational, key-value structure)
> - **Localization**: Localize.js plugin integration
> - **Mobile Bundling**: Wrapped using MobiLoud Canvas

---

### Prerequisites

- A **Bubble account** (Free Tier is sufficient)
- No programming skills required, but knowledge of visual app-building and workflows is recommended.

> [!TIP]
> This project uses **Localize Translation Plugin** and **Feather Icons Plugin**. Refer to the [Technical Specifications](./documents/technical_specification/technical_specification.md#33-bubble-plugins-used) for details.

---

## Contributing

To contribute to our project, follow the conventions written in the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

> [!IMPORTANT]
> Contributors must follow [Bubble naming conventions](./documents/technical_specification/conventions.md) and use defined reusable styles (`styles.md`) for UI consistency.

---

## Changelog

**Latest**: NULL \
**Curren**t: NULL \
**Version List**: [Click to view](https://github.com/algosup/2024-2025-project-5-bubble-intermarche-team-8/tags)

> [!NOTE]
> Versioning follows **Semantic Versioning** (`MAJOR.MINOR.PATCH`). Deployment changes are handled via Bubble’s built-in version manager and MobiLoud configuration dashboard.

---

## License & Copyrights

You can refer the license of the project at the root of the project, within the [LICENSE.md file](./LICENSE.md).

**Ownership:** Intermarché Saint-Rémy-de-Provence and ALGOSUP

**Copyright Notice:** © 2025 Intermarché Saint-Rémy-de-Provence and ALGOSUP. All rights reserved.

---

## Contacts

To contact our project team. Please, send a message to the following E-mails:

- Project Manager's E-mail: NOT DEFINED
- Program Manager's E-mail: <maxime.thizeau@algosup.com>

For other social media information, please, refer to [Credits and Acknowledgement](#credits-and-acknowledgement).

---

## Credits and Acknowledgement

Particular thanks to Célia Moustier and Chrys Cadeau from [Intermarché Saint-Rémy-de-Provence](https://www.intermarche.com/magasins/12499/saint-remy-de-provence-13210/infos-pratiques?srsltid=AfmBOop0EEl1kweuAi-_Wl8ZxZtGECSZVctJ-8clQ7uBjUKJHChK17Nd) for giving us the opportunity to work on this project.

Thanks to our school, [ALGOSUP](https://algosup.com/en.html) for letting us improve and having such interesting projects.

Finally, thanks to all the team members for those nine weeks. \
You can find their profiles underneath.

| Role                               | Name            | Contact                                                                                                                 |
| ---------------------------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Project Manager & Technical Leader | Antoine PREVOST | [GitHub](https://github.com/TechXplorerFR) \| [LinkedIn](https://www.linkedin.com/in/antoine-prevost-dev/?locale=fr_FR) |
| Program Manager                    | Maxime THIZEAU  | [GitHub](https://github.com/MaximeTAlgosup) \| [LinkedIn](https://www.linkedin.com/in/maxime-thizeau-0b311a293/)        |
| Software Engineer                  | Pavlo PRENDI    | [GitHub](https://github.com/PavloPrendi) \| [LinkedIn](https://www.linkedin.com/in/pavlo-prendi/)                       |
| Quality Assurance                  | Mariem ZAIANE   | [GitHub](https://github.com/Mariem-Zaiane) \| [LinkedIn](https://www.linkedin.com/in/mariem-zaiane/)                    |

[Back to the top](#bitematch---readme)
