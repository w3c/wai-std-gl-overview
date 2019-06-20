---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: W3C Accessibility Standards Overview  # Do not translate "title:". Do translate the text after "title:".
nav_title: "Standards/Guidelines" # A short title that is used in the navigation

lang: en   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2020-11-11   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translators: 
# - name: "@@"   # Replace @@ with translator name
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
  <p><strong>Date:</strong> Updated 13 March 2019.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-std-gl-overview/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces guidelines and other standards related to web accessibility.

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

## Introduction {#intro}

The World Wide Web Consortium (W3C) develops international Web standards: <abbr title="Hypertext Markup Language">HTML</abbr>, <abbr title="Cascading Style Sheets">CSS</abbr>, and many more. W3C's Web standards are called <dfn>W3C Recommendations</dfn>.

All W3C standards are reviewed for accessibility support by the Accessible Platform Architectures ([APA](/about/groups/apawg/)) Working Group.

The W3C standards and Working Group Notes introduced below are particularly relevant to accessibility.

## Accessibility Guidelines {#guidelines}

[[Essential Components of Web Accessibility]](/fundamentals/components/) shows how web accessibility depends on several components of web development and interaction working together, and how the WAI guidelines (WCAG, ATAG, UAAG) apply.

### 웹 콘텐츠 접근성 지침 (WCAG) {#wcag}

웹 "콘텐츠"는 일반적으로 웹 페이지나 어플리케이션 안의 정보를 가리킵니다. 다음의 내용으르 포함합니다. : 

* 텍스트, 이미지, 소리와 같은 기본 정보
* 구조나 표현 방법 등을 정의한 코드나 마크업

WCAG는 다양한 콘텐츠, 멀티미디어, "모바일" 등에 적용됩니다. WCAG는 [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/)에서 명시하듯이 웹이 아닌 정보 통신 기술(ICT)에도 적용됩니다. 

