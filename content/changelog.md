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
   <p>Thanks to Tolu Adegbite for updating this changelog in May 2021.</p>
---

_This changelog includes some Markdown and HTML syntax to facilitate updating translations._

## 18 February 2020
* Contributor names added:
```
- name: "محمد سليم"   # Replace @@ with name, or delete this line if not multiple translators
contributors:
- name: "محمد الموسوي"   # Replace @@ with contributor name, or delete this line if none
- name: "مريم نصيب"   # Replace @@ with name, or delete this line if not multiple contributors
```

## 17 February 2020
* Title changed to:
```
title: نبذة عن معيار الاتحاد العالمي للويب لإمكانية الوصول  # Do not translate "title:". Do translate the text after "title:".
nav_title: "معايير/إرشادات" # A short title that is used in the navigation
```
* Name changed to:
```
name: " الاتحاد السعودي للأمن السيبراني والبرمجة والدرونز "
```
* Contributor names changed to:
``
name: "محمد الموسوي"
name: "مريم نصيب"
``
* Footer text changed to:
```
<p><strong>التاريخ:</strong> تم التحديث في 13 مارس 2019.</p>
  <p><strong>محرر:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p> تم تطويره بمساهمة فريق التعليم و التوعية (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>
  
  {% include box.html type="start" h="2" title="الملخص" class="full" %}
{:/}

هذي الصفحة تقدم إرشادات و معايير أخرى متعلقة بإمكانية الوصول للويب.

{% include_cached toc.html type="start" title="محتوى الصفحة" class="full" %}
{:/}
```
* Guidelines text changed to:
```
[[المكونات الأساسية للوصول للويب]]( /fundamentals/components/) توضح مدى اعتماد مستوى الوصول على تفاعل المكونات المختلفة لتطوير الويب مع بعضها، و توضح كيف يمكن تطبيق ارشادات WAI (WCAG, ATAG, UAAG).
```
* WCAG text changed to:
```
بشكل عام، فإن المصطلح "محتوى الويب" يشير إلى معلومات في صفحة ويب أو تطبيق ويب، وذلك يشمل:

الكود البرمجي والعلامات المسؤولة عن بناء وتمثيل المعلومات الاساسية.
بالإمكان تطبيق معايير WCAG على المحتويات التفاعلية، ومتعددة الوسائط، وعلى "الهواتف المحمولة"، إلخ. بالإمكان أيضاً تطبيق معايير WCAG على تكنولوجيا المعلومات والاتصالات information and communications technologies (ICT) في غير الويب، وفقاً لما هو مفصل في [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/).

[كيفية العمل بـ WCAG 2 (المرجع السريع)](https://www.w3.org/WAI/WCAG21/quickref/)
```
* Text under ATAG section changed to:
```
أدوات التطوير هي خدمات برمجية يستخدمها "المنشؤون" (مطوروا الويب، المصممون، المؤلفون... إلخ) لإنتاج محتوى الويب. بعض الأمثلة لأدوات التطوير: محرر HTML (HTML editors)، أنظمة إدارة المحتوى content management systems (CMS)، والمواقع التي تتيح لمستخدميها إضافة المحتوى، مثل المدونات ومواقع شبكات التواصل الاجتماعي. وثيقة ATAG تشرح كيفية:
```
* UAAG section title changed to:
```
### دليل الوصول لمساعدات المستخدم (UAAG) {#uaag}
```
* Text under UAAG section changed to:
```
تشمل مساعدات المستخدم المستعرضات وامتداداتها، مشغلات الوسائط، القارئات، والتطبيقات الأخرى التي تعرض / تستدعي محتوى الويب
معلومات عن UAAG:
-	[نبذة عن UAAG](/standards-guidelines/uaag/)
-	[ملاحظات عن UAAG 2.0](https://www.w3.org/TR/UAAG20/)
```
* Text under ARIA section changed to:
```
[[نبذة عن WCAG-EM:]]( /test-evaluate/conformance/wcag-em/)&mdash; منهجية مطابقة الوصول للويب – WCAG-EM هي طريقة لتحديد مدى مطابقة موقع ما (ويب) لدليل الوصول لمحتوى الويب WCAG

[[لماذا يتم التنسيق بين المعايير المهمة للوصول للويب]](/standards-guidelines/harmonization/)

![ توضيح يبين المبادئ التوجيهية للمكونات المختلفة ، ووصف مفصل في https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.png" | relative_url }})
```

