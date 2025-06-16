# BiteMatch App - README


## Definition

This document serves to catalog the application's workflow, as there is no GitHub log tracking the development progress—since Bubble is a web-based, no-code development platform that doesn't integrate version control in the traditional way.

## First look

To maintain an efficient workflow, we divided the development phase into three main sections: **visual**, **data capture**, and **technical**. Our initial focus was on building the application according to the functional specifications, which accounted for roughly **55%** of the total project time. The data capture phase involved creating the database for wines, cheeses, and dishes, along with recording option sets such as tags and language support. This phase took about **10%** of the project time. The technical phase, which consumed the remaining **35%**, covered language setup, tag filtering, and implementing precise search functionality. A more detailed breakdown of each component is provided in the section below.

## How it works

Here we will provide a comprehensive guide into how the applications most complicated features function.

> [!NOTE]
> To understand some parts you need some knowledge on how bubble works, if you are unsure please refer to the [technical specifications](https://github.com/algosup/2024-2025-project-5-bubble-intermarche-team-8/blob/main/documents/technical_specification/technical_specification.md).

- **Language function:** The language is implemented using a plugin called [Localize translation](https://localizejs.com/). In order to use the plugin I had to login to their site and by adding **ALGOSUP** as my company I was provided with a 15 day free plan. The site then prompted us to choose two languages and we chose french and greek. After that, it auto translated phrases that we picked. Inside bubble, it was as easy as saying when I click this button, translate the page in this language.
- **Header:** Since the header appears on almost every page we decided to turn it into a **reusable element**. By doing so we saved alot of time and were able to swiftly apply navigation between pages.
- **Search function:** Searching works by entering a value in the search bar which initializes bubble to look through the database and display a result closely to what the value is. This means that if I enter "**ig**" it will display wines that contain those two letters.
- **Filtering by tags:** To filter by tags, we recorded each tag in an **option set**, and then assigned said tags in each wine and cheese inside the database. After that, we implemented a workflow to which when a tag is clicked and the search begins, it checks if the searched value intersects with the applied tag.
- **Recommendations:** The application recommends to you based on which tags intersect with each other between wine and cheese tags and dishes tags.

Everything else is pretty straight forward, meaning that if the information is in the database, then display it.



## Bugs

The app is far from perfect, in fact there two distinct bugs that are recognized by the team but are not fixed due to having reached the deadline of the project. Some of those include:

- **Back button:** Bubble relies heavily on **states**, but these states do not retain information once they are reloaded. In order to retain information we had to save information inside the **URL**. Unfortunately this causes the back button to not work correctly since the "go back to the previous page" workflow only goes back to the URL's previous state, instead of going back to the previous page. There is an easy way to fix this using code, however fixing it without it is more time consuming and complicated so we decided to prioritize other matters.
- **Group flicker upon searching:** The issue here is when searching for something that is not in the database. When you initiate your search, Bubble looks through the database and displays the **default set of data** immidiately, but if it finds nothing it takes half a second and a bit of flickering to display the "**not found**" group which looks quite bad-looking. To fix this, we would've tried to add a state on the page called "**seach completed**" which would control when the database is shown for better visual clarity.

## Future improvements

In order for this application to be finalized there are quite a few things that we would like to polish and improve upon. Some of those will be major, such as:

- Adding **animations** to each sequence of redirection and button clicking 
- **Tag searching**(searching solely through tags without having to enter a wine or cheese name)
- Expanding upon the information of the wine and cheese to include their region and the location to which the customer can locate the product in the store. We will also expand and update our database to more accurately represent the stores individual stock and display which items are available for sale and which aren't.
- **Responsiveness** of the application. So far only a couple of resolution match the best apps appearance, but in the future we will make sure that the app looks it's best on every resolution possible.
- Use a better plugin which does not limit us as much.
- Accompaniment tags are not functional because a database was not provided for them, once there is a database, we will also be able to search for dishes in the searchbar.

---
