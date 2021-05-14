---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.

title: Gambaran Umum Standar Aksesibilitas W3C  # Do not translate "title:". Do translate the text after "title:".
nav_title: "Standar/Panduan" # A short title that is used in the navigation

lang: id   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry

last_updated: 2021-05-08   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators: 
- name: "Fri Rasyidi"   # Replace @@ with translator name
#  link: @@
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple translators
# contributors:
# - name: "@@"   # Replace @@ with contributor name, or delete this line if none
# - name: "@@"   # Replace @@ with name, or delete this line if not multiple contributors

ref: /standards-guidelines/   # Do not change this
changelog: /standards-guidelines/changelog/
layout: default
github:
  repository: w3c/wai-std-gl-overview
  path: content/index.id.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
permalink: /standards-guidelines/id   # Add the language shortcode to the end; for example /standards-guidelines/fr
feedbackmail: wai@w3.org

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
  <p><strong>Tanggal:</strong> Diperbarui 30 April 2021. CHANGELOG.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Dikembangkan dengan masukan dari Kelompok Kerja Edukasi dan Pendampingan (<a href="https://www.w3.org/WAI/EO/">EOWG</a>).</p>

# Read Important Translations Guidance at https://www.w3.org/WAI/about/translating/#important
# Read Translations Notes for this resource at https://github.com/w3c/wai-std-gl-overview/blob/master/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Ringkasan" class="full" %}
{:/}

Halaman ini memperkenalkan panduan dan standar lainnya terkait aksesibilitas web.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Daftar isi" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Pengantar {#intro}

Konsorsium World Wide Web (W3C) mengembangkan standar web internasional: <abbr title="Bahasa Penanda Hiperteks">HTML</abbr>, <abbr title="Lembar Gaya Berjenjang">CSS</abbr>, dan banyak lagi. Standar Web W3C dikenal dengan nama <dfn>Rekomendasi W3C</dfn>.

Untuk mendukung aksesibilitas, semua standar W3C ditinjau oleh Kelompok Kerja Arsitektur Platform yang Aksesibel ([APA](/about/groups/apawg/)).

Standar W3C dan Catatan Kelompok Kerja yang diuraikan di bawah ini sangat relevan dengan aksesibilitas.

## Panduan Aksesibilitas {#guidelines}

[[Komponen Esensial dari Aksesibilitas Web]](/fundamentals/components/) menunjukkan bagaimana aksesibilitas web bergantung pada kerja sama dari beberapa komponen pengembangan dan interaksi web, serta bagaimana pedoman WAI (WCAG, ATAG, UAAG) diterapkan.

### Panduan Aksesibilitas Konten Web (WCAG) 2 {#wcag2}

"Konten" Web pada umumnya merujuk pada informasi dalam halaman atau aplikasi web, termasuk:

* informasi standar seperti teks, gambar, dan suara
* kode atau penanda yang menentukan struktur, presentasi, dll.

WCAG berlaku untuk konten dinamis, multimedia, "seluler", dll. WCAG juga dapat diterapkan ke teknologi informasi dan komunikasi (TIK) non-web, seperti yang dijelaskan dalam [WCAG2ICT](/standards-guidelines/wcag/non-web-ict/).

