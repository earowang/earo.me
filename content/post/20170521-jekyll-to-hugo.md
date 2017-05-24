+++
date = "2017-05-21T15:46:00"
draft = false
tags = ["life"]
title = "Jekyll to Hugo, Undergraduate to Postgraduate"
summary = """
A brief summary of what I've done while switching to Hugo.
"""
math = false
+++

I started my personal website at the end of 2012 when there were quite a lot hits on Jekyll. Back then, I knew little about web, programming, and git. But I was keen on cool technology and decided to learn something new (outside Econometrics) over the 3-month-long summer break. I took the path--learn by doing--to build a Jekyll website host on the Github. There were floods of tutorials teaching how to make a website using Jekyll and Github on the web, and I followed one of them step by step. During the day time, I made countless commits (or mistakes) and finally got my head around what's going on behind the screen. Before dark, <http://earo.me> went live. I would never forget that magic moment when I owned a micro-tiny spot on the Internet. That 3 months were filled with "oh"s and "wow"s, as I touched on Ubuntu, Vim, R, git, css, html, and other bits and odds.

This website has served as my online CV since the beginning. As it's a custom domain running on the Github, the SSL encryption doesn't work. Just out of curiosity, I wanna add a green lock to the web address. It takes me down to a different web-wandering journey this time. I first tried on Hugo that claims itself a faster static website generator and adopted the Academic theme as a base template. I bought a SSL certificate from my domain provider--GoDaddy for the convenience sake. Chrome popped up a warning saying the website is potentially dangerous as the SSL certificate issuer is different from the web host. Consequently, I switched the web hosting to cPanel and the website got protected then. Seems everything has been settled, a new look website with a green lock. However, it led me to a very old and inefficient way to sync the files between local disk and remote server via FTP, as well as manage two separate repos (source files and the `public` folder). Certainly it's not smart and modern. Defining the question and then googling, repeat the process several times and the "ultimate" solution comes to the surface. Logging to the server via SSH and git initialising the `public_html` folder with a couple tweaks. On the local repo, the `public` folder is newly created as a git submodule linking to the remote server. At the moment, I place [the source files](https://github.com/earowang/earo.me) on the Github and edit, add, commit, push as usual with git. The shell script [`deploy.sh`](https://gohugo.io/tutorials/github-pages-blog/#hosting-personal-organization-pages) helps to automatically push to the remote server running the website. Now here is <https://earo.me>.

------------------------------Update 2017-05-24------------------------------

It turns out the web hosting service provided by GoDaddy runs so slow, which I cannot bear (at least what's the point in having a static site if it takes long time to load). Now I turn over the DNS and hosting service to the [netlify](https://www.netlify.com). Easy deployment and super fast. Luckily, I get refunded for the web hosting and SSL certificate from GoDaddy.
