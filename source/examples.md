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

### Identify

![Dribbble](example-dribbble.png)
![Dribbble](example-dribbble-bottom.png)

#### Structure & Layout

First, we start by identifying the most reusable modules, the ones used for structure and layout.

- Row
- Cell
- Well
- Grid

##### Row

The `row` module handles width-spanning blocks.

- Full-width background colors
- Horizontal padding

![Dribbble](example-dribbble-row-01.png)
![Dribbble](example-dribbble-row-02.png)
![Dribbble](example-dribbble-row-03.png)

##### Cell

The `cell` module handles width-limiting.

- Horizontal centering
- `max-width`

![Dribbble](example-dribbble-cell-01.png)
![Dribbble](example-dribbble-cell-02.png)

##### Well

The `well` module handles vertical spacing.

- Top/bottom margin

![Dribbble](example-dribbble-well.png)

##### Grid

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

#### Common Patterns

Next, we tackle the common patterns that we're used to seeing.

- List
- Thumb
- Icon
- Form
- Card
- Bucket

#### Unique Patterns

I'm not seeing any unique patterns, but that might change as you build out the site.

**Link to code**

Instagram
---------
[http://instagram.com/](http://instagram.com/)

1. Identify
2. Define
3. Build
4. Combine
5. Refine

GitHub
------
[http://github.com/](http://github.com/)

1. Identify
2. Define
3. Build
4. Combine
5. Refine