WCAG 정보: 
- [WCAG 개요](/standards-guidelines/wcag/)
- [[WCAG 2.1 한눈에 보기]](/standards-guidelines/wcag/glance/)
- [WCAG 2를 충족하는 방법 (빠른 참조)](https://www.w3.org/WAI/WCAG21/quickref/)
- [WCAG 2.0 표준](https://www.w3.org/TR/WCAG20/)
- [WCAG 2.1 표준](https://www.w3.org/TR/WCAG21/)

### 웹 저작 도구 접근성 지침 (ATAG) {#atag}

저작도구는 "저자" (웹 개발자, 디자이너, 작가 등)가 웹 콘텐츠를 생산하는 데에 사용하는 서비스나 소프트웨어를 가리킨다. 예를 들어, HTML 에디터, 콘텐츠 관리 시스템 (CMS), 사용자가 콘텐츠를 생산할 수 있는 블로그나 소셜 네트워킹 사이트가 있다. ATAG 문서는 다음 내용을 목표로 한다. :

* 저작도구의 접긍성을 더 좋게 하여 장애가 있는 사용자가 웹 콘텐츠를 생산할 수 있도록 하고, 
* 저자가 더 접근성이 좋은 웹 콘텐츠를 생산하는 것을 돕는다.

ATAG 정보:
- [ATAG 개요](/standards-guidelines/atag/)
- [[ATAG 한눈에 보기]](/standards-guidelines/atag/glance/)
- [ATAG 2.0 표준](https://www.w3.org/TR/ATAG/)

### 사용자 에이전트 접근성 지침 (UAAG) {#uaag}

사용자 에이전트는 브라우저, 브라우저 확장프로그램, 미디어 플레이어, 리더기와 같은 웹 콘텐츠를 제공하는 어플리케이션을 포함합니다.  

UAAG 정보:
- [UAAG 개요](/standards-guidelines/uaag/)
- [UAAG 2.0 Note](https://www.w3.org/TR/UAAG20/)

## 기술 명세

### 접근가능한 리치 인터넷 어플리케이션 (WAI-ARIA) {#aria}

ARIA는 의미를 제공하여 저자가 유저 인터페이스 행동이나 구조적 정보를 스크린 리더와 같은 보조 기술에 전달할 수 있게 합니다. ARIA 기술 명세는 역할, 상태, 접근가능한 유저 인터페이스 요소로 정의되는 속성들의 온톨로지를 제공합니다.  

ARIA 모음은 유저 에이전트 실행 가이드라인을 제공하는 명세를 모은<abbr title="응용 프로개름 프로그래밍 인터페이스">API</abbr>를 포함합니다. 그래픽, 디지털 출판을 위한 모듈 또한 포함됩니다. 

ARIA 정보:
- [WAI-ARIA 개요](/standards-guidelines/aria/) – [모듈, API 맵핑 목록과 설명](/standards-guidelines/aria/#versions)을 포함합니다.
- [WAI-ARIA 저작 연습](https://www.w3.org/TR/wai-aria-practices/)
- [WAI-ARIA 1.1 표준](https://www.w3.org/TR/wai-aria-1.1/)

### 오디오와 비디오 {#multimedia}

- [WebVTT: 웹 비디오 텍스트 트랙 형식](https://www.w3.org/TR/webvtt/)는 오디오나 비디오에 대한 캡션, 비디오에 대한 텍스트 설명, 시간순으로 정렬된 다른 메타 데이터를 위한 형식입니다.

- [타임드 텍스트 마크업 언어 (TTML)](https://www.w3.org/TR/ttml/)는 자막과 캡션을 위한 법적 배포 콘텐츠 형식들 간의 타임드 텍스트 정보를 트렌스코딩하거나 변환하기 위해 사용되는 것을 목적으로 한다. 

### 평가 {#eval}

The following resources support development of accessibility evaluation methods and tools:
다음 자료들은 접근성 평가 방법과 도구의 개발을 지원합니다.: 

- [[접근성 부합 여부 테스트(ACT) 개요]](/standards-guidelines/act/) &mdash; ACT는 웹 콘텐츠가 접근성 표준에 부합하는지 테스팅하기 위한 원칙들을 문서화하고 발행합니다.

- [[평가와 보고 언어 (EARL) 개요]](/standards-guidelines/earl/) &mdash; EARL는 테스트 결과를 보여주기 위한 기계가 읽을 수 있는 형식입니다.

평가와 관련된 추가 자료들은 [[웹 접근성 평가 개요]](/test-evaluate/)에 기록되어 있습니다. 다음 자료도 포함되어 있습니다. : 

- [[WCAG-EM 개요: 웹사이트 접근성 부합 평가 방법론]](/test-evaluate/conformance/wcag-em/) &mdash; WCAG-EM은 웹 사이트가 웹 콘텐츠 접근성 지침(WCAG)에 얼마나 부합하는지를 결정하는 접근법입니다.

### 개인화

[[개인화 개요]](/personalization/) &mdash; 개인화는 각 개인의 사용자의 선호와 필요를 충족시키기 위한 사용자 경험을 조정하는 것을 포함합니다. 콘텐츠 저자는 최소한의 공수로 기본 디자인을 제공하고, 사용자 개인화가 가능하도록 하는 데에 개인화 표준을 사용할 수 있습니다. 

## W3C WAI의 다른 영역

- [[W3C의 모바일 접근성]](/standards-guidelines/mobile/)

- [[W3C의 인지 접근성]](/cognitive/)

## 추가 정보 {#moreinfo}

- [W3C 접근성 전체 목록 -관련된 표준 ("W3C Recommendations")과 실무 그룹 기록](https://www.w3.org/TR/#tr_Accessibility__All_)

- [[웹 접근성 법과 정책]](/policies/) 목록은 전 세계 나라, 지역의 웹 접근성과 관련된 정부 차원의 법과 정책을 정리하였습니다. 이중 대부분은 W3C 접근성 표준을 참고하고 있습니다.

- [[Why Standards Harmonization is Essential to Web Accessibility]](/standards-guidelines/harmonization/)

- [[Referencing and Linking to WAI Guidelines and Technical Documents]](/standards-guidelines/linking/)

- [How WAI Develops Accessibility Guidelines through the W3C Process: Milestones and **Opportunities to Contribute**](/standards-guidelines/w3c-process/)

![illustration showing the guidelines for the different components, detailed description at https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.png" | relative_url }})
