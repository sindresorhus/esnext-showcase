## ES.next showcase

<img src="http://i.imgur.com/yy1sACZ.png" width="120" align="right">

> Showcasing real-world usage of [ECMAScript 6 features](http://wiki.ecmascript.org/doku.php?id=harmony:specification_drafts) in today's libraries/frameworks/projects/etc


These projects make use of ES6 features. Dig into their source, learn, and [try out ES6](http://benvie.github.io/continuum/) yourself!

There's already a lot of [tooling](https://github.com/addyosmani/es6-tools) that lets you develop with ES6 *today*.

-

### [AngularJS 2.0](http://blog.angularjs.org/2014/03/angular-20.html)

> All code in AngularJS 2 is already being written in ES6

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]


### [ember.js](https://github.com/emberjs/ember.js/tree/master/packages)

> We'll make modules a first-class citizen, and soon every developer who starts using Ember will also be using ES6 modules.

- Features: [Modules][], [Promises][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [tpyo](https://github.com/mathiasbynens/tpyo)

> Enables support for typos in JavaScript property names. Powered by ES6 proxies + Levenshtein string distance.

- Features: [Proxy][]


### [negative-array](https://github.com/sindresorhus/negative-array)

> Negative array index support `array[-1]` using ES6 Proxy

- Features: [Proxy][]


### [stevia](https://github.com/traviskaufman/stevia)

> Natural sweetening for JavaScript objects using ES6 Proxy

- Features: [Proxy][]


### [Backbone TodoMVC + ECMAScript 6](https://github.com/addyosmani/traceur-todomvc/)

> Backbone TodoMVC rewritten using ES6

- Features: [Modules][], [Block Scoped Bindings][block-scoped-bindings], [Classes][], Spread operator, [Arrow functions][], Default parameters
- Transpiler: [Traceur][traceur]


### [Ember Extension](https://github.com/tildeio/ember-extension)

> Adds an Ember tab to chrome dev tools that allows you to inspect Ember objects in your application.

- Features: [Modules][], [Promises][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [hyperagent.js](https://github.com/weluse/hyperagent)

> A HAL client for JavaScript

- Features: [Modules][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [rsvp.js](https://github.com/tildeio/rsvp.js)

> A lightweight library that provides tools for organizing asynchronous code

- Features: [Modules][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [router.js](https://github.com/tildeio/router.js)

> A lightweight JavaScript library that builds on route-recognizer to provide an API for handling routes

- Features: [Modules][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [json-normalizer](https://github.com/tildeio/json-normalizer)

> A small, lightweight library for normalizing JSON properties and values

- Features: [Modules][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]


### [htmlbars](https://github.com/tildeio/htmlbars)

> A variant of Handlebars that emits DOM and allows you to write helpers that manipulate live DOM nodes

- Features: [Modules][]
- Transpiler: [ES6 Module Transpiler][es6-module-transpiler]

### [defs.js][]

> Static scope analysis and transpilation of ES6 block scoped const and let variables to ES3 vars

- Features: [Block Scoped Bindings (const, let)][block-scoped-bindings]
- Transpiler: [defs.js][]

###[Templating](https://github.com/angular/templating)

> The templating engine for Angular 2.0.

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[di](https://github.com/angular/di.js)

> Dependency Injection Framework for the future generations...

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[ngHttp](https://github.com/angular/ngHttp)

> Data Persistence

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[Watchtower](https://github.com/angular/watchtower.js)

> Super-fast change detection

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[Expressionist](https://github.com/angular/expressionist.js)

> Expression parser

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[Diary](https://github.com/angular/diary.js)

> Flexible logging and profiling library for JavaScript

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

###[Deferred](https://github.com/angular/deferred)

> This project makes available an ES6 Deferred implementation, using ES6 Promises

- Features: [Modules][], [Classes][], [Arrow functions][], [Promises][]
- Transpiler: [Traceur][traceur]

### [varify](https://github.com/thlorenz/varify)

> browserify transform that converts all const assignments to var assignments.

- Features: [const](http://wiki.ecmascript.org/doku.php?id=harmony:const) immutability support only, **no block scope**
- Transpiler: [varify](https://github.com/thlorenz/varify)


### [catiline](https://github.com/calvinmetcalf/catiline)

> Small library for using workers in the browser.

- Features: [Block Scoped Bindings (const, let)][block-scoped-bindings]
- Transpiler: [defs.js][]


### [DOMtastic](https://github.com/webpro/DOMtastic)

> Small & fast DOM and event library for modern browsers.

- Features: [Modules][], [Arrow functions][], [Spread][], [Default Parameter Values][default-parameter-values]
- Transpiler: [Traceur][traceur]


### [Koa](https://github.com/koajs/koa)

> Expressive middleware for node.js using generators to make web applications and APIs more enjoyable to write.

- Features: [Generators][]


### [Co](https://github.com/visionmedia/co)

> Generator based flow-control goodness using thunks or promises, letting you write non-blocking code in a nice-ish way.

- Features: [Generators][]


### [Shen](https://github.com/cultofmetatron/Shen)

> Higher order flow control functions for creating generators.

- Features: [Generators][]


### [task.js](https://github.com/mozilla/task.js)

> Beautiful concurrency for JavaScript.

- Features: [Generators][]


## Features

- [Modules][]
- [Block Scoped Bindings][block-scoped-bindings]
- [Proxy][]
- [Generators][]
- [Classes][]
- [Arrow functions][]
- [Spread][]
- [Default Parameter Values][default-parameter-values]
- [Promises][]


## Transpilers

- [Traceur][]
- [ES6 Module Transpiler][es6-module-transpiler]
- [defs.js][]
- [Regenerator — Facebook’s ES6 generator transpiler](http://facebook.github.io/regenerator/)
- [illusionist][]


## Reading material

- [ECMAScript 6 specification](http://wiki.ecmascript.org/doku.php?id=harmony:specification_drafts)
- [ECMAScript 6 compatibility table](http://kangax.github.io/es5-compat-table/es6/)
- [A Few New Things Coming To JavaScript](http://addyosmani.com/blog/a-few-new-things-coming-to-javascript/)
- [Author In ES6, Transpile To ES5 As A Build-step: A Workflow For Grunt](http://addyosmani.com/blog/author-in-es6-transpile-to-es5-as-a-build-step-a-workflow-for-grunt/)
- [ES3 \<3 block scoped const and let => defs.js](http://blog.lassus.se/2013/05/defsjs.html)
- [An aggregation of tooling for ES6](https://github.com/addyosmani/es6-tools)
- [Overview of ECMAScript 6 features](https://github.com/lukehoban/es6features)


[modules]: http://wiki.ecmascript.org/doku.php?id=harmony:modules
[block-scoped-bindings]: http://wiki.ecmascript.org/doku.php?id=harmony:block_scoped_bindings
[proxy]: http://soft.vub.ac.be/~tvcutsem/proxies/
[generators]: http://wiki.ecmascript.org/doku.php?id=harmony:Generators
[classes]: http://wiki.ecmascript.org/doku.php?id=strawman:maximally_minimal_classes
[arrow functions]: http://wiki.ecmascript.org/doku.php?id=harmony:arrow_function_syntax
[spread]: http://wiki.ecmascript.org/doku.php?id=harmony:spread
[default-parameter-values]: http://wiki.ecmascript.org/doku.php?id=harmony:parameter_default_values
[promises]: http://wiki.ecmascript.org/doku.php?id=strawman:promises

[traceur]: https://github.com/google/traceur-compiler
[es6-module-transpiler]: https://github.com/square/es6-module-transpiler
[defs.js]: https://github.com/olov/defs
[illusionist]: https://github.com/mirego/illusionist


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work. This work is published from: Norway.
