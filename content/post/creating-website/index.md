---
title: 'Creating this website'
subtitle: 'Hugo + Academic + Netlify = an elegant & minimal website :rocket:'
summary: Using Hugo with Academic theme and Netlify to create a minimal website.
authors:
- admin
#tags:
#- Academic
#categories:
#- Demo
date: "2016-04-20T00:00:00Z"
lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [**Olalekan Oladipupo from Pixabay**](https://pixabay.com/users/lakexyde-2489063/)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

This month, I finally managed to convince myself to create a website. Some tools made this really easy and that's what this post is all about. 

## Choosing a site generator

Options like [Wordpress](https://wordpress.com/), [Medium](https://medium.com/) make writing/publishing really easy for non-programmers who just want to publish their content and don't care about retaining more control over their content. 

Being a programmer, I preferred to create a website from scratch and after exploring some options, narrowed it down to static site generators (SSGs). This [article](https://snipcart.com/blog/choose-best-static-site-generator) goes into detail about SSGs.

Among the SSGs, [Jekyll](https://jekyllrb.com/) was my initial choice but Ruby dependencies made it very limiting.

[Hugo](https://gohugo.io/), on the contrary, is based on a single binary and builds sites in milliseconds. I could preview the content updates in (almost) real-time!

## Template for website

I chose the [Academic theme](https://themes.gohugo.io/academic/) for Hugo which made it really easy to create a minimal website. It's a great framework for writing [code](https://sourcethemes.com/academic/docs/writing-markdown-latex/#code-highlighting), [math](https://sourcethemes.com/academic/docs/writing-markdown-latex/#rm-latex-math), and [other](https://sourcethemes.com/academic/docs/writing-markdown-latex/) content. 

For version control of the content, [GitHub](https://github.com/) was an easy choice.

## Hosting

I chose [Netlify](https://www.netlify.com/) instead of [GitHub Pages](https://pages.github.com/) for hosting the website since it supports continuous deployment with Hugo. This [post](https://yihui.org/en/2017/06/netlify-instead-of-github-pages/) makes the case for choosing Netlify over GitHub Pages.

## Domain registration

There are a variety of domain registrars to choose from. Here's an [article](https://hostingfacts.com/domain-registrars/) comparing the top registrars. I chose [NameCheap](https://www.namecheap.com/) to register a personal domain and Netlify made it easy to [setup a custom DNS](https://docs.netlify.com/domains-https/custom-domains/). This [article](https://medium.com/@panjunweide/configure-customer-domain-on-netlify-1418a0464731) details the steps for setting up a custom DNS with illustrations.

## **Summary**

In brief, this is what went into creating this website:

- _Hugo + Academic theme_ for content creation and building site
- _Github_ for version control of website content
- _Netlify_ for hosting the website
- _NameCheap_ for domain registration

