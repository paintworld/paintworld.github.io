---
title: "토탈페인트 네트워크"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: 도료에 대한 이해를 도움으로써 페인트에 대한 기초를 통해 응용제품에 대한 이해도를 높일 수 있도록 두와 줄 것입니다.
---

{% include note.html content="If you're cloning this theme, you're probably writing documentation of some kind. I have a blog on technical writing here called <a alt='technical writing blog' href='http://idratherbewriting.com'>I'd Rather Be Writing</a>. If you'd like to stay updated with the latest trends, best practices, and other methods for writing documentation, consider <a href='https://tinyletter.com/tomjoht'>subscribing</a>. I also have a site on <a href='http://idratherbewriting.com/learnapidoc'>writing API documentation</a>." %}

## 페인트 개요

페인트의 구성은 수지(RESIN), 안료(pigment) , 체질안료(TALC),신나(THINNER)로 기본구성을 하고 있으며,					
수지(RESIN)의 종류에 따라 수성페인트.유성페인트,분체페인트등으로 또 분류하며,					
또한 수지의 성분구성에 의해  유성페인트는 락카페인트, 에나멜페인트, 에폭시페인트, 우레탄페인트로 크게 분류하여					
사용하고 있는데, 일반인들은 수성페인트와 에나멜페인트,친환경페인트 혹은 방수용 수성우레탄페인트를 					
주로 생활에 사용하고 있는 편이다					
					
  이외에도 U.V페인트, 세라믹페인트, 우레아페인트, ,불소페인트, 선박용페인트등 특수페인트 들은 					
공업용과 산업용, 또는 도장공장등에 그 기능과 사용방법에 따라 다양하게 사용중이며,					
특히 그 용도와 작업성등의 필요에 따라  페인트제조사들은 새로운물성과 기능을 매일 개발중이다					


### 1. 수지(RESIN)

First, download or clone the theme from the [Github repo](https://github.com/tomjoht/documentation-theme-jekyll). Most likely you won't be pulling in updates once you start customizing the theme, so downloading the theme (instead of cloning it) probably makes the most sense. In Github, click the **Clone or download** button, and then click **Download ZIP**.

### 2. 안료(PIGMENT)

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows]

### 3. 체질안료(TALC)

In case you haven't installed Bundler, install it:

```
gem install bundler
```

You'll want [Bundler](http://bundler.io/) to make sure all the Ruby gems needed work well with your project. Bundler sorts out dependencies and installs missing gems or matches up gems with the right versions based on gem dependencies.

### 4. 첨가제(ADD AGENT)

Use this option if you're not planning to publish your Jekyll site using [Github Pages](https://pages.github.com/).

Bundler's Gemfile specifies how project dependencies are managed. Although this project includes a Gemfile, this theme doesn't have any dependencies beyond core Jekyll. The Gemfile is used to list gems needed for publishing on Github Pages. **If you're not planning to have Github Pages build your Jekyll project, delete these two files from the theme's root directory:**

* Gemfile
* Gemfile.lock

If you've never run Jekyll on your computer (you can check with `jekyll --version`), you may need to install the jekyll gem:

```
gem install jekyll
```

Now run jekyll serve (first change directories (`cd`) to where you downloaded the project):

```
jekyll serve
```

### 5. 신나(THINNER)
If you *are* in fact publishing on Github Pages, leave the Gemfile and Gemfile.lock files in the theme.The Gemfile tells Jekyll to use the github-pages gem. **However, note that you cannot use the normal `jekyll serve` command with this gem due to dependency conflicts between the latest version of Jekyll and Github Pages** (which are noted [briefly here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)).

You need Bundler to resolve these dependency conflicts. Use Bundler to install all the needed Ruby gems:

```
bundle update
```

Then *always* use this command to build Jekyll:

```
bundle exec jekyll serve
```

If you want to shorten this long command, you can put this code in a file such as jekyll.sh (on a Mac) and then simply type `. jekyll.sh` to build Jekyll.

## 페인트 제조사

