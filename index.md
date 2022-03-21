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


### 11. 방청도료 [ rust resisting paint , 防錆塗料 ]

요약 각종 금속, 특히 철이 녹스는 것을 방지하기 위한 도료이다. 공기·물·이산화탄소 등이 금속면과 접촉하는 것을 방지하고 또 화학적으로 녹의 발생을 막는 두 가지 작용을 해야 한다. 대표적인 종류에는 유성 페인트, 광명단 페인트가 있다.
금속의 녹은 공기·물·이산화탄소 등의 작용에 의한 것이므로, 방청도료는 이것들과 금속면이 접촉하는 것을 방지하고 또 화학적으로 녹의 발생을 막는 두 가지 작용을 해야 한다. 초벌칠용은 바탕금속에 대한 부착력이 특히 강해야 하며, 덧칠용은 특히 도막(塗膜)이 공기나 수분을 통과시키지 않고 흡수성이 좋으며, 균열이 잘 생기지 않고 내후성·내구력이 커야 한다. 건성유(乾性油)와 방청안료를 조합한 유성 페인트가 주가 되며, 광명단(光明丹:사삼산화납)과 보일유(油)를 조합한 광명단 페인트가 널리 사용된다.

광명단 대용 방청도료로는 아연분말, 아산화납, 염기성 크로뮴산아연(아연황), 염기성 크로뮴산납(징크크로마이트) 등의 안료를 사용하는데, 뒤의 두 가지는 화학적 방청작용이 있다. 이 밖에 산화철분이나 벵갈라[鐵丹] 단독 또는 아연화(亞鉛華)·광명단과의 혼합물을 안료로 하는 것이 있다. 또 전색재(展色材)로는 덧칠이나 초벌칠에 각각 알맞은 것을 사용하는데, 보일유 외에 오일 니스, 합성수지 니스 등이 많이 사용된다.

근래에 알루미늄·아연·주석 등의 금속에 대한 방식처리(防蝕處理)에 염기성 크로뮴산아연과 인산과 뷰티랄 수지를 알코올·케톤·물로 된 혼합용제로 분산시킨 도료가 사용되고 있으며, 에팅프라이머라 불린다. 선박·차량, 일반 금속재의 도장(塗裝)을 우선 이것으로 방식처리하고, 이어서 도장하는 방법이 널리 쓰이고 있다. 또한 선박 바닥을 바닷물이나 고착생물의 부착으로부터 보호하는 도료도 방청도료의 일종이다.
[네이버 지식백과] 방청도료 [rust resisting paint, 防錆塗料] (두산백과)

### 12. 방화도료 [ fireproof coating , 防火塗料 ]

요약 목재 또는 플라스틱 등 가연성 물질에 도포(塗布)하여 착화(着火)를 방지하거나 착화시간을 지연시키는 도료이다. 난연성(難燃性)재료에 의한 것과, 가열되면 발포하여 가연물질(可燃物質)과의 사이에 차단층을 만들어 열이 전도되는 것을 지연시키는 것이 있다.
방화도료는 난연성(難燃性)재료에 의한 것과, 가열되면 발포하여 가연물질(可燃物質)과의 사이에 차단층을 만들어 열이 전도되는 것을 지연시키는 것의 두 종류가 있다. 전자는 물유리 ·각종 에멀션 수지 ·염소화합물 등의 난연재료에 각종의 안료나 불연 고체물질을 첨가한 것이다. 후자는 아민계의 합성수지를 주체로 하고 각종 방화제 ·발포제와 단열탄화 형성제(斷熱炭化形成劑)를 사용해서 가열에 의해 도막(塗膜)이 열분해되어 불연성 가스를 발생하는 것과 수cm 두께의 스펀지 모양으로 된 단열층을 형성함으로써 가연물에 열을 전하는 것을 지연시키는 것이다.
[네이버 지식백과] 방화도료 [fireproof coating, 防火塗料] (두산백과)

- 무기질 방화 도료 : 석회유, 규산나트륨, 마그네시아 시멘트 등의 무기질 교착제를 전색제로 하고, 안료, 방화제(인산 화합물, 붕산 화합물, 할로겐 화합물 등)를 배합하여 만든다. 도포 건조 후 공기 중의 이산화탄소를 흡수하여 경화하거나 인산수소칼슘, 아연 분말 등으로 녹지 않게 한다. 밀착성, 휨성, 내후성, 미장 효과는 떨어진다.

- 수성 방화 도료 : 밀크 카세인, 대두 카세인, 수용성 요소 수지 등의 전색제와 안료, 방화제 등을 배합하여 만든다. 물로 녹여 바른다.

- 발포성 방화 도료 : 요소 수지와 멜라민 수지를 전색제로 하며, 사용 전에 인산암모늄, 인산아닐린 등의 인산염, 붕산염, 암모늄염 등을 발포제로서 첨가하여 바른다. 화재가 났을 때 불연성 가스를 발생하며, 빵과 같이 거품층이 생겨 방화 목적을 달성한다.

