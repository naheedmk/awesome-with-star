# Information comes from [Urigo/awesome-meteor](https://github.com/Urigo/awesome-meteor)
# Awesome Meteor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Meteor Packages, libraries and software.

The official Meteor resources page can be found [here](https://www.meteor.com/tools/resources)

- [Awesome Meteor](#awesome-meteor)
    - [Getting Started](#getting-started)
    - [Collections](#collections)
    - [Forms and Templates](#forms-and-templates)
    - [Users and Authentication](#users-and-authentication)
    - [REST](#rest)
    - [Files](#files)
    - [Routers](#routers)
    - [Debugging Tools](#debugging-tools)
    - [Editor Plugins](#editor-plugins)
    - [Search, sort and paginate](#search-sort-paginate)
    - [Mobile](#mobile)
    - [Offline](#offline)
    - [Testing](#testing)
    - [SEO](#seo)
    - [Data Visualization](#data-visualization)
    - [Analytics](#analytics)
    - [Cron Jobs](#cron-jobs)
    - [Payments](#payments)
    - [Deployment](#deployment)
    - [Front End Frameworks](#front-end-frameworks)
    - [Alternative Databases](#alternative-databases)
    - [Package managers](#package-managers)
    - [Internationalization](#internationalization)
    - [Scaffolding](#scaffolding)
    - [Tooling](#tooling)
- [Boilerplate](#boilerplate)
- [Resources](#resources)
    - [Books](#books)
    - [Courses](#courses)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
    - [Job Boards](#job-boards)
- [Contributing](#contributing)

- - -


## Getting Started

*Where to start*

* [Official Meteor tutorial](https://www.meteor.com/try)
* [Discover Meteor Book](https://www.discovermeteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Why Meteor](https://wiki.dandascalescu.com/essays/why_meteor) to begin with, and [Meteor vs. the MEAN stack](https://wiki.dandascalescu.com/essays/meteor_js_vs_the_mean_stack)

## Collections

*Helpers and expensions for collections*

* [node-simple-schema](https://github.com/aldeed/node-simple-schema/) - A JavaScript schema validation package that supports direct validation of MongoDB update modifier objects :star:318
* [aldeed:collection2](https://github.com/aldeed/meteor-collection2/) - Automatic validation of insert and update operations on the client and server.
* [dburles:collection-helpers](https://github.com/dburles/meteor-collection-helpers/) – Transform your collections with helpers that you define.
* [matb33:collection-hooks](https://github.com/matb33/meteor-collection-hooks/) - Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne.
* [reywood:publish-composite](https://github.com/englue/meteor-publish-composite) - publish a set of related documents from various collections using a reactive join :star:522
* [jagi:astronomy](https://github.com/jagi/meteor-astronomy/) - The Model layer for Meteor

## REST

*REST support for Meteor*

* [simple:rest](https://github.com/stubailo/meteor-rest) - automatically make your Meteor app accessible over HTTP and DDP alike. :star:345
* [nimble:restivus](https://github.com/kahmali/meteor-restivus) - Make REST endpoints for your Meteor app with incredible ease. :star:530

## Forms and Templates

*Helpers for templates*

* [aldeed:autoform](https://github.com/aldeed/meteor-autoform) - UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation. :star:1451
* [aldeed:template-extension](https://github.com/aldeed/meteor-template-extension) - A Meteor package: Replace already defined templates, inherit helpers and events from other templates. :star:219
* [kadira:blaze-layout](https://github.com/kadirahq/blaze-layout) - Layout Manager for Blaze (works well with Meteor FlowRouter)
* [dispatch:scrollview](https://github.com/DispatchMe/meteor-scrollview) - A high performance infinite scrollview for meteor :star:25
* [themeteorites:blaze-magic-events](https://github.com/themeteorites/blaze-magic-events) - A new way of binding event handlers to html elements for Meteor's Blaze :star:26
* [manuel:viewmodel](https://github.com/ManuelDeLeon/viewmodel) - MVVM for Meteor :star:205
* [webix:webix](https://github.com/dandv/meteor-webix) - Meteor.js - Webix UI integration :star:340
* [uniforms](https://github.com/vazco/uniforms) - Bunch of React components and helpers to easily generate and validate forms. [Seamlessly integrate with `aldeed:simple-schema` and `simpl-schema`](https://github.com/vazco/uniforms/blob/master/INTRODUCTION.md#quick-start). :star:483

## Users and Authentication

*Tools for handling users and authentication*

* [accounts-base](https://guide.meteor.com/accounts.html) - Meteor's user account system.
* [alanning:roles](https://github.com/alanning/meteor-roles) - Roles support for the built-in accounts packages. :star:872

## Deployment

*Tools for deploying and maintaining Meteor apps*

* [When a Meteor finally hits production](https://medium.com/@davidyahalomi/when-a-meteor-finally-hits-production-6c37b81f795b) - Blog post about deploying Meteor apps
* [BulletProof Meteor](https://bulletproofmeteor.com/)
* [meteorhacks:kadira](https://github.com/meteorhacks/kadira) - Performance Monitoring for Meteor. :star:201
* [meteor-up](https://github.com/arunoda/meteor-up) – Meteor Deployments.
* [davidyaha:collection2-migrations](https://github.com/davidyaha/meteor-collection2-migrations) - Auto DB migrations with collection2 and simple schema on Meteor :star:37
* [percolate:migrations](https://github.com/percolatestudio/meteor-migrations) - Simple migration system for Meteor :star:222
* [meteorhacks:fast-render](https://github.com/kadirahq/fast-render) - Render you app even before the DDP connection is live :star:582
* [meteorhacks:cluster](https://github.com/meteorhacks/cluster) - Clustering solution for Meteor with load balancing and service discovery :star:646
* [yogiben:admin](https://github.com/yogiben/meteor-admin) - A complete admin dashboard solution :star:844
* [demeteorizer](https://github.com/onmodulus/demeteorizer) - Converts a Meteor app into a "standard" Node.js application :star:738
* [Amazon auto scaling and Meteor](https://allandequeirozblog.wordpress.com/2015/09/27/amazon-auto-scaling-and-meteor/) - An detailed description of how to build an infrastructure that auto scale and auto update without human interaction.
* [houston:admin](https://github.com/gterrono/houston) - A zero-config, Django Admin-like admin for Meteor :star:827
* [pm2-meteor](https://github.com/andruschka/pm2-meteor) - Simplest way to deploy, scale and run Meteor Apps with PM2. :star:142

## Routers

*Routers for Blaze*

* [iron:router](https://github.com/iron-meteor/iron-router) - A client and server side router designed specifically for Meteor. :star:2054
* [kadira:flow-router](https://github.com/kadirahq/flow-router) - Client Side Router for Meteor. :star:1104
* [meteorhacks:picker](https://github.com/meteorhacks/picker) - Server Side Router for Meteor. :star:165

## Offline

*Tools for Meteor offline support*

* [ground:db](https://github.com/GroundMeteor/db) - GroundDB is a thin layer providing Meteor offline database and methods. :star:558

## Testing

*Testing tools*

* [Meteor Testing Manual](http://www.meteortesting.com/)
* [Velocity](http://velocity.meteor.com/) - A reactive test-runner for Meteor.
* [mike:mocha](https://github.com/mad-eye/meteor-mocha-web/) – Run mocha tests within the Meteor framework.
* [xolvio:chimp](https://github.com/xolvio/chimp) - Testing so easy, a primate could do it! Supports mocha, Cucumber, jasmine, and chai. :star:741
* [velocity:html-reporter](https://github.com/meteor-velocity/html-reporter) - HTML reporter for Meteor velocity testing framework. :star:24
* [Gagarin](https://github.com/anticoders/gagarin) - Another testing framework for your meteor apps.  :star:156

## Files

*Handling files in Meteor*

* [Meteor-CollectionFS](https://github.com/CollectionFS/Meteor-CollectionFS) - Meteor webbased filesystem handling up and downloads. :star:1088
* [ostrio:files](https://github.com/VeliovGroup/Meteor-Files) - Upload files via DDP, HTTP and WebRTC/DC. To Meteor server FS, AWS, GridFS, DropBox or Google Drive. Fast, secure and robust. :star:804
* [netanelgilad:excel](https://github.com/netanelgilad/meteor-excel) - Parsing and generating excel files (xlsx, xls). :star:52

## Search, sort and paginate

*Search, sort and paginate related tools*

* [tmeasday:publish-counts](https://github.com/percolatestudio/publish-counts) - Publish the count of a cursor, in real time. :star:195
* [percolate:find-from-publication](https://github.com/versolearning/find-from-publication) - Enable finding all documents that have been published by a given publication. :star:35
* [meteorhacks:search-source](https://github.com/meteorhacks/search-source) - Reactive Data Source for Search :star:153
* [matteodem:easy-search](https://github.com/matteodem/meteor-easy-search) - Easy-to-use search with Blaze Components (+ Elastic Search Support)
* [alethes:pages](https://github.com/alethes/meteor-pages) - Out of the box Meteor pagination :star:410
* [Discover Meteor Blog about pagination](https://www.discovermeteor.com/blog/pagination-problems-meteor/)

## Mobile

*Mobile Development*

* [meteoric:ionic](https://github.com/meteoric/meteor-ionic) - Ionic components for Meteor. :star:1579
* [driftyco:ionic](https://github.com/driftyco/ionic) - Official Ionic support for Meteor. :star:34131
* [raix:push](https://github.com/raix/push) - Push notifications for cordova (ios, android) browser (Chrome, Safari, Firefox). :star:491
* [martijnwalraven:meteor-ios](https://github.com/martijnwalraven/meteor-ios) - Integrates native iOS apps with the Meteor platform through DDP. :star:757
* [delight-im/Android-DDP](https://github.com/delight-im/Android-DDP) - DDP for clients on Android. :star:264
* [okland:accounts-phone](https://github.com/okland/accounts-phone) - A login service based on mobile phone number for Meteor. :star:110
* [okland:camera-ui](https://github.com/okland/camera-ui) - Meteor package for taking photos with user interface, one function call on desktop and mobile. Allows to choose between camera to photoLibrary on mobile. :star:29
* [percolatestudio/cordova-plugin-safe-reload](https://github.com/percolatestudio/cordova-plugin-safe-reload) - Cordova plugin to watch and recover after a broken Meteor Hot Code Push. :star:14

## Data Visualization

*Data Visualization in Meteor: charts, maps, tables, etc.*

* [AnyChart-Meteor](https://github.com/AnyChart/AnyChart-Meteor) - This package provides a simple way to use AnyChart JavaScript charting component in Meteor. :star:15
* [aldeed:tabular](https://github.com/aldeed/meteor-tabular) - Reactive datatables for large or small datasets. :star:353

## Analytics

*Analytics*

* [okgrow:analytics](https://github.com/okgrow/analytics/) - Google Analytics, Mixpanel, KISSmetrics (and more) integration for meteor.

## Cron Jobs

*Cron Jobs in Meteor*

* [percolate:synced-cron](https://github.com/percolatestudio/meteor-synced-cron) - Cron system for Meteor. It supports syncronizing jobs between multiple processes. :star:471
* [vsivsi:job-collection](https://github.com/vsivsi/meteor-job-collection/) - A persistent and reactive job queue for Meteor, supporting distributed workers that can run anywhere.

## Debugging Tools

*Debugging Tools*

* [msavin:mongol](https://github.com/msavin/Mongol/) - Visual Editing Tool for Meteor for MongoDB Collections. :star:825
* [msavin:jetsetter](https://github.com/msavin/JetSetter) - Visual Get/Set Tool for Meteor Session Variables. :star:188
* [meteorhacks:kadira-debug](https://github.com/kadirahq/meteor-debug) - Full Stack Debugging Solution for Meteor. :star:157
* [babrahams:constellation](https://github.com/JackAdams/constellation-distro/) - An extensible dev console for Meteor.
* [Meteor DDP Monitor](https://github.com/thebakeryio/meteor-ddp-monitor) - Chrome Dev tools extension for monitoring Meteor DDP traffic :star:241
* [Dr. Mongo](http://www.drmongo.com/) - Open-source MongoDB admin app built on MeteorJs.

## Package Managers

*Using package managers in Meteor*

* [meteorhacks:npm](https://github.com/meteorhacks/npm/) - Use Npm Modules with Your Meteor App.
* [cosmos:browserify](https://github.com/elidoran/cosmos-browserify) - Browserify npm modules for client side in Meteor packages. :star:79

## Scaffolding

*Scaffolding*

* [Meteor Kitchen](http://www.meteorkitchen.com/) - Code generator for Meteor
* [iron-cli](https://github.com/iron-meteor/iron-cli) - A scaffolding command line tool for Meteor applications  :star:656
* [Differential - meteor-boilerplate](https://github.com/Differential/meteor-boilerplate) :star:919
* [meteoris2](https://github.com/radiegtya/meteoris2) :star:258
* [Base](https://github.com/themeteorchef/base) :star:671

## Tooling

* [ESLint-plugin-Meteor](https://github.com/dferber90/eslint-plugin-meteor/) - ESLint plugin for Meteor

## Boilerplate

* [matteodem - meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) :star:862
* [React with Webpack + Meteor as a backend](http://julian.io/react-with-webpack-meteor-as-a-backend/)

## Open source apps
* [VulcanJS](https://github.com/VulcanJS/Vulcan) - A toolkit to quickly build apps with React, GraphQL & Meteor :star:6764
* [Microscope](https://github.com/DiscoverMeteor/Microscope) - The Discover Meteor book's example app :star:925
* [Wekan](https://github.com/wekan/wekan) - Open source Trello-like kanban :star:12751
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - Open source Commerce platform developed with Meteor :star:7096
* [Crowducate Platform](https://github.com/Crowducate/crowducate-platform) - Open source education platform Powered by meteor :star:189
* [Orion CMS](http://orionjs.org/)

## Front End Frameworks

*Alternative Front End Frameworks to Blaze*

* [Blaze](http://blazejs.org/guide/introduction.html)
* [React](http://react-in-meteor.readthedocs.org/en/latest/) - Working with React and Meteor
* [Angular](https://github.com/Urigo/angular-meteor) - Working with Angular and Meteor :star:2313
* [Angular 2](https://github.com/Urigo/angular2-meteor) - Working with Angular 2 and Meteor :star:323
* [Famo.us](https://github.com/gadicc/meteor-famous-views/) - Famo.us and Meteor
* [Vue](https://github.com/Akryum/meteor-vue-component) - Working with Vue and Meteor (plus single-file components & apollo support)

* [frozeman:build-client](https://github.com/frozeman/meteor-build-client) - A tool to bundle the client part of a Meteor app. :star:243
* [Asteroid](https://github.com/mondora/asteroid) - An alternative client for a Meteor backend :star:715
* [ddp.js](https://github.com/mondora/ddp.js) - Isomorphic JavaScript DDP client :star:188

## Alternative Databases

**Alternative Databases for MongoDB

* [meteor-pg](https://github.com/Richie765/meteor-pg) - New and improved PostgreSQL support for Meteor :star:21
* [numtel:pg](https://github.com/numtel/meteor-pg) - Reactive PostgreSQL for Meteor :star:304
* [numtel:mysql](https://github.com/numtel/meteor-mysql) - Reactive MySQL for Meteor :star:347
* [simple:rethink](https://github.com/Slava/meteor-rethinkdb) - RethinkDB integration for Meteor :star:313

# Resources

Where to discover new Meteor things.

## Books

* [Meteor Explained](https://gumroad.com/l/meteor-explained)
* [Meteor Tips](http://meteortips.com/)
* [Meteor Cookbook](https://github.com/awatson1978/meteor-cookbook) :star:1674

## Courses

* [EventedMind](https://www.eventedmind.com/)
* [Udemy — Meteor: Build a real-time web app using only JavaScript](https://www.udemy.com/meteor-course/)
* [Udemy - A Beginner's Guide to the Meteor JavaScript Framework](https://www.udemy.com/meteorjs/)
* [tuts+ - Single Page Web Apps with Meteor](http://code.tutsplus.com/courses/single-page-web-apps-with-meteor)
* [DevFreeCasts.org](http://devfreecasts.org/meteor/)
* [MeteorTuts](http://meteortuts.com/)

## Tutorials

* [Building a CMS-powered blog in Meteor](https://buttercms.com/blog/meteor-cms-blog-tutorial)
* [scotch.io - Building a Slack Clone in Meteor](https://scotch.io/tutorials/building-a-slack-clone-in-meteor-js-getting-started)
* [Rocket-Chat Slack Clone](https://rocket.chat/)
* [Meteor Learning](https://github.com/ericdouglas/Meteor-Learning) - List of resources to learn :star:1624
* [Learning Resources for Meteor](https://www.yauh.de/best-learning-resources-for-meteorjs/)
* [Phusion Passenger: Meteor tutorial](https://github.com/phusion/passenger/wiki/Phusion-Passenger:-Meteor-tutorial)

## Blogs

* [Official Meteor blog](http://blog.meteor.com)
* [Meteor Hacks Blog](https://meteorhacks.com/)
* [Meteor Create](http://meteorcreate.com/) - Discover the Best Meteor Tutorials
* [The Meteor podcast](http://podcast.crater.io)
* [Meteor club podcast](https://podcast.meteorjs.club/)
* [Blog about Optimistic UIs With Meteor Latency Compensation](http://info.meteor.com/blog/optimistic-ui-with-meteor-latency-compensation)

## Websites

* [Official website](https://www.meteor.com/)
* [Official Documentation](http://docs.meteor.com/)
* [Official Guide](http://guide.meteor.com/) 
* [Atmosphere](https://atmospherejs.com/) - The catalog of Meteor packages, resources and tools.
* [BulletProof Meteor](https://bulletproofmeteor.com/) - Online course for Meteor performance in production, by Arunoda Susiripala
* [Meteorpedia](http://www.meteorpedia.com) ([infrequently](http://www.meteorpedia.com/special/RecentChanges/) updated)
* [DiscoverMeteor Encyclopedia](https://www.discovermeteor.com/encyclopedia)
* [Roadmap](https://trello.com/b/hjBDflxp/meteor-roadmap)
* [Meetups](http://meteor.meetup.com/)
* [Reddit](https://www.reddit.com/r/meteor)
* [YouTube](https://www.youtube.com/channel/UC3fBiJrFFMhKlsWM46AsAYw) videos from meetups around the world
* [Unofficial Meteor FAQ](https://github.com/oortcloud/unofficial-meteor-faq) :star:1004
* [The Meteor Chef](https://themeteorchef.com) 

### Q&A

* [Stack Overflow](http://stackoverflow.com/questions/tagged/meteor?sort=newest&pagesize=15)
* [Meteor forums](https://forums.meteor.com/)
* [Gitter IM channel](https://gitter.im/meteor/meteor)
* [The Meteor Chef Slack channel](https://themeteorchef.slack.com)
* IRC - #meteor on freenode


## Weekly

* [Meteor-Blog](http://info.meteor.com/blog)
* [Meteor Weekly](https://goodbits.io)
* [Crater.io](https://crater.io/)
* [This Week In Meteor](https://goodbits.io)

## Twitter

* [Official Meteor](https://twitter.com/meteorjs)

## Job Boards

* [We Work Meteor](https://www.weworkmeteor.com/)

# [Contributing](https://github.com/urigo/awesome-meteor/blob/master/CONTRIBUTING.md)

Your contributions are always welcome!

Thank you @gillesfabio for creating this repo!

