# Angular Developer Roadmap
# Table of contents  
1. [Topics covered + suggested resources](https://github.com/doctorc30/angular-developer-roadmap#topics-covered--suggested-resources)
1. [Angular](https://github.com/doctorc30/angular-developer-roadmap#angular)
    1. [Basic functional](https://github.com/doctorc30/angular-developer-roadmap#basic-functional)
    2. [Components](https://github.com/doctorc30/angular-developer-roadmap#components)
    3. [Modules](https://github.com/doctorc30/angular-developer-roadmap#modules)
    4. [State Management](https://github.com/doctorc30/angular-developer-roadmap#state-management)
    5. [Architecture](https://github.com/doctorc30/angular-developer-roadmap#architecture)
3. [Rx programming](https://github.com/doctorc30/angular-developer-roadmap#rx-programming)
    1. [Observable](https://github.com/doctorc30/angular-developer-roadmap#observable) 
    2. [Subject](https://github.com/doctorc30/angular-developer-roadmap#subject)
    3. [Help to learn](https://github.com/doctorc30/angular-developer-roadmap#help-to-learn)

## Topics covered + suggested resources
### The basics:
- HTML
  - [marksheet.io](https://marksheet.io/)
  - [MDN on HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- CSS
  - [marksheet.io](https://marksheet.io/)
  - [patterns](https://csslayout.io/)   
  - [MDN on CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- JavaScript
  - ["You Don't Know JS"](https://github.com/getify/You-Dont-Know-JS)
  - [NodeSchool.io](https://nodeschool.io/)
  - [ES6 Overview in 350 Bullet Points](https://ponyfoo.com/articles/es6)
### General Development Skills
- GIT
   - ["Learn Git Branching"](https://learngitbranching.js.org/)
- HTTP/HTTPS
- Learn to search for solutions
- Terminal usage
- Data Structures and Algorithms
- Design Patterns
### Build tools
- Package Managers
  - [npm](https://www.npmjs.com/)
  - [Yarn](https://yarnpkg.com/lang/en/)
- Angular CLI
  - [Angular CLI Wiki](https://github.com/angular/angular-cli/wiki)
  - [Bazel](https://bazel.build/)
  - [Rollup](https://rollupjs.org/guide/en)
- Task runners
  - [npm scripts](https://medium.freecodecamp.org/introduction-to-npm-scripts-1dbb2ae01633)
  - [gulp](https://gulpjs.com/)
### Styling
- CSS Preprocessors
  - [Sass/SCSS](https://sass-lang.com/guide)
  - [PostCSS](https://postcss.org/)
  - [Less](http://lesscss.org/)
- CSS Frameworks
  - [Bootstrap](https://getbootstrap.com/)
  - [Zurb Foundation](https://foundation.zurb.com/)
  - [Bulma](https://bulma.io/)
  - [Semantic UI](https://semantic-ui.com/)
  - [Tailwind CSS](https://tailwindcss.com/)
- Design Systems
  - [Angular Material](https://material.angular.io/)
  - [Clarity Design System](https://vmware.github.io/clarity/)
  - [Ant Design](https://ng.ant.design/docs/introduce/en)
### Coding style
- [Angular Styleguide](https://angular.io/guide/styleguide)
- [TSLint](https://palantir.github.io/tslint/)
- [Prettier](https://prettier.io/)
### Fundamental 3rd parties
- TypeScript
  - ["TypeScript Deep Dive"](https://github.com/basarat/typescript-book)
  - [Typescript Docs](https://www.typescriptlang.org/docs/)
- RxJS
  - [The introduction to Reactive Programming](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
  - [RxJS manual](http://reactivex.io/rxjs/manual/overview.html#introduction)
  - [RxJS In-Depth (video)](https://www.youtube.com/watch?v=KOOT7BArVHQ)
### Progressive Web Apps
- [@angular/pwa](https://angular.io/guide/service-worker-getting-started)
- [Workbox](https://developers.google.com/web/tools/workbox/)
### Utility Libraries
- [Lodash](https://lodash.com/)
- [Moment.js](https://momentjs.com/)
### Testing
- Unit Testing
      - [Jasmine](https://jasmine.github.io/)
      - [Karma](http://karma-runner.github.io/2.0/index.html)
      - [Jest](http://jestjs.io/)
- E2E Testing
      - [Protractor](https://www.protractortest.org/#/)
      - [cypress.io](https://www.cypress.io/)
### Non-browser Environments
- Mobile
  - @angular/pwa (`ng add @angular/pwa`)
  - [NativeScript](https://www.nativescript.org/)
  - [Ionic](https://ionicframework.com/)
- [Angular Universal](https://universal.angular.io/)
- [Electron](https://electronjs.org/)

## Angular
### [Basic functional](https://angular.io/guide/architecture)
- Components
- Modules
- Directives
- Pipe
- Routing
- Services
- Libraries
### Components / Derectives
- [Components vs Derectives](https://stackoverflow.com/questions/32680244/directive-vs-component-in-angular)
    </br>`Components is directives with a template.`
- Types of directives
   - [Built-in](https://angular.io/guide/built-in-directives)
   - [Attribute](https://angular.io/guide/attribute-directives)
   - [Structural](https://angular.io/guide/structural-directives)
- Binding
   - [property](https://angular.io/guide/property-binding)
   - [event](https://angular.io/guide/event-binding)
   - [two way](https://angular.io/guide/two-way-binding)
- Templating
- [ViewChild](https://angular.io/api/core/ViewChild)
- [HostListener](https://angular.io/api/core/HostListener)
- [Lifecycle](https://angular.io/guide/lifecycle-hooks#lifecycle-hooks)
- [Change detection](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular)
- Dynamic components
- View encapsulation
- Angular elements
- [Entry components.](https://angular.io/guide/entry-components) [Why is it deprecated?](https://angular.io/guide/deprecations#entrycomponents-and-analyze_for_entry_components-no-longer-required)
- Forms
    - [Reactive](https://angular.io/guide/reactive-forms)
    - [Dynamic](https://angular.io/guide/dynamic-form)
### Modules
- [Lazy load modules](https://angular.io/guide/lazy-loading-ngmodules)
- declarations
- exports
- imports
- providers
- bootstrap
### Routing
- [routes](https://angular.io/guide/router)
- activated route
- guards
- resolvers
- data
- loadChildren
- outlets
- [router module config](https://angular.io/api/router/ExtraOptions)
### Services
- [dependency injection](https://angular.io/guide/architecture-services)
- [Client-server interaction](https://angular.io/guide/architecture-next-steps#client-server-interaction)
### State Management
#### [ngrx](https://github.com/ngrx/platform/blob/master/docs/store/README.md)
  - [/effects](https://github.com/ngrx/platform/blob/master/docs/effects/README.md)
    - [Action Stream](https://medium.com/@tanya/understanding-ngrx-effects-and-the-action-stream-1a74996a0c1c#:~:text=NgRx%20Effects%20allow%20us%20to,and%20also%20as%20its%20destination.) 
  - [/entity](https://github.com/ngrx/platform/tree/master/docs/entity/README.md)
  - [ngrx-data](https://github.com/johnpapa/angular-ngrx-data)
#### [NGXS](https://ngxs.gitbook.io/ngxs/)
### Architecture
- [Schematics](https://www.npmjs.com/package/@angular-devkit/schematics)
- [Building Libraries](https://medium.com/@tomsu/how-to-build-a-library-for-angular-apps-4f9b38b0ed11)
- [@angular/elements](https://angular.io/guide/elements)
### Performance
[Check list](https://github.com/mgechev/angular-performance-checklist/blob/master/README.ru-RU.md)
- [Tree-shaking](https://webpack.js.org/guides/tree-shaking/)
- [AoT](https://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)
- Runtime Optimizations
    - Change Detection
    - trackBy  
## [Rx programming](http://reactivex.io/)
### What is it?
1. [MoscowJS 42 – RxJS по косточкам](https://www.youtube.com/watch?v=3rEDHnqn-Cw)
2. [Введение в реактивное программирование](https://habr.com/ru/company/arcadia/blog/432004/)
3. [Реактивное программирование на реальных примерах: подробное введение](https://tproger.ru/translations/reactive-programming/)
### Observable
1. [Marble diagrams](http://reactivex.io/rxjs/manual/overview.html#marble-diagrams)
3. [Operators](https://rxjs-dev.firebaseapp.com/guide/operators)
    - Which Operator to Use? [this](https://github.com/Reactive-Extensions/RxJS/blob/master/doc/gettingstarted/which-instance.md) or [this](http://reactivex.io/rxjs/manual/overview.html#choose-an-operator)
    - Filtering
    - Mapping
    - [Flattening](https://www.youtube.com/watch?v=rUZ9CjcaCEw)
    - Merging
    - [Combining](https://scotch.io/tutorials/rxjs-operators-for-dummies-forkjoin-zip-combinelatest-withlatestfrom/amp)
4. [Hot / Cold](https://softchris.github.io/books/rxjs/hot-n-cold-observables/)
5. [Multicast](http://reactivex.io/rxjs/manual/overview.html#multicasted-observables)
### Subject
1. [Subject](http://reactivex.io/rxjs/manual/overview.html#subject)
1. [BehaviorSubject](http://reactivex.io/rxjs/manual/overview.html#behaviorsubject)
1. [ReplaySubject](http://reactivex.io/rxjs/manual/overview.html#replaysubject)
1. [AsyncSubject](http://reactivex.io/rxjs/manual/overview.html#asyncsubject)
### Help to learn
1. [Marbles](https://rxmarbles.com/)
1. [rxjs-fruits](https://www.rxjs-fruits.com/subscribe)
1. [libraries](https://habr.com/ru/post/348818/)
    

