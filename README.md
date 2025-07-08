<h1 align=center>Hugo PaperFlow | <a href="https://0ky.github.io/hugo-PaperFlow/" rel="nofollow">Demo</a></h1>

<h4 align=center>⚡ Fast | ☁️ Fluent | 🌊 Smooth | 📱 Responsive</h4>
<br>

> Hugo PaperFlow is a fork of [PaperMod](https://github.com/adityatelange/hugo-PaperMod) that's based on [hugo-paper](https://github.com/nanxiaobei/hugo-paper/tree/4330c8b12aa48bfdecbcad6ad66145f679a430b3).<br>
> The goal of this project is to add more features and customization.

<!-- **Documentation** can be found here: [**📚 Wiki**](https://github.com/0Ky/hugo-PaperFlow/wiki) -->

<!-- **ExampleSite** can be found here: [**exampleSite**](https://github.com/0Ky/hugo-PaperFlow/tree/exampleSite). Demo is built up with [exampleSite](https://github.com/0Ky/hugo-PaperFlow/tree/exampleSite) as source. -->

<p align="center">
  <kbd><img src="https://user-images.githubusercontent.com/21258296/114303440-bfc0ae80-9aeb-11eb-8cfa-48a4bb385a6d.png" alt="Mockup image" title="Mockup"/></kbd>
</p>

<h1 align=center>🥇 Lighthouse Score</h1>

<p align="center">
  <a href="https://pagespeed.web.dev/report?url=https://0ky.github.io/hugo-PaperFlow/&form_factor=desktop">
    <img width="700" alt="Lighthouse Score" src="PageSpeed-Insights.svg">
  </a>
</p>

## ✨ Features/Mods

-   Uses Hugo's asset generator with pipelining, fingerprinting, bundling and minification by default.
-   3 Modes:
    -   [Regular Mode.](https://github.com/0Ky/hugo-PaperFlow/wiki/Features#regular-mode-default-mode)
    -   [Home-Info Mode.](https://github.com/0Ky/hugo-PaperFlow/wiki/Features#home-info-mode)
    -   [Profile Mode.](https://github.com/0Ky/hugo-PaperFlow/wiki/Features#profile-mode)
-   Table of Content Generation (newer implementation).
-   Archive of posts.
-   Social Icons (home-info and profile-mode).
-   Social-Media Share buttons on posts.
-   Menu location indicator.
-   Multilingual support. (with language selector).
-   Taxonomies.
-   Cover image for each post (with Responsive image support).
-   Light/Dark theme (automatic theme switch a/c to browser theme and theme-switch button).
-   SEO Friendly.
-   Multiple Author support.
-   Search Page with Fuse.js
-   Other Posts suggestion below a post
-   Breadcrumb Navigation.
-   Code Block Copy buttons.
-   Hugo's Chroma syntax highlighter.
-   No webpack, nodejs and other dependencies are required to edit the theme.

<!-- Read Wiki For More Details => **[PaperMod - Features](https://github.com/0Ky/hugo-PaperFlow/wiki/Features)** -->

## 👷 Installation

### New Hugo Site

1. Create a new Hugo site (using YAML configuration format):
   ```
   hugo new site MyBlog --format yml
   cd MyBlog
   ```

2. Start a new project with Git:
   ```
   git init
   ```

3. Edit `hugo.yml` file and add `theme: hugo-PaperFlow` to use the theme.
   Note: It's recommended to use the [`config.yml`](https://github.com/0Ky/hugo-PaperFlow/blob/master/exampleSite/config.yml) file from the example site as a starting point for your configuration.

4. Add your first content:
   ```
   hugo new posts/my-first-post.md
   ```

5. Install the theme (choose one):

   5.1. Clone the repo:
        ```
        git clone https://github.com/0Ky/hugo-PaperFlow.git themes/hugo-PaperFlow
        ```

   5.2. Git submodule:
   ```
   git submodule add https://github.com/0Ky/hugo-PaperFlow.git themes/hugo-PaperFlow
   git submodule update --init --recursive
   ```

6. Start the local development server:
   ```
   hugo server -D
   ```

## 👷 Contributing

Contributions are welcome and encouraged! This Hugo theme is a community-driven project and all kinds of improvements are appreciated, whether you're working on new features, bug fixes, styling updates, accessibility improvements, optimization, documentation or contents in the `exampleSite`.

You can contribute by:

#### ✨ Adding new features or layout components
#### 🐞 Fixing bugs or compatibility issues
#### 🖋 Updating or expanding the documentation
#### 🧪 Improving or restructuring the `exampleSite` (demo) content
#### 🎨 Enhancing design, responsiveness or accessibility
#### 🧰 Creating blog posts, tutorials or integration guides
#### 🧹 Refactoring code or improving performance

### Getting Started
1. [Fork](https://github.com/0Ky/hugo-PaperFlow/fork) the repository.
2. Create a new branch for your changes.
3. Make your changes or additions in the codebase.
4. Test thoroughly using the `exampleSite` by running `hugo server --source exampleSite`.
5. Submit a pull request with a clear description of what you've changed and why.

<!-- Read Wiki For More Details => **[PaperMod - Installation](https://github.com/0Ky/hugo-PaperFlow/wiki/Installation)** -->

<!-- ---

## FAQs / How To's Guide 🙋

Read Wiki For More Details => **[PaperMod-FAQs](https://github.com/0Ky/hugo-PaperFlow/wiki/FAQs)** -->

<!-- ---

## Social-Icons/Share-Icons 🖼️

Read Wiki For More Details => **[PaperMod-Icons](https://github.com/0Ky/hugo-PaperFlow/wiki/Icons)** -->

## 📃 Release Changelog

Release ChangeLog has info about stuff added: **[Releases](https://github.com/0Ky/hugo-PaperFlow/releases)**

## 🫶 Support

-   Star 🌟 this repository.
-   Help spread the word about PaperFlow by sharing it on social media and recommending it to your friends. 🗣️
-   You can also sponsor 🏅 on [Github Sponsors](https://github.com/sponsors/0Ky)<!-- / [Ko-Fi](https://ko-fi.com/adityatelange)-->.

## 🌟 Special Thanks

-   [**Nán Xiǎo Běi**](https://github.com/nanxiaobei/hugo-paper)
-   [**Aditya Telange**](https://github.com/adityatelange/hugo-PaperMod)
-   [**Highlight.js**](https://github.com/highlightjs/highlight.js)
-   [**Fuse.js**](https://github.com/krisk/fuse)
-   [**Feather Icons**](https://github.com/feathericons/feather)
-   [**Simple Icons**](https://github.com/simple-icons/simple-icons)
-   **All Contributors and Supporters**

<!-- ## Stargazers over time 📈

[![Stargazers over time](https://starchart.cc/0Ky/hugo-PaperFlow.svg?background=%23ffffff00&axis=%23858585&line=%236b63ff)](https://starchart.cc/0Ky/hugo-PaperFlow) -->
