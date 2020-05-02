# Skills Categories

1. Add `category_name-skills.yml` to `_data/`.
2. Add skills to the file using the previously mentioned method.
3. Open `pages/about.md`.
4. Add the following lines to the skills section between `<div class="row">` and `</div>`:

```text
{% raw %}{% include about/skills.html title="Category_Name Skills" source=site.data.category_name-skills %}{% endraw %}
```

