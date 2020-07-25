<h1>
  Assessment: Accessibility Troubleshooting
</h1>
  
<h2 id="table-of-contents">Table of contents</h2>

* [Introduction](#introduction)
* [Features](#features)
* [Launch](#launch)
* [Screenshots](#screenshots)
* [Technologies](#technologies)

<h2 id="introduction">Introduction</h2>

This is a repository of my (Jose Nicolas Mora) completion of the [MDN Accessibility Troubleshooting Assessment](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Accessibility_troubleshooting).

In this project we are presented with a fictional nature site displaying an article about bears. The original webpage has multiple accessibility issues, and my task was to explore the existing site and fix several of them.

The website was tested for accessibility using the [NVDA screenreader tool](https://www.nvaccess.org).

Check out my [LinkedIn](https://linkedin.com/in/nicolas-mora-a54245105/)

<h2 id="features">Features</h2>

The accessibility improvements include:
- Improved color contrast
  - I also added a better, more suitable color scheme.
- More semantic html tags.
- Skip to main content link.
- More accessible images with alt text and figure tags.
- Text representation of text file to make audio player more accessible to screenreader users.
- The audio player is now more accessible to users that are using older browsers that dont support HTML5 audio.
- The input element in the search form now has label only accessible to screenreaders.
- The two <input> elements in the comment form have better labels.
- Show/hide comment control button is now key-board accessible.
- Comments are tabbable to improve screenreader accessibility.
- Table is now more accessible to screenreader users.
  - Data rows and columns are better associated.
  - Table summary was added.

<h2 id="launch">Launch</h2>

The old webpage is located in the [original-webpage-poor-accessibility folder](./original-webpage-poor-accessibility). Open its [index.html file](./original-webpage-poor-accessibility/index.html) to open it.

The new webpage is located in the [improved-webpage-better-accessibility folder](./improved-webpage-better-accessibility). [Visit the deployed webpage](https://nikelausm.github.io/accessibility-exercise/index.html), or open its [index.html file](./improved-webpage-better-accessibility./index.html) to open it.

<h2 id="screenshots">Screenshots</h2>

### Old Webpage With Poor Accessibility
<img src="./original-webpage-poor-accessibility/screenshots/old-webpage-1.png" 
alt="Screenshot of nature site showing the main header level 1, navbar, and the sections: 'The trouble with Bears', 'Types of bear', data table about bears, and first half of 'Habitats and Eating habits'. It also shows the 'Related' section showing a list of links to relevant articles.">
<img src="./original-webpage-poor-accessibility/screenshots/old-webpage-2.png" 
alt="Screenshot of nature site showing the 'Habitats and Eating habits section.">
<img src="./original-webpage-poor-accessibility/screenshots/old-webpage-3.png" 
alt="Screenshot of nature site showing the following sections: 'Mating rituals', audio player, 'About the author'. It also shows the hide comment button.">
<img src="./original-webpage-poor-accessibility/screenshots/old-webpage-4.png" 
alt="Screenshot of nature site after pressing the 'Show comments' button, showing that the button now says 'Hide comments'. Below the button is the expanded 'Add comment' form, and the section showing the comments made. The screenshot also shows the footer.">

### New Webpage With Better Accessibility
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-1.PNG" 
alt=Screenshot of nature site showing the main header level 1, navbar, and the sections: 'The trouble with Bears', and 'Types of bear'. It also shows the 'Related Articles' section showing a list of links to relevant articles.">
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-2.PNG" 
alt="Screenshot of nature site showing the data table, and the first half of the 'Habitats and Eating habits' section, incuding an image of a brown bear in a river.">
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-3.PNG" 
alt="Screenshot of nature site showing the second half of the 'Habitats and Eating habits' section including black and white image of a bear in a cage.">
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-4.PNG" 
alt="Screenshot of nature site showing the following sections: 'Mating rituals section', audio player, 'Show transcript' button, 'About the author', 'show comments' button, and the footer.">
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-5.PNG" 
alt="Screenshot of nature site after the 'Show transcript button' was pressed, showing that the button now says 'Hide transcript', and below the button is the transcript of the audio file.">
<img src="./improved-webpage-better-accessibility/screenshots/improved-webpage-6.PNG" 
alt="Screenshot of nature site after pressing the 'Show comments' button, showing that the button now says 'Hide comments'. Below the button is the expanded 'Add comment' form and the section showing the comments made. The screenshot also shows the footer">

<h2 id="technologies">Technologies</h2>

- HTML5
- CSS3
- Javascript
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Coolors.co color scheme generator](https://coolors.co)
- [NVDA Screenreader Tool](https://www.nvaccess.org) 