- 비발포성 방화 도료 : 보일유, 프탈산 수지, 요소 수지, 멜라민 수지, 비닐 수지 바니시에 클로로파라핀, 염화고무를 가한 전색제에 안료를 가해 반죽하여 만든다. 체질 안료로서는 특히 탄산칼슘, 규산염, 바륨염을 사용하며, 백색 안료로서는 특히 산화안티몬을 사용하면 내화성이 향상한다. 밀착성, 휨성, 내후성, 미장 효과가 뛰어나며 방화 도료로서 널리 사용되고 있다.


### 13. 내열도료 [ heat resistant coating , 耐熱塗料 ]

요약 100℃ 이상의 고온으로 되는 물체에 칠하여 내식(耐蝕)이나 미관 유지의 구실을 하는 도료이며 전동기, 변압기, 난방기구 등을 칠하는 데에 사용된다. 
100℃ 이상의 고온으로 되는 물체에 칠해도 변색·균열·연화(軟化)·휘발·박리(剝難) 등의 파손이 일어나지 않거나 손상이 가벼운 도료를 말한다. 안료(顔料)로는 알루미늄 가루, 아연 가루, 흑연, 백색주석, 규조토, 아연화(亞鉛華:산화아연), 타티타늄백, 군청(ultramarine), 카드뮴레드, 리토폰, 황산납, 앰버(amber), 석면 등 내열성의 것이 사용된다. 도막(塗膜)의 주요소인 전색제(展色劑)로는 내열성이 최고인 실리콘수지가 많이 사용되며, 이 밖에 너무 고온이 되지 않는 부분의 도료로는 타이타늄산에스터·에폰·페놀수지·프탈산수지·슈퍼니스 등의 유기물이 사용된다.

이전에는 규산나트륨 등의 무기물도 사용되었으나, 현재는 사용되지 않는다. 고내열안료를 첨가한 실리콘수지 도료는 500℃ 이상에서 몇 시간 동안 사용해도 견딘다. 또 알키드수지 등으로 변성(變性)한 실리콘수지는 변성하지 않은 수지에 비해 내열성이 부족하다. 전동기·변압기·석면제품·기관·반응관(反應管)·난방기구·노(爐)의 바깥벽 등을 도장하는 데에 사용된다.
[네이버 지식백과] 내열도료 [heat resistant coating, 耐熱塗料] (두산백과)

### 14. 캐슈도료 [ cashew resin paint ]

요약 열대성 식물인 옻나무과 캐슈의 과실 껍질에 함유되어 있는 액을 주원료로 한 유성도료로서 천연산 옻과 비슷한 성질로 합성 칠도료라고도 한다. 이 액에 포르말린 등을 작용시키면, 주성분인 카르단올과 카르돌이 중합하여, 점조성(粘稠性)의 흑갈색의 액체를 얻을 수 있다. 이것이 캐슈도료인데, 내열성 ·내유성(耐油性) ·내약품성이며 전기절연도도 우수하다. 광택은 우수하지만 천연 옻칠처럼 내후성(耐候性)에 약한 결점이 있다.
천연산 옻과 비슷한 성질로 합성 칠도료라고도 한다. 이 액에 포르말린 등을 작용시키면, 주성분인 카르단올과 카르돌이 중합하여, 점조성(粘稠性)의 흑갈색의 액체를 얻을 수 있다. 이것이 캐슈도료인데, 내열성 ·내유성(耐油性) ·내약품성이며 전기절연도도 우수하다. 광택은 우수하지만 천연 옻칠처럼 내후성(耐候性)에 약한 결점이 있다.
건조성과 도막의 성질을 개선하기 위하여, 알키드수지 ·멜라민수지 ·요소수지 등을 첨가하여 사용하는데, 상온 건조도 가능하고, 베이킹도료로도 사용된다. 목재와 금속에 대한 부착력이 좋아서 차량이나 목공용 밑바탕 도료, 특히 가구의 도장(塗裝)에 많이 쓰인다. 건조 도막은 내용제성(耐溶劑性)이 커서 다른 많은 도료를 겹쳐서 칠할 수 있으며, 가격이 싸고 사용법이 간단하여 천연 옻칠 대용으로 칠기나 공예품의 도장에 쓰인다.
[네이버 지식백과] 캐슈도료 [cashew resin paint] (두산백과)

### 15. 선박용 도료 [ 船舶用塗料 , marine paint ]

