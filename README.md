연구소 미래 전략 및 방향성을 관점으로 선행기술 개발 측면의 다양한 과제를 리딩하셨고, Software Defined Vehicle 관점의 독자 기술력 확보 및 선행기술 선도하는 프로젝트를 중점적으로 수행하셨습니다. 특히, 선행기술개발의 유용성을 차량데이터를 활용하여 증명하기 위해서 데이터 활용관점으로 디지털엔지니어링센터와의 적극적인 협업을 강조하여 센터 간의 협업 아이템을 발굴하고 기술개발 단계의 역할분담을 통한 부문간 시너지 확보를 위해서 노력하셨다고 생각합니다. 그 결과로 인공지능 학회 게재를 통해 대외적으로 인정받는 결과를 도출하였습니다. 향후에도 적극적인 기술개발협업을 통해 다양한 기술 과제 협업 아이템을 발굴하고 성공적으로 의미 있는 결과를 도출하여 상호간 윈윈하는 결과물 도출할 수 있게 지원/리딩해주실 것이라 생각합니다



## Usage

To use the Slate theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-slate
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

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

