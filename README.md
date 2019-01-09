# YprawBlog

A [GatsbyJS](https://www.gatsbyjs.org/) blog starter. <br /><br />


[![GitHub license](https://img.shields.io/github/license/ypraw/ypraw-blog-source.svg?style=for-the-badge&logo=appveyor)](https://github.com/ypraw/ypraw-blog-source/blob/master/LICENSE)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=for-the-badge&logo=appveyor)](https://github.com/prettier/prettier)


## Deskripsi

Source code untuk blog saya. Dibuat menggunakan GatsbyJS dan ReactJS

## Fitur:

- Easy editable content in **Markdown** files (posts, pages and parts)
- **CSS** with `styled-jsx` and `PostCSS`
- **SEO** (sitemap generation, robot.txt, meta and OpenGraph Tags)
- **Social** sharing (Twitter, Facebook, Google, LinkedIn)
- **Comments** (Disqus or Facebook)
- **Images** lazy loading and `webp` support (gatsby-image)
- Post **categories** (category based post list)
- Full text **searching** (Algolia)
- Form elements and validation with `ant-design`
- **RSS** feed
- 100% **PWA** (manifest.webmanifest, offline support, favicons)
- Google **Analytics**
- App **favicons** generator (node script)
- Easy customizable base **styles** via `theme` object generated from `yaml` file (fonts, colors, sizes)
- React **v.16.3** (gatsby-plugin-react-next)
- **Components** lazy loading (social sharing)
- **ESLint** (google config)
- **Prettier** code styling
- Webpack `BundleAnalyzerPlugin`
- **Gravatar** image (optional) instead local Avatar/Logo image

## Instalasi GatsbyJS

Pastikan bahwa nodeJS telah terinstall pada komputer anda.
Kemudian install gatsby-cli dengan syntaks berikut,

```bash
npm install --global gatsby-cli
```

Info lebih lanjut dapat ditemukan dalam tautan berikut ini [GatsbyJS.org](https://www.gatsbyjs.org/tutorial/part-one)

## Memulai Instalasi Tema

Install tema menggunakan command dibawah ini

```text
gatsby new [NEW_SITE_DIRECTORY_FOR_YOUR_BLOG] https://github.com/ypraw/ypraw-blog-source.git
```

arahkan ke folder yang telah dibuat lalu mulai dengan perintah dibawah ini untuk melihat tema.

```bash
gatsby develop
```

arahkan pada `localhost:8000` atau `127.0.0.1:8000`, anda akan melihat tampilan web dengan mode developer.
untuk tahap produksi gunakan perintah berikut

```text
gatsby build
```

perintah ini akan membuat folder (/public) yang siap diupload pada hosting yang anda gunakan.

##### External services

The starter uses external services for some functions: comments, searching, analytics. To use them you have to secure some access data. All services are free to use or have generous free tiers big enough for a personal blog.

Create an `.env` file like below in the root folder. Change `...` placeholders with real data.
<br />By default, your `.env` file will be ignored by git. Remove `.env` from `.gitignore` in order to be able to push the file to your repository.

```text
GOOGLE_ANALYTICS_ID=...
ALGOLIA_APP_ID=...
ALGOLIA_SEARCH_ONLY_API_KEY=...
ALGOLIA_ADMIN_API_KEY=...
ALGOLIA_INDEX_NAME=...
FB_APP_ID=...
```

### Instructions & tutorials


## Windows users

You should take a look at this: [Gatsby on Windows](https://www.gatsbyjs.org/docs/gatsby-on-windows/)

## Authors

- [Yunindyo Prabowo](https://github.com/ypraw)

- Thanks to Base Theme built by [@greglobinski](https://github.com/greglobinski)

## Contributing

- Fork the repo
- Create your feature branch (git checkout -b feature/fooBar)
- Commit your changes (git commit -am 'Add some fooBar')
- Push to the branch (git push origin feature/fooBar)
- Create a new Pull Request

## Licence

MIT License

Copyright (c) 2017 gatsbyjs <br />Copyright (c) 2018 greg lobinski <br />Copyright (c) 2019 Yunindyo Prabowo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