선박에 사용되는 도료. 방식, 방오, 방조, 미장 등의 목적으로 사용된다. 해양이란 매우 가혹하고 다양한 환경에서 사용되므로 매우 많은 종류의 도료가 있으며 모두 고품질 도료이다. 선저 도료, 수선(水線)도료, 외현(外舷) 도료 등 사용 부위에 따라 호칭이 다르다. 방오, 방조 도료, 에폭시 수지 도료, 염화고무 도료, 딩크리치 도료 등이 사용된다.
[네이버 지식백과] 선박용 도료 [船舶用塗料, marine paint] (화학용어사전, 2011. 1. 15., 화학용어사전편찬회, 윤창주)

### 16. 선저도료 [ ship-bottom paint , 船底塗料 ]

요약 수면 아래의 외판 부식과 오손을 방지하기 위하여 사용되는 페인트.
선박전용의 가장 중요한 도료로서 여러 종류가 있다.
① 1호 선저도료(anticorrosive paint:AC):선저의 강판은 해수에 젖으므로 잘 부식된다. AC 페인트는 방청용(防선저도료 본문 이미지 1用) 선저도료로서 외판에 직접 또는 광명단·워시프라이머(wash primer) 위에 바르며, 그 위에 바르는 2호 선저도료가 다량의 독물을 함유하므로 독물에 의한 강판의 부식을 방지하기 위한 중간 도료로서의 역할도 한다. 따라서 건조가 빠르고 방청력이 커야 한다. 강판과 밀착도 잘되고 진동에 의하여 떨어지지 않아야 하며, 2호 선저도료와도 잘 떨어지지 않아야 한다.
② 2호 선저도료(antifouling paint:AF):경하흘수선(輕荷吃水線) 아래쪽 선저부에 발라 해중생물(패류·해조류)의 부착을 방지하는 선저방어용 도료이다. 성분 중에 유독한 수은과 구리의 화합물인 산화수은·이산화구리를 함유하여 직접 강판에 바르면 이를 부식시키므로 AC도장 후 약 2시간 경과 한 다음 바른다. 따라서 AF와 AC는 잘 밀착되고 해수에 강하며, 건조가 빠르고 도막에 균열이 생기지 않아야 한다. 그리고 건조도막은 해수 중에서 독물이 서서히 표면으로부터 조금씩 녹아서 독물화합물·독물이온에 의하여 생물의 부착을 방지하고, 부착된 것은 탈락시킬 수 있어야 한다.
③ 3호 선저도료(boot topping paint:BT):수선부, 즉 만재흘수선과 경하흘수선 사이에 AC 위에 바르는 도료. 수선 부근은 해수에 젖었다 말랐다 하며, 파도의 충격을 많이 받고, 통선이나 부선 등이 마찰에 의해 마모되므로 선체 중 가장 부식마모가 심하다. 또 해중생물도 부착하므로 도료는 내구성과 함께 방오성·방수성이 있어야 한다. AC, AF와 함께 에나멜 페인트이지만 특히 방청과 내마모성에 중점을 둔 것이다.
④ 목선용(木船用) 선저도료:목선도 강선과 같이 해중생물이 부착하는 이외에 해충에 의하여 선저가 침식된다. 이를 방지하기 위하여 이산화구리를 주요 독물로 하는 코퍼(copper) 페인트가 주로 사용된다.
[네이버 지식백과] 선저도료 [ship-bottom paint, 船底塗料] (두산백과)


### 17. 방오도료 [ 防汚塗料 , antifouling paint ]

따개비, 굴, 말류의 부착을 방지하는 도료. 오염방지 도료라고도 한다. 선박 밑바닥 도료가 대표적 예이다. 실용되고 있는 도료는 이산화 구리, 유기 주석계 화합물을 포함한다. 오염방지제의 용출속도 제어가 중요하다. 최근에는 독물을 함유하지 않는 방오 도료도 사용되고 있다.
[네이버 지식백과] 방오 도료 [防汚塗料, antifouling paint] (화학용어사전, 2011. 1. 15., 화학용어사전편찬회, 윤창주)


### 18. 오염 방지 도료 [ 汚染防止塗料 ]

구리를 함유한 도료. 주로 바닷말 따위의 해양 생물이 배의 밑바닥에 달라붙는 것을 막기 위하여 바른다.
[네이버 지식백과] 오염 방지 도료 [汚染防止塗料] (국방과학기술용어사전, 2021. 05. 31.)

### 19. 방식 도료 [ corrosion proof paint , corrosion protective paint ]

부식을 막을 수 있도록 재작된 도료
참고 : 건축학용어사전, 세화
[해양]
강구조물에 있어서는 강재의 방식을 목적으로 사용되는 도료이며 표에 나타내는 것과 같은 것이 있다. 철근콘크리트 구조물용 방식도료로서는 강구조물용 도료 중 비교적 두터운 막두께로 사용되는 것과 동계열의 것이 사용된다. 그렇지만 특히 콘크리트구조물에 적용에 있어서는 내알칼리성 및 하지(下地)의 균열에 대한 추종성(追從性)이 뛰어난 도료를 선택할 필요가 있다. 단 강구조물 및 철근콘크리트 구조물에 있어서도 도료의 선택에는 방식성능은 물론 도막(塗膜)의 외견, 내후성(耐候性), 접착성, 시공성 등에 대해서 상세히 검토할 필요가 있다.
[네이버 지식백과] 방식 도료 [corrosion proof paint, corrosion protective paint] (대한건축학회 건축용어사전)


