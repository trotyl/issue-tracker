# Angular Issue Tracker

## Core

### Change Detection

Problems:

+ [ExpressionChangedAfterItHasBeenCheckedError when changing a component 'non model' value in afterViewInit](https://github.com/angular/angular/issues/15464): Puzzle; working as intended
+ [Projected templates do not update when using ChangeDetectionStrategy.OnPush](https://github.com/angular/angular/issues/16012): Bug; needs confirmation

### Dependency Injection

Problems:

+ [Eager providers and Injector.get() can cause errors](https://github.com/angular/angular/issues/15501): Bug; regression in 4.0
+ ~~["Can't resolve all parameters for X" only when component is referenced in a routing module](https://github.com/angular/angular/issues/15627)~~: Puzzle; needs confirmation
+ [Missing Providers don't log helpful error messages in ng test](https://github.com/angular/angular/issues/15985): Bug
+ [Structural Directive's provides are no longer available in template as of Angular 4.0](https://github.com/angular/angular/issues/15998): Puzzle; working as intended

### Life-cycle Hooks

Problems:

+ ~~[ViewChild not ready by ngAfterViewInit](https://github.com/angular/angular/issues/15100)~~: Puzzle; working as intended

### Decorator / Annotation / Metadata

Problems:

+ ~~[Inheritance for Angular decorators is not well-defined](https://github.com/angular/angular/issues/11606)~~: Bug; fixed in 2.3

### Renderer

Problems:

+ [HTML5 datalist element's id property is not limited to the containing component's scope](https://github.com/angular/angular/issues/16142): Puzzle

## Compiler

Links: 

+ [Tracking: Template type checker](https://github.com/angular/angular/issues/15988): Official tracker

Problems:

+ [Could not load the summary for directive](https://github.com/angular/angular/issues/15506): Bug; regression in 4.0
+ [AOT on case insensitive file systems fails](https://github.com/angular/angular/issues/15767): Bug

## Http

Problems:

+ [Angular 4 fails to provide MockBackend](https://github.com/angular/angular/issues/15521): Bug; regression in 4.0

## Router

Problems:

+ [&lt;a href="#"&gt;&lt;/a&gt; doesn't work as expected after upgrading to angular 2.2.0](https://github.com/angular/angular/issues/12945): Bug; regression in 2.2; fix in progress
+ ~~[CanDeactivate being called with null component and providers not being provided to new component](https://github.com/angular/angular/issues/15626)~~: Bug; regression in 4.0.1; fixed in 4.0.2
+ [Angular is ignoring withcredentials](https://github.com/angular/angular/issues/15805): Puzzle; needs confirmation
+ [RouterLinkActive causes `Maximum call stack size` error when wrapped in `ng-template`](https://github.com/angular/angular/issues/15825): Bug; regression in 4.0; fix in progress
+ [Router / Resolver stuck?](https://github.com/angular/angular/issues/15997): Puzzle
+ [Routing: Preserve trailing slash](https://github.com/angular/angular/issues/16051): Feature request
+ [ng2 path normalization doesn't work if query parameters are present](https://github.com/angular/angular/issues/16069): Puzzle; needs confirmation

## Animations

Problems:

+ ~~[[Feat] Allow to animate transitions between routes?](https://github.com/angular/angular/issues/9845)~~: Feature request; solved in 4.1
+ [[@state]="true|false" should translate to "true" or "1" and "false" or "0"](https://github.com/angular/angular/issues/15433): Bug; regression in 4.0
+ [Angular 4.0.0 animations](https://github.com/angular/angular/issues/15507): Bug; regression in 4.0; fix in progress

## Build

Problems:

+ [Request dependency <=2.68 opens to potential memory exposure vulnerability](https://github.com/angular/angular/issues/10352): Bug; security vulnerability
+ ~~[SystemJS error trying to use BrowserAnimationsModule](https://github.com/angular/angular/issues/16027)~~: Puzzle; needs confirmation

## Compatibility

Problems:

+ ~~[Compiler-generated factory doesn't call 'new', which fails for ES6.](https://github.com/angular/angular/issues/14816)~~: Bug; closed for tracking
+ [Angular compiler - custom decorators does not work with AOT build](https://github.com/angular/angular/issues/16023): Puzzle; needs confirmation

## Testing

Problems:

+ [Provide a mock service using TestBed](https://github.com/angular/angular/issues/10727): Puzzle
+ [Angular 4 test using whenStable hangs (worked in Angular 2)](https://github.com/angular/angular/issues/15486): Bug; needs confirmation; regression in 4.0;
+ ~~[Testing - Async object not exists](https://github.com/angular/angular/issues/15889)~~: Puzzle; issue of rxjs
+ [Clarify status of TestBed.override<X> methods](https://github.com/angular/angular/issues/16026): Puzzle

## Branding

Problems:

+ [Branding guide makes searching for Angular 2+ content difficult](https://github.com/angular/angular/issues/14802): Puzzle

