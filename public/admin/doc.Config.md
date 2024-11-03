- @file doc.Config.md
- @description This file provides an explanation of the Category section within the admin documentation.
  Can be difficult to add, When require new Carogry add new catogory in `\src\data\categories.ts` and `\public\admin\config.yml` in `Category` `label` in `options` add new catogry. Editing Catogry is not recommended as you will need to edit that catogery in all posts manually once postd

- @fileoverview This file contains the configuration settings for the admin documentation.
-
- Tags:
- - Explain Tags: A placeholder for explaining the tags used in the configuration file.
    Can easily add when writing post in domain.com/admin

- This file contains the configuration for the documentation page.
-
- Index:
- - Use `#` for main heading
- - Use `##` for main subheading
- - Use `###` for subheading for main subheading
- - Continue with more `#` for deeper levels of headings
-
- These headings will be displayed as a table of contents on the left side of the page.

- `package.json`

  - change github repo link to your repo link

- `astro.config.mjs`

  - change site link to your website link

- `/src/data/categories.ts`

  - edit/add your categories

- `/src/data/disqus.config.ts`

  - enable/disable disqus comments

- `/src/data/site.config.ts`

  - enable/disable disqus comments

- `/src/content/config.ts`

  - schema for posts

- `/src/components/Header.astro`

  - schema for posts

- `/public/robot.txt`

  - edit link to your website sitemap

- `/public/favicon.svg`

  - change your website home page logo

- `/public/admin/config.yml`
  - schema for creating posts using netlify CMS
