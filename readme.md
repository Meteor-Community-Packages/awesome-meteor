<!--lint disable awesome-git-repo-age-->
<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Meteor.JS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/Meteor-Community-Packages/awesome-meteor/actions/workflows/lint.yaml/badge.svg)](https://github.com/Meteor-Community-Packages/awesome-meteor/actions/workflows/lint.yaml)

<!-- subtitle -->

Awesome packages, articles, tips and people all around Meteor.js

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/Meteor-Community-Packages/awesome-meteor/blob/main/awesome-meteor.png" width="200" alt="Awesome Meteor.js"/>
</a>

<!-- description -->

<a href="https://www.meteor.com" target="_blank" rel="noopener noreferrer">Meteor.js</a> is an open source platform for building Web, Mobile, and Desktop applications.

</div>

<!-- TOC -->

## Contents

- [Featured (new releases)](#featured-new-releases)
- [News and Blogs](#news-and-blogs)
- [Packages](#packages)
- [Guides](#guides)
- [Courses](#courses)
- [Services](#services)
- [Companies](#companies)
- [Open Source Apps](#open-source-apps)
- [Follow](#follow)
- [Other](#other)

<!-- CONTENT -->

## Featured (new releases)

- [Meteor 2.13.1](https://docs.meteor.com/changelog#v213120230904) - Current recommended release.
- [Meteor 3 PR](https://github.com/meteor/meteor/pull/12359) - Development of the next generation of Meteor.js.

## News and Blogs

- [Meteor Blog](https://blog.meteor.com/) - Official blog of Meteor Software. 
- [Meteor Dispatched - Weekly podcast](https://www.youtube.com/@meteorjscommunity/podcasts) - Amazing podcast driven by the community about Meteor.js and related things.


## Packages

Awesome packages listed in groups.

- Application Structure
  - [zodern:types](https://github.com/zodern/meteor-types) - Tooling to use Typescript types from Meteor.js packages in your apps.
  - [mdg:validated-method](https://github.com/meteor/validated-method) - Define methods in a structured way, with mixins.
  - [meteor-partitioner](https://github.com/Meteor-Community-Packages/meteor-partitioner) - Transparently divide a single Meteor.js app into several different instances shared between different groups of users.

- Analytics
  - [okgrow:analytics](https://github.com/okgrow/analytics/) - Google Analytics, Mixpanel, KISSmetrics (and more) integration for meteor.
  - [quave:analytics](https://github.com/quavedev/analytics) - A Meteor package that allows you to send your page views and more to Google Analytics. 

- Collections
  - [aldeed:collection2](https://github.com/Meteor-Community-Packages/meteor-collection2) - Attach a schema to a Mongo.Collection. Automatically validates against that schema when inserting and updating from client or server code.
  - [aldeed:schema-deny](https://github.com/longshotlabs/meteor-schema-deny) - Allows you to deny inserting or updating certain properties in your database by setting options in your schema.
  - [aldeed:schema-index](https://github.com/longshotlabs/meteor-schema-index) - Control some MongoDB indexing from your SimpleSchema.
  - [matb33:collection-hooks](https://github.com/Meteor-Community-Packages/meteor-collection-hooks) - Extends Mongo.Collection with before/after hooks for insert, update, remove, find, and findOne.
  - [rywood:publish-composite](https://github.com/Meteor-Community-Packages/meteor-publish-composite) - Provides a flexible way to publish a set of related documents from various collections using a reactive join. This makes it easy to publish a whole tree of documents at once. The published collections are reactive.
  - [dburles:collection-helpers](https://github.com/dburles/meteor-collection-helpers) - Collection helpers automatically sets up a transformation on your collections.
  - [cultofcoders:grapher](https://github.com/cult-of-coders/grapher) - Grapher: Meteor.js Collection Joins + Reactive GraphQL like queries.
  - [quave:collections](https://github.com/quavedev/collections) - Helps to create collections in a standard way.

- Scalability & Performance Improvers
  - [redis-oplog](https://github.com/Meteor-Community-Packages/redis-oplog) - Re-implementation of the Meteor's MongoDB oplog tailing with the help of Redis. This package will solve lots of scale problems.
  - [oplogtoredis](https://github.com/tulip/oplogtoredis) - Not a package but may be needed when using redis-oplog. This program tails the oplog of a Mongo server, and publishes changes to Redis.
  - [changestream-to-redis](https://github.com/radekmie/changestream-to-redis) - Not a package but may be needed when using redis-oplog. This program listens to a MongoDB Change Stream, and publishes changes to Redis. An alternative to oplogtoredis.
  - [maestroqadev:pub-sub-lite](https://github.com/adtribute/pub-sub-lite) - Transform publications to be non-reactive.
  - [artillery-engine-meteor](https://github.com/kschingiz/artillery-engine-meteor) - Artillery load testing for applications.
  - [bundle-visualizer](https://docs.meteor.com/packages/bundle-visualizer) - An analysis tool which provides a visual representation within the web browser showing what is included in the initial client bundle.
  - [ddp-rate-limiter](https://docs.meteor.com/api/methods.html#ddpratelimiter) - Customize rate limiting for methods and subscriptions to avoid a high load of WebSocket messages in your app.

- Users & Roles
  - [alanning:roles](https://github.com/Meteor-Community-Packages/meteor-roles) - Authorization package - compatible with built-in accounts package.
  - [meteor-user-status](https://github.com/Meteor-Community-Packages/meteor-user-status) - Keeps track of users and their metadata.

- Forms
  - [uniforms](https://github.com/vazco/uniforms) - Bunch of React components and helpers to easily generate and validate forms. [Seamlessly integrate with `simpl-schema`](https://uniforms.tools/docs/installation).
  - [aldeed:autoform](https://github.com/Meteor-Community-Packages/meteor-autoform) - Adds UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation.

- Data Display
  - [aldeed:tabular](https://github.com/Meteor-Community-Packages/meteor-tabular) - Creates reactive DataTables in an efficient way, allowing you to display the contents of enormous collections without impacting app performance.
  - [aslagle:reactive-table](https://github.com/aslagle/reactive-table/) - Reactive table for Meteor.js, using Blaze.js.
  - [luixal:blaze-paginated-custom-list](https://github.com/luixal/meteor-blaze-paginated-custom-list) - Reactive and paginated item list.
  - [luixal:meteor-apexcharts](https://github.com/luixal/meteor-apexcharts) - Reactive ApexCharts library packaged for Meteor.js.

- File Management
  - [meteor-files](https://github.com/veliovgroup/Meteor-Files) - Simple files management.
  - [mikkelking:slingshot](https://github.com/Back2bikes/meteor-slingshot) - Upload files directly to AWS S3, Google Cloud Storage and others in Meteor.js.

- Internationalization
  - [universe:i18n](https://github.com/vazco/meteor-universe-i18n) - Internationalization package.
  - [Meteor-Internationalization](https://github.com/veliovgroup/Meteor-Internationalization) - Super-Lightweight and fast i18n isomorphic driver for Meteor.js with support of placeholders.

- Logging
  - [ostrio:logger](https://packosphere.com/ostrio/logger) - Logger driver with different adapters.

- Performance Monitoring
  - [mdg:meteor-apm-agent](https://atmospherejs.com/mdg/meteor-apm-agent) - If you are hosting on Galaxy professional tier you should install this package to get performance monitoring in Galaxy APM.
  - [montiapm:agent](https://github.com/monti-apm/monti-apm-agent) - Monitor your application in production to improve performance and fix errors.
  - [meteorhacks:zones](https://github.com/meteorhacks/zones) - Improves error tracking. It can be used to capture stack traces over the async execution path.
  - [kschingiz:meteor-elastic-apm](https://github.com/kschingiz/meteor-elastic-apm) - Performance monitoring for Meteor.js applications based on Elastic APM.

- Routers
  - [ostrio:flow-router-extra](https://github.com/veliovgroup/flow-router) - Routing for client-side apps and compatible with React, Vue, Svelte, and Blaze.
  - [communitypackages:picker](https://github.com/Meteor-Community-Packages/picker/) - Server side router for Meteor 2.

- Cron Jobs
  - [msavin:sjobs](https://github.com/msavin/stevejobs/) - A Meteor.js-first jobs queue / task scheduler. 
  - [percolate:synced-cron](https://github.com/percolatestudio/meteor-synced-cron) - Cron system for Meteor.js. It supports synchronizing jobs between multiple processes.
  - [ostrio:cron-jobs](https://github.com/VeliovGroup/Meteor-CRON-jobs) - Package with similar API to native `setTimeout` and `setInterval` methods, but synced between all running Meteor.js (Node.js) instances.

- Debugging Tools
  - [meteor-devtools-evolved](https://github.com/leonardoventurini/meteor-devtools-evolved) - A chrome extension.

- Deployment
  - [meteor-up](https://github.com/zodern/meteor-up) - Helps you to deploy Meteor.js application to your server with a single command (Works well with redis-oplog).

- Blaze
  - [ostrio:templatehelpers](https://github.com/VeliovGroup/Meteor-Template-helpers) - Utility helpers for your Blaze templates.
  - [kadira:blaze-layout](https://github.com/TeamGrid/blaze-layout) - Layout manager for Blaze (works well with FlowRouter).
  - [aldeed:template-extension](https://github.com/longshotlabs/meteor-template-extension) - Great extension for blaze templates. This helps you to inherit helpers and events from other templates and reduces code duplications.
  - [matteodem:easy-search](https://github.com/matteodem/meteor-easy-search) - Easy-to-use search component with Blaze (+ elasticsearch support).

- SEO
  - [mdg:seo](https://atmospherejs.com/mdg/seo) - Makes use of the built-in SEO support in Galaxy.
  - [ostrio:spiderable-middleware](https://github.com/VeliovGroup/spiderable-middleware/) - Prerendering (_a.k.a. Spiderable_) with support of ES6 (ECMAScript2015) - Meteor app crawled perfectly by search engines.

- Tooling
  - [ESLint-plugin-Meteor](https://github.com/dferber90/eslint-plugin-meteor/) - ESLint plugin for Meteor.js.

## Guides

- [Official Meteor Guide](https://guide.meteor.com) - Official Meteor.js guide to improve your Meteor.js skills.
- [How to migrate to Meteor Async in Meteor 2.x](https://guide.meteor.com/prepare-meteor-3.0) - Meteor.js 3.0 will be fiber-free. This is the official guide to prepare your application to the Meteor.js 3.0 version. 

## Courses

- [YouTube](https://www.youtube.com/@MeteorVideos) - Learn by YouTube videos.
- [EventedMind](https://learn-meteor.netlify.app/) - It's old but goes into detail regarding how Meteor.js internals.

## Services

- [Galaxy](https://galaxy.meteor.com/) - All the required services for most Meteor.js applications.
- [Monti APM](https://montiapm.com/) - APM service for your Meteor.js application. The free package will help you a lot.

## Companies

- [Any Run](https://any.run/) - Interactive malware analyzer.
- [Apify](https://apify.com/) - The platform where developers build, deploy, and monitor web scraping and browser automation tools is using Meteor.js at their application https://console.apify.com/.
- [Awell Health](https://www.awellhealth.com/) - Automate routine clinical tasks. 
- [Azumuta](https://www.azumuta.com/) - Most complete software tool that eliminates the use of paperwork in your factory. Their application at https://app.azumuta.com/login is written with Meteor.js.
- [Bike Soup](https://www.bikesoup.com/) - The cycle marketplace.
- [Biscoint](https://biscoint.io/) - Compare and find in realtime the best effective prices in Brazil's top Bitcoin exchanges. 
- [Candis](https://app.candis.io/) - Digitize your invoice management now.
- [Chatra](https://app.chatra.io/) - Live chat, chatbots, email & social messaging for business.
- [Cheat Code](https://cheatcode.co/login) - The application at https://cheatcode.co/login is written with Meteor.js.
- [Code Signal](https://codesignal.com/) - Seamless technical hiring, from screening to interview.
- [CSGO.NET](https://csgo.net/) - CSGO related website is written by Meteor.js.
- [Cuadds](https://www.cuadds.com/) - The productivity platform that lets you do things your way.
- [Edabit](https://edabit.com/) - A better way to learn programming. 
- [Favro](https://www.favro.com/) - Collaborative planning application at https://favro.com/l/login is written with Meteor.js.
- [Flow Hub](https://flowhub.com/) - Fast, reliable, and easy to use, Flowhub is the dispensary growth platform built for compliant, high-performing cannabis retailers.
- [Hubro](https://hubro.education/) - Online business simulations that allow participants to practice business skills through experiential learning.
- [Ledgy](https://ledgy.com/) - Ledgy is the equity management platform that takes your company further.
- [Literary Universe](https://www.literaryuniverse.com/)
- [Long Tail](https://longtailpro.com/) - Keyword research tool for long tail keywords at https://app.longtailpro.com/ is written with Meteor.js.
- [Maestro QA](https://www.maestroqa.com/) - Improves agent performance, measure BPOs, power Root-Cause Analysis.
- [md5hashing](https://md5hashing.net/) - The service provides tooling for hashing.
- [Mockup Jar](https://mockupsjar.com/) - Eacy to use mockup generator.
- [MongoBooster](https://www.mongobooster.com/) - The application is written with Meteor.js.
- [Qualia](https://www.qualia.com/) - Powering real estate's digital transformation.
- [Plutio](https://www.plutio.com/) - Toolkit to run your business application at https://app.plutio.com/ is written with Meteor.js. 
- [Rankuup](https://rankuup.com/)
- [Ritapos](https://ritapos.com) - Cloud based POS solution for cafes & restaurants. Their point-of-sale application at https://app.ritapos.com is written with Meteor.js.
- [Rocket Chat](https://www.rocket.chat/) - Largest open source communications community in the world is written with Meteor.js.
- [Roti.express](https://roti.express/) - Get instant feedbacks from your meetings, training sessions, workshops, conferences.
- [Seidat](https://www.seidat.com/) - Modern presentation platform for sales teams. Their application at https://app.seidat.com is written with Meteor.js.
- [Self Made](https://www.selfmade.co/) - Procuring high-quality creatives has never been more straightforward or accessible.
- [Sidebar](https://sidebar.io/) - Sidebar has been collecting the best design links of the day since October 2012. It's maintained by Sacha Greif and built with Vulcan Meteor. Sidebar's code is open-source and available on GitHub.
- [Signature](https://si.gnatu.re/) - Create your personalised HTML email signature.
- [Submit Hub](https://www.submithub.com/) - The most-transparent place to promote your music.
- [Swydo](https://www.swydo.com/) - Automated Reporting and Monitoring for Online Marketers application at https://app.swydo.com/ is written with Meteor.js.
- [Team Grid](https://web.teamgrid.app/) - Team management tool at https://web.teamgrid.app/ is written with Meteor.js.
- [Testrigor](https://testrigor.com) - Generative AI-based test automation tool.
- [The Forage](https://www.theforage.com/) - Explore careers and prepare for the job with hundreds of free job simulations designed by the world's top employers.
- [Visibook](https://visibook.com/) - The easiest way to schedule customers and send appointment reminders.
- [xcusy](https://www.xcusy.com/) - Free and Anonymous Alternative to Chatroulette.
- [Wekan](https://wekan.github.io/) - Open-Source Kanban.
- [Zip Board](https://zipboard.co/) - Proofing tool for faster approval and production application at https://app.zipboard.co is written with Meteor.js.

## Open Source Apps
- [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) - Realtime chat application.
- [Wekan](https://github.com/wekan/wekan) - Open source Trello-like kanban.
- [Nosqlclient](https://github.com/nosqlclient/nosqlclient) - MongoDB management tool.
- [radgrad2](https://github.com/radgrad/radgrad2) - Education management system.
- [coauthor](https://github.com/edemaine/coauthor) - Coauthor supercollaboration/discussion forum.

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->
- Jan Dvořák [GitHub](https://github.com/sponsors/storytellercz), [X/Twitter](https://twitter.com/storytellercz), [Meteor Forums](https://forums.meteor.com/u/storyteller)
- Jan Küster [GitHub](https://github.com/sponsors/jankapunkt), [X/Twitter](https://twitter.com/Kuester_Jan), [Meteor Forums](https://forums.meteor.com/u/jkuester)
- Zodern [GitHub](https://github.com/zodern), [Meteor Forums](https://forums.meteor.com/u/zodern/)
- Alim Gafar [X/Twitter](https://twitter.com/alimgafar), [Meteor Forums](https://forums.meteor.com/u/alimgafar)
- Radosław Miernik [GitHub](https://github.com/radekmie), [Meteor Forums](https://forums.meteor.com/u/radekmie)
- Dr. Dimitru [GitHub](https://github.com/dr-dimitru), [Meteor Forums](https://forums.meteor.com/u/dr.dimitru)
- Frederico Maia [GitHub](https://github.com/fredmaiaarantes), [X/Twitter](https://twitter.com/fredmaiaarantes), [Meteor Forums](https://forums.meteor.com/u/fredmaiaarantes)
- Filipe Nevola [GitHub](https://github.com/filipenevola), [X/Twitter](https://twitter.com/FilipeNevola), [Meteor Forums](https://forums.meteor.com/u/filipenevola)
- Gabriel Grubba [GitHub](https://github.com/Grubba27), [X/Twitter](https://twitter.com/gab_grubba),[Meteor Forums](https://forums.meteor.com/u/grubba/summary)

Who else should we be following!?

## Other

- [Awesome Node.js security](https://github.com/lirantal/awesome-nodejs-security)
- [🍃 A curated list of awesome MongoDB resources, libraries, tools and applications](https://github.com/ramnes/awesome-mongodb)

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/Meteor-Community-Packages/awesome-meteor/graphs/contributors)!
