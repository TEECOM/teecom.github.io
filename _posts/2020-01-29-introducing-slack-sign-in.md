---
layout: post
title: "Introducing: <code>slack_sign_in</code> for Rails"
summary: Streamlined sign-in (or up) with Slack for Rails applications
author: Tom Schaefer
author_url: http://teecom.com/people/tommy-schaefer/
---

Over the past year, our team has built a number of Slack applications for
internal tools, demos, and for fun. We found ourselves writing the same
[OmniAuth](https://github.com/omniauth/omniauth) code over and over again, so we
decided to try and make it a bit easier on ourselves.

Inspired by Basecamp's
[`google_sign_in`](https://github.com/basecamp/google_sign_in) gem, our goal was
to make something that would let us integrate "Sign in with Slack" into our
Rails apps:

  - with minimal configuration
  - as quickly as possible
  - without sacrificing on long-term stability and maintainability

And so,
[`slack_sign_in`](https://github.com/teecom/slack_sign_in) came to be! You can
find the gem on [GitHub](https://github.com/teecom/slack_sign_in) with written
documentation, but we also made a short getting started video.

<iframe src="https://player.vimeo.com/video/387819353" width="711" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