### 20. 특수도료 [ special paint , 特殊塗料 ]

특수한 원료를 주성분으로 하는 도료, 또는 특수한 방법으로 도장하는 도료(보기；구워붙임 에나멜), 그리고 각종 도료 중에 특히 새롭게 변한 도면을 만드는 도료(보기；크래킹 래커) 등 여러 가지 뜻으로 해석함
[네이버 지식백과] 특수도료 [special paint, 特殊塗料] (대한건축학회 건축용어사전)


### 21. 제거도료 [ stripping paint , 除去塗料 ]

오염제거를 쉽게 하기 위해 고안한 도료. 미리 이것을 발라 두면 피막이 잘 벗겨지므로 표면이 방사능에 오염되더라도 그것을 도료와 함께 벗겨서 처분하고 다시 도장하면 된다.
[네이버 지식백과] 제거도료 [stripping paint, 除去塗料] (원자력용어사전, 2011., 한국원자력산업협회)

### 22. 내산도료 [ acid-proof paint , 耐酸塗料 ]

① 산성물질에 의한 부식 작용을 방지할 목적으로 쓰이는 도료.
② → 내산페인트.
[네이버 지식백과] 내산도료 [acid-proof paint, 耐酸塗料] (대한건축학회 건축용어사전)

### 23. 측온도료
-> 시온도료

### 24. 내면도료 [ enamel for internal protection , 內面塗料 , ないめんとりょう ]

<식품> 통조림 내용물이 관재 금속과 접촉하여 관 내면의 부식을 촉진할 경우 부식 방지 및 내용물의 변색 방지 또는 내용물에 금속취가 옮아오는 것을 방지하기 위하여 양철관 내면에 칠하는 도료
[네이버 지식백과] 내면도료 [enamel for internal protection, 內面塗料, ないめんとりょう] (농업용어사전: 농촌진흥청)

### 25. 절연도료 [ insulating varnish , 絶緣塗料 ]

요약 전선을 절연피복(絶緣被覆)하기 위하여 또는 절연피복한 코일 등의 표면에 바르고, 건조시켜 절연물에 습기가 들어가지 않게 보호하는 도료이다. 휘발성·유성(油性)·아스팔트계(系)·합성수지계 등의 절연도료가 있다.
절연니스라고도 한다. 그 종류에는 휘발성·유성(油性)·아스팔트계(系)·합성수지계 등이 있다. 자연건조니스·전기건조니스 등은 전기기기 코일의 절연에 쓰이며, 동선(銅線) 자체의 절연피복에는 폴리에스터수지·실리콘수지 등이 쓰이고, 규소강판(珪素鋼板)의 표면 절연용으로는 아스팔트계의 코아니스가 있다. 다 같이 절연의 내력(耐力)은 0.1mm당 1만 V 정도이다.
[네이버 지식백과] 절연도료 [insulating varnish, 絶緣塗料] (두산백과)

### 26. 비닐 도료 [ Vinyl Paint , vinyl塗料 ]

비닐계 합성 수지 도료. 알칼리에 강하고 모르타르 바탕면 도장에 적당하며, 내수성이 우수하여 내부 콘크리트, 모르타르, 슬레이트, 사무실 칸막이 등 보수용 · 도장용 및 인테리어가 요구되는 건물 내부 벽면 등에 미장용 도료로 사용된다.
[네이버 지식백과] 비닐 도료 [Vinyl Paint, vinyl塗料] (국방과학기술용어사전, 2021. 05. 31.)

### 26. 도전 도료 [ conductive paint , 導電塗料 ]

도료에 은 등의 미립자를 분산시켜, 고착 후에 도전성을 갖도록 한 것. 부품의 단자에 리드선을 납땜하기 위한 바탕을 만드는 경우 등에 사용한다.
[네이버 지식백과] 도전 도료 [conductive paint, 導電塗料] (전자용어사전, 1995. 3. 1., 월간전자기술 편집위원회)

### 27. 아스팔트도료 [ asphalt paint ]

