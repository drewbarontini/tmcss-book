---
title: Intro
type: page
priority: 2
---

Intro
=====

The name of this talk is "Thinking Modular CSS." Before we get started, I'd like to take a moment and talk about Dan Denney.

Musings about Dan Denney
------------------------

I'm fortunate enough that I get to work with Dan Denney. He is one of my favorite people on this planet.

The story I like to always tell that illustrates this is his encounter with HTML emails. I'm sure all of us here know how painful they are. You have to code in `table`s, use inline styles, and it's just generally not fun. All of our front-end developers just get in, do them, and get out. However, not for Dan Denney. Instead of pushing through and moving on, what did he do? He made our HTML emails awesome, pushed the technology, and now wears the crown of "HTML Email King."

He's truly a saint, and everyone needs to know that.

`#saintdenney`

I love this conference
----------------------

In all seriousness, though, I love this conference. I've only missed it once, and I look forward to it every year. The Denney family does a tremendous job, and I'm super pumped to be here, and to be speaking to all of you.

And as proof that I've been here before, here is a picture of me from last year. Funny story: in our company chatroom, if you use the word "unimpressed", this picture shows up because, apparently, I look unimpressed. However, I think I was more just in awe while looking at all the bacon.

What is this talk about?
------------------------

So what am I hear to talk about? This talk is called, "Thinking Modular CSS". What does that mean?

> Learn the "why" of modular CSS by analyzing the decisions that craft a flexible architecture.

I *really* want to explore the thought process behind writing modular CSS. We've talked a lot about the "how" of things like object-oriented CSS (and other CSS methodologies), but we haven't really talked about the process that we take to get there.

It's something that we see with new front-end developers that we teach our system to. They understand how we structure things, what we call certain elements, how we organize our CSS, but how we get there, the thought process, is the tough part to teach.

How is this going to work?
--------------------------

So how are we going to go about this? First, we'll define "modular CSS." Next, we'll talk about the process of writing modular CSS, and then we'll go through a set of popular sites to actually apply this process and knowledge we've all gained.

Who am I?
---------

Before we get into that, I want to give you some information about me. As Dan said, I'm Drew Barontini. You can find me on Twitter, or most places on the Internet, **@drewbarontini**.

What do I do?
-------------

I'm a front-end developer at Code School. We have our offices right over in Orlando. Being in Orlando, we get to have fun company events, like:

- Trips to the Epcot Food & Wine Festival each year, where we get to eat and drink the day away
- Playing WhirlyBall
- And occasionally attending Orlando Magic basketball games

What is Code School?
--------------------

If you're not familiar with Code School, it is an online platform for teaching web technologies. We have interactive courses teaching technologies like Ruby on Rails, Sass, Git, Angular, iOS, and a lot of other languages and frameworks.

What am I responsible for?
--------------------------

### I maintain and lead the front-end for the .com

Our .com, codeschool.com, holds all of our courses, our users, our teams, and it allows them to track their progress and pick and choose which courses to take.

### Our course engine

I'm also responsible for our course engine, which is a separate entity from the .com, and it's what runs each course.

### Buildout of individual courses

In addition to that, I also oversee the buildout of individual courses, as well as keeping courses up-to-date.

The journey
-----------

What has been my journey into front-end development? This is a question that we ask all new hires because it's really interesting to see the various paths people have taken to the field, particularly into "front-end development."

### Band

For me, it all started when I was in a band back in High School and into College. Music is a creative field, obviously, but it was actually the abundance of design and web needs for the band that got me started.

### MySpace

MySpace was a really big thing for bands back in the day (not sure what it is now?), and we didn't have the money to pay a web designer to create a custom MySpace page, so I took a stab at it. Little did I know, I'd really find a passion in the horrid CSS I wrote for custom MySpace pages.

Side note: if anyone in here ever did custom MySpace pages, let's get together at some point and share a good cry. You will understand.

### T-shirts

Eventually, that evolved into more traditional illustration and graphic design, primarily for custom t-shirt and apparel designs. This was a really big component in the music world; custom t-shirt designs. There was a great community of designers that I learned a lot from.

However, I continued honing my HTML, CSS, and JavaScript skills in college, and ultimately became interested in more advanced, traditional programming.

### Computer science

I took some computer science classes in college, and I became fascinated with programming.

### Front-end

Ultimately, the balance and blend of design and programming landed me right where I'm happy to be now, front-end development.

Front-end is a specialization
-----------------------------

"Front-end Development" truly is a specialization; it's a craft, and it's not easy to do. It's not just for designers who code or developers who write HTML & CSS. It's an area of focus for unique individuals with particular skill sets.

### Developers respect us (mostly)

Developers used to trample over the HTML and CSS, largely qualifying their actions as "HTML and CSS are so easy, any of us can write it." Although HTML and CSS are easy to write, they aren't easy to write well. 

### We're building complex systems now

Our styles are built out on large-scale applications that need to be performant and easily understood by a large team.

### Programmatic layer of abstraction

We're (generally) working with preprocessors like Sass and LESS,which add a more programmatic layer of abstraction to our CSS, which is allows us to use more advanced methods for creating module CSS.

### Ability for styles to flex and work in different situations, environments

Our styles need to be flexible so that we can add new features and pages, as well as have a solid foundation for each new site or application that we build.

In order to create flexible and modular systems, we have to adhere to the ideas of "Modular CSS," so let's talk about those ideas.

