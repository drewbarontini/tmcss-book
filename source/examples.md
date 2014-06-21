---
title: Examples
type: page
priority: 5
---

Examples
========

Now that we've defined "Modular CSS" and talked about the process of discovering and writing patterns, let's take that knowledge and walk through some real sites and determine how we'd structure our CSS.

Dribbble
--------
[http://dribbble.com/](http://dribbble.com/)

1. Identify
2. Define
3. Build
4. Combine
5. Refine

![Dribbble](example-dribbble.png)
![Dribbble](example-dribbble-bottom.png)

### Structure & Layout

First, we start by identifying the most reusable modules, the ones used for structure and layout.

- Row
- Cell
- Well
- Grid

#### Row

The `row` module handles width-spanning blocks.

- Full-width background colors
- Horizontal padding

![Dribbble](example-dribbble-row-01.png)
![Dribbble](example-dribbble-row-02.png)
![Dribbble](example-dribbble-row-03.png)

#### Cell

The `cell` module handles width-limiting.

- Horizontal centering
- `max-width`

![Dribbble](example-dribbble-cell-01.png)
![Dribbble](example-dribbble-cell-02.png)

#### Well

The `well` module handles vertical spacing.

- Top/bottom margin

![Dribbble](example-dribbble-well.png)

#### Grid

The `grid` module handles grid-based element arrangement.

![Dribbble](example-dribbble-grid-01.png)
![Dribbble](example-dribbble-grid-02.png)

```html
<div class="row">
  <div class="cell well">
    <div class="grid">
      <!-- ... -->
    </div>
  </div>
</div>
```

With these modules in place, we have a simple structure that we can use to set up the layout of the site.

### Common Patterns

Next, we tackle the common patterns that we're used to seeing.

- List
- Thumb
- Icon
- Form
- Card
- Bucket

#### List

We can see that there are a lot of lists throughout the site.

![Dribbble](example-dribbble-list-01.png)
![Dribbble](example-dribbble-list-02.png)

We have a few different types of lists:

- Inline
- Block
- Object (floated)

##### Thumb

We'll want a `thumb` module to handle our user thumbnails and create the circle avatars.

![Dribbble](example-dribbble-thumb.png)

#### Icon

We'll need an `icon` module to handle all the site-wide icons.

![Dribbble](example-dribbble-icon-01.png)
![Dribbble](example-dribbble-icon-02.png)

#### Form

![Dribbble](example-dribbble-form.png)

#### Card

![Dribbble](example-dribbble-card.png)

#### Bucket

![Dribbble](example-dribbble-bucket-01.png)
![Dribbble](example-dribbble-bucket-02.png)

### Unique Patterns

I'm not seeing any unique patterns, but that might change as you build out the site.

### Audit

Based on our assessment, we'll have these modules to build the primary page of our site, and set the foundation for building out more pages.

- Row
- Cell
- Well
- Grid
- List
- Thumb
- Icon
- Form
- Card
- Bucket

Since it would take me all day to run through how to write all of these elements, I'm going to spare you the pain of listening to me that long and provide a link to the code up on GitHub.

**Link to code**

Digg
----
[http://digg.com/](http://digg.com/)

1. Identify
2. Define
3. Build
4. Combine
5. Refine

![Digg](example-digg-01.png)
![Digg](example-digg-02.png)
![Digg](example-digg-03.png)

### Structure & Layout

First, we start by identifying the most reusable modules, the ones used for structure and layout.

- Row
- Cell
- Well
- Grid

#### Row

The `row` module handles width-spanning blocks.

- Full-width background colors
- Horizontal padding

![Digg](example-digg-row-01.png)
![Digg](example-digg-row-02.png)
![Digg](example-digg-row-03.png)
![Digg](example-digg-row-04.png)
![Digg](example-digg-row-05.png)

#### Cell

The `cell` module handles width-limiting.

- Horizontal centering
- `max-width`

![Digg](example-digg-cell-01.png)
![Digg](example-digg-cell-02.png)
![Digg](example-digg-cell-03.png)
![Digg](example-digg-cell-04.png)

#### Well

The `well` module handles vertical spacing.

- Top/bottom margin

![Digg](example-digg-well-01.png)
![Digg](example-digg-well-02.png)
![Digg](example-digg-well-03.png)

#### Grid

The `grid` module handles grid-based element arrangement.

![Digg](example-digg-grid-01.png)
![Digg](example-digg-grid-02.png)
![Digg](example-digg-grid-03.png)

```html
<div class="row">
  <div class="cell well">
    <div class="grid">
      <!-- ... -->
    </div>
  </div>
</div>
```

With these modules in place, we have a simple structure that we can use to set up the layout of the site.

### Common Patterns

Next, we tackle the common patterns that we're used to seeing.

- List
- Icon
- Bucket
- Button
- Form

#### List

We can see that there some lists throughout the site.

![Digg](example-digg-list-01.png)
![Digg](example-digg-list-02.png)
![Digg](example-digg-list-03.png)

#### Icon

We'll need an `icon` module to handle all the site-wide icons.

![Digg](example-digg-icon-01.png)
![Digg](example-digg-icon-02.png)
![Digg](example-digg-icon-03.png)

#### Bucket

![Digg](example-digg-bucket.png)

#### Button

![Digg](example-digg-button.png)

#### Form

![Digg](example-digg-form.png)

### Unique Patterns

I'm not seeing any unique patterns, but that might change as you build out the site.

### Audit

Based on our assessment, we'll have these modules to build the primary page of our site, and set the foundation for building out more pages.

- Row
- Cell
- Well
- Grid
- List
- Icon
- Bucket
- Button
- Form

Since it would take me all day to run through how to write all of these elements, I'm going to spare you the pain of listening to me that long and provide a link to the code up on GitHub.

**Link to code**