요약 아스팔트 ·타르(tar) 등의 역청질(瀝靑質)을 용제나 유성(油性) 니스에 용해시킨 도료이다. 내약품성(耐藥品性) ·내수성이 크며, 아스팔트도료 ·흑(黑)니스 등이 있다.
내약품성(耐藥品性) ·내수성이 크며, 아스팔트도료 ·흑(黑)니스 등이 있다. 아스팔트도료는 역청질을 용제에 녹여, 용제가 증발함으로써 건조 ·고체화하는 것으로, 내산(耐酸) ·내습(耐濕)의 목적으로 콘크리트바닥 ·탱크 등의 도장에 쓰인다. 흑니스는 역청질을 오동나무기름 ·아마인유(油) 등에 녹인 것으로, 내약품성이 우수하며, 기계기구, 화학공장의 건축물, 각종 배관 등의 도장에 사용된다. 상온건조(常溫乾燥)와 가열건조가 있으며, 가열건조가 우수하다.
[네이버 지식백과] 아스팔트도료 [asphalt paint] (두산백과)

### 28. 알루미늄도료 [ aluminium paint ]

요약 알루미늄의 분말을 유성(油性) 니스에 안료로 넣어 은색광택을 내는 도료이다. 내구력(耐久力), 피복력(被覆力), 철강재의 산화방지력이 크다. 주로 옥외 도료로 사용되는데, 내열성이 있어 방열(防熱)의 목적으로 석유탱크 ·냉동차 등의 외부도장에 쓰인다.
알루미늄은 대기 중에서 산화되면 알루미나(산화알루미늄)라는 산화막이 형성되어 그 이상 산화가 내부로 침식되는 것을 방지하는 성질이 있으므로, 이 성질을 이용하여 녹막이 도료로 이용된다. 내구력(耐久力), 피복력(被覆力), 철강재의 산화방지력이 크다. 주로 옥외 도료로 사용되는데, 완전 불투명하고 광선의 반사성도 좋으며, 내열성이 있기 때문에 방열(防熱)의 목적으로 석유탱크 ·냉동차 등의 외부도장에 쓰인다.
[네이버 지식백과] 알루미늄도료 [aluminium paint] (두산백과)

### 29. 전파흡수도료 [ electric wave absorption paint , 電波吸收塗料 ]

요약 장애가 되는 전파를 흡수하기 위한 도료를 말한다. 예를 들면, 육지와 섬을 잇는 대교의 가설에 따라 그 부근을 항해하는 선박의 레이더에 위상(僞像)이 생겨, 야간이나 짙은 안개가 낄 때의 안전항행에 영향을 준다.
최근 육지와 섬, 또는 섬과 섬을 잇는 대교의 가설에 따라 그 부근을 항해하는 선박의 레이더에 위상(僞像)이 생겨, 야간이나 짙은 안개가 낄 때의 안전항행에 영향을 준다. 대형선박에서는 마스트와 갑판 위의 구조물로부터의 레이더 전파의 반사로도 위상이 생기는 문제와, 전파의 고스트현상과 전파간섭장애 등의 문제 때문에 전파흡수도료가 개발되었다.
금속표면은 도전성(導電性) 재료와 페라이트를 구성성분으로 한 흡수층과, 페라이트를 배합한 변성층(變成層)과의 2층 구조이다. 2층 구조는 종래의 단층형 페라이트식(式)에 비해 훨씬 폭넓은 주파수대에서 전파를 흡수할 수 있다.

도료는 두껍게 칠할 수 있는 것이어야 하고 내구성이 높아야 한다.
[네이버 지식백과] 전파흡수도료 [electric wave absorption paint, 電波吸收塗料] (두산백과)


### 30. 반투명도료

 도막이 반정도 투명하게 하는 도료.

### 31. 세라믹 도료 [ Ceramic Paint , ceramic塗料 ]

고온에서 구워 만든 비금속 무기질 고체 재료를 사용하여 만든 도료.
[네이버 지식백과] 세라믹 도료 [Ceramic Paint, ceramic塗料] (국방과학기술용어사전, 2021. 05. 31.)

### 32. 열융착 도료 [ thermosetting paint , 熱融着塗料 ]

열경화성 수지의 미분말을 주체로 하는 도료로, 그것을 칠한 표면을 가열하여 융착 경화시켜서 피막을 만드는 것이다. 복잡한 형상의 부품 전체를 절연하는 경우에 쓰인다.
[네이버 지식백과] 열융착 도료 [thermosetting paint, 熱融着塗料] (전자용어사전, 1995. 3. 1., 월간전자기술 편집위원회)

### 33. 카멜레온도료 [ chameleon塗料 ]

① 일정한 온도로 색이 변화하는 화합물을 이용해서 온도를 알 수 있게 한 도료.
② ＝시온(示溫)도료(⇦)＝측온(測溫)도료＝서모컬러.
③ 가열에 의해 변색한 것이 냉각에 의해 환원된 것(可逆性)과 환원하지 않은 것(不可逆性)이 있으며 후자는 온도가 상승할 때에만 쓰임.
[네이버 지식백과] 카멜레온도료 [chameleon塗料] (대한건축학회 건축용어사전)

### 34. 내약품성 도료 [ 耐藥品性塗料 ]

