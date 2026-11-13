<h1 align="center">Hi, I'm Curtis 👋</h1>
<p align="center">
  Software developer building browser extensions, cross-platform apps and developer tools.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/curtis-spence-0b94b8132/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## About me

- Full-stack developer who likes shipping small, useful tools end to end
- Published a Chrome extension to the Chrome Web Store
- Building cross-platform mobile apps with React Native and Expo, backed by AWS

## 🛠️ Tech stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

## 📂 Recent projects

### 🖼️ Resolve: Gallery & Full-Size Image Downloader
**[Live on the Chrome Web Store](https://chromewebstore.google.com/detail/fdfieelgobaoehibbfaepkibkgpcngnk?utm_source=item-share-cb)** · Firefox version in progress

A browser extension that finds every image on a page, works out the largest original version of each one, filters out logos and icons, and saves your picks as a single ZIP.
- Detects images from `srcset`, `<picture>`, lazy-load attributes, CSS backgrounds, JSON-LD, shadow DOM and more
- Rewrites URLs to find bigger originals across 20+ sites and CDNs (WordPress, Shopify, Cloudinary, Reddit, Pinterest…), then verifies each guess by reading only the first few KB
- Content-hash de-duplication, custom ignore rules and a live mode for infinite-scroll pages
- Manifest V3, no build step, no dependencies, no remote code

`JavaScript` `Manifest V3` · [Project site](https://github.com/spen0203/Resolve.github.io)

### 🛒 Flyer Picks
**Live at [flyer-picks.pages.dev](https://flyer-picks.pages.dev/)** · Updated weekly
 
Compares this week's flyers from 17 Ottawa grocers to find the cheapest store for each home-cooking staple.
- Weekly GitHub Actions cron pulls Flipp flyer data, sorts items into 50 regex-matched categories and converts prices to per kg, per L or per item
- Plans a shopping route with a weighted greedy set cover: up to 4 stores, protein deals count double, a store qualifies within 10% of the best price
- Fills 47 rule-based meal templates from what's on sale, ranked by cost per serving
- Shares one dependency-free `core.mjs` between Node and the browser, so unticking a store recalculates the route, deals and meals in the browser
`JavaScript` `Node.js` `GitHub Actions` `Cloudflare Pages` `Docker` `Flipp API`


## 📫 Get in touch

The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/curtis-spence-0b94b8132/).
