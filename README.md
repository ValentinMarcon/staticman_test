# "Bio.tools Entry" a test on staticman application

## Introduction: Static man

Staticman is a Node.js application that receives user-generated content and uploads it as data files to a GitHub repository. In practice, this allows you to have dynamic content (e.g. blog post comments) as part of a fully static website, as long as your site automatically deploys on every push to GitHub, as seen on [GitHub Pages](https://pages.github.com/), [Netlify](http://netlify.com/) and others.		

[...read more](https://github.com/eduardoboucas/staticman)


## This project

This is a sample page to demonstrate how [Staticman](https://staticman.net) can be used to integrate user-generated content into a static site. 

When the form is submitted, the data is sent to the Staticman API via Ajax, which will push it to [the GitHub repository](https://github.com/ValentinMarcon/staticman_test) and cause a regeneration of the Jekyll site.

This staticman config is based on  [popcorn demo](https://github.com/eduardoboucas/popcorn), following the [staticman doc](https://staticman.net/docs/), but as staticman bot is broken we use the [static man app](https://github.com/apps/staticman-net) currently [under development](https://github.com/eduardoboucas/staticman/issues/243#issuecomment-453754860)

## Requirement and run

### [Ruby Gems](https://jekyllrb.com/docs/installation/)

`sudo apt-get install ruby-full build-essential zlib1g-dev`

### [Jekyll](https://jekyllrb.com/docs/)

`gem install jekyll`

### RUN

`cd staticman_test`

`jekyll serve`

Go to : http://127.0.0.1:4000/


## Links

- [bio.tools](https://bio.tools/)
- [staticman](https://staticman.net/)
- [staticman github](https://github.com/eduardoboucas/staticman)
- [popcorn demo](http://popcorn.staticman.net/)
- [popcorn github](https://github.com/eduardoboucas/popcorn)
