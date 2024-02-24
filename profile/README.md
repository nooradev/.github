# Noora

JavaScript UI rendering solutions (e.g., React, Vue, Svelte) introduced a new paradigm for web interfaces that revolutionized the web ecosystem.
Developers could suddenly encapsulate markup, style, and behavior in components that used NPM packages as a unit for distribution.
They became a layer upon which new developer experiences and paradigms emerged. For example, [Storybook](https://storybook.js.org/),
to showcase your project's components,
or or the [CSS-in-JS](https://css-tricks.com/a-thorough-analysis-of-css-in-js/) pattern.
Many non-JS web apps, for example Rails projects,
felt inclined to absorb the complexity of embracing [SPAs](https://en.wikipedia.org/wiki/Single-page_application) and maintaining and synchronizing state through an API,
for the sake of having access to the emerging ecosystem.
Some even added additional runtimes (e.g., NodeJS) to their production environments.
Non-JS frameworks like Rails, Phoenix, or PHP tried to come up with their answer to building interactive experiences. Although some came to approaches that resembled what the JS frameworks were doing,
they were far from having an ecosystem as rich as the JS one, which is one of the reasons why many projects are betting on JS despite all the layers of indirection and complexity that comes with it.
What if we didn't have to be like that?

**The paradigms of those JavaScript technologies don't need to be exclusive to the JavaScript ecosystem.**
We can build a lower-level and technology-agnostic native compiler that draws inspiration from CSS-in-JS, state-driven UIs, and the many other patterns that emerged
and provide bindings for the various programming languages and runtimes available.
We'll design a language and a compiler that will act as a [narrow-waist](https://www.oilshell.org/blog/2022/02/diagrams.html) upon which new paradigms, 
tools, design systems, and more can emerge without being coupled to the JavaScript ecosystem.
