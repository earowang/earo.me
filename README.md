Currently [Netlify](https://www.netlify.com) takes care of the web hosting service and the DNS management for my website <https://earo.me>. The repo contains the source files to generate the web pages. Netlify automatically and continuously deploys the website from Github by running the `hugo` command to build the `public` folder.

## Main site

I adapt and personalise [the Academic theme](https://github.com/gcushen/hugo-academic) to manage the portfolios for the main site <https://earo.me>.

## Personal blog

The Academic theme provides a nice template for presenting personal portfolios, but isn't a beauty for personal blog. I managed to have a subdomain <https://blog.earo.me> by creating and maintaining the `blog` branch (again Netlify takes care of the subdomain). It has a fresh look from the main site as [the ghostwriter theme](https://github.com/roryg/ghostwriter) running in the backend. I'm quite happy about the `ghostwriter` theme.
