# Angular Developer Roadmap
  
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
### Components
- Binding
   - [property](https://angular.io/guide/property-binding)
   - [event](https://angular.io/guide/event-binding)
   - [two way](https://angular.io/guide/two-way-binding)
- Templating
- [Change detection](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular)
- Dynamic components
- View encapsulation
- Angular elements
- Forms
    - [Reactive](https://angular.io/guide/reactive-forms)
    - [Dynamic](https://angular.io/guide/dynamic-form)
### Modules
- Lazy load modules
- declarations
- exports
- imports
- providers
- bootstrap
- libraries
### Services
- [dependency injection](https://angular.io/guide/architecture-services)
- [Client-server interaction](https://angular.io/guide/architecture-next-steps#client-server-interaction)

### State Management
- [@ngrx](https://github.com/ngrx/platform/blob/master/docs/store/README.md)
    - [/effects](https://github.com/ngrx/platform/blob/master/docs/effects/README.md)
    - [/entity](https://github.com/ngrx/platform/tree/master/docs/entity/README.md)
    - [ngrx-data](https://github.com/johnpapa/angular-ngrx-data)
- [NGXS](https://ngxs.gitbook.io/ngxs/)

### Architecture
- [Schematics](https://www.npmjs.com/package/@angular-devkit/schematics)
- [Building Libraries](https://medium.com/@tomsu/how-to-build-a-library-for-angular-apps-4f9b38b0ed11)
- [@angular/elements](https://angular.io/guide/elements)
    
## [Rx programming](http://reactivex.io/)
### Observable
1. [Operators](https://rxjs-dev.firebaseapp.com/guide/operators)
    - [Which Operator to Use?](https://github.com/Reactive-Extensions/RxJS/blob/master/doc/gettingstarted/which-instance.md)
    - Filtering
    - Mapping
    - [Fattening](https://www.youtube.com/watch?v=rUZ9CjcaCEw)
    - Merging
    - [Combining](https://scotch.io/tutorials/rxjs-operators-for-dummies-forkjoin-zip-combinelatest-withlatestfrom/amp)
1. Hot / Cold  
1. [Multicast](http://reactivex.io/rxjs/manual/overview.html#multicasted-observables)
### Subject
1. [Subject](http://reactivex.io/rxjs/manual/overview.html#subject)
1. [BehaviorSubject](http://reactivex.io/rxjs/manual/overview.html#behaviorsubject)
1. [ReplaySubject](http://reactivex.io/rxjs/manual/overview.html#replaysubject)
1. [AsyncSubject](http://reactivex.io/rxjs/manual/overview.html#asyncsubject)

### Help to learn
1. [Marbles](https://rxmarbles.com/)
1. [rxjs-fruits](https://www.rxjs-fruits.com/subscribe)
1. [libraries](https://habr.com/ru/post/348818/)
    

