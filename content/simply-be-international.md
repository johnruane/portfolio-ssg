+++
title = "SimplyBe International"
date = 2015-01-01
description = "Fully responsive rebuild of the UK website, optimised for Mobile and Tablet devices."

[extra]
group = "work"
released = "Released 2015"
pills = ["Responsive", "LESS", "Wireframing", "Hybris", "Grunt"]
+++

Introduction
In late 2014 the IT department at N Brown Group began a transformation programme called 'Fit4Future' - the largest business transformation the company had ever undertaken. Its aim was to transfer all the old tech that had been powering our websites for decades, and move them to new systems that can truly make Brown a modern digital retailer. The platform that the current website ran on was top on the list for migrating. A new web platform also meant a new frontend - built from scratch. 
Previously we had separate codebases for desktop, mobile and tablet in order to provide different content to customers optimised to for the viewport they were browsing on. Over the years managing the UI over three codebases inevitably fell out of sync and building new features always took priority. The new frontend would be responsive in order to cater for all viewport widths. It also had to be modular; the UI would be built as fragments and blocks so it could be reused and would mean consistency across the different pages.

Shared codebase across all devices on the Hybris Commerce platform.

Approach to the design
Usually our design process would begin with a problem. A teams made up of a cross-section of designers, developers and product owners would come up with some initial sketches of ideas based on budgets and previous experience. These sketches would be documented and this information would form the basis of a mockup which should solve the original problem.
But with responsive web design we couldn’t do the usual flat mockup designs. We would have endless versions of a design at various viewport sizes, which would all have to be updated if a change was made. It's much better to be able to interact with a design in order to see what works and what does not. Something that works on paper may not work on a small screen. By building our mockups in the browser out of the building blocks of our modular system, we could build quickly and consistency. These designs could then be reviewed by the business on any device and given approval or have changes requested - creating a circular process of design, review and refine.
Build decisions
The frontend was built using a customised version of Bootstrap. Like blocks of Lego, Bootstrap is modular and pieces can be reused throughout the codebase. The styling for these blocks also had to customisable across our large set of brands. In order to modularise the CSS and only have styles related a particular brand we used a dynamic stylesheet language which we would build using a JS package runner. The markup was written in LESS. All reusable styles were written as variables so that every brand could have different values so that once compiled the CSS output would be a unique combination different from the other brands.
We also used the JS task runner to compile out the pages which were made up of the various blocks of UI we’d built. There was an initial time cost to setting all this up, but the time saved once implemented was huge.
Testing strategy
Testing was simplified for this project. Because our customer base typically is not as tech-savvy as you typically find for other ecommerce brands, a lot of work would be required to make sure legacy browsers were supported. Making UI display consistently across multiple browser versions was expensive and time consuming. It also limited a design such that new features couldn’t take advantage of new browser capabilities. The Bootstrap framework had been extensively tested and any bugs reported got resolved quickly.
This didn’t mean we were free from testing. We used browser emulation to test designs before they were developed. For device testing we had our own testing lab that contained a vast array of mobile devices.

SimplyBe international has provided a foundation for all our new technologies going forward.