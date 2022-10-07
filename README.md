# New tab

A custom "New tab" for Google Chrome.

## Introduction

I wanted to have some control over what I see when I open a new tab in Chrome. I was also looking for a great way to stay up-to-date with some of my RSS feeds without hassle.

So I built a client-side RSS-feed parser that runs fast enough to process feeds on the fly.

## Features

- All-in-one html file `new-tab.html`
- Optimised for high focus
- Ready to be forked, so you can
  - Add your own RSS feeds
  - Configure amount of articles to show
  - Change anything else however you like

#### Caveat

Some hosts don't allow cross-origin requests from **_origin: null_**, which basically means you won't be able to access its feed from a local html file. In that case you have to use the online version of the html file. For example by hosting it on GitHub pages.

## Installation

- Install [Custom New Tab URL](https://chrome.google.com/webstore/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia) plugin.
- Clone the repository or simply download `new-tab.html`
- Set the URL to the index file. For example: `file:///C:/Users/Webber/repositories/new-tab/index.html`.
- Open a new tab and enjoy!

## Licence

This repository is [MIT](./LICENSE) licensed.
