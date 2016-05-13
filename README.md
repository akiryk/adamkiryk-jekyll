# Adam Kiryk's Blog and Portfolio

This is a jekyll blog site. Not too much more to say.

## Create a new blog post

Create a file and name it 2016-12-22-name-of-post.md. This will be a markdown file. Add some front matter at the top like so:

    ---
    layout: post
    title: Name of Post
    teaser: A brief description.
    micro-teaser: A few words that will appear above the title, like a slug or tagline.
    category : blog
    assets: name of directory in _assets where jekyll can find images
    hero: name of the hero image file.
    hero-caption: Snapshots of a bunch of NPR Member Station homepages.
    tags : [design, product, work-history]
    ---

## Create a new portfolio post

    ---
    layout: portfolio
    title: Name of Project
    teaser: Brief description.
    micro-teaser: A few words that will appear above the title, like a slug or tagline.
    employer-dates: optional: only use this if the item is a collection of work from a particular employer.
    category : portfolio
    assets: name of directory in _assets where jekyll can find images
    hero: name of the hero image file.
    hero-caption: duh.
    tags : [design, product, work-history]
    ---