# Pages

1. Add `page-name.html` or `page-name.md` to `pages/`, `new subfolder` or to `root directory` of your project.
2. Add [front matter](https://jekyllrb.com/docs/front-matter/) to the top of your new page.

   ```yaml
    ---
    layout: default
    title: Page Name
    permalink: /page_permalink/ (the output path for the page)
    weight: 2 (the order of the page in the navigation bar)
    ---
   ```

3. The new page will be added to the navigation bar automatically.
4. Check more pages templates from [here](https://github.com/abraham-musa/abraham-musa.github.io/tree/dadde2be32a9641fc6386bd290e88fdffa9e0c4c/documentation/partials/04-adding-content/%7B%7B%20site.github.repository_url%20%7D%7D/tree/master/docs/pages/README.md).

