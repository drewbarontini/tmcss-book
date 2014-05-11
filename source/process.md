---
title: Process
type: page
priority: 4
---

Process
=======

To make sense of the "why," the thought process behind building a modular CSS architecture, it's important to establish a process by which you can craft your styles, and constantly evaluate the system. I like to break it down into five simple steps.

1. Identify
2. Define
3. Build
4. Combine
5. Refine

1. Identify
-----------

Obviously the first step is to identify the patterns that you'll start with when building your modules. In order to write the pattern, we need to find the pattern.

### Structure, layout (highest level)

I like to start at the highest level: the structure and layout elements. These tend to be the most reusable elements project to project.

#### Rows

Freqently on the web, you'll see these full-width bars, generally with a `background-color` or `image`.

![Twitter](process-twitter-01.png)

We call these `row`s, and they are a very common layout pattern that we'll reuse from site to site. You can see it here on [Twitter's About page](https://about.twitter.com/). They have a few different `row` variations.

![Twitter](process-twitter-02.png)
![Twitter](process-twitter-03.png)
![Twitter](process-twitter-04.png)

A `row` generally includes some horizontal `padding` and a `background-color`. There isn't much to the pattern, and it's easily reusable across your projects.

#### Cell

Virtually all sites have some container or wrapper that keeps the content contained. We used to do something like this:

```html
<div id="wrapper"></div>
```

We call them `cell`s, and they handle the `max-width` on a container, and *generally* the horizontal centering via `margin: 0 auto`.

On [Meagan Fisher's site](http://owltastic.com/), she has her content contained within a set width so that things line up nicely.

![Owltastic](process-owltastic-01.png)
![Owltastic](process-owltastic-02.png)

#### Grids

We're all familiar with grids. They've existed for a long time on the web, and they are a very common and clear pattern to identify.

![GitHub Guides](process-github-01.png)
![GitHub Guides](process-github-02.png)

We can see that the [GitHub Guides](http://guides.github.com) have a 50/50 grid for each row of guides.

And on the GitHub user profile page, they have several nested grids.

![GitHub Guides](process-github-03.png)
![GitHub Guides](process-github-04.png)

#### Buckets

The media object is the cornerstone example of OOCSS, and it's another very common layout pattern that you can use on most projects. If you aren't familiar with the pattern, it's a media element with content next to it. For example:

![Dribbble Comment](process-dribbble-01.png)
![Dribbble Comment](process-dribbble-02.png)
![Dribbble Comment](process-dribbble-03.png)
![Dribbble Comment](process-dribbble-04.png)

### Common patterns (known)

Next, look for the common patterns that you continually encounter and build for each project.

#### Card

Cards are stylistic containers for content, that general have some `background-color`, a `border-radius`, a `box-shadow` or `border`, and some `padding`. Here, this is what I'd call a `card` on [Dribbble](http://dribbble.com):

![Dribbble Card](process-dribbble-05.png)
![Dribbble Card](process-dribbble-06.png)

#### List

Lists are *everywhere* on the web, and it's a very common pattern that you'll have to write on each site. I try and break doing `list` pattern into simple text lists, and simple objects lists. Beyond that, you might have more complex and unique lists, but we're trying to write a modular list that applies to various patterns.

![Designer News](process-dn-01.png)
![Designer News](process-dn-02.png)

### Unique patterns (unknown)

Finally, find the more unique patterns. Do you notice very specific style patterns?

**Example**

### Front-end Audit

[https://github.com/drewbarontini/front-end-audit/](https://github.com/drewbarontini/front-end-audit/)

To help you document these, you can use what I call the "Front-end Audit." It's simply a document that you can use to outline and explain all of the components of your front-end architecture.

- Info
- Browser Support
- Features
- Tools
- Icons
- CSS Architecture
- Notes & Ideas
- Issues
- Log

2. Define
---------

After you've identified the pattern(s), you need to define them. This is always the fun part in the front-end world. Naming is tricky, and you want to give it a meaningful name that isn't overly specific.

### Responsibility

First, though, determine what the responsibility of the pattern is. That will help dictate the name of the pattern.

**Example**

### Name

With the responsibility defined, you can then name the element.

**Example**

3. Build
--------

Now that the pattern is identified and defined, you can build the module.

**Example**

4. Combine
----------

With your module built, you will want to combine it with other modules that you have created. For example, your layout patterns &mdash; `row`s, `cell`s, and `grid`s, will be used in conjuntion with one another to lay out the page.

The goal of a flexible CSS architecture is to have separate, encapsulated modules that can work together and be mixed and matched to create various styles.

**Example**

5. Refine
---------

With all of your modules now working together, you'll want to refine, or refactor, as necessary. You're never going to write something perfect the first time (most likely), so be sure to constantly evaluate and refactor your CSS code. Don't be afraid to write something specifically, and abstract as you build out the site. Frequently, we're building sites in an unpredictable manner, so we'll have to change the structure are we build out the system.

**Example**