자재 등을 산, 알칼리, 염 등의 약품 용액에 담가도 변화하기 힘든 성질을 가진 도료의 총칭.
[네이버 지식백과] 내약품성 도료 [耐藥品性塗料] (대한건축학회 건축용어사전)

### 35. 베이킹도료 [ baking paint ]

요약 도포(塗布) 후 가열하여 건조하도록 제조된 도료로서, 니스계(系)에는 투명(透明) 베이킹니스와 베이킹흑(黑)니스가 있고, 에나멜계에는 베이킹용의 요소수지도료(尿素樹脂塗料) ·프탈산수지도료 ·멜라민수지도료 ·페놀수지도료 등이 있다. 자동차 차체 ·전기기기 ·기계 등 모든 종류의 금속제품의 고급도장 마무리에 많이 사용된다.
니스계(系)에는 투명(透明) 베이킹니스와 베이킹흑(黑)니스가 있고, 에나멜계에는 베이킹용의 요소수지도료(尿素樹脂塗料) ·프탈산수지도료 ·멜라민수지도료 ·페놀수지도료 등이 있다. 베이킹 도장(塗裝)에 의해 단시간에 견고하고 부착력이 좋은, 게다가 도톰하고 아름다운 도막(塗膜)을 얻을 수 있다. 가열은 전기로(電氣爐)나 적외선으로 하고, 가열온도(80∼360℃)와 시간(20분∼3시간)은 각 도료의 종류에 따라 엄밀하게 선택해야 하며, 만일 그렇지 않을 경우에는 황변(黃變:yellowing)이 생긴다. 자동차 차체 ·전기기기 ·기계 등 모든 종류의 금속제품의 고급도장 마무리에 많이 사용되지만, 목재나 죽재(竹材)에는 적합하지 않다. 또 결정(結晶)베이킹이라 하여, 마무리면(面)에 설화(雪花) 모양의 결정무늬가 형성되도록 하는 방법도 있다.
[네이버 지식백과] 베이킹도료 [baking paint] (두산백과)


### 36. 반사도료 [ refectorized paint , 反射塗料 ] 

노면표시에 사용되는 도료로서 빛을 반사하는 물질을 넣은 도료.
[네이버 지식백과] 반사도료 [refectorized paint, 反射塗料] (대한건축학회 건축용어사전)

### 37. 제진도료 [ damping paint ]

방진도료 또는 방음도료라고도 하며, 자동차의 보닛의 이면이나 상면(床面) 상부에 도장하여 얇은 금속의 비비리 진동을 방지하기 위하여 사용하고 있다. 아스팔트와 같이 점도가 높은 재료를 주체로 이것에 충전제와 방청 도료 등을 배합한 제진재료의 일종이다.
[네이버 지식백과] 제진도료 [damping paint] (철도관련큰사전, 2007. 4. 20., 백남욱, 이상진)


### 38. 방부도료 [ rust proof paint , 防腐塗料 ]

① 목재나 금속의 부식을 막기 위해 표면에 칠하는 도료.
② 주로 목재를 부식(腐蝕)시키는 균(菌)의 번식을 막기 위한 도료.
[네이버 지식백과] 방부도료 [rust proof paint, 防腐塗料] (대한건축학회 건축용어사전)

### 39. 경금속도료 [ 輕金屬塗料 ]

① 알루미늄 · 마그네슘 등의 경금속은 바닷물 · 묽은 산 · 묽은 알칼리 등에 부식되기 쉽고, 또 도막이 잘 부착되지 않기 때문에, 내식성과 부착력이 강한 도료를 필요로 함.
② 바닥칠용 도료로서는 염기성 크롬산아연을 함유한 도료를 사용하며, 전색제에는 페놀수지 니스 · 프탈산수지 니스 · 벤질 셀룰로오스 니스 · 비닐계 수지 니스 등을 사용함.
③ 마그네슘의 바닥칠용 도료에는 연단 · 아연가루 · 염기성 크롬산 납 · 알루미늄 가루 등을 안료에 배합하며, 전색제에는 페놀수지 유성니스 · 벤질 셀룰로오스 니스 · 비닐계 수지 니스 등을 사용함.
[네이버 지식백과] 경금속도료 [輕金屬塗料] (대한건축학회 건축용어사전)

### 40. 에멀션/에멀젼도료 [ emulsion塗料 ]

물에  수성 도료 등을 현탁시킨  액상 도료. 도포 후는 물의 발산에 의해 고화되고, 표면에는 거의 광택이 없는 도막을 만듬.

### 41. 역청질도료 [ bituminous paint , 瀝靑質塗料 ]

비튜멘(원유,아스팔트,피치,석탄)을 전색제로 한 도료. 팽윤 타르를 사용한 타르 에폭시 수지 도료가 많이 알려져 있다
[네이버 지식백과] 역청질도료 [bituminous paint, 瀝靑質塗料] (대한건축학회 건축용어사전)

