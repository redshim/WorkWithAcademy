미국등록특허 10915764는 영상을 통해 획득된 도로 표면의 상태를 검출하도록 구성된 특허로서, 

등록청구항에 따르면 A road surface detecting 하는 구성에서는, 

획득된 노면의 이미지를 분할하여 학습시키고, 

도로 표면 이벤트를 분류하도록 구성된 분류장치로 구성됩니다.


그 외 독립항에서는 해당 도로 표면의 상태에 한정사항이 없으며, 

이에 따라 도로의 파손, 횡단보고, 과속방지턱 및 기타 사항들을 폭 넓게 특허 적용이 가능합니다.


이와 같은 구성은 자사에서 출시되거나 예정인 차량 뿐만 아니라, 

경쟁사 브랜드에서 출시될 자율주행차량등에서도

운전자의 운전 보조 수단으로 활용되거나,

자율주행레벨 0~5 사이의 모든 차량에 탑재되어 적용가능합니다.


이에 따라, 적극적으로 본 특허를 확보/유지하여 자사의 특허경쟁력 강화에 활용되는것이 바람직합니다.


https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb


gemini/use-cases/retrieval-augmented-generation/multimodal_rag_langchain.ipynb



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