국내 페인트 제조사는   (주)KCC , 조광페인트㈜, 노루표페인트, 삼화페인트, 제비표페인트 등 대형5개사가 				
있으며, 그외 신동페인트㈜, 등등 많은 중소기업 페인트 제조사들이 있다				
또한 외국회사로는 ㈜IPK , 조광요턴, 츄코쿠삼화, PPG코리아 등이 있다				

<pre>
---

< 페인트 제조사 공식 사이트>

조광페인트	http://www.ckpc.co.kr					
KCC페인트	www.kccworld.co.kr/ 					
삼화페인트	www.samhwa.com/ 					
노루표페인트	www.noroopaint.com/ 					
강남제비스코	www.jevisco.com/ 					
IPK	https://100.daum.net/encyclopedia/view/47XCOMD000266	

---
</pre>


## 도료의 종류 및 기능 소개


### 1. 우레탄도료 [ Urethane paint ]

요약 폴리우레탄을 주성분으로 한 도료로 폴리우레탄도료라고도 한다. 밀착성·내약품성·내용제성(耐溶劑性)·내마모성(耐磨耗性)·내후성(耐候性)이 뛰어나 공장설비나 기계장치·전기부품의 도장(塗裝)에 쓰인다.						
폴리우레탄도료라고도 한다. 내약품성(耐藥品性)·목재용·고무용·전기절연용 도료로서 공장설비나 기계장치·전기부품의 도장(塗裝)에 쓰인다. 밀착성·내약품성·내용제성(耐溶劑性)·내마모성(耐磨耗性)·내후성(耐候性)이 뛰어나다.						
[네이버 지식백과] 우레탄도료 [urethane paint] (두산백과)						

### 2. 수성도료 [ Water paint ]

도료를 칠하기 쉽게 하는 데 쓰는 매체로 물을 사용하는 도료이다. 보통 안료와 카세인 같은 수용성 호재의 수용액을 혼합한 도료를 일컫는다. 보통 안료와 카세인 · 젤라틴 · 녹말 등의 수용성 호재(水溶性糊材)의 수용액을 혼합한 도료를 말한다. → 에멀션 페인트.
[네이버 지식백과] 수성 도료 (대한건축학회 건축용어사전)


### 3. 분체 도료 [ Powder coating , 粉體塗料 ]

용제를 사용하지 않고 분말 상태에서 도장하고 가열하여 용융시켜 도막을 형성하는 도료. 
이에는 에폭시 아크릴폴리에스테르 등의 열경화성 타입이 사용된다.						
도장법에는 유동 침적법, 정전 도장법 등이 있다. 유기 용제를 전혀 사용하지 않기 때문에 휘발성 유기 화합물(VOC)이 적고, 환경 보호에 적합한 도료이다. 또한 유기용제로 인한 중독이나 인화의 위험도 없고 도막은 수십 마이크로미터(μm)에서 수백 마이크로미터(μm) 정도로 용제계와 같은 돌출이나 패임이 적고, 내구성도 훌륭하다. 공정에서 도착되지 않은 도료는 회수하여 재이용이 가능하나, 발색에서는 개선이 필요하다. 색 교체 시 용제계 도료와 같이 간단치가 않고 총비용이 많이 들며, 작업면의 평활성에서 외관상 문제가 있다.						
분체 도료는 일반적으로 입자의 직경이 작은 것이 미관상 좋은 반면, 평균 입자 크기보다 작은 미세한 분말이 많이 포함되어 있는 경우에는 도장의 효율이 거꾸로 낮아지고, 외관도 좋지 않다.						
최근에는 미립자 분말 도료가 개발되어 입자의 평균 지름이 25μm로 종래의 분체 도료보다 미세해지고, 표준 편차가 20μm 이하로 입자가 균일해져서 도장 대상품의 패인 부분에도 균일한 부착성을 나타내며, 용제 도료에 버금가는 평활한 작업면을 얻을 수 있다. 이러한 특징 때문에 종래의 분체 도료로는 이루기 어려웠던 박막화가 가능하고, 도료의 사용량도 3할 정도 낮출 수 있으며 비용이 높다는 문제도 해결되어, 휴대 전화나 개인용 컴퓨터 등과 같은 IT관련 기기를 시작으로 가전 전기 제품, 주방용품, 사무용품, 자판기, 건축 제재, 미관재 등에 광범위하게 사용되고 있다.						
[네이버 지식백과] 분체 도료 [powder coating, 粉體塗料] (색채용어사전, 2007., 박연선, 국립국어원)						


