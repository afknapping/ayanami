# Ayaname is a site-with-static-blog template for [Middleman](http://middlemanapp.com)…

…running on haml, sass and compass. Do
    
    git clone git@github.com:filtercake/ayanami.git ~/.middleman

to download the template. Then 
    
    middleman init MY_NEW_SITE --template=ayanami
    
to start a new project. It will geneerate the following directory structure:

    ├── Gemfile
    ├── README.md
    ├── config.rb
    └── source
        ├── assets
        │   ├── images
        │   ├── javascripts
        │   │   ├── jquery-1.7.2.min.js
        │   │   └── jquery.fancybox.pack.js
        │   └── stylesheets
        │       ├── gestalt
        │       │   └── _sketchbook.sass
        │       ├── modules
        │       │   ├── _variables.sass
        │       │   ├── _mixins.sass
        │       │   ├── _defaults.sass
        │       │   ├── _fluid.sass
        │       │   ├── _init.sass
        │       │   └── _github-buttons.sass
        │       ├── screen.css.sass
        │       └── source-sans-pro-fontfacekit
        │           └──  [lots of files… see below]
        ├── blog-bricks
        │   ├── calendar.html.erb
        │   ├── feed.xml.builder
        │   └── tag.html.erb
        ├── content
        │   ├── images
        │   │   └── littlesmoere.jpg
        │   ├── posts
        │   │   └── 2012-a-post.html.md
        │   └── static-text
        │       ├── _index-content.md
        │       └── _something-content.md
        ├── index.html.haml
        ├── index.html.haml.bak
        ├── layouts
        │   ├── layout.haml
        │   └── post.haml
        ├── pages
        │   ├── about.html.haml
        │   └── archive.html.haml
        └── partials
            ├── _blog-index.haml
            ├── _blog-latest.haml
            ├── _footer.haml
            ├── _head.haml
            ├── _nav.haml
            └── _script-embed.haml

## How to use

- put all styling into `stylesheets/gestalt/_sketchbook.sass`, split up later into more partials in `stylesheets/gestalt`.
- blogposts go into `content/posts` and follow the format year-title.md (eg `2013-a-post-md`). If you write often, you might want to add months ar even days
- static content goes into `content/static-text` and is rendered with `= partial '/content/static-text/_NAME-OF-PAGE-content.md'`
- all the sass and haml partials should hopefully be self-explanatory.
- notice that it *does* matter in which order sass partials are loaded into screen.css.sass. first the variables, then the mixins, then the other modules, then anything else

Powered by [Github pages](http://pages.github.com/), [Middleman](http://middlemanapp.com/), [Compass](http://compass-style.org/), [HAML](http://haml.info/) and [SASS](http://sass-lang.com/).

