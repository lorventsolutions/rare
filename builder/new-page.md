# New Page

Blank.html

we have to create new pages in `src/pages/`

It has the following Structure:

**Clear explanation for above structure,**

1. : With this we can get which type of layout from`macros/layout.html`through command like `gulp nunjucks --layoutname --bc`
2. \`

   `: by using`title`variable we can set title of the page and we can call variable`\`in required layout.

3. \`

   `: by using`page`variable we can set active page and we can call variable`\` in left menu.

4. \`

   `: by using`bc\_icon`variable we can set breadcrumb icon of the page and we can call variable`\` in Breadcrumb icon.

5. \`

   `: by using`breadcrumb\` variable we can set breadcrumb links of the page.

6. \`

   \`

7. : With this we can get which type of breadcrumb from `macros/breadcrumb.html` through command like `gulp nunjucks --layoutname --bcnumber(0 to 5).`

