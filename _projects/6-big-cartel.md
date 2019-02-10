---
title: 'Big Cartel'
subtitle: '2015-Present'
featured_image: '/images/bigcartel/bigcartel.png'
---

![Big Cartel](/images/bigcartel/bigcartel-main.png)

Big Cartel provides easy online tools for makers, designers, musicians, and other artists to set up an online store. As a Senior Software Engineer, I've touched every facet of their product from their marketing site, admin tools, mobile site, and checkout.  As part of a small remote team, I rely heavily on asychronous communication, pair programming, test driven development, code reviews and continuous integration during the development lifecycle. I also regularly collaborate with designers to improve the user experience of our products.

## Technologies
* Ruby on Rails
* Web components (Stencil.js, Riot.js)
* Typescript
* TDD (RSpec, Capybara, Jest, Jasmine, Karma)
* HAML
* Sass
* GraphQL

## GraphQL API

I'm currently helping design the next iteration of our API using [GraphQL](https://graphql.org/). There are a number of benefits, including adding flexibility for our integrators to only get the data they need using a single endpoint. It also allows for a frictionless evolution of our API without versions, giving us the ability to add new fields and types without impacting existing queries. It also is self-documenting, keeping our schema up-to-date whenever something changes. Although it is currently for internal use only, we are hoping to provide a public API in the future.

## Responsive admin

One of the largest projects I worked on was Big Cartel's responsive admin.  At the time, Big Cartel had a separate mobile site that didn't share a cohesive design or codebase with our desktop experience.  This led to inconsistencies and created double the amount of work on the team in order to push an update for both experiences.  Our aim was to do away with the current mobile site altogether and make the current desktop experience responsive.  We took a "mobile first" approach to responsive design and progressively enhanced them for larger screens.  I worked with designers to make sure the experience across device widths was as frictionless as possible with minimal need for custom code.

![Responsive admin](/images/bigcartel/bigcartel-responsive.png)


## Design system

Maintaining consistent experiences is difficult, especially as the team grows and more features and products get added. In order to tackle this issue, I worked with the designers on my team to create a design system and component library. This not only allowed design and development to share a common language, it gave us the ability to do our work more efficiently. We used UI methodologies like [Atomic Design](http://www.atomicdesign.bradfrost.com/chapter-2/) in order to break components down in a hierarchical manner and  web component libraries like [Stencil](https://stenciljs.com/) to easily turn components into reusable and maintable code. By creating a single source of truth that can be referenced by anyone on the team, it allows us to tackle more important stuff, like how to create an amazing customer experience for our users.


## Improving accessibility

At Big Cartel, we care deeply about our customers and want to make sure that our products are not only delightful but easy to use. An important part of that is to make our product as accessible as possible to our users. I helped spearhead an effort to think "accessibility" first and find ways to incorporate it into our process.  Thinking about accessibility encourages empathy and to think outside of just ourselves.  It allows us to reach a wider audience that otherwise wouldn't be able to use our product. It is also ethically the right thing to do. I helped establish accessibility standards, such as color contrast compliance, semantic markup, keyboard navigation,  and descriptive images and iconography that can be used with any product we work on.  We also established ways to audit accessiblity by using tools like [Axe](https://www.deque.com/axe/).

## Dashboard

One of the smaller, but still impactful projects I worked on was developing an interactive dashboard for users to track their earnings and visitor stats. Using [d3.js](https://d3js.org/), I was able to bring data to life in a beautiful and delightful way.

![Dashboard](/images/bigcartel/bigcartel-dashboard.gif)
