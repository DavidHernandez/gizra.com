---
title: "Be Responsive About Your Responsive Design Needs"
tags:
  - Bootstrap
  - "Drupal-planet"
permalink: "/content/simplify-bootstrap"
layout: post
author: YaronMiro
published: true
---

{% include setup %}

The vast majority of our projects at Gizra are based on [Bootstrap](http://getbootstrap.com/) framework and we often spend a lot of time and effort in creating the perfect responsive layout and UX (user experience)
across all breakpoints. As Bootstrap comes by default with four breaking points, we found ourself implementing them, until we started asking ourself:

__Q__: Is responsive really needed?  
__A__: Yes, Of course.

__Q__: Do we always need so many breakpoints?  
__A__: No.


<div class="thumbnail">
  <img src="{{BASE_PATH}}/assets/images/posts/simplify-bootstrap/image.gif">
  <div class="caption">Bootstrap default layout VS Bootstrap custom layout</div>
</div>

<!-- more -->

### "Full Responsive" approach

`Full Responsive` - The project adapts itself to support as many devices and screen sizes (large desktop, desktop, tablet, mobile).

Bootstrap provides us with a powerful responsive layout and a matching grid system
but with great power comes great responsibility!
Our responsibility is making sure that our website/app UX is
consist and that the layout looks perfect across all of the breakpoints isn't always
an easy task to achieve and above all it consume a considerable amount of project time.

### "Responsive Pattern" approach

`Responsive Pattern` - Defines the project responsive support range.

Project adapt it self according to a "Responsive Pattern" that's was defined by it's
internal requirements and needs. On this approach we have the advantaged of supporting what
is really vital and suitable for the current project state. This give us the ability to
create a rapid solid project in a reasonable amount of time.

The responsive pattern isn't absolute and may change in the future,
But the important thing is to have a clarified solid pattern to start from when working on a project.

Of course We can still decide that it's vital to do it all and have a "full responsive" support,
But in most cases we won't have to. At least not on the first stage of the project.
So by not doing it "full responsive" or by doing it in stages we simplify our workflow and making
it more intuitive. The beauty of it is that we can also have different "responsive patterns" on
different stages of the project.

### "Responsive pattern" discovery stage
The discovery stage of our project "responsive pattern" is very important
and must be done in the exact order because each step relies in the previous one.

1) `Project Audience`   
In our case the audience are devices (phones, tablets, Desktops)
Concentrate on the current most important audience.
In the future we can monitor our website/app with "google analytics" tool
and get a better comprehension of the kind of audience traffic we have and
adjust accordingly to it if it's necessary and worth while.

2) `Project UX`   
Find out what is the mandatory "UX" that the project must provide and can it be implemented
equivalently on any device/media screen size. This will help us see in a clearer way were we need to invest our responsive effort on the project.

3) `Project UI`   
Our project "Estimation Time" gets longer and the "Budget" will become more expensive
when taking into consideration the amount of time we need to invest in every page,
widget or feature to adapt itself on multiple breakpoints.
We need to concentrate on understanding which parts of the UI (User Interface)
are the vital for our project.

4) `Summary Stage`   
Now that we established a firm base ground about our `Project Audience`, `Project UX` and `Project UI`  responsive relevance to our project, Then we can wisely decide on what we want to fit in to the "Budget" and "Estimation Time" according to our preferences.

I have create a demo that demonstrates both of these approaches:

- `Default responsive layout` (4 breakpoints) - "Full Responsive"
- `Custom responsive layout` (2 breakpoints) - "Responsive Pattern"

</br>
{% include demo_block.html demo='http://ym-bs-responsive.gizra.com/' code='https://github.com/Gizra/bootstrap-responsive' %}

</br>
> I also add another "goodie" which is my personal "live responsive monitor".
  This little tool is very handy when working with a responsive layout.
  You get a live feedback on the current breakpoint when it changes.
  I like ti keep it at the top of my layout but you can put it where ever you desire.

> <div class="thumbnail" style="margin-bottom: 0">
    <img src="{{BASE_PATH}}/assets/images/posts/simplify-bootstrap/responsive-monitor.gif">
    <div class="caption">Live responsive monitor</div>
  </div>