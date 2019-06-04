---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: Resumen de los estándares de accesibilidad de W3C # Do not translate "title:". Do translate the text after "title:".
nav_title: "Estándares/Pautas" # A short title that is used in the navigation

lang: es   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2019-05-29   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translators: 
# - name: "Carlos Muncharaz"   # Replace @@ with translator name
#  link: @@
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /standards-guidelines/   # Do not change this
layout: default
github:
  repository: w3c/wai-std-gl-overview
  path: index.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /standards-guidelines/   # Add the language shortcode to the end; for example /standards-guidelines/fr
feedbackmail: wai@w3.org

footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
  <p><strong>Fecha:</strong> Actualizado el 13 de marzo del 2019.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Desarrollado con la colaboración del Grupo de Trabajo de Educación y Difusión (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-std-gl-overview/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Esta página presenta pautas y otros estándares relacionados con la accesibilidad web.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introducción {#intro}

El World Wide Web Consortium (W3C) desarrolla estándares web internacionales: <abbr title="Hypertext Markup Language">HTML</abbr>, <abbr title="Cascading Style Sheets">CSS</abbr> y muchos más. Los estándares de W3C se llaman <dfn>W3C Recommendations</dfn>.
 
El soporte para la accesibilidad de todos los estándares de W3C es revisado por el Grupo de Trabajo de Arquitecturas de la Plataforma Accesible ([APA](/about/groups/apawg/)).
 
Los estándares W3C y las Anotaciones de los Grupos de Trabajo que se mencionan abajo son particularmente relevantes para la accesibilidad.

## Pautas de accesibilidad {#guidelines}

Con los [[componentes esenciales de la accesibilidad web]](/fundamentals/components/) se puede ver que la accesibilidad depende de varios componentes del desarrollo web que interactúan juntos y cómo se aplican las pautas de WAI (WCAG, ATAG, UAAG).

### Pautas de accesibilidad para el contenido web (WCAG) {#wcag}

Por “contenido” web se hace referencia, generalmente, a la información que se puede encontrar en una página o aplicación web, lo cual incluye:
 
* información natural como textos, imágenes y sonidos.
* código o marcado que define la estructura, la presentación, etc.
 
Las pautas WCAG se aplican al contenido dinámico, multimedia, “móvil”, etc. También se pueden aplicar a tecnologías de la información y la comunicación (TIC) no relacionadas con la web, como se explica en [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/).

Información sobre las pautas WCAG:
- [Resumen de WCAG](  /standards-guidelines/wcag/)
- [[WCAG 2.1 de un vistazo]](/standards-guidelines/wcag/glance/)
- [Cómo seguir las pautas WCAG 2 (Guía rápida)](https://www.w3.org/WAI/WCAG21/quickref/)
- [Estándar WCAG 2.0](https://www.w3.org/TR/WCAG20/)
- [Estándar WCAG 2.1](https://www.w3.org/TR/WCAG21/)

### Pautas de accesibilidad para las herramientas de creación de contenido (ATAG) {#atag}

Las herramientas de creación de contenido son programas o servicios que los “autores” (desarrolladores web, diseñadores, redactores, etc) utilizan para producir contenido web. Por ejemplo: editores de HTML, sistemas de gestión de contenidos (CMS) y sitios web que permiten a los usuarios añadir contenido tales como blogs y redes sociales. Los documentos ATAG explican cómo:

* hacer que las herramientas de creación de contenido sean accesibles en sí mismas, de forma que las personas con discapacidad puedan crear contenido web, y
* ayudar a los autores a crear contenido web más accesible.

Información sobre las pautas ATAG:
- [Resumen de ATAG](/standards-guidelines/atag/)
- [[ATAG de un vistazo]](/standards-guidelines/atag/glance/)
- [Estándar ATAG 2.0](https://www.w3.org/TR/ATAG/)

### Pautas de accesibilidad para el agente de usuario (UAAG) {#uaag}

Los agentes de usuario son navegadores, extensiones de los navegadores, reproductores multimedia, lectores y otras aplicaciones que presentan contenido web.

Información sobre las pautas UAAG:
- [Resumen de UAAG](/standards-guidelines/uaag/)
- [Nota sobre UAAG 2.0](https://www.w3.org/TR/UAAG20/)

## Especificaciones técnicas

### Accessible Rich Internet Applications (WAI-ARIA) {#aria}

ARIA provides semantics so authors can convey user interface behaviors and structural information to assistive technologies (such as screen readers). The ARIA specification provides an ontology of roles, states, and properties that define accessible user interface elements.

The ARIA suite includes <abbr title="application programming interface">API</abbr> mapping specifications that provide user agent implementation guidance. It also include modules for Graphics and Digital Publishing.

ARIA info:
- [WAI-ARIA Overview](/standards-guidelines/aria/) – includes a [list and description of modules and API mappings](/standards-guidelines/aria/#versions)
- [WAI-ARIA Authoring Practices](https://www.w3.org/TR/wai-aria-practices/)
- [WAI-ARIA 1.1 Standard](https://www.w3.org/TR/wai-aria-1.1/)

### Audio and Video {#multimedia}

- [WebVTT: The Web Video Text Tracks Format](https://www.w3.org/TR/webvtt/) is a format for captions, text video descriptions, and other metadata that is time-aligned with audio or video content.

- [Timed Text Markup Language (TTML)](https://www.w3.org/TR/ttml/) is intended to be used for transcoding or exchanging timed text information among legacy distribution content formats for subtitling and captioning.

### Evaluation {#eval}

The following resources support development of accessibility evaluation methods and tools:

- [[Accessibility Conformance Testing (ACT) Overview]](/standards-guidelines/act/) &mdash; ACT establishes and documents rules for testing the conformance of web content to accessibility standards.

- [[Evaluation and Report Language (EARL) Overview]](/standards-guidelines/earl/) &mdash; EARL is a machine-readable format for expressing test results.

Additional resources related to evaluation are listed in the [[Evaluating Web Accessibility Overview]](/test-evaluate/), including:

- [[WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology]](/test-evaluate/conformance/wcag-em/) &mdash; WCAG-EM is an approach for determining how well a website conforms to Web Content Accessibility Guidelines (WCAG).

### Personalization

[[Personalization Overview]](/personalization/) &mdash; Personalization involves tailoring the user experience to meet the needs and preferences of the individual user. Content authors can use personalization standards to provide a default design and enable user personalization with minimal work.

## Otras áreas del trabajo de W3C WAI

- [[Accesibilidad móvil en W3C]](/standards-guidelines/mobile/)

- [[Accesibilidad cognitiva en W3C]](/cognitive/)

## Información adicional {#moreinfo}

- [Listado de todos los estándares W3C relacionados con la accesibilidad ("W3C Recommendations") y notas de los Grupos de Trabajo](https://www.w3.org/TR/#tr_Accessibility__All_)

- [[Leyes y políticas de accesibilidad web]](/policies/) donde se relacionan leyes gubernamentales y políticas sobre accesibilidad web en países y regiones de todo el mundo. Muchas de estas hacen referencia a los estándares de accesibilidad del W3C.

- [[Por qué la armonización de los estándares es fundamental para la accesibilidad web]](/standards-guidelines/harmonization/)

- [[Creación de referencias y enlaces a las pautas y documentos técnicos de WAI]](/standards-guidelines/linking/)

- [Cómo se desarrollan las pautas de accesibilidad en WAI a través del método de trabajo de W3C: hitos y **oportunidades para participar**](/standards-guidelines/w3c-process/)

![Ilustración mostrando las pautas de los diferentes componentes, una descripción detallada se puede encontrar en https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.png" | relative_url }})
