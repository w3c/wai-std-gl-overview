---
# IN-PROGRESS #
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: Vue d’ensemble des standards d’accessibilité du W3C # Do not translate "title:". Do translate the text after "title:".
nav_title: "Standards/Règles" # A short title that is used in the navigation

lang: fr   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2019-06-15   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators: 
- name: "@code-elegant"   # Replace @@ with translator name
#  link: @@
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /standards-guidelines/   # Do not change this
layout: default
github:
  repository: w3c/wai-std-gl-overview
  path: index.fr.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /standards-guidelines/fr   # Add the language shortcode to the end; for example /standards-guidelines/fr
feedbackmail: wai@w3.org

footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
  <p><strong>Date :</strong> Mis à jour le 13 mars 2019.</p>
  <p><strong>Éditrice :</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Élaboré avec des contributions du groupe de travail « Éducation et Rayonnement » (Education and Outreach Working Group <a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-std-gl-overview/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Résumé" class="full" %}
{:/}

Cette page introduit les lignes directrices et autres standards relatifs à l’accessibilité du web.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Contenu de la page" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction {#intro}

Le World Wide Web Consortium (W3C) developpe des standards internationaux pour le web : <abbr title="Hypertext Markup Language">HTML</abbr>, <abbr title="Cascading Style Sheets">CSS</abbr>, and bien d’autres. Les standards web du W3C sont appelés <dfn>Recommandations du W3C</dfn>.

Tous les standards du W3C sont revus pour la prise en compte de l’accessibilité par le groupe de travail Architectures de plateforme accessibles ([APA](/about/groups/apawg/)).

Les standards du W3C et les notes de groupe de travail ci-dessous sont particulièrement pertinents pour l’accessibilité.

## Règles d’accessibilité {#guidelines}

Les [[Éléments essentiels de l'accessibilité du Web]](/fundamentals/components/fr) montre comment l’accessibilité du web dépend de la combinaison harmonieuse des nombreux composants du développement web et de l’interaction utilisateur, et comment les règles WAI ((WCAG, ATAG, UAAG) s’appliquent.

###  Règles pour l'accessibilité des contenus Web (WCAG) {#wcag}

Le « contenu » web fait référence à l’information présente dans une page ou application web, y compris :

* de l’information primaire telle que du texte, des images et des sons ;
* du code ou du balisage qui définit la structure, la présentation etc.

Les WCAG s’appliquent au contenu dynamique, multimédia, « mobile » etc. Les WCAG peuvent aussi être appliquées aux technologies de l’information et de la comunication « non-web », ainsi que décrit dans [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/) (en anglais). 

Informations autour des WCAG :
- [Vue d’ensemble des WCAG](/standards-guidelines/wcag/) (en anglais)
- [Les WCAG 2.1 en un coup d’œil](/standards-guidelines/wcag/glance/) (en anglais)
- [Comment satisfaire aux WCAG 2 (référence rapide)](https://www.w3.org/WAI/WCAG21/quickref/) (en anglais)
- [Le standard WCAG 2.0](https://www.w3.org/Translations/WCAG20-fr/)
- [Le standard WCAG 2.1](https://www.w3.org/TR/WCAG21/) (en anglais)

### Règles d'accessibilité pour les outils d'édition (ATAG) {#atag}

Les outils d’édition sont des logiciels et des services que les « auteurs » (développeurs web, concepteurs, rédacteurs…) utilisent pour produire du contenu web. Par exemple : des éditeurs HTML, des gestionnaires de contenu (CMS), et des sites web qui permettent aux utilisateurs d’ajouter du contenu, tels que des blogues et des sites de réseau social. Les documents ATAG expliquent comment :
* rendre les outils d’édition eux-mêmes accessibles, afin que les personnes handicapées puissent créer du contenu, et
* accompagner les auteurs dnas la création de contenu web plus accessible.

Informations autour des ATAG :
- [Vue d’ensemble des ATAG](/standards-guidelines/atag/) (en anglais)
- [Les ATAG en un coup d’œil](/standards-guidelines/atag/glance/) (en anglais)
- [Le standard ATAG 2.0](https://www.w3.org/TR/ATAG/) (en anglais)

### Les règles pour l'accessibilité des agents utilisateurs (UAAG) {#uaag}

Les agents utilisateur incluent les navigateurs, leurs greffons, les lecteurs de média, les lecteurs et toutes les applications qui restituent du contenu web.

Informations autour des UAAG info :
- [Vue d’ensemble des UAAG](/standards-guidelines/uaag/) (en anglais)
- [Note UAAG 2.0](https://www.w3.org/TR/UAAG20/) (en anglais)

## Spécifications techniques

### Applications internet riches accessibles (WAI-ARIA) {#aria}

ARIA définit de la sémantique afin que les auteurs puissent transmettre des comportements d’interface utilisateur et de l’information structurée aux technologies d’assistance (telles que les revues d’écran). La spécification ARIA fournit une ontologie de roles, états et propriétés qui définit des éléments d’interface utilisateur accessible.

La suite ARIA comprend des spécification de correspondance d’interface de programmation d’application (<abbr title="application programming interface" lang="en">API</abbr>) qui fournissent de l’accompagnement lors de l’implémentation d’agent utilisateur. Elle inclut aussi des parties pour la publication numérique et graphique. 

Informations autour d’ARIA :
- [Vue d’ensemble de WAI-ARIA](/standards-guidelines/aria/) – comprend une [liste et description de modules et de correspondances d’API mappings](/standards-guidelines/aria/#versions)
- [Pratiques de création WAI-ARIA](https://www.w3.org/TR/wai-aria-practices/) (en anglais)
- [Standard WAI-ARIA 1.1 Standard](https://www.w3.org/TR/wai-aria-1.1/) (en anglais)

### Audio et vidéo {#multimedia}

- Le [WebVTT : le format des pistes textuelles pour la vidéo web](https://www.w3.org/TR/webvtt/) est un format pour les sous-titres, descriptions textuelles de vidéos et autres métadonnées qui sont synchronisées temporellement avec du contenu audio ou vidéo.

- Le [Langage de balisage du texte cadencé (Timed Text Markup Language TTML)](https://www.w3.org/TR/ttml/) est conçu dans la perspective du transcodage ou de l’échange dd’information de texte cadencé entre formats de diffusion de contenu patrimoniaux de sous-titrage et d’audiodescription.

### Évaluation {#eval}

Les ressources suivantes favorisent le développement de méthodes et outils d’évaluation de l’accessibilité :

- [Vue d’ensemble de Tests de conformité à l’accessibilité (Accessibility Conformance Testing ACT)](/standards-guidelines/act/) &mdash; ACT met en place et documente establishes and documents rules for testing the conformance of web content to accessibility standards.

- [Evaluation and Report Language (EARL) Overview](/standards-guidelines/earl/) &mdash; EARL is a machine-readable format for expressing test results.

Additional resources related to evaluation are listed in the [[Evaluating Web Accessibility Overview]](/test-evaluate/), including:

- [[WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology]](/test-evaluate/conformance/wcag-em/) &mdash; WCAG-EM is an approach for determining how well a website conforms to Web Content Accessibility Guidelines (WCAG).

### Personalization

[[Personalization Overview]](/personalization/) &mdash; Personalization involves tailoring the user experience to meet the needs and preferences of the individual user. Content authors can use personalization standards to provide a default design and enable user personalization with minimal work.

## Other Areas of W3C WAI work

- [[Mobile Accessibility at W3C]](/standards-guidelines/mobile/)

- [[Cognitive Accessibility at W3C]](/cognitive/)

## Additional Information {#moreinfo}

- [List of all W3C accessibility-related Standards ("W3C Recommendations") and Working Group Notes](https://www.w3.org/TR/#tr_Accessibility__All_)

- [[Web Accessibility Laws & Policies]](/policies/) lists governmental laws and policies relating to web accessibility in countries and regions around the world. Many of these reference W3C accessibility standards.

- [[Why Standards Harmonization is Essential to Web Accessibility]](/standards-guidelines/harmonization/)

- [[Referencing and Linking to WAI Guidelines and Technical Documents]](/standards-guidelines/linking/)

- [How WAI Develops Accessibility Guidelines through the W3C Process: Milestones and **Opportunities to Contribute**](/standards-guidelines/w3c-process/)

![illustration showing the guidelines for the different components, detailed description at https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.fr.png" | relative_url }})
