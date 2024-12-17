### 1111
https://teams.microsoft.com/l/meetup-join/19%3ameeting_NGE3MTZiZjUtYjg0Ny00NzE0LThlMDAtMDI3MDIyNzQ0YmZi%40thread.v2/0?context=%7b%22Tid%22%3a%22f85ca5f1-aa23-4252-a83a-443d333b1fe7%22%2c%22Oid%22%3a%225c97e0ed-9076-4513-86a8-8d2d17b3fbed%22%7d



#

http://121.134.159.217:41248/lab/tree/Demo


https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb


gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb

2024/12/17
내구 TCC 워크샵
조직변화 : 차량 성능 + 고성능 TBD 개발 통합담당,
+----------------------------------------------------------------------------------------------------------------------+
내구 
--> 전문가 위원회(설계, 시험) 내구 TCC 역할 고민(내구시험, 내구해석, 상용쪽 전자신뢰성 등 다양한 부문 참여 연속성있게 ) 제안
내년에도 연속적으로 진행

내구 TCC 주요활동
Phase1 
 - 만프레도 부사장님 : 품질관련 비용 증가, 주행성능 향상도 필요하다.
 - 기본성능 향상 TFT 
	> 내구영역 : 내구시험팀 팀장/파트장 위주 구성원 참여 
    > 경쟁차 대비 부족한 점 파악
	> PT, 배터리 등 인원 보강 품질/내구개선위한 방향성 수립 
	> VDS 기존 결과 활용 하여 GAP 분석 수행 : 인포테인먼트, 외장, ADAS, PT 등 취약 (LX2, RG3, CN7, OS)
	> CR 신뢰성 지수 개선 필요 : 다른 영역은 Top 항목인데 비해서 신뢰성 지수 취약
    > 품질비용 보증비용/리콜 캠페인 분석 : 클레임 율은 샤시부품이 교체용이성으로 높은데 비해서, 비용을 분석 필요(PT 시스템 Top)
		취약부문 - HEV 배터리 모듈/시스템, 엔진 베어링/피스톤링(2세대 엔진 보증비용이 끝나지 않아서..), 변속기, 엔진, 냉각수 컨트롤
Phase2
 - 문제점 리뷰를 통한 추진 액티비티 정의 활동(PT,변속기, 모터/감속기 등 베어링 소손 증상 선제대응) 전기차 판매대수,마일리지 올라가면 문제점 대응 필요
	배터리 제작공정(간극,쇼트) 품질 문제 초기 품질문제 대응, 배터리TFT 내 품질개선 활동	
 - 샤시 : FMEA 활동
 - 최고속 내구 : 고속조건 주행시 안보이는 문제점 발생(한계를 뛰어넘는 개발기준 정립 필요) 아우토반 주행 NVH, 내구 떨림, 토잉 capacity(유기연) 증대
	FTA(Failure Tree Analysis) 

연구소에서 생산공정 관련 이해하는 전문가 필요하다.
해외 연구소 검증 역량 커버리지 늘리는 이슈
배터리 개발센터 내구/신뢰성 도움필요
파워트레인 부분도 필드 문제점 재현성 검증 부분도 도움 필요(엔진/변속기/PE 시스템등)
샤시시스템 조향,현가,제동쪽 전문가들 참여요청
+----------------------------------------------------------------------------------------------------------------------+
최고속 내구시험 강화방안
누구사장님 유럼에서 출퇴근중 문제 발생, 와이퍼 닦임성능 NVH 등 경쟁사 대비 문제 
만프레도 부사장님 : 포르쉐 주행시험 예로 제네시스 차량 적용검토
뉘버그링내구 : 고성능 EV, ICE 1만 km 480 LAP, 이외차종 5천 km
대상 : 제네시스 마그마 확대 적용(기아 GT 포함) 
남양 PG --> 카트리(220kph 이상) 
유럽 소비자 190KM 2000KM 정도 되더라(마이라) 근거 공력부품이상, 엔진누유, 와이퍼 성능
아우토반 플릿 검토
+----------------------------------------------------------------------------------------------------------------------+
북미 픽업트럭 토잉성능 내구 선행개발
- 토잉내구 : 동적하중, 정하중 강화하여 11000 파운드 TDP 재개정
+----------------------------------------------------------------------------------------------------------------------+
공동연구실 개요
Safty, CBM(타이어, 샤시시스템, 모터감속기) , Data Platform, Digital Twin

상용버추얼개발팀 장홍석
PHM TF 업무 소개 -선제적 고장 진단/예측 기술
업타임 센터 구축 대방동 DTC 기반 모니터링
Uptime PHM  연계
+----------------------------------------------------------------------------------------------------------------------+
AI-powered Digital Twin chassis Twin
디지털 샤시트윈기술 적용
AD/ADAS 고장 한계 진단 기술
Foundation model
운전자 성향별 마모정도 학습 AAE-VAE 운전자 성향 분류(가상운전자모델)
운전성향과 마모정도간의 관계성 확인 --> 옴니버스 상 운전자모델-차종 간 마모 상관성
운전성향(주행패턴) 휠속 가감속 요레이트등 CAN 데이터활용
운전 성향별 부품 마모정도 학습
가감속 조향 제동 통함 시나리오 --> 운전자 공격성 지표 판단(속도, 가속도) 극단적인행동, 평균적인행동 파악가능
실제 운전자 주행데이터 활용 성향 패턴 도출 및 검증
제동주행패턴, 제동효율성, 마모도
간단한 마모모델 적용하여 연속성있게 추정가능한 모델 생성

+----------------------------------------------------------------------------------------------------------------------+
휠속센서 기반 타이어 압력/하중 추정기술
주요 연구실적 : 차량동력학 및 제어 2. 시스템 모델 기반 주행환경 시스테 ㅁ상태 추정
Data Agumentation 을 통한 차종간 모델 전계
모델 기반 주파수 특성 제어
iTPMS(indirect TPMS) 타이어 압력 추정
휠속센서를 활용한 타이어의 상태 추정기술 개발을 위한 목적 압력, 하중, 마모 예측으로 확장
C 코드로 차량에 이식해서 적은 계산량으로 예측 모델 반영
타이어-휠 진동모형
고유진동수

실시간 임베딩하여 하중 예측(한국타이어 산학)

+----------------------------------------------------------------------------------------------------------------------+
차량 PHM 기술 북미출장
크래들 PoC 협업 논의
Siemens 배터리 제조 결함감지 Digital Twin
AI 로보틱스, 벤쳐캐피탈 인원 참석
PHM 학회 - Unist 아주대 정준하 교수 데이터챌린지
LLM 사고경위 리포팅 웨스팅하우스, 원자력발전, 회전기기분야 고장예측, 산업계 적용가능한 PHM기술
12V 내부저항 전류변화 활용 Health Index GM 온스타

		


!!!!!!





https://opendrivelab.com/AD23Challenge.html
https://drive.google.com/file/d/11Ky0z0RKp7Uzh1mOpd9Mr5mk_dZjW387/view?usp=sharing


## Usage

To use the Slate theme:

1. Add the following to y
2. our site's `_config.yml`:

    ```yml
    theme: jekyll-theme-slate
    ```

3. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Slate will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/slate/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/slate/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```

