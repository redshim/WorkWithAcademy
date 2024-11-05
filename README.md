### 1111
https://teams.microsoft.com/l/meetup-join/19%3ameeting_MTBiZjNmMzEtZmRkYS00ZWFkLTg3MTItMWMyMWZiYjExZjQ4%40thread.v2/0?context=%7b%22Tid%22%3a%22f85ca5f1-aa23-4252-a83a-443d333b1fe7%22%2c%22Oid%22%3a%229512adcc-f9d5-4b42-847d-31bce0c0c4ba%22%7d
https://teams.microsoft.com/l/meetup-join/19%3ameeting_MTBiZjNmMzEtZmRkYS00ZWFkLTg3MTItMWMyMWZiYjExZjQ4%40thread.v2/0?context=%7b%22Tid%22%3a%22f85ca5f1-aa23-4252-a83a-443d333b1fe7%22%2c%22Oid%22%3a%229512adcc-f9d5-4b42-847d-31bce0c0c4ba%22%7d

#

http://121.134.159.217:41248/lab/tree/Demo


https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb


gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb


PHM 고장예측 공동연구실 킥오프
1. 윤병동 교수님 - PHM 플랫폼 방향성
	1) CAN 데이터 기반 차량 중량 예측 : 샤시 서스펜션 성능, 제어 등 영향을 미칠수 있기 때문에 차량 중량을 예측하는것은 중요하다.
		비용효율적으로 할수 있는 방법
		페라리,히타치(진동),굿이어(주행기반 가속도 속도데이터) 중량 추정 모델 개발
		한계점 - 추가센서활용 가속도속도, 실자적용 적합성이 낮다.
		종/횡방향 가속도 앙상블 모델
	PHM 기술 노화 열화를 예측하는 기술 
	
	2) PHM 플랫폼 방향성
		미래 모빌리티 트렌드 변화 CASE conectivity, autonomous, Shared Mobilty Electrification
		SDV 기술중에서 PHM 기술이 중요한 기술
		전장화 고장이 급격히 발생, 전조증상을 탐지하기 어려움
		
		모델링 알고리즘, 레이블링, 데이터파이프라인견고화, AI MLOPs 
		PINN AI MLOPs 
		
2. 성균관대학교 Cloud API 기반 샤시계 고장 진단 시스템 구현 위한 프레임워크 개발
	1. 온보드 API 클라우드 서버전송 : 멀티모달 관점 딥러닝 모드 개발. 클라우드 단에서 개발 가능한 
		타이어, 모터에 촛점을 맞춰서 개발
		모든데이터를 클라우드서버에 올리는것은 부담, CAN 신호 특징을 파악해서 올리는것으로 전략
		데이터수집주기, 고장/열화현상 트리거 조건(적응형 데이터수집기술) 
		부품의 여러 차량 조건을 만족할수 있는 산업기반 표준화된 형태 데이터 체인기술 제안 및 검증
		
3. 차량 상태 및 파라미터 예측
	타이어 마모도 예측 기술 
	


이슬기 교수 
	1. 인공지능을 활용한 PHM Embedding 모델 개발(모델 경량화) On device AI
		차량에서 발생하는 데이터로 부터 고장진단, PHM 알고리즘 적용
		
		


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

