# WorkWithAcademy


https://s3.amazonaws.com/sinjoonk-lab/hol/scripts/BigDataHoL-ver0.3.yaml



https://dashboard.eventengine.run/login?hash=1903-031f8b5de4-bd


https://forms.gle/46UEYVKqjtoKk8Xm9

https://signin.aws.amazon.com/federation?Action=login&Issuer=localhost&Destination=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3Fregion%3Dus-east-1&SigninToken=67WXEHpPCDtNX0ztvmvkOUBFSedyewa_Sezkw9esjL8i2cgI6JWLZ8R88G-WMK3DzNb0Jo_CmR2xTKDigDGfXVXljDts-b0sQIhAmL8bH-eROfSI--nviYJMksy97nPshZ0Ac9Cm4cDZ8JnVC5XVEWrA5wK6mu07Bh7iqA7FDPqBePiNHsB62P6iti4FSmf9NYwV_adUvpCJNYGNLW8h5-XjZQZHP89-EdpG2GSJySe94XaCWp2iwE1osfI_7viK08RAR6-RhrsR75PVOcRVKFfAXDhDYoNstYG5pFg_b7vQrkSxXtlfDEgfdGbbcK4qos67diI-vvA1fz1Au5CmmjkcLbSYwcNKwcNWdqVNnbPIlGi8i6-PxiHrOWc6QBz49SOGMRxOxoKFLsMjplJn33Q3gpaA6XkgdfvN5tHl_5F9opZ1dOYsfTcgDcigslUpm46xbFsXwiO7J4yodBM8DP6wvu3Bt0MpQ8eFKLh3HnSxx8koMLbK_TiMBpIewBA37DjDPIT78tXYdFA6eADhFoNaL4Vsi_sHPJCXncJSKSsPQejreCdSmjgWn_LLwEMF8LZrDHqqw4D0nISI00_sHFTJ6JSKo_8nXUT6BBpaBr3HxsZZCIf-h2ZF7fPWDfM2bNhAbij1w6dTWqflH4mqrWmWhwmKaS-BxHxulezAE4NPCuqdps9Bz1wJs0pb7_z3Qkc5O3pS6r6mcie28oYOR-nPaEzaKDMzatgSCEGLhfr0rz47XR1BCza9mmGQVBD1hNAyB-nzDz8F12l0Fg9MN0m_o6jbqQmhoElxPSiU1ErnPxwkI-07i32aFS0HN9EtHB19mJOCuK6P3CqAtNtOyE9__tgwnwyetbXjgZeRMdMIlpwS-t3rhOtXtIebQy6sP9I2kta6tJVa4f-D50QN-skWu7P565fYn_mThrGG1gPEu-euCFmRusx5W9kxm0pjBRgDINwTevttSwO1Tt5DrM3PFoopfKnEYVd6u3xr6ODVrFIFVGCduupNKwf85wjW94ja3EKmQUx63vwntXF30g23s1-gY7kK3_qmgbr6ioSq0Z7S9DbU7FzTNcZIZHyIoIZsfwYihW5eJlrmsOdPp196YPKc_Ky4YuJolxHupbmQeRPKv8oTx1pKz3qX2XAINGB5rqwHjc6QA0vQXdCh0EYj3Yn5LVBcLeoyxu7Rv0bkkQo8K_1_rm7r97tvzv844dVYbP6moRmjICLJJGVp-ur3y7ggW0n4BWOKUagmkGM6rCR3Rn4vzclnw-J3-wYdGljB_55hJyP6ubAeG7sjlrkKhUOwaXccfZgIDLx8ODrQEYa9_bSVZ1TRN5aQg3qXNnMB302xlMOQD4xhcsEIbeHevBZaxXiM3eaqtOOvzE0QEu2SyAyxeZ9DyEeZdWEM7X5gLPmzYfM46mWDZoXd3F8D4Q

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

