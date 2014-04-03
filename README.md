![Workflow Guide Logo](logo-wg.jpg "Workflow Guide")

> This is a work in progress and I will likely add (or replace) more functionality in the future.


## Introduction

Hello there! I'm Vitor Britto, a Full Stack Web Developer extremely passionate about my work. I discovered the world of code almost two decades ago and kept the same passion from the first day of this discovery. I have worked full time as a freelancer for nearly 4 years developing projects for the web, and I direct part of my time to researchs, collaborative projects, development of personal projects and writing some articles for my blog.

But enough about me! I would like to present this project and why it was created.

**First reason:**

Apply rules and be based on a principle and methodology of process which could maintain the structure of my standards.

**Second reason:**

Not only have a code style guide, but relevant informations about my Workflow. Thus I always keep the same logic process and can initiate the development of my projects without any questions when making a scaffolding, building process, automation rotines, unit testing and others tasks.

**This guide consist with three parts:** :ghost:

1. My workflow context with tools, approaches and methods that I use.
2. My own code conventions. Which is inspired by what is popular within the community, and flavored with some personal opinions.
3. Major dependencies that I use on Grunt, Gulp, Bower, Karma and Node/CLI.

## Table of Contents

- [Workflow](#workflow)
- [Guides](#guides)
- [Dependencies](#dependencies)
- [References](#references)


## Workflow

This is a simple table with tools, aproaches and methods that I use.

| Setup       | Develop        | Build                | Automation | Managers   | Deploy     | Database |
|-------------|----------------|----------------------|------------|------------|------------|----------|
| Scaffolding | Sass / Stylus  | Linting              | Grunt      | NPM        | Rsync      | MySQL    |
| Libraries   | Haml / Jade    | Unit Test            | Gulp       | Bower      | Git        | MongoDB  |
| Templates   | Browser-Sync   | Compilation          | Just       | Component  | FTP        | Redis    |
| Frameworks  |                | Minify and Concat    | Guard      | Bundler    | Capistrano |          |
|             |                | Deployment           | Makefile   |            |            |          |
|             |                | Optimize Performance | Rakefile   |            |            |          |
|             |                | Deployment           |            |            |            |          |

**[⬆ back to top](#table-of-contents)**

### Scaffolding and Build

- [Skeleton](http://skeleton.vitorbritto.com.br/)
- [Boilerplates](https://github.com/vitorbritto/boilerplates)
- [Managers](http://managers.vitorbritto.com.br/)
- [Just](http://vitorbritto.github.io/just/)
- [Gone](https://github.com/vitorbritto/gone)

**[⬆ back to top](#table-of-contents)**

### Debug and Inspection

- [JSHint](https://github.com/vitorbritto/workflow-guide/blob/master/files/.jshintrc)
- [CSSLint](https://github.com/vitorbritto/workflow-guide/blob/master/files/.csslintrc)
- [DevTools](https://developers.google.com/chrome-developer-tools/)
- [JSPerf](http://jsperf.com/)
- [JSFiddle](http://jsfiddle.net/)
- [JSbin](http://jsbin.com/)

**[⬆ back to top](#table-of-contents)**

### Tests

- [Karma](http://karma-runner.github.io/)
- [Jasmine](https://github.com/pivotal/jasmine)
- [Mocha](https://github.com/visionmedia/mocha)
- [Chai](http://chaijs.com/)
- [DalekJS](http://dalekjs.com/)
- [Browser-sync](http://browsersync.io/)
- [PhantomJS](http://phantomjs.org/)

**[⬆ back to top](#table-of-contents)**


## Guides

- [HTML](guides/html.md)
- [CSS](guides/css.md)
- [JavaScript](guides/javascript.md)
- [NodeJS](guides/nodejs.md)
- [Ruby](guides/ruby.md)
- [Erlang](guides/erlang.md)
- [C/C++](guides/c.md)
- [Go](guides/go.md)
- [Git](guides/git.md)

**[⬆ back to top](#table-of-contents)**


## Dependencies

- [Grunt](https://gist.github.com/vitorbritto/6163803#file-grunt-md)
- [Gulp](https://gist.github.com/vitorbritto/6163803#file-gulp-md)
- [Bower](https://gist.github.com/vitorbritto/6163803#file-bower-md)
- [Karma](https://gist.github.com/vitorbritto/6163803#file-karma-md)
- [Node/CLI](https://gist.github.com/vitorbritto/6163803#file-cli-md)

**[⬆ back to top](#table-of-contents)**


## References

- [Annotated ECMAScript 5.1](http://es5.github.com/)
- [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
- [Douglas Crockford's Code Conventions for JavaScript](http://javascript.crockford.com/code.html)
- [Code Guide by @mdo](https://github.com/mdo/code-guide)
- [idiomatic CSS](https://github.com/necolas/idiomatic-css/)
- [idiomatic.js](https://github.com/rwldrn/idiomatic.js/)
- [jQuery JavaScript Style Guide](http://contribute.jquery.org/style-guide/js/)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
- [jQuery Core Style Guidelines](http://docs.jquery.com/JQuery_Core_Style_Guidelines)
- [Principles of Writing Consistent, Idiomatic JavaScript](https://github.com/rwldrn/idiomatic.js/)
- [Naming this in nested functions](https://gist.github.com/4135065) - Christian Johansen
- [Conditional Callbacks](https://github.com/airbnb/javascript/issues/52)
- [Popular JavaScript Coding Conventions on Github](http://sideeffect.kr/popularconvention/#javascript)
- [Understanding JavaScript Closures](http://javascriptweblog.wordpress.com/2010/10/25/understanding-javascript-closures/) - Angus Croll
- [Basic JavaScript for the impatient programmer](http://www.2ality.com/2013/06/basic-javascript.html) - Dr. Axel Rauschmayer
- [You Might Not Need jQuery](http://youmightnotneedjquery.com/) - Zack Bloom & Adam Schwartz
- [ES6 Features](https://github.com/lukehoban/es6features) - Luke Hoban

**[⬆ back to top](#table-of-contents)**


## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
