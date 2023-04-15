---
title: My Journey Back to Static Websites 
description: Rediscovering the Magic of Web Development
date: 2023-04-11
tags:
  - tech
layout: layouts/post.njk
---
## The Genesis of a Journey

Once upon a time, my software development adventure began with a burning desire to craft a simple website. In the early days of 2009, I stumbled upon a charming WYSIWYG HTML editor called NVU. It was a relic from the past, but it worked! With NVU, I was able to design HTML pages without diving too deep into code. Thus, my first static website was born.

![NVU Editor](https://upload.wikimedia.org/wikipedia/commons/b/b2/Nvu_screenshot2.png)

As curiosity took the reins, I delved deeper into the realms of web development, exploring PHP, C++, and a myriad of languages and frameworks. I soon found myself creating websites with Java Spring Boot, databases, and Vaadin interfaces.

Along the way, I built a file-sharing service using PHP, which looked like this:

![Redlinks](/img/redlinks_web.jpg)

But my ultimate goal was simple: to create a website where I could effortlessly share information and images.

## A Modern Quandary
In today's world, having a website typically calls for hosting and a backend, perhaps involving Node.js or PHP. Content management systems like WordPress offer a multitude of customization options, but do we truly need all that complexity for a personal blog?

## The Answer: Static Website Generators
Enter the realm of static website generators. There are a few noteworthy options:
- [Hugo](https://gohugo.io/)
- [Jekyll](https://jekyllrb.com/)
- [Eleventy](https://www.11ty.dev/) - my choice

Here's how they work: You describe your posts in .md files or similar formats, like this:

``` markdown
---
title: My Journey Back to Static Websites 
description: Rediscovering the Magic of Web Development
date: 2023-04-11
tags:
  - tech
layout: layouts/post.njk
---
Text...
```

Then you need to build your MDs into proper html.
```shell
npm run watch
```
or 
```shell
npm run build
```

The generator then weaves your pages into static HTML, complete with your content and a preconfigured design. Numerous designs are available, allowing you to tailor the look and feel to your taste.

### Hugo templates

![Hugo Templates](/img/hugo-templates.jpg)

But where can you host your static masterpiece? Here are a few options to consider:

- [GitHub Pages(free)](https://pages.github.com/)
- [Cloudflare Pages(free)](https://pages.cloudflare.com/)
- [Vercel (free)](https://vercel.com/)

Upon pushing a new commit to your repository, your hosting provider simply updates the folder with your website. It's as simple as that. For me, this was the perfect solution for managing my personal blog.

Thank you for joining me on this nostalgic adventure through web development. I wish you the best of luck as you embark on your own static website journey!