### 42. 무기질도료 [ 無機質塗料 ]

① 수성도료와 같이 유기질의 고착제를 써서 안료를 고착시키는 것이 아니라, 물속에 흩어진 무기물질이 물경화성 또는 물을 발산시킴에 따라 무기질 자신이 도막을 형성하는 성질을 이용한 도료.
② 일반적으로 강인도가 낮으며, 특히 가요성이 결핍되어 있기 때문에 목재 · 금속 등에 도장할 수 없음.
③ 현재는 불연성을 이용하여 내화도장에 사용되고 있으며, 또 콘크리트 · 모르타르의 착색도장 등에 쓰이는 정도.
[네이버 지식백과] 무기질도료 [無機質塗料] (대한건축학회 건축용어사전)

### 43. 광학 도료 [ 光學塗料 ]

LCD, HDTV 프로젝터, 선글라스, 건축용 유리 및 광섬유 등의 광학 장치에 쓰이는 도료.
[네이버 지식백과] 광학 도료 [光學塗料] (국방과학기술용어사전, 2021. 05. 31.)

### 44. 유기 도료 [ Organic Coatings , 有機塗料 ]

보호용 및 장식용 마감재로 사용되는 인화성 및 가연성 용제를 결합한, 액체 혼합물로 된 도료

### 45. 급결 도료 [ 急結塗料 ]

조색(調色), 경화제의 혼합, 시너 희석을 완료하여 즉시 분사할 수 있는 상태의 도료를 가리키는 말이다.

### 46. 플랫도료 [ flat paint ]

건조 후에도 광택이 나지 않는 도막이 형성되는 도료. 60°거울면 광택도 40~30 이하의 도막이 표준적이다.

### 47. 구리도료 [ Copper Paint , --塗料 ]

구리와 산소의 화합물인 산화구리를 사용하는 도료. 산화구리Ⅰ 및 산화구리Ⅱ가 있다. 산화구리Ⅰ은 주로 구리의 붉은 녹이며, 안료 · 적색 착색제 등으로 쓰인다. 산화구리Ⅱ는 천연에서 흑동석으로 존재하며, 청색 착색제 · 산화제 · 촉매 등으로 쓰인다.
[네이버 지식백과] 구리 도료 [Copper Paint, --塗料] (국방과학기술용어사전, 2021. 05. 31.)

### 48. 내열도료 [ heat resisting paint ]

고열에 잘 견디며 내식성이나 내후성에도 우수하고 미관상으로도 좋은 도료로 100 ℃ 이상의 고열이 있는 장소에 사용한다. 알키드 수지, 페놀 수지는 150℃까지의 장소에, 알키드변성 실리콘 수지·실리콘 수지·불소 수지·티탄산에스텔 수지 등은 150℃ 이상의 장소에 사용한다. 안료로는 알루미늄 가루·아연 가루·탄화규소·흑연·규조토·아연화 산화철 등이 사용된다.
[네이버 지식백과] 내열 도료 [heat resisting paint] (공조냉동건축설비 용어사전, 2011. 1. 15., 공조설비용어사전 편찬회)

### 49. 마감도료 [ setting coat ]

목공예품이나 기계제품, 건축물 외장 등 표면 마감을 위해 칠하는 도료 일체.
목공예품의 경우 보통 사포질로 표면을 정리한 후에 바르는데, 피막을 형성해 표면의 광택을 더하고, 방수와 균열 방지 등 내구성을 높이는 데 효과적이다. 크게 천연 도료, 화학 도료로 구분한다. 천연 도료로는 옻, 들기름, 콩기름, 올리브기름, 잣기름 등을 주로 쓴다.
19세기 이후 천연도료의 확보와 가공의 어려움을 해결하기 위해 화학물을 합성한 다양한 화학 도료가 생산되어 사용되고 있다.
[네이버 지식백과] 마감 도료 [setting coat] (색채용어사전, 2007., 박연선, 국립국어원)

### 50. 이액도료 [ two-component coating ]

주제와 경화제의 혼합으로 일어난 가교 반응에 의해 그물눈 구조로 경화가 이루어지는 타입의 도료.
이에는 에폭시 수지 도료, 우레탄 수지 도료 등이 있으며, 가교 반응은 온도가 높을수록 빨라지고, 섭씨 40~80℃에서 강제 건조시킨다. 열경화형 도료와 같은 치밀한 그물눈 구조를 이루기 때문에 광택이 좋고, 경도, 가소성, 내마모성, 내약품성, 내오염성 등의 도막 성능이 우수하다.
래커보다도 색의 표현 범위가 넓어 자동차 보수용, 목제품, 가구, 플라스틱 제품 등에 폭넓게 사용되고 있으며, 휘발성유기화합물(VOC)의 배출이 적기 때문에 유럽에서는 최근에 자동차 생산라인에서 클리어 코팅(clear coating) 용도로 사용하고 있다.
[네이버 지식백과] 이액 도료 [two-component coating] (색채용어사전, 2007., 박연선, 국립국어원)

