# adhamfathalla.com

A landing page for selling the premium domain name **adhamfathalla.com**.

## Overview

This repository contains the source code for the landing page displayed when visitors navigate to `adhamfathalla.com`. The page acts as a digital billboard, allowing potential buyers to see that the domain is for sale and make an offer.

## Features

- Lightweight, fast static HTML
- SEO optimized with meta tags and Open Graph attributes
- Responsive design for mobile, tablet, and desktop
- Cloudflare Pages ready

## Deployment

This site is configured to be deployed using [Cloudflare Pages](https://pages.cloudflare.com/) and Cloudflare Workers via `wrangler`.

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/install-and-update/) installed

### Running Locally

You can preview the site locally using Wrangler:

```bash
npx wrangler pages dev .
```

### Deploying

To deploy the site to Cloudflare Pages:

```bash
npx wrangler pages deploy .
```
