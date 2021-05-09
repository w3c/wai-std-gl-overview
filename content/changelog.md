---
title: "Changelog for W3C Accessibility Standards Overview "
title_html: "Changelog for <a href='/WAI/standards-guidelines/'>W3C Accessibility Standards Overview</a>"
nav_title: "Changelog"
lang: en
layout: default

permalink: /standards-guidelines/changelog/
ref: /standards-guidelines/changelog/
github:
 repository: w3c/wai-std-gl-overview
 path: content/changelog.md

feedbackmail: wai@w3.org
footer: >
 <p>Thanks to Tolu Adegbite for updating this changelog.</p>
---

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{::options toc_levels="2,3" /}
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}


## May 2021
* In the frontmatter at the top, add ```changelog: /videos/standards-and-benefits/changelog/``` between ref and layout:<br>
```
ref: /videos/standards-and-benefits/   # Do not change this
changelog: /videos/standards-and-benefits/changelog/
layout: default
```
* In the frontmatter, under the footer text, add ```CHANGELOG. ``` after the date. _Leave it in all capital letters and do not translate it._<br>
```<p><strong>Date:</strong> Updated 6 January 2021. CHANGELOG.</p>```

## 6 Jan 2021
* Change "### Web Content Accessibility Guidelines (WCAG) {#wcag}" to:
```
### Web Content Accessibility Guidelines (WCAG) 2 {#wcag2}
```
* Change "WCAG info:" to:
```
WCAG 2 info:
```
* Around ```- [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)```add one link before and two links after:
```
        - [[WCAG 2 Translations]](/standards-guidelines/wcag/translations/)
        - [WCAG 2.0 Standard](https://www.w3.org/TR/WCAG20/)
        - [WCAG 2.1 Standard](https://www.w3.org/TR/WCAG21/), [[What’s New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)
        - [[What's New in WCAG 2.2 Working Draft]](/standards-guidelines/wcag/new-in-22/)
```

* Before “## Technical Specifications”, add:
```
        ### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}
        WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web.
WCAG 3 info:
        - [[WCAG 3 Introduction]](/standards-guidelines/wcag/wcag3-intro/)
```

## 11 Sep 2019
* Before “## Other Areas of W3C WAI work”, add:
```
### Pronunciation
[[Pronunciation Overview]](/pronunciation/) &mdash; Pronunciation is about screen readers and other text-to-speech (TTS) synthesis pronouncing content properly.
```

## 17 Jul 2019
* Under “## Additional Information {#moreinfo}”, in first item, change URI link to ``` https://www.w3.org/TR/?tag=accessibility```:
```
        - [List of all W3C accessibility-related Standards ("W3C Recommendations") and Working Group Notes](https://www.w3.org/TR/?tag=accessibility)
```
