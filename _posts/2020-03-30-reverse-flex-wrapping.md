---
layout: post
title: "Reverse Flex Wrapping"
summary: "I used reverse flex wrapping for the first time, and it was really convenient!"
author: Tom Schaefer
author_url: http://teecom.com/people/tommy-schaefer/
---

While working on a side project last week, I ran into a pretty ugly visual bug
with long content.

![](/assets/reverse-flex-wrap/before-design.png)

After brainstorming a bit, I decided that wrapping the `Discussed IRL` badge
across lines might look okay. Then the question was, should it wrap upwards or
downwards?

![](/assets/reverse-flex-wrap/mockup.png)

Based on my really rough mockup, I decided that the badge should wrap upward.
I struggled to find the best way of implementing this until I learned that
[`flex-wrap`](https://www.w3schools.com/cssref/css3_pr_flex-wrap.asp) has a
`reverse` option.

![](/assets/reverse-flex-wrap/wrapping.png)

Perfect! After applying this to my existing code, I was pretty happy with the
result!

![](/assets/reverse-flex-wrap/after-design.png)
