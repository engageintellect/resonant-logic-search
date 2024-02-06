---
collectionId: "9ktkng9a95n6199"
collectionName: "pages"
content: "<p><strong>Tailwind CSS</strong> is an <a title=\"Open source\" href=\"https://en.wikipedia.org/wiki/Open_source\">open source</a> <a title=\"CSS\" href=\"https://en.wikipedia.org/wiki/CSS\">CSS</a> <a title=\"CSS framework\" href=\"https://en.wikipedia.org/wiki/CSS_framework\">framework</a>. The main feature of this library is that, unlike other CSS frameworks like <a title=\"Bootstrap (front-end framework)\" href=\"https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)\">Bootstrap</a>, it does not provide a series of predefined classes for <a title=\"HTML element\" href=\"https://en.wikipedia.org/wiki/HTML_element\">elements</a> such as buttons or tables. Instead, it creates a list of \"utility\" CSS classes that can be used to style each element by mixing and matching.<sup id=\"cite_ref-4\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-4\">[4]</a></sup><sup id=\"cite_ref-5\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-5\">[5]</a></sup></p>\r\n<p>For example, in other traditional systems, there would be a class <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">message-warning</code> that would apply a yellow background color and bold text. To achieve this result in Tailwind, one would have to apply a set of classes created by the library: <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">bg-yellow-300</code> and <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">font-bold</code>.</p>\r\n<p>As of 30th July 2023, Tailwind CSS has over 70,000 stars on <a title=\"GitHub\" href=\"https://en.wikipedia.org/wiki/GitHub\">GitHub</a>.<sup id=\"cite_ref-6\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-6\">[6]</a></sup></p>\r\n<h2><span id=\"Features\" class=\"mw-headline\">Features</span></h2>\r\n<p>Due to the difference in basic concepts in relation to other traditional CSS frameworks such as Bootstrap, it is important to know the philosophy from which Tailwind was created, as well as its basic usage.</p>\r\n<h3><span id=\"Utility_Classes\" class=\"mw-headline\">Utility Classes</span></h3>\r\n<p>The <em>utility-first</em> concept refers to the main differentiating feature of Tailwind.<sup id=\"cite_ref-7\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-7\">[7]</a></sup> Instead of creating classes around components (button, panel, menu, textbox ...), classes are built around a specific style element (yellow color, bold font, very large text, center element...). Each of these classes is called <strong>utility classes</strong>.</p>\r\n<p>There are many utility classes in Tailwind CSS that enable to control a large number of <a title=\"CSS\" href=\"https://en.wikipedia.org/wiki/CSS\">CSS</a> properties like colors, border, display type (<em>display</em>), font size and font, layout, shadow...</p>\r\n<table class=\"wikitable\"><caption>Example: yellow notice</caption>\r\n<tbody>\r\n<tr>\r\n<th scope=\"row\">Result</th>\r\n<td colspan=\"2\"><a class=\"mw-file-description\" title=\"FExample Tailwind yellow warning.png\" href=\"https://en.wikipedia.org/wiki/File:Example_Tailwind_yellow_warning.png\"><img class=\"mw-file-element\" src=\"https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Example_Tailwind_yellow_warning.png/500px-Example_Tailwind_yellow_warning.png\" srcset=\"//upload.wikimedia.org/wikipedia/commons/thumb/1/12/Example_Tailwind_yellow_warning.png/750px-Example_Tailwind_yellow_warning.png 1.5x, //upload.wikimedia.org/wikipedia/commons/1/12/Example_Tailwind_yellow_warning.png 2x\" alt=\"FExample Tailwind yellow warning.png\" width=\"500\" height=\"90\" data-file-width=\"1000\" data-file-height=\"180\"></a></td>\r\n</tr>\r\n<tr>\r\n<th scope=\"row\">Code</th>\r\n<td colspan=\"2\">\r\n<div class=\"mw-highlight mw-highlight-lang-html mw-content-ltr\" dir=\"ltr\">\r\n<pre><span class=\"p\">&lt;</span><span class=\"nt\">div</span> <span class=\"na\">class</span><span class=\"o\">=</span><span class=\"s\">\"m-4 p-4 bg-yellow-200 font-bold rounded-lg\"</span><span class=\"p\">&gt;</span>\r\n  <span class=\"p\">&lt;</span><span class=\"nt\">p</span><span class=\"p\">&gt;</span>Please be careful when feeding the birds.<span class=\"p\">&lt;/</span><span class=\"nt\">p</span><span class=\"p\">&gt;</span>\r\n<span class=\"p\">&lt;/</span><span class=\"nt\">div</span><span class=\"p\">&gt;</span>\r\n</pre>\r\n</div>\r\n</td>\r\n</tr>\r\n<tr>\r\n<th rowspan=\"6\" scope=\"row\">Classes</th>\r\n<th>Tailwind</th>\r\n<th>CSS equivalent</th>\r\n</tr>\r\n<tr>\r\n<td><code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">m-4</code></td>\r\n<td><code class=\"mw-highlight mw-highlight-lang-css mw-content-ltr\" dir=\"ltr\"><span class=\"nt\">margin</span><span class=\"o\">:</span> <span class=\"nt\">1rem</span><span class=\"o\">;</span></code></td>\r\n</tr>\r\n<tr>\r\n<td><code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">p-4</code></td>\r\n<td><code class=\"mw-highlight mw-highlight-lang-css mw-content-ltr\" dir=\"ltr\"><span class=\"nt\">padding</span><span class=\"o\">:</span> <span class=\"nt\">1rem</span><span class=\"o\">;</span></code></td>\r\n</tr>\r\n<tr>\r\n<td><code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">bg-yellow-200</code></td>\r\n<td><code class=\"mw-highlight mw-highlight-lang-css mw-content-ltr\" dir=\"ltr\"><span class=\"nt\">background-color</span><span class=\"o\">:</span> <span class=\"nt\">rgba</span><span class=\"o\">(</span><span class=\"nt\">254</span><span class=\"o\">,</span> <span class=\"nt\">240</span><span class=\"o\">,</span> <span class=\"nt\">138</span><span class=\"o\">,</span> <span class=\"nt\">1</span><span class=\"o\">);</span></code></td>\r\n</tr>\r\n<tr>\r\n<td><code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">font-bold</code></td>\r\n<td><code class=\"mw-highlight mw-highlight-lang-css mw-content-ltr\" dir=\"ltr\"><span class=\"nt\">font-weight</span><span class=\"o\">:</span> <span class=\"nt\">700</span><span class=\"o\">;</span></code></td>\r\n</tr>\r\n<tr>\r\n<td><code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">rounded-lg</code></td>\r\n<td><code class=\"mw-highlight mw-highlight-lang-css mw-content-ltr\" dir=\"ltr\"><span class=\"nt\">border-radius</span><span class=\"o\">:</span> <span class=\"nt\">0</span><span class=\"p\">.</span><span class=\"nc\">5rem</span><span class=\"o\">;</span></code></td>\r\n</tr>\r\n</tbody>\r\n</table>\r\n<h3><span id=\"Variants\" class=\"mw-headline\">Variants</span></h3>\r\n<p>Tailwind offers the possibility to apply a utility class only in some situations through <em><a class=\"mw-redirect\" title=\"Media query\" href=\"https://en.wikipedia.org/wiki/Media_query\">media queries</a></em>, which is called a variant. The main use of variants is to design a <a class=\"mw-redirect\" title=\"Responsive Web Design\" href=\"https://en.wikipedia.org/wiki/Responsive_Web_Design\">responsive interface</a> for various screen sizes.<sup id=\"cite_ref-8\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-8\">[8]</a></sup> There are also variants for the different states an element can have, such as <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">hover&nbsp;:</code> for when hovered, <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">focus:</code> when keyboard selected or <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">active:</code> when in use,<sup id=\"cite_ref-9\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-9\">[9]</a></sup> or when the browser or operating system has <a class=\"mw-redirect\" title=\"Dark mode\" href=\"https://en.wikipedia.org/wiki/Dark_mode\">dark mode</a> enabled.<sup id=\"cite_ref-10\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-10\">[10]</a></sup></p>\r\n<p>Variants have two parts: the condition to be met and the class that is applied if the condition is met. For example, the variant <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">md:bg-yellow-400</code> will apply the class <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">bg-yellow-400</code> if the screen size is greater than the value defined for <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">md</code>.</p>\r\n<p>Tailwind CSS is developed using <a title=\"JavaScript\" href=\"https://en.wikipedia.org/wiki/JavaScript\">JavaScript</a>, runs via <a title=\"Node.js\" href=\"https://en.wikipedia.org/wiki/Node.js\">Node.js</a>, and installs with environment package managers like <a class=\"mw-redirect\" title=\"Npm (software)\" href=\"https://en.wikipedia.org/wiki/Npm_(software)\">npm</a> or <a title=\"Yarn (package manager)\" href=\"https://en.wikipedia.org/wiki/Yarn_(package_manager)\">yarn</a>.<sup id=\"cite_ref-11\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-11\">[11]</a></sup></p>\r\n<h3><span id=\"Settings_and_Themes\" class=\"mw-headline\">Settings and Themes</span></h3>\r\n<p>It is possible to configure the utility classes and variants that Tailwind offers through a configuration file usually named <code id=\"\" class=\"mw-highlight mw-highlight-lang-text mw-content-ltr\" dir=\"ltr\">tailwind.config.js</code>. In the configuration one can set the values of the utility classes, such as the color-palette or the sizes between elements for margins.</p>\r\n<h4><span id=\"Build_All_and_Purge\" class=\"mw-headline\">Build All and Purge</span></h4>\r\n<p>The default mode of Tailwind is that the system generates all possible CSS combinations based on the project settings. Then, by means of another utility such as <a class=\"new\" title=\"PurgeCSS (page does not exist)\" href=\"https://en.wikipedia.org/w/index.php?title=PurgeCSS&amp;action=edit&amp;redlink=1\">PurgeCSS</a>, all the files are traversed, and the classes that are not being used are removed from the resulting CSS file.</p>\r\n<p>Due to the number of classes that can be generated by the number of variants and their combinations, this method has the drawbacks of long waiting times and large sizes of CSS files before being purged. This mode of operation is no longer available in version 3 of Tailwind CSS.<sup id=\"cite_ref-v3_12-0\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-v3-12\">[12]</a></sup></p>\r\n<h4><span id=\"JIT\" class=\"mw-headline\">JIT</span></h4>\r\n<p>JIT mode (<em>Just-In-Time</em>) is an alternative way to generate the CSS that, instead of generating all possible classes and then removing all those that are not being used, parses the content of HTML files (or configured extensions or locations) and instantly generates only those classes that are needed and used.</p>\r\n<p>Because all possible variables are no longer generated, the waiting time and size of the resulting CSS files is greatly reduced.<sup class=\"noprint Inline-Template Template-Fact\" style=\"white-space: nowrap;\">[<em><a title=\"Wikipedia:Citation needed\" href=\"https://en.wikipedia.org/wiki/Wikipedia:Citation_needed\"><span title=\"This claim needs references to reliable sources. (August 2022)\">citation needed</span></a></em>]</sup> This technical improvement has made it possible to introduce numerous new variants and utility classes, as well as the ability to create utility classes on the fly with arbitrary values not set in the configuration.</p>\r\n<p>Starting with version 3 of Tailwind CSS, JIT mode has become the default.<sup id=\"cite_ref-v3_12-1\" class=\"reference\"><a href=\"https://en.wikipedia.org/wiki/Tailwind_CSS#cite_note-v3-12\">[12]</a></sup></p>\r\n<h2><span id=\"Versions\" class=\"mw-headline\">Versions</span></h2>\r\n<p>Tailwind CSS uses <a class=\"mw-redirect\" title=\"Semantic versioning\" href=\"https://en.wikipedia.org/wiki/Semantic_versioning\">semantic versioning</a> to identify its version compatibility.</p>\r\n<p>&nbsp;</p>\r\n<h2><span id=\"References\" class=\"mw-headline\">References</span></h2>\r\n<div class=\"reflist reflist-columns references-column-width reflist-columns-2\">\r\n<ol class=\"references\">\r\n<li id=\"cite_note-1\"></li>\r\n</ol>\r\n</div>\r\n<ul>\r\n<li id=\"cite_note-1\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://github.com/tailwindlabs\" rel=\"nofollow\">\"Tailwind Labs\"</a>.</cite></span></li>\r\n<li id=\"cite_note-wikidata-bb5df3aafbd8fee9b918fce8ec05d20c653c7799-v8-2\"></li>\r\n<li id=\"cite_note-wikidata-bb5df3aafbd8fee9b918fce8ec05d20c653c7799-v8-2\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.3.3\" rel=\"nofollow\">\"Release v3.3.3\"</a>. 13 July 2023<span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">26 July</span> 2023</span>.</cite></span></li>\r\n<li id=\"cite_note-licencia-3\"></li>\r\n<li id=\"cite_note-licencia-3\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://github.com/tailwindlabs/tailwindcss/blob/769d22fecc1c5faafb5b5d6c406ac33ed3ecc33f/LICENSE\" rel=\"nofollow\">\"Github: tailwindlabs/tailwindcss, LICENSE\"</a>.</cite></span></li>\r\n<li id=\"cite_note-4\"></li>\r\n<li id=\"cite_note-4\"><span class=\"reference-text\"><cite id=\"CITEREFGerchev2022\" class=\"citation book cs1\">Gerchev, Ivaylo (2022). <a class=\"external text\" href=\"https://www.worldcat.org/oclc/1314257318\" rel=\"nofollow\"><em>Tailwind CSS</em></a>. Sebastopol: O'Reilly Media. <a class=\"mw-redirect\" title=\"ISBN (identifier)\" href=\"https://en.wikipedia.org/wiki/ISBN_(identifier)\">ISBN</a>&nbsp;<a title=\"Special:BookSources/1-0981-4099-0\" href=\"https://en.wikipedia.org/wiki/Special:BookSources/1-0981-4099-0\"><bdi>1-0981-4099-0</bdi></a>. <a class=\"mw-redirect\" title=\"OCLC (identifier)\" href=\"https://en.wikipedia.org/wiki/OCLC_(identifier)\">OCLC</a>&nbsp;<a class=\"external text\" href=\"https://www.worldcat.org/oclc/1314257318\" rel=\"nofollow\">1314257318</a>.</cite></span></li>\r\n<li id=\"cite_note-5\"></li>\r\n<li id=\"cite_note-5\"><span class=\"reference-text\"><cite id=\"CITEREFRappin2021\" class=\"citation book cs1\">Rappin, Noel (2021). <a class=\"external text\" href=\"https://www.worldcat.org/oclc/1277046918\" rel=\"nofollow\"><em>Modern CSS with Tailwind flexible styling without the fuss</em></a>. Raleigh. <a class=\"mw-redirect\" title=\"ISBN (identifier)\" href=\"https://en.wikipedia.org/wiki/ISBN_(identifier)\">ISBN</a>&nbsp;<a title=\"Special:BookSources/978-1-68050-857-4\" href=\"https://en.wikipedia.org/wiki/Special:BookSources/978-1-68050-857-4\"><bdi>978-1-68050-857-4</bdi></a>. <a class=\"mw-redirect\" title=\"OCLC (identifier)\" href=\"https://en.wikipedia.org/wiki/OCLC_(identifier)\">OCLC</a>&nbsp;<a class=\"external text\" href=\"https://www.worldcat.org/oclc/1277046918\" rel=\"nofollow\">1277046918</a>.</cite></span></li>\r\n<li id=\"cite_note-6\"></li>\r\n<li id=\"cite_note-6\"><span class=\"reference-text\"><cite class=\"citation cs2\"><a class=\"external text\" href=\"https://github.com/tailwindlabs/tailwindcss\" rel=\"nofollow\"><em>tailwindlabs/tailwindcss</em></a>, Tailwind Labs, 2022-12-05<span class=\"reference-accessdate\">, retrieved <span class=\"nowrap\">2022-12-05</span></span></cite></span></li>\r\n<li id=\"cite_note-7\"></li>\r\n<li id=\"cite_note-7\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://tailwindcss.com/docs/utility-first\" rel=\"nofollow\">\"Utility-First - Tailwind CSS\"</a>. <em>tailwindcss.com</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n<li id=\"cite_note-8\"></li>\r\n<li id=\"cite_note-8\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://tailwindcss.com/docs/responsive-design\" rel=\"nofollow\">\"Responsive Design - Tailwind CSS\"</a>. <em>tailwindcss.com</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n<li id=\"cite_note-9\"></li>\r\n<li id=\"cite_note-9\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://tailwindcss.com/docs/hover-focus-and-other-states\" rel=\"nofollow\">\"Hover, Focus, &amp; Other States - Tailwind CSS\"</a>. <em>tailwindcss.com</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n<li id=\"cite_note-10\"></li>\r\n<li id=\"cite_note-10\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://tailwindcss.com/docs/dark-mode\" rel=\"nofollow\">\"Dark Mode - Tailwind CSS\"</a>. <em>tailwindcss.com</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n<li id=\"cite_note-11\"></li>\r\n<li id=\"cite_note-11\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://tailwindcss.com/docs/installation\" rel=\"nofollow\">\"Installation - Tailwind CSS\"</a>. <em>tailwindcss.com</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n<li id=\"cite_note-v3-12\"></li>\r\n</ul>\r\n<div class=\"reflist reflist-columns references-column-width reflist-columns-2\">\r\n<ol class=\"references\">\r\n<li id=\"cite_note-v3-12\" value=\"12\"><span class=\"reference-text\"><cite class=\"citation web cs1\"><a class=\"external text\" href=\"https://github.com/tailwindlabs/tailwindcss/releases/tag/v3.0.0-alpha.1\" rel=\"nofollow\">\"Release v3.0.0-alpha.1 tailwindlabs/tailwindcss\"</a>. <em>GitHub</em><span class=\"reference-accessdate\">. Retrieved <span class=\"nowrap\">2021-11-13</span></span>.</cite></span></li>\r\n</ol>\r\n</div>\r\n<h2><span id=\"External_links\" class=\"mw-headline\">External links</span></h2>\r\n<ul>\r\n<li><a class=\"external text\" href=\"https://tailwindcss.com/docs\" rel=\"nofollow\">Official Tailwind Documentation</a>.</li>\r\n<li><a class=\"external text\" href=\"https://play.tailwindcss.com\" rel=\"nofollow\">Tailwind Play</a>, real-time testing environment.</li>\r\n<li><a class=\"external text\" href=\"https://lembdadev.com/css-to-tailwind-converter\" rel=\"nofollow\">Tailwind Converter</a>.</li>\r\n</ul>"
created: "2023-06-10 00:28:57.829Z"
division: []
id: "s35p2wh9w4mj4w1"
likes: []
name: "Tailwind"
tagline: "CSS for people who hate css"
tags: ["yd4ys091kfpxyde","8p5fnjif3a2opwb"]
thumbnail: "tailwindcss_iogTG59At1.png"
updated: "2023-08-11 16:44:16.736Z"
url: "https://google.com"
user: "8ti99kn9yavd7mb"
verified: true
expand: {}
---

undefined