### 51. 녹막이도료 [ rust proof paint, rust resisting paint, anticorrosive paint] 

강철재의 겉면에 도포하는 녹 방지가 주목적인 도료로 노출부분일 경우에는 그 위에 다시 마감도장을 하는 것이 좋다.

### 52. 라텍스 도료 [ latex paint] 

유화 중합법으로 생긴 에멀션을 전색제로 한 도료를 말한다.

### 53. 하이솔리드형 도료 [ high solid paint ]

도장할 때의 고형 성분이 용제형 도료 또는 로솔리드형 도료에 비하여 15~25% 정도 높은 도료.
로솔리드형 도료는 시너에 고형 성분을 30% 전후로 희석하여 스프레이 도장을 하나, 이 도료는 고형 성분을 60% 전후까지 높일 수 있어 시너의 희석률이 낮음에도 불구하고 스프레이 도장이 가능하다. 따라서 휘발성 유기 화합물(VOC)의 비율이 낮아 환경 보호용 도료의 하나로 사용되고 있다. 도장할 때에는 도료의 비휘발 성분(NV)을 높이기 위하여 저분자량의 알키드 수지, 아크릴 수지, 멜라민 수지가 사용된다.
하이솔리드 수지는 로솔리드 수지에 비하여 크랙이나 격리, 자외선이나 산화에 대한 대응, 도료 점성의 제어, 기포 대책 등이 필요하고 광휘재의 배향이나 도막의 평활성이 불리한 점이 많기 때문에 이에 필적하는 외관을 확보하기 위하여 베이스 도료와 클리어 도료의 경화 속도를 조정할 필요가 있다. 미들솔리드형 도료는 이 두 가지의 중간형이고, 양쪽의 좋은 점을 활용하려 한 것이다.
[네이버 지식백과] 하이솔리드형 도료 [high solid paint] (색채용어사전, 2007., 박연선, 국립국어원)

### 54. 가역성 온도지시 도료 [ reversible temperature indicating paint , 可逆性溫度指示塗料 ]

온도지시 도료의 일종. 특정한 온도에서 물리변화(전이)를 하여 변색하는 화합물을 온도센서로써 사용한 것인데, 냉각하면 본래의 색으로 복원되는 것이다. 동작온도와 색의 노정하는 변화를 표시한다. 수은화합물을 사용한 것이 많기 때문에 입에 넣어서는 안된다.					
가역성 온도지시 도료					
			
  <pre>

번호		변색 온도(℃)	저온색↔고온색		
저온용	R-4	40	황적색↔주홍색		
	R-5	50	황색↔주황색		
	R-6	60	밝은주황색↔진보라		
	R-7	70	적색↔진보라		
고온용	R-13	130	황색↔등황색		
	R-15	150	담황색↔황색		
	R-17	170	담황록↔황색		

  </pre>

			[네이버 지식백과] 가역성 온도지시 도료 [reversible temperature indicating paint, 可逆性溫度指示塗料] (센서용어사전, 2011. 1. 20., 손병기)		


### 55. 반사 방지 도료 [反射防止塗料] 

반사광으로 인한 광량 손실을 막기 위하여 레인지에 입힌 투명 코팅.

### 56. 카세인수성도료 [casein water paint] 

분말로서, 사용시 물을 넣어 액상으로 하여 씀.

### 57. 락카도료 [ lacquer ]


도료의 하나. 니트로셀룰로스 따위의 유도체를 용제로 하고 수지나 가소제·안료 따위를 가하여 만듬. 래커의 주요 성분이 니트로셀룰로오스란 뜻은 래커의 조성에 니트로셀룰로오스가 양적으로 대부분을 차지하고 있을 뿐만 아니라, 래커의 특성이 주로 니트로셀룰로오스의 성질을 그대로 가지고 있다는 뜻임. 질산·초산·벤질섬유소등의 유도체를 휘발성 용제에 녹여 수지·가소제(可塑劑)·연화제(軟化劑)등을 가하여 만듬. 질산 섬유소를 쓴 것이 대표적이고, 안료를 가하여 조합한 것이「 래커 에나멜」이고, 가하지 않은 것이「 클리어 래커」(투명래커)인데, 보통「 래커」라면 후자를 말함. 건조가 빠르고, 도막이 견고하며, 광택이 좋고, 연마가 용이하며, 불점착성, 내마멸성·내수성·내유성·내후성 등이 강한 고급 도료임. 용도에 따라 금속용·목부용·외부용·솔칠용 등이 있다.
[네이버 지식백과] 래커 [lacquer] (인테리어 용어사전, 2006. 10. 10., 동방디자인 교재개발원)



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