Informasi seputar WCAG 2:
- [Gambaran Umum WCAG](/standards-guidelines/wcag/)
- [[Selayang Pandang WCAG 2.1]](/standards-guidelines/wcag/glance/)
- [Cara memenuhi WCAG 2 (Referensi Singkat)](https://www.w3.org/WAI/WCAG21/quickref/)
- [[Terjemahan WCAG 2]](/standards-guidelines/wcag/translations/)
- [Standar WCAG 2.0](https://www.w3.org/TR/WCAG20/)
- [Standar WCAG 2.1](https://www.w3.org/TR/WCAG21/), [[Yang Baru di WCAG 2.1]](/standards-guidelines/wcag/new-in-21/)
- [[Yang Baru di Draf Kerja WCAG 2.2]](/standards-guidelines/wcag/new-in-22/)

### Pedoman Aksesibilitas Sarana Penulisan (ATAG) {#atag}

Sarana penulisan adalah perangkat lunak dan jasa yang digunakan oleh "para penulis" (pengembang web, desainer, penulis konten, dsb.) untuk membuat konten web. Sebagai contoh: editor HTML, sistem pengelola konten (CMS), dan situs yang memungkinakan pengguna untuk menambahkan konten, seperti blog dan situs jejaring sosial. Dokumen ATAG menjelaskan bagaimana cara untuk:
* membuat sarana penulisan tersebut aksesibel, sehingga para penyandang disabilitas dapat membuat konten web, dan
* membantu para penulis membuat konten web yang aksesibel.

Informasi seputar ATAG:
- [Gambaran Umum ATAG](/standards-guidelines/atag/)
- [[Selayang Pandang ATAG]](/standards-guidelines/atag/glance/)
- [Standar ATAG 2.0](https://www.w3.org/TR/ATAG/)

### Pedoman Aksesibilitas Agen Pengguna (UAAG) {#uaag}

Agen pengguna termasuk browser, ekstensi browser, pemutar media, perangkat pembaca, dan aplikasi lainnya yang menerjemahkan konten web.

Informasi seputar UUAG:
- [Gambaran Umum UAAG](/standards-guidelines/uaag/)
- [Catatan UAAG 2.0](https://www.w3.org/TR/UAAG20/)

### Draf Kerja Pedoman Aksesibilitas Konten Web (WCAG) 3 W3C {#wcag3}

WCAG 3 adalah draf awal yang ditujukan untuk menjadi Standar W3C. WCAG 3 berlaku untuk konten web, aplikasi, alat, penerbitan, dan teknologi baru dalam web.

Informasi seputar WCAG 3:
- [[Pengantar WCAG 3]](/standards-guidelines/wcag/wcag3-intro/)

## Spesifikasi Teknis

### Aplikasi Internet Kaya yang Aksesibel (WAI-ARIA) {#aria}

ARIA menyediakan semantik agar penulis web dapat menyampaikan perilaku antarmuka pengguna dan informasi struktural ke teknologi pendukung (seperti pembaca layar). Spesifikasi ARIA menyediakan hakikat peran (*roles*), keadaan (*states*), dan properti yang mendefinisikan elemen antarmuka pengguna yang aksesibel.

Rangkaian ARIA mencakup spesifikasi pemetaan <abbr title="Antarmuka Pemrograman Aplikasi">API</abbr> yang menyediakan panduan implementasi agen pengguna. Termasuk juga modul untuk Publikasi Digital dan Grafis.

Informasi seputar ARIA:
- [Gambaran Umum WAI-ARIA](/standards-guidelines/aria/) – mencakup [daftar dan deskripsi pemetaan modul dan API](/standards-guidelines/aria/#versions)
- [Praktek Penulisan WAI-ARIA](https://www.w3.org/TR/wai-aria-practices/)
- [Standar WAI-ARIA 1.1](https://www.w3.org/TR/wai-aria-1.1/)

### Audio dan Video {#multimedia}

- [WebVTT: Format Trek Teks Video Web](https://www.w3.org/TR/webvtt/) adalah format untuk teks, deskripsi video berbentuk teks, dan metadata lainnya yang waktunya diselaraskan dengan konten video atau audio.

- [Bahasa Penanda Teks Berjadwal (TTML)](https://www.w3.org/TR/ttml/) dimaksudkan untuk digunakan antar format konten distribusi lama terkait konversi transcoding atau bertukar informasi teks berjadwal untuk pembuatan teks video.

### Evaluasi {#eval}

Sumber informasi berikut mendukung pengembangan metode dan sarana evaluasi aksesibilitas:

- [[Gambaran Umum Uji Kesesuaian Aksesibilitas (ACT)]](/standards-guidelines/act/) &mdash; ACT menetapkan dan mendokumentasikan aturan untuk menguji kesesuaian konten web dengan standar aksesibilitas.

- [[Gambaran Umum Bahasa Evaluasi dan Laporan (EARL)]](/standards-guidelines/earl/) &mdash; EARL adalah format yang dapat dibaca oleh mesin dalam mengekspresikan hasil pengujian.

Sumber informasi tambahan terkait evaluasi terdapat pada [[Gambaran Umum Mengevaluasi Aksesibilitas Web]](/test-evaluate/), termasuk:

- [[Gambaran Umum WCAG-EM: Metodologi Evaluasi Kesesuaian Aksesibilitas Situs Web]](/test-evaluate/conformance/wcag-em/) &mdash; WCAG-EM adalah sebuah pendekatan untuk menentukan seberapa baik kesesuaian sebuah situs terhadap Pedoman Aksesibilitas Konten Web (WCAG).

### Personalisasi

[[Gambaran Umum Personalisasi]](/personalization/) &mdash; Personalisasi melibatkan penyesuaian pengalaman pengguna untuk memenuhi kebutuhan dan preferensi masing-masing pengguna. Penulis konten dapat menggunakan standar personalisasi untuk menyediakan pengaturan awal pada desain dan memungkinkan personalisasi dengan usaha minimal.

### Pengucapan

[[Gambaran Umum Pengucapan]](/pronunciation/) &mdash; Pengucapan adalah mengenai pengucapan konten dengan benar oleh pembaca layar dan penerjemah teks-ke-suara (TTS).

## Area kerja W3C WAI lainnya

- [[Aksesibilitas Seluler pada W3C]](/standards-guidelines/mobile/)

- [[Aksesibilitas Kognitif pada W3C]](/cognitive/)

## Informasi Tambahan {#moreinfo}

- [Daftar semua Standar W3C yang berhubungan dengan aksesibilitas ("Rekomendasi W3C") dan Catatan Kelompok Kerja](https://www.w3.org/TR/?tag=accessibility)

- [[Hukum dan Kebijakan Aksesibilitas Web]](/policies/) daftar hukum dan kebijakan pemerintah terkait aksesibilitas pada negara-negara dan daerah-daerah di seluruh dunia. Dari daftar tersebut, banyak yang merujuk pada standar aksesibilitas W3C.

- [[Mengapa Penyelarasan Standar Penting untuk Aksesibilitas Web]](/standards-guidelines/harmonization/)

- [[Menautkan dan Merujuk ke Panduan dan Dokumen Teknis WAI]](/standards-guidelines/linking/)

- [Bagaimana WAI Mengembangkan Panduan Aksesibilitas melalui Proses W3C: Target dan **Kesempatan untuk Berkontribusi**](/standards-guidelines/w3c-process/)

![ilustrasi yang menunjukkan pedoman untuk berbagai komponen, uraian terperinci pada https://www.w3.org/WAI/intro/components-desc.html#guide]({{ "/content-images/wai-std-gl-overview/specs.png" | relative_url }})
