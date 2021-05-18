# WorkWithAcademy


https://dashboard.eventengine.run/login?hash=9634-0905f2cd74-78



https://signin.aws.amazon.com/federation?Action=login&Issuer=localhost&Destination=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3Fregion%3Dus-east-1&SigninToken=zJ602c_1IAmtSZ3jwJBrs4TOX5anY5h242ettIlRXakzekfH135R2iBvSG9z-yV55Fse8OvQISjJz5q1JhJsoss_ccwEpGr32tRuvkmmpAPW6-ToNfEE9H63OcXKwd0RDL3Aduztv-bOu3piBics1krVGHvpuodN-CiAIBIj6UWgimGtbDB3l1A6-W3dUyU3bUChK2_iukyKpBWzA-PTI5_95dO0uskk37wvq7jrWQODY75g0W5YDgjCkAgeumTvYz9kEuZ4rb7ZTgmGRtFzgjDPOGWGFpx60_7fAv0d05_gm2PhO4F9v0xHMZSr3HiFeVbe-asoTxe8eyraQCGMLrMM9EFy4Y2Z1cFLeSgRJO7TzNQf-be-R2K5VwwEvNjv7dSzBHnmsI2_x6p4oADirNaIn7y-D3ZGpRdav-sNkCgeK75s-0RWGhIcpeokbvQAjL_5735b1pmALNL98g5vpIqnlrlVmuODjEL2bfxeHgCTgX1mSLHO6imCez0DwOahhzqLcemOzponbVVdBqYmpbl9RjokhXGbLmBtlkMqYB6SMrGZEwK1IushN8kIb1V4JgIX8QrpE74QzNFh8gpYTenH1f5i42OZ0B71qLkoZu9-L0PCLVA6K2qz-2Q5sdWul-ZHEYmSl6UWk4aFF4h9B_p4WNamggvdaJdH4TGLWUx2VNAq6MJ0pIM0LRhZHntSGYhG1PiSn4mQymb1J6WzeCtbGYqr6K-2MsfqKnT6GS4eL9C0FFOf1M-8hW_jw5OToAW6ErxXMKY_cGiSy_-sMamT3gHxNk2kcK9ip8JPXiDQ5rnwpa8lIUmiI-J1Y_BV7UL1MH-ArE4MDG7dO5brEqrSvFx7jl_acKSob1aVCCx_ZO4JxSPQwIqEO38G0ZLc_JWiaojso-v6dVbbdpC4R74o3NQmvfuA1wuCKiwRb-UqX0GnTUTLn2sP1ZDb1r4_-1ChUVH4iBrZqmho68SoHAxnkZENPIWIen8woIGiS5MTIxv4Li5r7A9r3qpaJfeiLcwtPWtj_nS-9kEk8u1Ua6rmgipWoZO-lHFaAuYDChkv6hISdRu9yEtSQNpJccXxpSZtzSMvboHdodFeGTIkpwEoJ4UGul2Ey7K-Mad_5VuKEINGM_yXJbOeKo0gVODZX-J9jyp_o7vrFseQBAL0dFvj39CHIYFvJT7pKIECV08ntkGd0J9i2sNKa8hUDI2SbH6UYhLm1ew7zhgTsJLt93M-du240aQvGVOOCYBrB8VS0PYyEiF_eM5XhCd7vNeOsJfz9z86FpjZe6Scn7D_zeXy4j0tlSwYsM0uordZGcVrCnQnCJgcl2B6XXeg0h80z4B4RhSAIHLgCfujAbtHZ3xe9fjDNsf6yVep8qE9j7ru0gpl55XoNUzN5MWARlpNV2Ztg0Hd8jJ73CBzFfB16NwZWNE


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

