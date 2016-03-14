---
layout: post
title: The Meta Post
comments: True
permalink: the-meta-post
rebirect_from: 2016/02/28/the-meta-post
tags: [programming, meta ]
---

I like it when people write about how they solved a particular problem or when they rant about something they found on internet. I want to be one of those people. <br> That led to me thinking of setting up my own website blog thingy. I decided to host this on github as I didn't want to buy my own server and also because github supports [Jekyll](https://jekyllrb.com/).

One of the perks of using Jekyll is that many awesome people around the world have made a lot of themes which are open source. And I didn't want to make the entire thing from scratch. All I had to do was search for a theme that appeases me. So after doing some research(this actually took me two days) I decided on using [Lanyon](http://lanyon.getpoole.com/). 

Lanyon didn't come with some of the specific things I wanted. So I did some more research, like always, and finally ended up with [this](https://themouli.github.io). Many people wrote about how to set up a clean blog using Jekyll and Lanyon, so I will ignore that area.

## Author info footer below each post

I liked this little footer in [Jasper](https://biomadeira.github.io/jasper/), another good Jekyll theme.

![Footer Image](/assets/images/jasper-footer.png)
As with all the things I like, I didn't get this without effort. If you forked the default [Lanyon](https://github.com/poole/lanyon) repo and want this feature in your posts, follow my command. 

- Download [these](https://github.com/themouli/themouli.github.io/tree/master/assets/fonts) font files and place them in a folder named `fonts` above the directory of your css files. 
- Include [this](https://github.com/themouli/themouli.github.io/blob/master/assets/css/footer-author-info.css) css in your project. You can paste it in your default css file or make a new css file and link it in your `head.html` like other css files.
- Paste [this](https://gist.github.com/themouli/b49e53b23131e7293738) code in your `post.html`
- Add `image: <your-image-url>` in your `_config.yml`
- Add `bio: <your-bio>` in the `author` section of your `_config.yml`

<br>
That's it. You are good to go.

Some of you may be wondering why it isn't working after doing all the aforementioned things. Well, that may be because I am a crappy teller or you are a crappy follower. But mostly it's because our project structure is different. You can always find my source code [here](https://github.com/themouli/themouli.github.io) and figure it out.


Below are most of the links that helped me make this.

## Resources

- [Setting up Github pages](https://pages.github.com/)
- [List of sites that use Jekyll](https://github.com/jekyll/jekyll/wiki/Sites) 
- [Demos of Jekyll themes](http://themes.jekyllrc.org/demos/)
- [Adding site links in the header](http://joshualande.com/jekyll-github-pages-poole/)
- [Customising sidebar and adding Google Analytics](http://patricksteadman.ca/2014/08/04/lanyonsetup/)
- [Tags](http://anandmanisankar.com/tags.html)
- [Disqus comments](http://www.perfectlyrandom.org/2014/06/29/adding-disqus-to-your-jekyll-powered-github-pages/)

<br>
Also you can find this site's code [here](https://github.com/themouli/themouli.github.io) for some of my custom css tweaks.