### 4. 아크릴수지도료 [ Acryl 樹脂塗料 ]

① 아크릴수지를 주성분으로 하여 용제에 용해제조한 도료.
② 용액형의 도료로는 자연 건조형(래커제) 및 가열건조형(열경화성)인 것이 생산 공급되고 있으나, 알루미늄 · 경금속 · 아연과 같은 금속에도 잘 부착되기 때문에 주로 금속 표면 도장용으로도 사용.
③ 도막은 단단하며 색채가 선명하여 보색성이 좋고 광택도 오래 갈 뿐 아니라, 부착성 · 내수성 · 내오염성 · 내약품성 · 내유성 및 내자외선성이 매우 강함. 특히 열경화성 도료는 단단하고 부착성이 좋기 때문에 한번에 원하는 도막을 만들 수 있음.
④ 래커제의 도료는 차량(차량 · 경차량) · 비행기 · 전기기구 · 가구 및 조리대류 등에 사용하며, 열경화성 도료는 강판 · 알루미늄판 등의 공업용 도장에 이용하고, 가정 전기기구 · 건축재 · 가구 및 집기류 등에도 사용.
[네이버 지식백과] 아크릴수지도료 [acryl 樹脂塗料] (대한건축학회 건축용어사전)


### 5. 곰팡이 방지 도료 [ Fungus resistant paint ]

바탕이나 도막에 곰팡이가 피는 것을 방지하기 위해 구리나 수은 및 유기 살균제 등을 혼입한 도료이다.						
[네이버 지식백과] 곰팡이 방지 도료 [fungus resistant paint] (공조냉동건축설비 용어사전, 2011. 1. 15., 공조설비용어사전 편찬회)						

### 6. 내알칼리성 도료 [ Alkali proof paint ]

합성수지류로 만든 알칼리에 강한 도료. 욕실이나 새로 바른 콘크리트 위에 칠해도 비누화하지 않는다.						
[네이버 지식백과] 내알칼리성 도료 [耐alkali性塗料, alkali proof paint] (대한건축학회 건축용어사전)						

### 7. 정전 도료 [ Electrostatic Coating, Electrostatic Spraying ]

일반적으로 피도장물을 양극, 분무장치를 음극으로 하여 직류고전압을 걸어 정전기를 대전시킨 분무상의 도료를 물품에 전기적으로 흘려 도장하는 방법. 도료 손실이 적고, 에너지 절약에는 좋으나, 요철부의 도료 부착이 적고, 전기 불량도체에는 특수한 장치를 필요로 하며, 설비비가 고가이다.
[네이버 지식백과] 정전 도료 [Electrostatic Coating, Electrostatic Spraying] (도금기술 용어사전, 2000. 6., 성주창)

### 8. 전착 도료 [ Electrophoretic Painting , 電着塗料 ]

(1) 전기 분해에 의해 전극에 도료를 전착시키는 과정.						
(2) 수용성 수지 도료를 넣은 수조 내에 전극과 도장 재료를 넣고, 직류 전압을 걸어 전기영동에 의해 도장하는 방법.						
[네이버 지식백과] 전착 도료 [Electrophoretic Painting, 電着塗料] (국방과학기술용어사전, 2021. 05. 31.)						


### 9. 발광도료 [ luminous paint ]

