---
title: "Creating a Blog with Astro"
description: "Lean how I created my tech blog with real web development tools."
pubDate: "June 03 2024"
heroImage: "/hero/creating_a_blog_with_astro.png"
---

## Why a blog?

While social media platform are often the first point of call when creating content, I wanted to create something that I run and that I have control over.
I really believe in the value that the old school internet provided. RSS feeds (still used for all podcasts, by the way) and personal blogs were what got us to where we are today.
While I believe these new platforms also have value, I wanted to try something different.
This also gives me the excuse to mess around and learn something new.

## What is Astro

At its core, Astro is just another front end web framework.
Pages are built using the somewhat familiar `.astro` syntax (similar to JSX if you've ever used react).
They have many [integrations](https://astro.build/integrations/) that allow developers to integrate multiple different front end frameworks into one project.
It renders everything statically and serves it to the browser with the option of creating dynamic Javascript elements whenever needed.
It has great support for Markdown and MDX, making it a great choice for building out personal blogs.
Previously I have used [Hugo](https://gohugo.io/) (a static site generator written in Go) for my personal blogging attempts, but I never fully came around to it.

## Creating the blog

**Prerequisites**

1. Node.js
2. A text editor (one that supports an astro extension)
3. Terminal

For a more detailed guide, check the [official installation documentation](https://docs.astro.build/en/install/auto/).

Once the prerequisites have been installed, simply run:

```bash
# create a new project with npm
npm create astro@latest
```

_NOTE: This command can be run anywhere on your machine. You will be able to specify a new project location through the setup wizard._

Next, you can start astro:

```bash
npm run dev
```

The new Astro site is now running locally.
Astro also hosts a collection of [themes](https://astro.build/themes/) to get new websites started quickly.

## Next steps

I plan to iterate on my blog continuously into the future. For the time being, I just wanted something barebones with minimal design.
One day I might be able to have one of those crazy developer portfolios with tons of animations. Then I could finally call myself an HTML engineer.

That's about it. Thanks.
