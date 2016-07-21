---
title: "The Verge 50"
date: 2014-07-30T03:47:00.000Z
posted_date: 2015-07-11T03:47:00.000Z
type: showcase
slug: the-verge-50
website: http://www.theverge.com/a/the-verge-50
image_path: 1436586481330_thenewdynamic-showcase-verge-at-50-ogov-150710.jpg
tool:
  - middleman
creator:
  - role: "Design, development"
  - link: http://product.voxmedia.com/
  - name: Vox Product
---
Last December, The Verge published [The Verge 50](http://www.theverge.com/a/the-verge-50), one of our earliest examples of our [Editorial Apps](https://source.opennews.org/en-US/learning/evolution-news-apps-teams/) system built by VP of Technology [Pablo Mercado](https://twitter.com/odacrem "Ham") during last October's [VAX](http://product.voxmedia.com/2013/10/4/5426870/product-team-all-hands-2013-return-of-vax) hackathon, inspired by the work done by the [NPR Visuals](http://blog.apps.npr.org/) team. In a nutshell, our Editorial Apps system consists of a static [Middleman](http://middlemanapp.com/) site, which is populated from one or more Google Spreadsheets at build time (using our [middleman-google-drive](https://github.com/voxmedia/middleman-google_drive) extension, which we'll talk about in a future article), and then deployed to [Chorus](http://product.voxmedia.com/2012/5/6/5426772/all-together-now-introducing-the-vox-product-blog-and-chorus) by doing a `git push` and using git post-receive hooks, in a way not unlike deploying an app to [Heroku](https://www.heroku.com/). Continue reading at [Vox Product](http://product.voxmedia.com/2014/7/29/5863004/take-a-peek-at-the-code-that-powered-the-verge-50)
