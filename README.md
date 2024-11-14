# **Project Structure**

This outlines a well-organized folder structure for managing websites. This approach promotes code reusability, simplifies maintenance, and enhances project clarity.

```

global/
    css/
        global.css
        header.css
    javascript/
        global.js
        header.js
    data/
        ...
    images/
        ...
pages/
    index/
        local-css/
            ...
        local-javascript/
            ...
        data/
            ...
    about/
        local-css/
            about.css
        local-javascript/
            about.js
        data/
            ...
        images/
            ...
        about.html
resources/
    css/
        ...
    javascript/
        ...
    fonts/
        font.tff
        font.woff
.gitignore
index.html
README.md

```

## **global**

* **css:** Contains global CSS stylesheets that apply to the entire website.
* **data:** Contains data files (e.g., JSON) for reusable components or modules.
* **images:** Stores images used across multiple pages or reusable components.
* **javascript:** Contains global JavaScript files that are used across multiple pages.

## **pages**

* **contact_form:** This directory holds specific files related to the contact form page, including:
  * **data:** Contains data files (e.g., JSON) for the contact form.
  * **local-css:** Contains CSS stylesheets specific to the contact form page.
  * **local-javascript:** Contains JavaScript files specific to the contact form page.
  * **form.html:** The main HTML file for the contact form page.

## **index**

* **data:** Contains data files (e.g., JSON) for the index page.
* **local-css:** Contains CSS stylesheets specific to the index page.
* **local-images:** Stores images used specifically on the index page.
* **local-javascript:** Contains JavaScript files specific to the index page.

## **resources**

* **css:** Contains CSS stylesheets for librarys or frameworks.
* **fonts:** Stores custom fonts used throughout the project.
* **javascript:** Contains JavaScript files for librarys or frameworks.

## **Additional Files**

* **.gitignore:** Specifies files and directories to be ignored by Git.
* **index.html:** The main HTML file for the project.
* **README.md:** This file! Provides an overview of the project sort of a documantation for the project.

## **Notes**

* The `global` directory is for assets that are used across the entire project.
* The `pages` directory is for assets specific to individual pages.
* The `resources` directory is for reusable components and modules.
* This structure promotes modularity and makes it easier to maintain and update the project.

By adopting this structure, you'll enhance your static website development experience and maintain a well-organized and manageable codebase.

## **for a project that needs even more organizing you can use numbers easily to keep everything in order**

This proposes a meticulous folder structure for websites, enhancing organization and maintainability.

**Core Folder Structure:**

```

00-global/
    01-css/
        01-01-global.css
        01-02-header.css
        01-03-footer.css
    02-javascript/
        02-01-global.js
        02-02-header.js
        01-03-footer.js
    03-data/
        ...
    04-images/
        ...
01-pages/
    01-index/
        01-css/
            01-01-index.css
        02-javascript/
            02-01-index.js
        03-data/
            ...
        04-images/
            ...
    02-about/
        01-css/
            01-01-about.css
        02-javascript/
            02-01-about.js
        03-data/
            ...
        04-images/
            ...
        05-about.html
02-resources/
    01-css/
        ...
    02-javascript/
        ...
    03-fonts/
        02-01-font.tff
        02-02-font.woff

.gitignore
index.html
README.md

```

**this way you can have even more organized folder structure and always keep everything in the same place**
