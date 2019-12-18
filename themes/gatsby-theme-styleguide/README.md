<p align="center">
  <a href="https://themes.lekoarts.de">
    <img alt="Gatsby Theme" src="https://img.lekoarts.de/gatsby/gatsby-themes-illustration.png" />
  </a>
</p>
<h1 align="center">
  @lekoarts/gatsby-theme-styleguide
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-themes/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="@lekoarts/gatsby-theme-styleguide is released under the MIT license." />
  </a>
  <a href="https://www.npmjs.org/package/@lekoarts/gatsby-theme-styleguide">
    <img src="https://img.shields.io/npm/v/@lekoarts/gatsby-theme-styleguide.svg" alt="Current npm package version." />
  </a>
  <a href="https://npmcharts.com/compare/@lekoarts/gatsby-theme-styleguide?minimal=true">
    <img src="https://img.shields.io/npm/dm/@lekoarts/gatsby-theme-styleguide.svg" alt="Downloads per month on npm." />
  </a>
  <a href="https://npmcharts.com/compare/@lekoarts/gatsby-theme-styleguide?minimal=true">
    <img src="https://img.shields.io/npm/dt/@lekoarts/gatsby-theme-styleguide.svg" alt="Total downloads on npm." />
  </a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  <a href="https://twitter.com/intent/follow?screen_name=lekoarts_de">
      <img src="https://img.shields.io/twitter/follow/lekoarts_de.svg?label=Follow%20@lekoarts_de" alt="Follow @lekoarts_de" />
    </a>
</p>

TODO

[![Live Preview](https://img.lekoarts.de/gatsby/preview.svg)](https://styleguide.lekoarts.de)

Read the [Source Code](https://github.com/LekoArts/gatsby-starter-styleguide).

Also be sure to checkout other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de)

## Features

- TODO

## Installation

```sh
npm install @lekoarts/gatsby-theme-styleguide
```

### Install as a starter

This will generate a new site that pre-configures use of the theme.

```sh
gatsby new styleguide LekoArts/gatsby-starter-styleguide
```

[**View the starter's code**](https://github.com/LekoArts/gatsby-starter-styleguide)

## Usage

### Theme options

| Key      | Default Value | Description |
| -------- | ------------- | ----------- |
| `option` | `{}`          | text        |

#### Example usage

```js
// gatsby-config.js
module.exports = {
  plugins: [
    {
      resolve: `@lekoarts/gatsby-theme-styleguide`,
      options: {
          // TODO
        }
      }
    }
  ]
};
```

#### Additional configuration

In addition to the theme options, there are a handful of items you can customize via the `siteMetadata` object in your site's `gatsby-config.js`

```js
// gatsby-config.js
module.exports = {
  siteMetadata: {
    // Used for the title template on pages other than the index site
    siteTitle: `Styleguide`,
    // Default title of the page
    siteTitleAlt: `Styleguide - @lekoarts/gatsby-theme-styleguide`,
    // Can be used for e.g. JSONLD
    siteHeadline: `Styleguide - Gatsby Theme from @lekoarts`,
    // Will be used to generate absolute URLs for og:image etc.
    siteUrl: `https://styleguide.lekoarts.de`,
    // Used for SEO
    siteDescription: `TODO`,
    // Will be set on the html tag
    siteLanguage: `en`,
    // Used for og:image and must be placed inside the `static` folder
    siteImage: `/banner.jpg`,
    // Twitter Handle
    author: `@lekoarts_de`
  }
};
```

### Shadowing

Please read the guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.org/docs/themes/shadowing/) to understand how to customize the this theme! Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-styleguide/` to shadow/override files. The Theme UI config can be configured by shadowing its files in `src/gatsby-plugin-theme-ui/`.

## 🌟 Supporting me

Thanks for using this project! I'm always interested in seeing what people do with my projects, so don't hesitate to tag me on [Twitter](https://twitter.com/lekoarts_de) and share the project with me.

Please star this project, share it on Social Media or consider supporting me on [Patreon](https://www.patreon.com/lekoarts)!

If you want to hire me for **contract/freelance work**, you can do so! [Get in touch with me!](https://www.lekoarts.de/en/contact)