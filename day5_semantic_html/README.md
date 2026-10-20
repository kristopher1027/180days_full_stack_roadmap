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

> Here is a complete, categorical reference list of the most important semantic HTML tags and exactly what they communicate to browsers, search engines, and screen readers.

### 🧱 Layout & Structure Elements

1. These tags define the structural bones of your page, replacing generic layout <div> elements.
* `**: Defines a container for introductory content, logos, navigation, or introductory headers.
*  ```<nav>:``` Blocks out a set of primary navigation links.
* ```<main>:``` Identifies the primary, dominant content unique to that single document. (Only one allowed per page).
* `**: Groups related content together into a distinct theme or chapter.
* ```<article>:``` Encloses a completely self-contained piece of content that could be distributed independently (e.g., a blog post, interactive widget, or product card).
* ```<aside>:``` Identifies content that is tangentially related to the main content (e.g., sidebars, advertising blocks, or callout notes).
* ```<footer>:``` Marks the footer section of a page or individual section, typically holding copyright information, site maps, or contact links.

### 📝 Text & Inline Element Meanings

2. These tags give specific context to the words and characters inside your paragraphs.
* ```<h1> to <h6>:``` Establishes a strict structural hierarchy of topics. ```<h1> is the main topic; <h2> through <h6> represent sub-topics.```
* ```<em>:``` Applies linguistic stress emphasis to a word or phrase, changing the vocal meaning of the sentence.
* ```<strong>:``` Marks text of crucial, urgent importance, high priority, or seriousness.
* ```<mark>:``` Highlights text to show its relevance in a specific context or search result (like a physical highlighter marker)
* ```<time>:``` Converts human text into a machine-readable date/time string using the datetime attribute.


