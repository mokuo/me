# https://mokuo.me

## Setup

ref: https://gohugo.io/getting-started/quick-start/

```sh
brew install hugo
hugo version
```

## Start the Hugo server

```sh
hugo server
```

## Add Some Page

hugo new hoge.md

## Update theme

ref: https://themes.gohugo.io/themes/hugo-coder/

```sh
cd themes/hugo-coder/
git branch # => master
git pull
```

ref: [Git \- サブモジュール](https://git-scm.com/book/ja/v2/Git-%E3%81%AE%E3%81%95%E3%81%BE%E3%81%96%E3%81%BE%E3%81%AA%E3%83%84%E3%83%BC%E3%83%AB-%E3%82%B5%E3%83%96%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)

## Deploy

Merge PR to master branch.

[![Netlify Status](https://api.netlify.com/api/v1/badges/7312ceec-f8f7-4778-9cdf-06c7767e46e2/deploy-status)](https://app.netlify.com/sites/mokuo-me/deploys)
