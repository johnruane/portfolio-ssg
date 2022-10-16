+++
title = "JD Williams"
date = 2010-01-01
description = "Fully responsive rebuild of the UK website, optimised for Mobile and Tablet devices."

[extra]
group = "work"
released = "Released 2010"
pills = ["Desktop", "Wireframing", "Prototyping", "UX", "Agile"]
+++

Introduction
The N Brown website has been completely transformed since I started in 2005. Running parallel to the other optimisation projects has been a Tactical workstream designed to yield quick functional benefits on a regular basis, rather than a big bang release after a prolonged period of time. Projects that can be conceived, built, tested and released in a short time frame (usually 2 weeks) in order to continually improve the website.
Recently the Desktop has been undergoing changes to make it more fluid as desktop screen widths become more varied.

Online sales account moved from 20% in 2005 to 70% today.

Approach to the design
Typically the process of mocking up ideas is done in Photoshop. By keeping projects small and Agile, it means heavy planning and prototyping is not necessary. When it has been necessary to show interactions then I have used Axure, which is a tool that allows you to animate common interactions within a wireframing environment.
For the fluid work, which has typically done on larger projects, the team used a mixture of design tools - Pen & paper sketching is always a good place to start. Designs can then be more formally presented in applications such as Photoshop or Illustrator - the latter best for displaying the flow of a process.
Build decisions
The build process for desktop could go down one of two routes: for small projects I would make the markup/css changes in the existing files whilst running a local build of the code on my machine, for larger projects I would build these pages using an editor such as Dreamweaver and then collaborate with a Java developer to integrate this into the codebase (usually) in the form of JSP pages.
The biggest challenge was working with code that was first developed in 1999. It had gone through 3rd party developers and many in-house developers - it was a spaghetti code in places. The concept of modular: modules, components & reusability were not as prevalent as they are now so the code grew with little planning and foresight of the wider whole. The code became very fragile and was easily broken.
Testing strategy
Because we usually ran a copy of the website on a local server we were able to test any work we did with stub data. Browser support was extensive due to the many versions used by our customers whom a large percentage seldom updated their computers. For a long time we would be including browser specific hacks or css work arounds in order to get the display the same on every browser. Thankfully these days its given that there may be small differences between browsers, and that these differences are not an issue worth resolving.
Most browsers now have the ability emulate various devices and legacy versions. If you want to 100% test something though then there is no substitute to actually using that device or legacy browser - for this I use virtual machines.

In some form or other, I've been working on the desktop website since I started in 2005.