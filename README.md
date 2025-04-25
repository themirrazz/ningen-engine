# How I "run" websites on my brain
## Introduction
I started learning the basics of JavaScript and HTML when I was in elementary school (around when I was 7). 10 years later, I've written modern websites that run in Internet Explorer, created an antivirus entirely in JavaScript, and made not only a StudentVUE but also a *Parent*VUE client for Windows 96 (a website that simulates a 9X OS, to the point where it has it's own JavaScript API for writing apps and everything - I recommend trying it out). While the StudentVUE and ParentVUE client didn't last that long (thanks Replit), what did is my knowledge. I've gotten so accustomed to writing in HTML, JavaScript, and CSS that I can "run" websites on my brain.

But how?

## Code is just instructions
Code is just instructions. That's all it is. It tells a computer what to do. In order to write code, you need to understand it. After 10 years of writing JavaScript, I'm now familiar enough with the syntax, as well as the browser APIs, that I can run the code in my head.

## I'm not just pretending to run the code
If you think I'm not actually running it and just have a good understanding of it, then think about what computers do. To run code, computers just follow all the steps in it to create a result. That's what I'm doing. I'm doing the exact same steps as computers are - just with more accurate decimal points. It's like a recipe. If you make a robot that scans a recipe in a recipe book, follows the instructions, and bakes cookies for you, is it just pretending to follow the recipe? Is it pretending to make cookies?

## Compatibility is key
As with all open standards, compatibility is key. Browser engines like Blink, WebKit, Gecko, and Trident - along with the upcoming ones like Ladybird and Servo - all have to agree on a set of standards to make sure websites work across different browsers. Of course, Chrome does add a bunch of non-standard features, just like IE did, but lots of the features that *are* standardized across browsers also work on Chrome. The Web Share API and Web Speech API, normally only available in Chrome and Safari, can be enabled in Firefox. Even the Battery Status API, which was removed from Firefox, can be used in browsers like my own Kyōsuke (which is Firefox-based)!

With that being said, you're probably wondering what level of compatibility I can run websites in my head with.

### HTML
In my head, I can understand all the following HTML elements: `<html>`, `<head>`, `<body>`, `<base>`, `<title>`, `<meta>`, `<link>`, `<style>`, `<script>`, `<noscript>`, `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`, `<p>`, `<pre>`, `<code>`, `<span>`, `<a>`, `<b>`, `<i>`, `<u>`, `<strong>`, `<em>`, `<strike>`, `<font>`, `<sub>`, `<sup>`, `<ul>`, `<ol>`, `<li>`, `<hr>`, `<br>`, `<ruby>`, `<rt>`, `<rp>`, `<img>`, `<svg>`, `<picture>`, `<figure>`, `<figcaption>`, `<video>`, `<audio>`, `<source>`, `<canvas>`, `<iframe>`, `<frame>`, `<embed>`, `<noframes>`, `<div>`, `<section>`, `<header>`, `<footer>`, `<table>`, `<th>`, `<tr>`, `<td>`, `<button>`, `<form>`, `<input>`, `<label>`, `<textarea>`, `<option>`, `<optgroup>`, `<select>`, `<details>`, `<summary>`, `<marquee>`, `<article>`, `<aside>`, `<main>`, `<nav>`, `<blockquote>`, `<s>`, `<small>`, `<big>`, `<wbr>`, `<track>`, `<caption>`, `<fieldset>`, `<legend>`

I can understand these HTML attributes: `href`, `src`, `rel`, `name`, `property`, `value`, `content`, `disabled`, `style`, `class`, `id`, `data-*`, `aria-disabled`, `alt`, `type`, `allow`, `action`, `method`, `min`, `max`, `multiple`, `accept`, `autocapitalize`, `spellcheck`, `formaction`, `maxlength`, `minlength`, `placeholder`, `readonly`, `checked`, `selected`, `required`, `step`, `autocomplete`, `autofocus`, `target`, `title`, `outline`, `border`, `fill`, `color`, `face`, `size`, `width`, `height`

### CSS
I can use these CSS properties: `color`, `background-color`, `background-image`, `background-position`, `background-size`, `background`, `backdrop-filter`, `width`, `height`, `min-width`, `min-height`, `max-width`, `max-height`, `resize`, `user-select`, `pointer-events`, `cursor`, `font-family`, `src`, `font-size`, `font-style`, `content`, `font-weight`, `text-decoration`, `padding`, `margin`, `transition`, `animation`, `animation-*`, `--webkit-animation`, `--webkit-animation-*`, `transform`, `opacity`, `--webkit-opacity`, `scrollbar-width`, `scrollbar-color`, `position`, `top`, `left`, `bottom`, `right`, `display`, `flex-direction`, `flex-grow`, `flex-shrink`, `justify-content`, `align-items`, `text-direction`, `text-align`, `fill`, `outline`, `border`, `border-color`, `border-style`, `border-width`, `border-*-color`, `border-*-style`, `border-*-width`, `border-radius`, `border-*-*-radius`, `text-shadow`, `z-index`, `perspective`, `overflow`, `overflow-x`, `overflow-y`, `visibility`, `box-shadow`

### JavaScript
I can use most ES2020 syntax, and I can do both client-side (browser) and server-side (Node.js) JavaScript.

For server-side, I only really support the packages `fs`, `fs.promises`, and `http` (mostly because those are my most used packages).

For client-side, I support the following properties of the `navigator` object: `navigator.userAgent`, `navigator.mediaDevices`, `navigator.mediaSession`, `navigator.platform`, `navigator.vendor`, `navigator.appName`, `navigator.appCodeName`, `navigator.doNotTrack`, `navigator.globalPrivacyControl`, `navigator.getBattery()`, `navigator.geolocation`, `navigator.share()`, `navigator.canShare()`, `navigator.permissions`, `navigator.honorifics`, `navigator.requestMIDIAccess()`\*, `navigator.clipboard`, `navigator.onLine`, `navigator.connection`, `navigator.deviceMemory`, `navigator.contacts`, `navigator.cookieEnabled`, `navigator.javaEnabled()`, `navigator.language`, `navigator.languages`, `navigator.pdfViewerEnabled`, `navigator.serviceWorker`, `navigator.webdriver`, `navigator.virtualKeyboard`, `navigator.xr`\*, `navigator.standalone`, `navigator.mimeTypes`, `navigator.plugins`, `navigator.product`, `navigator.setAppBadge()`*, `navigator.clearAppBadge()`\*, `navigator.getAutoplayPolicy()`\*, `navigator.vibrate()`

I officially support the Battery Status API, Web MIDI API, Web Share API, Web Vibrations API, Geolocation API, Autoplay Policy API, Web Contacts API, Media Devices API, Media Session API, Clipboard API, WebXR API*, and Connection Status API. I also support Web Workers (including Service Workers).

I also support WebExtensions (`.ngx` for **N**in**G**en e**X**tension) for specific popular APIs (`tabs`, `history`, `bookmarks`, etc.)

### Python
I can do basic Python syntax.

### Ignore Errors
I can run JavaScript even after critical errors - including syntax errors.

### Mixed Scripts
Using a **N**in**G**en **M**ixed script (.ngm), you can combine client-side code, WebExtensions, Node.JS, HTML, and Python in one giant file. What is the purpose? I don't know. PHP can be inserted in `.ngm` files, but it'll be ignored.
