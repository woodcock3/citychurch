A church jekyll powered single page site
======================
This is site is based on http://github.io/t413/SinglePaged
Template is Jekyll 3.0

Permissions
===========
The following directory and its content is copyright of City Evangelical Church. You may not reuse anything therein without the church's written permission:

    /img

Materialize CSS
==============
[Materialize](https://materializecss.com/grid.html) css is used to build the grids/columns, accordions, etc E.g: Responsive grids for Mobile & desktop

~~~
<div class="row">
    <div class="col s12"><p>s12</p></div> #full size grid
    <div class="col s12 m4 l2"><p>s12 m4</p></div> #
    <div class="col s12 m4 l8"><p>s12 m4</p></div>
    <div class="col s12 m4 l2"><p>s12 m4</p></div>
  </div>
  <div class="row">
    <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
    <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
    <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
    <div class="col s12 m6 l3"><p>s12 m6 l3</p></div>
  </div>
  ~~~


Video and mp3
=============
There are two ways to load a video you can embed the video in a the div below:

~~~
<div class="icontain"><iframe title="The title of the video" src="//www.youtube-nocookie.com/embed/8SLeE2a6Q4" allowfullscreen></iframe></div>
~~~

Or there is a script that will tranform a Youtube or Vimeo URL in the content (on a new line) into an embedded video. It also detects URL’s that point to mp3 files and replaces them with a default HTML5 player. This uses ([Jekyll Codex] (https://jekyllcodex.org/without-plugin/open-embed/)) script.

E.g.

~~~
https://www.mymusic.mp3
// or
https://www.youtube.com/watch?v=1ZM-jnXh4uw
~~~

Forestry
========
Forestry.io is linked to this site to enable content editors to use a CMS. https://forestry.io. Forestry is built on Git so that Developers and Content editor can use the same workflow and toolset.
The folder called .forestry manages this connection. This can be deleted if it is not needed.

Generate & Check Favicon
==================
https://realfavicongenerator.net


Insert the following code in the <head> section of your index.html (and config.yml: 
  
~~~
<link rel="apple-touch-icon" sizes="180x180" href="/img/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/img/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/img/favicon-16x16.png">
<link rel="manifest" href="/img/site.webmanifest">
<link rel="mask-icon" href="/img/safari-pinned-tab.svg" color="#f29526">
<link rel="shortcut icon" href="/img/favicon.ico">
<meta name="msapplication-TileColor" content="#009ddf">
<meta name="msapplication-config" content="/img/browserconfig.xml">
<meta name="theme-color" content="#009ddf">
~~~
  
Other singlepaged sites for ideas
====================
- **The original demo site** is also a live demo, see it at [t413.com/SinglePaged](http://t413.com/SinglePaged)
- **Education:**
  - [Global Health Project](http://gcarrozza.github.io/global-health-proj/) for Public Health class at UIC (student project) ([source](https://github.com/gcarrozza/global-health-proj/))
  - [Bioinformatics at Harvard Medical School](http://bioinformatics.hms.harvard.edu/) --  ([source](https://github.com/hbc-hms/hbc-hms.github.io))
  - [Dutch Introduction to Electronics class](http://tverbesselt.github.io/) ([source](https://github.com/tverbesselt/tverbesselt.github.io)) ([translation](https://translate.google.com/translate?sl=auto&tl=en&js=y&prev=_t&hl=en&ie=UTF-8&u=http%3A%2F%2Ftverbesselt.github.io%2F&edit-text=&act=url))
  - [Innovation Lab + Smart Data Hack](http://smartdatahack.org/) 5-day student challenge at University of Edinburgh, Turkey ([source](https://github.com/ilwhack/ilwhack.github.io))
- **Open Source Projects:**
  - [ALM](http://alm.tools/) A cloud ready IDE for TypeScript ([source](https://github.com/alm-tools/alm-tools.github.io))
  - [argon.js](http://argonjs.io/) JS framework for adding augmented reality to web apps ([source](https://github.com/argonjs/argonjs.github.io))
  - [Mockito](https://mockito.github.io/) mocking framework for unit tests in Java ([source](https://github.com/mockito/mockito.github.io))
  - [REMnux](http://www.elabftw.net/) Electronic lab notebook ([source](https://github.com/elabftw/elabftw/tree/gh-pages))
  - [REMnux](http://remnux.github.io/) A Linux Toolkit for Reverse-Engineering and Analyzing Malware ([source](https://github.com/REMnux/remnux.github.io))
  - [Langmuir](https://langmuirsim.github.io/) Charge transfer simulations in organic electronics. ([source](https://github.com/LangmuirSim/langmuirsim.github.io))
  - [SMS-Tools](http://t413.com/SMS-Tools/) is another project of mine that uses this template ([source](https://github.com/t413/SMS-Tools/tree/gh-pages))
  - [HTML Tidy Advocacy Community Group](http://www.htacg.org/) ([source](https://github.com/htacg/htacg.github.io))
  - [AfriLeaks](https://afrileaks.org/) (since changed, still cool!) - secure whistleblowers confidential submition project page ([source when single-paged](https://github.com/CodeForAfrica/AfriLeaks-Landing-Page/tree/698e3b0b1a67cc5f072ccd3a8f24b6d5e3ad406a))
  - [FitNesse](http://fitnesse-eclipse.github.io/) Eclipse Plugin ([source](https://github.com/fitnesse-eclipse/fitnesse-eclipse.github.io))
  - [Lazy Dubuntu](http://lazydubuntu.com/) ([source](https://github.com/darol100/lazydubuntu.com))
  - [The Rosette Platform](https://rosette-proj.github.io/)- git-based, internationalization framework (Ruby) ([source](https://github.com/rosette-proj/rosette-proj.github.io))
  - [PHP Cat](http://phpcat.github.io/phpcat/) PHP Developer Group in Catalan (grup de desenvolupadors PHP de llengua catalana) ([source](https://github.com/phpcat/phpcat/))
  - [Alt.Net Australia User Group](http://www.ozalt.net/) ([source](https://github.com/ozaltnet/ozaltnet.github.io))
  - [FeedReader](http://jangernert.github.io/FeedReader/) Desktop RSS client ([source](https://github.com/jangernert/FeedReader/tree/gh-pages))
  - [Coala Analyzer](http://coala-analyzer.org/) command-line interface for linting ([source](https://github.com/coala-analyzer/website))
  - [Easy Shell](http://lucasviola.github.io/easyshell/) Linux and Shell Commands the Easy Way ([source](https://github.com/lucasviola/easyshell/tree/gh-pages)) 
- **Events / Conferences**
  - [CodeWeek 15 @ DI](http://cesium.github.io/codeweek15) CodeWeek at the University of Minho in 2015 by [CeSIUM](http://cesium.di.uminho.pt) - ([source](http://github.com/cesium/codeweek15))
  - [Innovation Lab + Smart Data Hack](http://smartdatahack.org/) 5-day student challenge at University of Edinburgh, Turkey ([source](https://github.com/ilwhack/ilwhack.github.io))
  - [FSU Festival of New Music](https://fsufnm.github.io/) (17th Biennial) ([source](https://github.com/fsufnm/fsufnm.github.io))
  - Code Across 2015 @Seoul 전 세계 시빅해커들과 함께 하는 -> since changed, ([source](https://github.com/codeforseoul/codeacross))
- **Personal:**
  - [Karen and Scott wedding](http://karenandscott.com/) ([source](https://github.com/karenandscott/karenandscott.github.io))
  - [ryan & rachel wedding](https://r-and-r.github.io/) ([source](https://github.com/r-and-r/r-and-r.github.io))
  - [Chris & Katie wedding](http://katieball.me/wedding-style/) ([source](https://github.com/roachhd/wedding-style))
- **Products:**
  - [Pawan Kumar film](http://c10h14n2movie.com/) info page ([source](https://github.com/c10h14n2movie/c10h14n2movie.github.io))
  - [Helpers in Korea](https://itgame.github.io/) ([source](https://github.com/itgame/itgame.github.io))
  - Zeno- internet for gamers original teaser page: ([source](https://github.com/zenoio/zenoio.github.io))
  - Original DEVISSCHER web design page ([source](https://github.com/devisscher/templates/))
- **Resumes:**
  - [magiciansanfrancisco.com](http://magiciansanfrancisco.com) professional page ([source](https://github.com/strongrobert/MagicianSanFrancisco))
  - [Lia Bogoev](https://bogoli.github.io/) UX designer from utah ([source](https://github.com/bogoli/bogoli.github.io))
  - [Bill Ryan](http://www.yuanbin.me/)'s homepage is a snazzy personal example! ([source](https://github.com/billryan/homepage))
  - [Christophe Gabard](http://christophe.gabard.net/) resume ([source](https://github.com/cgabard/cgabard.github.io))
  - [Leppotone Electrical Recordings](http://www.nathanmclaughlin.com/leppotone/) temporary homepage ([source](https://github.com/nathanmclaughlin/leppotone))
  - [Michael A. Schmidt](http://micha-a-schmidt.github.io/physics/) particle physics lecturer at the University of Sydney ([source](https://github.com/micha-a-schmidt/physics/))
  - [Jin Li](https://just4jin.github.io/) MS student in Systems and Information Engineering @ UVA ([source](https://github.com/just4jin/just4jin.github.io))
- *Let me know of more!*


## Getting started

Make an easy single-page site to show it all off. SinglePaged uses jekyll niceties to make a ***polished, modular, and beautiful* single page site**.

- Each vertical section is a markdown file in **_posts/** directory.
  * They're sorted by 'date'. (we don't use date anywhere, it only sorts)
- Each vertical section sets it's own **color**, **header icon** (or image), **title**, and easy-to-write markdown body.
- Only **two things** to edit:
  1. Edit `_config.yml` to set the site title, description, etc
  2. Add _posts/*.md to make each vertical section. Copy some examples and add the sections from your README.md for a fast start!
- Easy adding of **SEO terms**, **favicon** & such, and **google analytics token**.

Sound good? Let's go!

There are three way to get started: (links jump to that section)

1. Make a [**user homepage**](#setup-as-user-homepage) (or organization)
2. Make a [**standalone project**](#setup-as-standalone-project-page) page


-------------------------

## Setup as user homepage

- Go click **fork** on the [github project page](https://github.com/t413/SinglePaged)
- Click the **template button** to add a new repository 
- Rename your new repository to `**username**.github.io`. (click settings in the right column)

Now hop over to [Usage](#usage) to get it running with your own stuff!

-------------------------


## Setup as standalone project page

- Go click **fork** on the [github project page](https://github.com/t413/SinglePaged)
- Click the **template button** to add a new repository
- Rename your new repository to `whatever you want`. (click settings in the right column)
  * It will go live at yourusername.github.io/**WhateverYouWant**
- Make sure your branch set to *gh-pages* in settings for the webpage to be published 

Now hop over to [Usage](#usage) to get it running with your own stuff!

## Usage

Alright, you've got a clean copy and are ready to push some schmancy pages for the world to ogle at.

- Edit `_config.yml` to change your title, keywords, and description.
- Create a new file in `_posts/` called `2014-01-01-intro.md`
  Edit it, and add:

~~~
  ---
  title: "home"
  bg: white     #defined in _config.yml, can use html color like '#010101'
  color: black  #text color
  style: center
  ---

  # Example headline!
  and so on..
~~~

- Create a second post called `2014-01-02-art.md` with an divider image this time:

~~~
  ---
  title: "Art"
  bg: turquoise  #defined in _config.yml, can use html color like '#0fbfcf'
  color: white   #text color
  fa-icon: paint-brush
  ---

  #### A new section- oh the humanity!
~~~

**Note:** That part `fa-icon: paint-brush` will use a font-awesome icon of [paint-brush](http://fortawesome.github.io/Font-Awesome/icon/paint-brush/). You can use any icon from this [font-awesome icon directory](http://fortawesome.github.io/Font-Awesome/icons/).

- install Jekyll with `sudo gem install github-pages`
- run `jekyll serve -w`
  - visit [localhost:4000](http://localhost:4000) to see a live locally served preview.
- Push changes and see them live!




## Changing your colors

- In each post file you can define `bg: mycolor` and `color: myothercolor` to change the background and text colors for that section.
- **mycolor** can be a quoted html color like `'#0fbfcf'` or a key to a special color defined in **_config.yml** under 'colors'.
  - **Note:** Changes to _config.yml require a manual restart to your local server with `^C` and `jekyll serve -w`.

Nifty, right!



## Updating

So you've got a copy running and there's some new update? Let's update!

1. Checkout your github-pages branch
  - `git checkout gh-pages` for a standalone or existing page
  - `git checkout master` for a *username.github.io* page
2. run `git remote | grep -q "singlepage" || git remote add -t publish singlepage https://github.com/t413/SinglePaged.git` to be sure you have access to this repository (you can run this command at any time).
2. `git fetch singlepage` to fetch-in-place new changes.
3. Update to the new base (using merge)
    1. `git merge singlepage/publish`
4. You can alternatively update using rebase. This *rewrites history* (**bad**), but it is cleaner.
    1. `git rebase singlepage/publish`

Accordion
=========
## How it works
Visit: https://jekyllcodex.org/without-plugin/accordion/
To create an accordion, add the following code to the front matter of your page:
~~~
    ---
    accordion: 
      - title: this is item 1
        content: Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
      - title: this is item 2
        content: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    ---
~~~
The code uses no javascript and uses the CSS ‘checkbox hack’ to toggle the content. The accordion deliberately refrains from setting the height of the content blocks. Calculating this height with javascript is required to add animation (slide down), but adds a lot of complexity.

## Installation
Step 1. The accordion file is called Accordion.html 
Step 2. Save the file in the ‘_includes’ directory of your project 
Step 3. Make sure your front matter of your page looks like the example above 
Step 4. Add the following line to your layout on the place where you want the form to appear:

{% include Accordion.html %}

Font Awesome icons
======================
This site uses Font Awesome 4.7 icons. To reference an icon inline use:
~~~
    <i class="fa fa-external-link" aria-hidden="true" style="color:black"></i>
~~~

Markdown
========
This site uses Kramdown, visit https://about.gitlab.com/blog/2016/07/19/markdown-kramdown-tips-and-tricks/#font-awesome for tips.