단파장의 빛 에너지를 가시광선으로 변화시킬 수 있는 물질을 함유하는 도료. 형광도료·축광(蓄光)도료·야광도료가 있다.			
형광도료는 도막이 빛을 받아 형광을 내게 하여 밝고 선명한 색을 드러내는 도료이며 옥외간판·안전표지 등에 사용된다.			
축광도료는 일광·자외선·전등 따위에 노출되면 빛에너지가 도막에 축적되어 광원이 없어도 어두운 곳에서 장시간 빛나는 도료이며 안전표지·낚시도구 등에 사용된다.			
야광 도료는 빚을 받지 않아도 도막이 어두운 곳에서 빛나는 도료로 축광성 안료에 방사성 동위원소를 첨가한 것을 안료성분으로 한다.			
동위원소에서 방사되는 β선에 의해 발광이 지속된다.			
안료와 비히클은 별도 용기로 판매되며, 발광도료 중 가장 비싸다.			
정밀 계기의 문자판, 라디오·시계의 지침, 중요표지에 사용된다.			

### 10. 시온도료 [ heat sensitive paint , thermo-paint , 示溫塗料 ]

① 일정한 온도가 되면 색이 변화하는 안료를 써서 만든 특수 도료.
② 도막 중에 안료를 포함시켜 일정한 온도가 되면 변색함. 이에 따라 온도를 측정.
③ ＝카멜레온도료＝서모페인트(thermo paint)＝측온도료.
④ 2차대전 전 독일에서 서모컬러라는 상품명으로 시판.
⑤ 온도에 의한 색의 변화가 1회만 있는 것과 온도의 상승에 따라 여러 번 색이 변하는 것이 있으며, 또 온도가 내려가면 원색이 되는 것과 되지 않는 것이 있음.
⑥ 전기기구의 과열에 의한 위험 방지 · 위험물의 용기 · 저장고의 온도 지시 · 노(爐)의 내부 · 원동기 운전시의 온도측정 등에 쓰임.
[네이버 지식백과] 시온도료 [heat sensitive paint, thermo-paint, 示溫塗料] (대한건축학회 건축용어사전)




```yaml
-
  scope:
    path: ""
    type: "pages"
  values:
    layout: "page"
    comments: true
    search: true
    sidebar: home_sidebar
    topnav: topnav
```

If you want to set different sidebar defaults based on different folders for your pages, specify your defaults like this:

```
-
  scope:
    path: "pages/mydoc"
    type: "pages"
  values:
    layout: "page"
    comments: true
    search: true
    sidebar: mydoc_sidebar
    topnav: topnav
```

This would load the `mydoc_sidebar` for each file in **pages/mydoc**. You could set different defaults for different path scopes.

For more detail on the sidebar, see [Sidebar navigation][mydoc_sidebar_navigation].

## Top navigation

The top navigation works just like the sidebar. You can specify which topnav data file should load by adding a `topnav` property in your page, like this:

```yaml
topnav: topnav
```

Here the topnav refers to the `_data/topnav.yml` file.

Because most topnav options will be the same, the `_config.yml` file specifies the topnav file as a default:

```yaml
-
  scope:
    path: ""
    type: "pages"
  values:
    layout: "page"
    comments: true
    search: true
    sidebar: home_sidebar
    topnav: topnav
```

## Sidebar syntax

The sidebar data file uses a specific YAML syntax that you must follow. Follow the sample pattern shown in the theme, specically looking at `mydoc_sidebar.yml` as an example: Here's a code sample showing all levels:

```yaml
entries:
- title: sidebar
  product: Jekyll Doc Theme
  version: 6.0
  folders:
  - title: Overview
    output: web, pdf
    folderitems:

    - title: Get started
      url: /index.html
      output: web, pdf
      type: homepage

    - title: Introduction
      url: /mydoc_introduction.html
      output: web, pdf

  - title: Release Notes
    output: web, pdf
    folderitems:

    - title: 6.0 Release notes
      url: /mydoc_release_notes_60.html
      output: web, pdf

    - title: 5.0 Release notes
      url: /mydoc_release_notes_50.html
      output: web, pdf

  - title: Tag archives
    output: web
    folderitems:

    - title: Tag archives overview
      url: /mydoc_tag_archives_overview.html
      output: web

      subfolders:
      - title: Tag archive pages
        output: web
        subfolderitems:

        - title: Formatting pages
          url: /tag_formatting.html
          output: web

        - title: Navigation pages
          url: /tag_navigation.html
          output: web

        - title: Content types pages
          url: /tag_content_types.html
          output: web
```

