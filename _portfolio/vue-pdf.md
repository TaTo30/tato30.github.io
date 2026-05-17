---
title: "vue-pdf"
excerpt: "PDF component for Vue 3. <br/> An easy-to-use component for rendering PDF pages in a dynamically and customizable way. VuePDF is a client-side component for Vue 3 that allows you to flexibly render PDF pages within your project. This library wraps pdf.js library so all main features of pdf.js are supported by VuePDF as well. <a href='https://tato30.github.io/vue-pdf/'>library website</a>"
collection: portfolio
---

This project started during 2022 as an alternative to the package vue-pdf developed by FranckFreiburger. At that time Vue team shipped Vue 3, a major version that introduced the composition API and changed completely how to develop single-file components (SFC). Our team decided to update all our projects from Vue 2 to Vue 3, what a journey! pratically all our projects stop working.

Then we started to rewrite our components, migrate to new APIs and update dependencies. The latter was sometimes easy because most authors already updated their projects to make them working with Vue 3 and sometimes a pain because many authors abandoned their projects like the case of the library `vue-pdf`. Since nobody were trying to migrate this project to Vue 3 and we wanted specific features for a pdf library I decided to create a pdf library myself.

At first, I developed this library only for our team sake but after seeing that no libraries weren't supporting Vue 3 yet I decided to publish this work to NPM with enough features to support multiple use cases.

This library is basically a wrapper around mozilla/pdf.js and It's the only dependency of this work. This library is no longer in active development but It's still in maintenance to keep it updated with pdf.js.

For any technical detail I invite you to check the GitHub repository: [vue-pdf](https://github.com/TaTo30/vue-pdf)
