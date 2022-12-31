---
title: Introducing Web Components Guide
authors:
  - Keith Cirkel
draft: false
excerpt: >
  Hello, world! Announcing the launch of a new way to learn how to create Web Components!
---

The Web is a special place. It's a giant ecosystem that organically grows day by day. Rather than being designed behind
closed doors by a single corporation, the web is designed in the open by developers who _use_ the platform. It's one of
the very few areas in which we see multiple competing corporations work together to ensure a productive, interoperable
set of APIs that millions of other companies can leverage. No other platform comes close.

When I first picked up Microsoft Front Page '98 and started trying to build my own site, I was immediately hooked. Over
20 years later I'm still here, building on this wonderful platform we call the web. The sites I work on are very
different to the ones built in Front Page, but the fundementals are still the same. In 1998, CSS was brand new, today
it's vastly more powerful but still retains the core identity it had back in 1998. Likewise 2008 saw the introduction of
HTML 5, building on the core foundations of HTML 4 and introducing a slew of exciting new tags to make more intricate
documents. I remember the introduction of HTML 5 and thinking "wouldn't it be great to define our own tags?". Luckily I
wasn't alone in that thought, and the next decade of innovation on the web saw exactly that, today Web Components allow
engineers to define their own tags with unique functionality.

Web Components had a rocky start. The initial release of the Custom Elements API in 2014 (referred to as "Custom
Elements V0") predates modern JavaScript idioms like ES6 Classes, which made them a little clunky to use, and various
other factors prevented vendors (other than Google) from shipping the V0 spec, despite multiple experiments like
Mozilla's [x-tag] and Google's [polymer]. Eventually vendors agreed on, and shipped a new specification (Custom Elements
V1), which also coincided with powerful new technologies such as ShadowDOM. Luckily today, that's all a footnote in the
history of the web platform and Web Components (the modern version) is a proven technology used by companies the world
over.

One of the best things about the web is the sheer number of learning materials accessible, for free, to learn how to
develop great experiences for the web. Corporations like Mozilla, Google and Microsoft collaborate on excellent
resources like [MDN][mdn], or [web.dev][web-dev], and an army of content creators produce blogs, videos, books, and
more. I _wish_ this amount of information was available to me when I opened up Front Page for the first time. Learning
how to develop for the web has never been better.

As great as these learning resources are, they typically cast a wide net. When speaking to developers that first learn
of Web Components, one question I am often asked is "how can I find out more?". "The documentation is all there!", I
say, "just look it up on MDN!". While MDN provides a great reference, it doesn't give you _the journey_. It can't give
you _the journey_, because it's job is to be a reference. [MDN still documents Custom Elements V0 APIs][mdn-ce-v0], and
despite the various sign posts telling you not to use this, it remains, because MDN's job is to be a reference!

_The journey_ is a hallmark of every great framework. The plethora of front-end frameworks today have _the journey_,
from [Lit] to [Vue] to [Svelte] to [React] to [Remix], every one starts out with the basics, and eventually leads you to
[drawing the rest of the owl][owl]. Web Components, however, have lacked this. MDN provides you with all the resources
to know about the building blocks, but doesn't tell you how to put them together. On how to draw the rest of the owl is
left to you.

And building good owls - I mean UI - is _hard_. Building a component thats durable to the variety of situations it gets
placed in, capable of accepting the wide inputs it needs, accessible for sighted users, users of screen readers,
braille, mobile, desktop, watch, fridge. That's not easy. Good documentation goes beyond "here's an API and here's how
it works" to showing its use cases, warding against pitfalls, defining best practices, demonstrating how to build a
system that _scales_.

That's why this site now exists. A team of Web Components advocates gathered together to start on _this journey_. Our
aim is to create a documentation site casting one very specific net: levelling you up on Web Components, giving you the
skills to use this great platform technology to build rich, interoperable, user experiences.

Today's version of this site is an early iteration. There's lots of empty rooms. Not all the furnishings have been
placed yet. We're working on it. Here's the content we have (or shortly hope to have):

- **[Learn][learn]**: This will take you through _the journey_. Learn the basic building blocks and learn how to connect
  them to make useful user experiences.
- **[Tutorials][tutorials]**: This section will give you more substantial end-to-end guides on how to build _one
  specific component_, end to end. Each tutorial might not cover all topics, will cover extended platform features or
  third-party libraries, and will make design decisions that might not be applicable to all web components. We hope this
  is an area where you can learn how experienced developers would build a robust component.
- **[Ecosystem][ecosystem]**: The Web Platform has a broad ecosystem, and lots of tools exist to make building Web
  Components a joy. This section will point you to the great libraries that exist outside of just the Web Platform APIs.
- **[Blog][blog]**: That's this section! Here we'll be sharing Web Component news, including new advancements in browser
  support, smaller guides and content that shows how Web Components are being used in the wild.

#### We need your help!

Hopefully you're here for one of two reasons: either you want to learn more about Web Components, or you're already a
fan and want to see the technology grow. We need you!

If you're new to Web Components then _please read what we have_, and let us know your thoughts! [Start with the
introduction][intro] and if you see bugs, typos or get stuck on a section then [file an issue][issue]! We want to make
this the best place to learn about Web Components and if you're the one learning, then this place is for you - we want
your feedback!

If you're already a fan of Web Components then we _want to hear from you_! Using them in novel ways? We'd love to hear
about it and welcome you to write a [Tutorial][tutorials], or a [Blog][blog] entry. Built a new tool that works with Web
Components? Please share it with us as we'd love to include it in the [Ecosystem][ecosystem] pages. If you feel
comfortable writing or refining content in the [Learn][learn] section then your input would be invaluable to countless
developers learning to build Web Components.

[x-tag]: http://x-tag.github.io/
[polymer]: https://polymer-library.polymer-project.org/
[mdn]: https://developer.mozilla.org/en-US/
[web-dev]: https://web.dev/
[mdn-ce-v0]: https://developer.mozilla.org/en-US/docs/Web/API/Document/registerElement
[lit]: https://lit.dev/docs/
[vue]: https://vuejs.org/guide/introduction.html
[svelte]: https://svelte.dev/tutorial/basics
[react]: https://reactjs.org/docs/getting-started.html
[remix]: https://remix.run/docs/en/v1
[owl]: https://knowyourmeme.com/memes/how-to-draw-an-owl
[intro]: https://webcomponents.guide/learn/
[issue]: https://github.com/WebComponentsGuide/webcomponents.guide/issues/new
[learn]: https://webcomponents.guide/learn/
[tutorials]: https://webcomponents.guide/tutorials/
[ecosystem]: https://webcomponents.guide/ecosystem/
[blog]: https://webcomponents.guide/blog/
