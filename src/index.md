---
layout: "devices-lab/default"
image: https://placecats.com/400/400/
---

# Overview

This is the official template repository to generate documentation in the devices-lab style.

The upstream package for the styles and layouts is [@devices-lab/user-doc-base](https://github.com/devices-lab/user-doc-base.git) but you can override any of these by simply defining your own. If you want to get the latest changes to our styles or resources, simply update this package.

We use the excellent [eleventy (11ty)](https://www.11ty.dev/) to build the static pages, and these will be placed in the `_site` folder by default, and we include a Github action to automatically build and deploy these to a Github Pages site.

## Writing Documentation

Ensure you have both `node` (nodejs) and `npm` installed.

To run the development server, which live updates your pages and serves a local development host, launch `npm run dev:11ty`.

Alternatively, to run a single one-shot build, run `npm run build`.

In both cases, the complete output will be available in the `_site/` subdirectory.

## Available Page Layouts, Styles and Assets

For an up-to-date list of available page layouts, styles and other assets, please see the upstream package: [@devices-lab/user-doc-base](https://github.com/devices-lab/user-doc-base.git)

## Troubleshooting

If you find that CSS styles are no longer updating, it may be that PostCSS is not noticing your changes while the pages are hot-reloaded with the development server. If this is the case, simply restart the development server and continue editing.

In extreme cases, stop the development server, delete the `_site/` folder, then re-run the development server to completely rebuild the site.