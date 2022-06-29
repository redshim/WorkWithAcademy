
https://teams.microsoft.com/l/meetup-join/19%3ameeting_MzU0ZjMxNjktYWY0Mi00ZTE1LWE3ZWMtZTI4YTg4ZjU5MTlm%40thread.v2/0?context=%7b%22Tid%22%3a%2201acd45f-97ff-4539-aa93-d2bcf027f631%22%2c%22Oid%22%3a%225b48f9d3-40ce-4ee9-a6db-a7bfa0bb1c00%22%7d

Monday, 23 May, 2022 9:00 KST | 8 hours
https://jftraining.webex.com/jftraining/j.php?MTID=m3ac24bd61584f251bbed89245de7d4c0

Meeting number: 2396 776 3053Password: E32McPXiTV5



https://teams.microsoft.com/l/meetup-join/19%3ameeting_MDM1NWE2ODUtZTg4OS00NDVhLTg5MjEtYTQ1OGY3OTNhZTdl%40thread.v2/0?context=%7b%22Tid%22%3a%22f85ca5f1-aa23-4252-a83a-443d333b1fe7%22%2c%22Oid%22%3a%22cef99daf-b661-42eb-9323-3ebc9a33b67d%22%7d
# WorkWithAcademy
http://www-sop.inria.fr/members/Freddy.Lecue/presentation/aaai_2022_xai_tutorial.pdf

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

