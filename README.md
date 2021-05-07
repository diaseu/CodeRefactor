# CodeRefactor

UCI Coding Bootcamp project to refactor code for Horiseon website.
The goal was to improve codebase to follow accessibility standards, as well for long term sustainability.  This includes ensuring that all links are functioning correctly, cleaning up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

<a href="https://diaseu.github.io/CodeRefactor/"><img src="https://i.imgur.com/8a36XJe.jpeg" alt="Screenshot of Revised Website"></a>

## Change Logs

index.html
- Added comment tags to clarify code elements
- Updated META tags in head to include viewport and X-UA-Compatible
- Updated title in head to reflect more accurate website description
- Updated 'header' tag to 'nav' tag to more accurately reflect purpose
- Updated 'section' tags to 'div' tags on line 16, 22 to match CSS
- Updated 'div' tag to 'main' tag on line 29 to more accurately reflect purpose
- Added id to div on line 31 so allow anchor link
- Added 'alt' properties to all img tags
- Updated 'div' tag to 'aside' tag on line 57 to more accurately reflect purpose
- Updated 'div' tag to 'footer' tag on line 85 to more accurately reflect purpose

style.css
- Consolidated duplicate styles for different tags
- Re-ordered all .benefits related CSS to after .search-engine-optimization, .online-reputation-management, .social-media-marketing to match order on site
