# Installation

The following steps demonstrate how to use portfolYOU as **GitHub Pages remote theme**.

1. \[Download\]\[download\] portfolYOU as .zip from official \[repo\]\[repo\] then extract it.
2. Rename **`portfolYOU-master/`** to **`<your-username>.github.io/`**
3. Remove everything **except** the **`docs/`** directory.
4. Lift up the **`docs/`** directory's content to the root directory _\(i.e move them to **`<your-username>.github.io/`**\)_.
5. Remove **documentation** stuff:
   * **`_elements/`**
   * **`documentation/`**
   * **`_config.yml`** : any line commented as `# For Documentation Only`
6. Your directory structure should be:

   ```text
    <your-username>.github.io/
    ├── _data/
    ├── _posts/
    ├── _projects/
    ├── pages/
    ├── _config.yml
    ├── .gitignore
    └── Gemfile
   ```

7. Update **`_config.yml`** with your data _\(follow the comments for more help\)_.
8. Update your site content \(posts, projects and about page\).
9. Finally, test portfolYOU [locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) then [publish](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/) it to [GitHub Pages](https://pages.github.com/).
10. _\[Optional\]_ To use a specific \[version\]\[versions\] of portfolYOU _\(defaults to latest version\)_:

    ```text
     remote_theme: YoussefRaafatNasry/portfolYOU@v1.0.0
    ```

\[repo\]:  \[download\]:  \[versions\]: 

