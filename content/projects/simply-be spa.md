+++
title = "SPA rebuild in React"
date = 2022-01-01

[extra]
short_description = "Full rebuild of front & backend code in NextJS following a custom design system, high accessibility standards and precise UX guidelines. Focus on high performace across all devices."
group = "work"
released = "2022"
role = "Senior Software Engineer"
pills = ["SPA", "NextJS", "REST", "Jest", "Cypress", "PostCSS", "GitLab", "Design system", "Performance"]
+++

Thrid time lucky. This project was the third attempt at getting the website off the in-house platforam that was built in 1999 and which served as the frontend website for 10+ brands and their content management system. Three years and 13 days from first commit to go-live date, this was a monumental effort with a starting team of 3, went through 2 contracting agencies, numerous u-turns on technologies, several reshuffles before finally being launched to the world.

Developed from scratch, the new platform has delivered a completely new frontend experience, a customised open-source CMS, an archetecture that can be independently deployed and a migration from traditional monolithic services to a lightweight modular microservice.

---
> TODO
---
### Design

The 4-point grid system was built from the ground up to meet WCAG online accessibility standards.

UX designs created in Zeplin were used to build the design system.

---
> TODO
---

### Build

The framework supports both client- and server-side code and was created with NextJS.

Custom properties were incorporated into CSS to allow for the application and branding of the design system.

CSS modules used for classname scoping.

Automating repetitive, mundane programming with PostCSS.

For scaling our monorepo for separate feature deployments and multi-branding we used the NX build system

---
> TODO
---

### Test

Jest, React Testing Library, and Cypress are used for unit, integration, and e2e testing.

GitLab CI/CD pipeline used, with stages for feature, QA & production enviroments.

Coverage quotas for unit and integration tests. Sonarcube is used to find code that could be improved.

### Challenges

Transitioning from UI developer to Software Engineer has a steep learning curve.

Simple to grasp React, but more difficult to master.

Another project in which consulting firms were brought in. This sped up development but made it difficult to monitor and maintain coding standards due to time constraints.

---
> TODO
---
### Likes

When working with a design system, there is no ambiguity in how it is implemented.

By using CSS modules, I was able to keep code and CSS separated - no more classname clashes.

When compared to previous work streams, CI/CD means being able to develop and deploy faster.

### Dislikes

Bugs in code may necessitate heuristic web development knowledge.

Silos can exist even within the same team. Monitoring code changes may become more difficult as developers may not be aware of all the logic.

Retrofitting tests that are missing from the codebase is time consuming and difficult.

### Lessons

The monumental task of creating a design system from the ground up.