Each `folder` or `subfolder` must contain a `title` and `output` property. Each `folderitem` or `subfolderitem` must contain a `title`, `url`, and `output` property.

The two outputs available are `web` and `pdf`. (Even if you aren't publishing PDF, you still need to specify `output: web`).

The YAML syntax depends on exact spacing, so make sure you follow the pattern shown in the sample sidebars. See my [YAML tutorial](mydoc_yaml_tutorial) for more details about how YAML works.

{% include note.html content="If you have just one character of spacing off, Jekyll won't build due to the YAML syntax error. You'll see an error message in your console that says \"Error ... did not find expected key while parsing a block mapping at line 22 column 5. Error: Run jekyll build --trace for more information.\" If you encounter this, it usually refers to incorrect indentation or spacing in the YAML file. See the example mydoc_sidebar.yml file to see where your formatting went wrong." %}

Each level must have at least one topic before the next level starts. You can't have a second level that contains multiple third levels without having at least one standalone topic in the second level. If you need a hierarchy that has a folder that contains other folders and no loose topics, use a blank `-` item like this:

```yaml
entries:
- title: sidebar
  product: Jekyll Doc Theme
  version: 6.0
  folders:
  - title: Overview
    output: web, pdf
    folderitems:

    -

  - title: Release Notes
    output: web, pdf
    folderitems:

    - title: 6.0 Release notes
      url: /mydoc_release_notes_60.html
      output: web, pdf

    - title: 5.0 Release notes
      url: /mydoc_release_notes_50.html
      output: web, pdf

  - title: Installation
    output: web, pdf
    folderitems:

    - title: About Ruby, Gems, Bundler, etc.
      url: /mydoc_about_ruby_gems_etc.html
      output: web, pdf

    - title: Install Jekyll on Mac
      url: /mydoc_install_jekyll_on_mac.html
      output: web, pdf

    - title: Install Jekyll on Windows
      url: /mydoc_install_jekyll_on_windows.html
      output: web, pdf
```

To accommodate the title page and table of contents in PDF outputs, each product sidebar must list these pages before any other:

```yaml
- title:
  output: pdf
  type: frontmatter
  folderitems:
  - title:
    url: /titlepage
    output: pdf
    type: frontmatter
  - title:
    url: /tocpage
    output: pdf
    type: frontmatter
```

Leave the output as `output: pdf` for these frontmatter pages so that they don't appear in the web output.

For more detail on the sidebar, see [Sidebar navigation][mydoc_sidebar_navigation] and [YAML tutorial][mydoc_yaml_tutorial].

## Comments

The theme integrates [Commento.io](https://commento.io/) for comments below pages and posts. (This commenting service doesn't inject controversial tracking ads like Disqus does.) You will need to Commento.io account + plan ($5/month) to authorize Commento with your domain (no other configuration should be required). If you don't want comments, in the \_config.yml file, change the `comments: true` properties (under `defaults`) to `comments: false` in every instance. Then in the commento.html include file (inside \_includes), the `{% raw %}{% unless page.comments == false %} ... {% endunless %}{% endraw %}` logic will not insert the Commentio form.

## Relative links and offline viewing

This theme uses relative links throughout so that you can view the site offline and not worry about which server or directory you're hosting it. It's common with tech docs to push content to an internal server for review prior to pushing the content to an external server for publication. Because of the need for seamless transferrence from one host to another, the site has to use relative links.

To view pages locally on your machine (without the Jekyll preview server), they need to have the `.html` extension. The `permalink` property in the page's frontmatter (without surrounding slashes) is what pushes the files into the root directory when the site builds.

## Page frontmatter

When you write pages, include these same frontmatter properties with each page:

```yaml
---
title: "Some title"
tags: [sample1, sample2]
keywords: keyword1, keyword2, keyword3
last_updated: Month day, year
summary: "optional summary here"
sidebar: sidebarname
permalink: filename.html
---
```

(You will customize the values for each of these properties, of course.)

For titles, surrounding the title in quotes is optional, but if you have a colon in the title, you must surround the title with quotation marks. If you have a quotation mark inside the title, escape it first with a backlash `\`.

Values for `keywords` get populated into the metadata of the page for SEO.

Values for `tags` must be defined in your \_data/tags.yml list. You also need a corresponding tag file inside the tags folder pages/tags/ that follows the same pattern as the other tag files shown in the tags folder. (Jekyll won't auto-create these tag files.)

If you don't want the mini-TOC to show on a page (such as for the homepage or landing pages), add `toc: false` in the frontmatter.

The `permalink` value should be the same as your filename and include the ".html" file extension.

For more detail, see [Pages][mydoc_pages].

## Where to store your documentation topics

You can store your files for each product inside subfolders following the pattern shown in the theme. For example, product1, product2, etc, can be stored in their own subfolders inside the \_pages directory. Inside \_pages, you can store your topics inside sub-subfolders or sub-sub-folders to your heart's content. When Jekyll builds your site, it will pull the topics into the root directory and use the permalink for the URL.

Note that product1, product2, and mydoc are all just sample content to demonstrate how to add multiple products into the theme. You can freely delete that content.

For more information, see [Pages][mydoc_pages] and [Posts][mydoc_posts].

## Configure the top navigation

The top navigation bar's menu items are set through the \_data/topnav.yml file. Use the top navigation bar to provide links for navigating from one product to another, or to navigate to external resources.

For external URLs, use `external_url` in the item property, as shown in the example topnav.yml file. For internal links, use `url` the same was you do in the sidebar data files.

Note that the topnav has two sections: `topnav` and `topnav_dropdowns`. The topnav section contains single links, while the `topnav_dropdowns` section contains dropdown menus. The two sections are independent of each other.

## Generating PDF

If you want to generate PDF, you'll need a license for [Prince XML](http://www.princexml.com/). You will also need to [install Prince](http://www.princexml.com/doc/installing/).  You can generate PDFs by product (but not for every product on the site combined together into one massive PDF). Prince will work even without a license, but it will imprint a small Prince image on the first page, and you're supposed to buy the license to use it.

If you're on Windows, install [Git Bash client](https://git-for-windows.github.io/) rather than using the default Windows command prompt.

Open up the css/printstyles.css file and customize the email address (`youremail@domain.com`) that is listed there. This email address appears in the bottom left footer of the PDF output. You'll also need to create a PDF configuration file following the examples shown in the pdfconfigs folder, and also customize some build scripts following the same pattern shown in the root: pdf-product1.sh

See the section on [Generating PDFs][mydoc_generating_pdfs] for more details about setting the theme up for this output.

## Blogs / News

For blog posts, create your markdown files in the \_posts folder following the sample formats. Post file names always begin with the date (YYYY-MM-DD-title).

The news/news.html file displays the posts, and the news_archive.html file shows a yearly history of posts. In documentation, you might use the news to highlight product features outside of your documentation, or to provide release notes and other updates.

See [Posts][mydoc_posts] for more information.

## Markdown

This theme uses [kramdown markdown](http://kramdown.gettalong.org/). kramdown is similar to Github-flavored Markdown, except that when you have text that intercepts list items, the spacing of the intercepting text must align with the spacing of the first character after the space of a numbered list item. Basically, with your list item numbering, use two spaces after the dot in the number, like this:

```
1.  First item
2.  Second item
3.  Third item
```

When you want to insert paragraphs, notes, code snippets, or other matter in between the list items, use four spaces to indent. The four spaces will line up with the first letter of the list item (the <b>F</b>irst or <b>S</b>econd or <b>T</b>hird).

```
1.  First item

    ```
    alert("hello");
    ```

2.  Second item

    Some pig!

3.  Third item
```

See the topics under "Formatting" in the sidebar for more information.

## Automated links

If you want to use an automated system for managing links, see [Automated Links][mydoc_hyperlinks.html#automatedlinks]. This approach automatically creates a list of Markdown references to simplify linking.

## Other instructions

The content here is just a getting started guide only. For other details in working with the theme, see the various sections in the sidebar.

{% include links.html %}