## 6 January 2020
* Last updated date changed to:
```
last_updated: 2021-01-06

<p><strong>Date:</strong> Updated 6 January 2021.</p>
```
* Title changed to:
```
### Web Content Accessibility Guidelines (WCAG) 2 {#wcag2}
```
* WCAG info section changed to:
```
WCAG 2 info:

[[WCAG 2 Translations]](/standards-guidelines/wcag/translations/)

[WCAG 2.1 Standard](https://www.w3.org/TR/WCAG21/), [[What’s New in WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)

[[What's New in WCAG 2.2 Working Draft]](/standards-guidelines/wcag/new-in-22/)
```
* Section added:
```
### W3C Accessibility Guidelines (WCAG) 3 Working Draft {#wcag3}

WCAG 3 is an early draft that is intended to become a W3C Standard. WCAG 3 applies to web content, apps, tools, publishing, and emerging technologies on the web.

WCAG 3 info:
- [[WCAG 3 Introduction]](/standards-guidelines/wcag/wcag3-intro/)
```


# 16 July 2019
* Guidelines info changed to:
```
[[В разделе Основные компоненты веб-доступности]](/fundamentals/components/) раскрывается информация о влиянии тесной взаимосвязи отдельных элементов разработки контента и взаимодействия с Интернет-пользователями на обеспечение веб-доступности, а также описаны способы применения рекомендаций WAI (WCAG, ATAG, UAAG).
```
* Intro text under WCAG section changed to:
```
Веб-«контент», как правило, подразумевает информацию, размещённую на Интернет-странице или в онлайн-приложении, в том числе:
```
* Aria section title changed to:
```
Доступные полнофункциональные Интернет-приложения (WAI-ARIA) {#aria}
```
* Text under Aria section changed to:
```
[Обзор WAI-ARIA](/standards-guidelines/aria/), включающий [список и описание модулей и API-мэппингов](/standards-guidelines/aria/#versions)
```
* Section under multimedia changed to:
```
[WebVTT: Формат текстовых дорожек видео в сети Интернет](https://www.w3.org/TR/webvtt/) представляет собой формат титров, текстовых описаний видеоматериалов и других сопроводительных данных, синхронизируемых с аудио- или видео-контентом.

Дополнительные ресурсы, связанные с процедурой оценивания [[Оценка веб-доступности]](/test-evaluate/), в частности:

[Как Инициатива WAI разрабатывает рекомендации по обеспечению веб-доступности в рамках деятельности консорциума W3C: Основные этапы и **возможности содействия**](/standards-guidelines/w3c-process/)
```

# 12 July 2019
* Translators info changed to:
```
translators: 
- name: "安佳"   # Replace @@ with translator name
  link: "https://github.com/anjia"
```

## 11 July 2019
* Footer text changed to:
```
<p><strong>Дата:</strong> Обновлено 13 марта 2019 года.</p>
  <p><strong>Под редакцией:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Разработано при участии Рабочей Группы по Образованию и Просвещению (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>
  ```
* Intro changed to:
```
Консорциум Всемирной паутины (W3C) занимается разработкой международных стандартов, таких как: <abbr title="Hypertext Markup Language - Язык гипертекстовой разметки">HTML</abbr>, <abbr title="Cascading Style Sheets - Каскадные таблицы стилей">CSS</abbr>, и многие другие. Стандарты консорциума называются Рекомендациями (<dfn><span lang="en">W3C Recommendations</span></dfn>).

Представленные далее стандарты W3C и примечания Рабочей Группы самым непосредственным образом связаны с обеспечением веб-доступности.
```
* Text under guidelines changed to:
```
обычную информацию, а именно, текстовые, графические и звуковые материалы;
```
* Intro text under ATAG section changed to:
```
Средства по разработке авторского контента – это программные средства и сервисы, используемые «авторами» (разработчиками, дизайнерами, программистами и т.д.) для создания веб-контента. К подобным сервисам относятся HTML-редакторы, системы управления контентом (CMS), а также веб-сайты, позволяющие пользователям добавлять информацию, например блоги и социальные сети. Материалы ATAG дают разъяснения относительно:
```

## 10 July 2019
* Name and link changed to:
```
name: "UNESCO IITE"
  link: https://iite.unesco.org/
```
* Footer changed to:
```
footer: > # Do not change these dates. Do translate the "Date", "Editor" and the dates themselves.
```
* Aria section changed to:
```
ARIA обеспечивают семантику, необходимую авторам для передачи информации о структурных данных и API-мэппинге в распоряжение вспомогательных технологий (таких как программы для чтения экрана). Спецификация ARIA прописывает онтологию ролей, состояний и свойств, определяющих доступные элементы пользовательского интерфейса.

[Стандарт WAI-ARIA 1.1](https://www.w3.org/TR/wai-aria-1.1/)
```
* Text under more info changed to:
```
[Как WAI разрабатывает рекомендации по обеспечению веб-доступности в рамках деятельности W3C: Основные этапы и **возможности содействия**](/standards-guidelines/w3c-process/)
```
