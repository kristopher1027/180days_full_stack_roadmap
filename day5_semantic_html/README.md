# Semantic HTML
* Semantic HTML means using HTML tags that clearly describe the meaning and purpose of the content to both the browser and the developer. Instead of building a page entirely out of generic wrappers like <div> or <span> (which say nothing about what's inside), you choose tags based on what the content actually is.

# 🔄 Semantic vs. Non-Semantic HTML

* Non-Semantic Elements: ```<div class="footer"> or <span class="heading">.``` They have no built-in meaning; they are just blank boxes used for styling or layout.
* Semantic Elements: ``` <footer> or <h1> ``` They instantly communicate their exact purpose to browsers, search engines, and assistive devices.

 ## 🏛️ Core Structure Elements (HTML5 Landmarks)

> Most modern websites use these semantic tags to lay out their primary page structure:
> Tag	Purpose	Best Practice
* ```<header>```	Introductory content, logos, or site-wide top bar.	Can be used multiple times (e.g., inside articles).
* ```<nav>```	A dedicated block containing the main navigation links.	Reserved for primary navigation menus.
* ```<main>```	The unique, central content of that specific page.	Only one visible <main> allowed per page.
* ```<section>```	A standalone, thematic grouping of content.	Should almost always include a heading  ```(<h2>-<h6>)```
* ```<article>```	Independent, self-contained content (e.g., blog post, news story).	Content should make sense even if syndicated elsewhere.
* ```<aside>```	Sidebars or callout boxes tangentially related to the main text.	Great for pull quotes, ads, or related article links.
* ```<footer>```	Bottom of a page or section containing copyright, legal, or contact info.	Placed at the very end of its parent container.


