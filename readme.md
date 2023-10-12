<!--lint disable awesome-git-repo-age-->
<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Meteor.js [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/Meteor-Community-Packages/awesome-meteor/actions/workflows/lint.yaml/badge.svg)](https://github.com/Meteor-Community-Packages/awesome-meteor/actions/workflows/lint.yaml)

<!-- subtitle -->

Awesome packages, articles, tips and people all around Meteor.js

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/Meteor-Community-Packages/awesome-meteor/blob/main/awesome-meteor.jpg" width="200" alt="Awesome Meteor.js"/>
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
- [Follow](#follow)

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

- Collections
  - [aldeed:collection2](https://github.com/Meteor-Community-Packages/meteor-collection2) - Attach a schema to a Mongo.Collection. Automatically validates against that schema when inserting and updating from client or server code.
  - [aldeed:schema-deny](https://github.com/longshotlabs/meteor-schema-deny) - Allows you to deny inserting or updating certain properties in your database by setting options in your schema.
  - [aldeed:schema-index](https://github.com/longshotlabs/meteor-schema-index) - Control some MongoDB indexing from your SimpleSchema.
  - [matb33:collection-hooks](https://github.com/Meteor-Community-Packages/meteor-collection-hooks) - Extends Mongo.Collection with before/after hooks for insert, update, remove, find, and findOne.
  - [meteor-publish-composite](https://github.com/Meteor-Community-Packages/meteor-publish-composite) - Provides a flexible way to publish a set of related documents from various collections using a reactive join. This makes it easy to publish a whole tree of documents at once. The published collections are reactive.
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

- File Management
  - [meteor-files](https://github.com/veliovgroup/Meteor-Files) - Simple files management.
  - [mikkelking:slingshot](https://github.com/Back2bikes/meteor-slingshot) - Upload files directly to AWS S3, Google Cloud Storage and others in Meteor.js.

- Internationalization
  - [universe:i18n](https://github.com/vazco/meteor-universe-i18n) - Internationalization package.
  - [Meteor-Internationalization](https://github.com/veliovgroup/Meteor-Internationalization) - Super-Lightweight and fast i18n isomorphic driver for Meteor.js with support of placeholders.

- Logging
  - [ostrio:logger](https://packosphere.com/ostrio/logger) - Logger driver with different adapters.

- Performance Monitoring
  - [montiapm:agent](https://github.com/monti-apm/monti-apm-agent) - Monitor your application in production to improve performance and fix errors.
  - [meteorhacks:zones](https://github.com/meteorhacks/zones) - Improves error tracking. It can be used to capture stack traces over the async execution path.
  - [kschingiz:meteor-elastic-apm](https://github.com/kschingiz/meteor-elastic-apm) - Performance monitoring for Meteor.js applications based on Elastic APM.

- Routers
  - [ostrio:flow-router-extra](https://github.com/veliovgroup/flow-router) - Routing for client-side apps and compatible with React, Vue, Svelte, and Blaze.

- Cron Jobs
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

## Guides

- [Official Meteor Guide](https://guide.meteor.com)

## Courses
- [YouTube](https://www.youtube.com/@MeteorVideos) - Learn by YouTube videos.
- [EventedMind](https://learn-meteor.netlify.app/) - It's old but goes into detail regarding how Meteor.js internals.

## Services

- [Galaxy](https://galaxy.meteor.com/) - All the required services for most Meteor.js applications.
- [Monti APM](https://montiapm.com/) - APM service for your Meteor.js application. The free package will help you a lot.

## Companies
- [Any Run](https://any.run/)
- [Azumuta](https://www.azumuta.com/)
- [Code Signal](https://codesignal.com/)
- [Favro](https://www.favro.com/)
- [Flow Hub](https://flowhub.com/)
- [Hubro](https://hubro.education/)
- [Ledgy](https://ledgy.com/)
- [Literary Universe](https://www.literaryuniverse.com/)
- [Maestro QA](https://www.maestroqa.com/)
- [Qualia](https://www.qualia.com/)
- [Rocket Chat](https://www.rocket.chat/)
- [Roti.express](https://roti.express/)
- [Self Made](https://www.selfmade.co/)
- [The Forage](https://www.theforage.com/)
- [Wekan](https://wekan.github.io/)

<!-- END CONTENT -->

## Follow

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->
- Jan Dvořák [GitHub](https://github.com/sponsors/storytellercz), [Twitter](https://twitter.com/storytellercz), [Meteor Forums](https://forums.meteor.com/u/storyteller)
- Jan Küster [GitHub](https://github.com/sponsors/jankapunkt), [Twitter](https://twitter.com/Kuester_Jan), [Meteor Forums](https://forums.meteor.com/u/jkuester)
- Zodern [GitHub](https://github.com/zodern), [Meteor Forums](https://forums.meteor.com/u/zodern/)
- Alim Gafar [Twitter](https://twitter.com/alimgafar), [Meteor Forums](https://forums.meteor.com/u/alimgafar)
- Radosław Miernik [GitHub](https://github.com/radekmie), [Meteor Forums](https://forums.meteor.com/u/radekmie)
- Dr. Dimitru [GitHub](https://github.com/dr-dimitru), [Meteor Forums](https://forums.meteor.com/u/dr.dimitru)
- Frederico Maia [GitHub](https://github.com/fredmaiaarantes), [Twitter](https://twitter.com/fredmaiaarantes), [Meteor Forums](https://forums.meteor.com/u/fredmaiaarantes)
- Filipe Nevola [GitHub](https://github.com/filipenevola), [Twitter](https://twitter.com/FilipeNevola), [Meteor Forums](https://forums.meteor.com/u/filipenevola)
- Grubba [GitHub](https://github.com/Grubba27), [Twitter](https://twitter.com/gab_grubba),[Meteor Forums](https://forums.meteor.com/u/grubba/summary)

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/Meteor-Community-Packages/awesome-meteor/graphs/contributors)!
