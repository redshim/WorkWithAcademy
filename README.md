# WorkWithAcademy


https://signin.aws.amazon.com/federation?Action=login&Issuer=localhost&Destination=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3Fregion%3Dus-east-1&SigninToken=mm_8xb4h7BgpTrRsQhNbKM5cdJlqlp13RUtxobX9NgmbT3zdrZXgcAmPhrTM8WthjCCi2MMZyDroXQrugf2PPKej7fPTaIR_yZJr6FoExMKsOhr6Tr98ydoiHlODMzZKx63J4mHddCWhdnNNjdj50VLcdFQx1wwxb_TdJPzv0h3Ppcr-KWJksoQYcXwq7YJRjim3io4ix0D_UckRZgqUxUgx8O9-g2AY2eFnxLwy73J3fVIcrrMZwQHUqByox78Hi5UR2Gs-PD7xJwBQCy_uR3UriLteOgZKIghTAevlXy3ahHFEZEL3ivfup6esFiikqRj894uBUiZFApo4WVX6O084vq3Gl7rqxdzEFZpV-5-VqglvFlEzr9bMccjKlOhaNcE7X0ihopXptcfX_eGGZHXnlav9plxGbdSD4sMIFflq3_kQ_dFO6veOZ5gZzeNyZ7snIDvpRQe2XRGKXU7g8A5IbYorza4fyaeI_yMNC7NlVdcGSlOk117-kVC4DcnRz071BvPw5hZ97bSpvSd5FQrn_JWsrIkFXrBd2WJ09mjxWkvpdixOAKpAdjWoDXbhwU8G00bnvPq608QSh2eFE4Os2TsvkBjoB6hOaY30fHRiKh98ZFrV2egEECInKCq0vNcURpyubD5iy8cVWesuPZ-1u4r8k753TXVhYX6kqWfiqqeU_m96rt-ioiBrmfb5XU26hCR3qGSmuSbMqTEDkW3DTb7K6e1Kmlqm1MZQ7o4ChG_4DJC4C9i9bNWxvQpaon6T0gAHbcB1YMWDS54N7n77fqsiH7TIY2Me0peYNEjn1mQF96yWmrJ64Drkxt7N_eMNlIarEI7GttFPc_t8XcyVaQEfHWV87xbKN1AwMQMwmWfNvs5eiI97W7XSKU-BvhtgxBE59i204AgENt0DOxVLBHOe0JJHNPQKZko4a7mWnhLQtESYGJn_L2Ex8xGewMO8y8r3hSBcIPDXReIPwvQtU6e8hgPYBDpi-E8dTLthfYut4k5Cz_sFZRFs37pouL3X3EE5V_fIKmeQzkfHqvvR-H0xv4g8X8FMS-4Qyd1XzC0DsEBUvSEa1d3mqYIQDjBXbqhGto4-Qy5HNyRhbhi-maVYyRKf5wg-4BS19G9sbCfBzWysADN9aTxi6qQrP0VGQzDzFbwscoRllNegSOLm0Sg5nRy8EmZMG82X11JT0AVbcrFSYlyqo2m7lGlIBWGYjXcqcc5bjDxriE7u10wNOAppw8pQQMDf9YzJNF2hMuXN6_nOswrkKmycJoBf1bT1FUriLrRvjii2ZPawmPvmaeHt6fEy1PohKRVYZbGKSv-ypT7WpcXGhezEy26z55W3bv6TAlTNoFfbNuhOtMlvvx1CHDxsS_K43xII7pOBpAH7Kig8K1r08mge5qEH5RELyXLdm9ALaV3ROgM-zpC8zUE


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

