---
title: 'Introduction to Next.JS'
date: '2020-01-02'
---

**Next.JS** creates fast, search engine optimize react apps with zero configuration.
A Traditional react app is rendered client side where the browser with a html page lacking any rendered content from there the browser fetches the javascript file containing the react code to render content to the page and make it interactive but there are two major drawbacks with client-side rendering 
1. The content is not reliably indexed by all search engines or even read by social media link bots. 
2. It can take longer to reach the first contentful paint when a user first lands on the web page 

Next.JS is a framework that allows you to build a react app but render the content in advance on the server so the first thing a user or search bot sees is the fully rendered html after receiving the initial page client-side rendering takes over and it works just like a traditional react app it's the best of both worlds fully rendered content for bits highly interactive content for users.

Next can perform multiple server rendering strategies from a single project.

1. **Statis Generation** or **Pre-rendering** allows you to render your pages at build time each page or component can implement it. It works great for a blog or any kind of app where the data doesn't change often.

2. If the data does change often you can implement **Server-side Rendering** which builds the html page each time it's requested by the user so instead of running at build time this function runs at request time that means the page will fetch the latest data on the server each time a new request comes in. That's great for pages with rapidly changing data. 
