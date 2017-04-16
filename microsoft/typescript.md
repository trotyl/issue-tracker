# TypeScript Issue Tracker

Collection of github issues and other documents for quick access.

## Syntax

Description: whatever relevant to new syntax with runtime effects

### Enum

+ [Allow enums of types other than number](https://github.com/Microsoft/TypeScript/issues/1206): Feature request

### Generator

Problems:

+ ~~[Partial classes](https://github.com/Microsoft/TypeScript/issues/563)~~: Feature request; out of scope
+ ~~[ES6 Generator support](https://github.com/Microsoft/TypeScript/issues/1564)~~: Feature request; solved by generator support in 2.3

### Other

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ ~~[Suggestion: use `:{type}` to omit formal parameter when declare function interface or something else](https://github.com/Microsoft/TypeScript/issues/10984)~~: Feature request; declined

## Semantics

Description: those unrelevant to syntax change but have effect on runtime behaviour

### Generator

Problems:

+ ~~[emit generators when targeting es5](https://github.com/Microsoft/TypeScript/issues/14903)~~: Feature request; closed as duplicate; solved by `downlevelIteration` compiler option in 2.3

### Strict Mode

Links:

+ [Add compiler option to parse in strict mode](https://github.com/Microsoft/TypeScript/issues/10758): Official tracker
+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes
+ [Fix #10758 Add compiler option to parse in strict mode](https://github.com/Microsoft/TypeScript/issues/11473): Pull request; introducing `alwaysStrict` compiler option

Problems:

+ ~~[How do I enable strict mode in TypeScript?](https://github.com/Microsoft/TypeScript/issues/4270)~~: Puzzle; solved by `alwaysStrict` compiler option in 2.3
+ ~~[Suggestion: Add a "forceStrictMode" compiler option](https://github.com/Microsoft/TypeScript/issues/7209)~~: Feature request; solved by `alwaysStrict` compiler option in 2.3
+ ~~[Warn when a subset of input files have "use strict" with --outFile](https://github.com/Microsoft/TypeScript/issues/11464)~~: Puzzle; solved by `alwaysStrict` compiler option in 2.3

### JSX

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

## Type System

Description: type checking behaviour with no runtime impact

### Variance / Covariance / Contravariance / Bivariance

Description: TODO

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

External Resources:

+ [Covariance and contravariance (computer science)](https://en.wikipedia.org/wiki/Covariance_and_contravariance_(computer_science)): Wiki

Problems:

+ [Covariance / Contravariance Annotations](https://github.com/Microsoft/TypeScript/issues/1394)
+ [allow a flag that turns off covariant parameters when checking function assignability](https://github.com/Microsoft/TypeScript/issues/6102): Feature request
+ [Functions passed as an argument to other functions are not type checked as expected](https://github.com/Microsoft/TypeScript/issues/6333): Puzzle; about string allowed as object
+ ~~[Allow `super` constrains for type parameters](https://github.com/Microsoft/TypeScript/issues/7265)~~: Feature request; closed as duplicate; can be solved by variance in future
+ [add `in`, `out` modifiers to allow being specific of expected contrvariant/covariant type parameters](https://github.com/Microsoft/TypeScript/issues/8137): Feature request; duplicated
+ [--strictNullChecks does not gaurd against optional arguments assignment](https://github.com/Microsoft/TypeScript/issues/9450): Puzzle
+ [Proposal: covariance and contravariance generic type arguments annotations](https://github.com/Microsoft/TypeScript/issues/10717): Feature request
+ [Variance error not caught by the type system](https://github.com/Microsoft/TypeScript/issues/14524): Puzzle; about array generics
+ [Unavoidable Type System Design limitation?](https://github.com/Microsoft/TypeScript/issues/14656): Puzzle; about union type with generics
+ [Generic parameters not fully type-checked (e.g., Promise)](https://github.com/Microsoft/TypeScript/issues/14770): Puzzle
+ ~~[No compile time error when passing wrong function object type](https://github.com/Microsoft/TypeScript/issues/14964)~~: Puzzle; closed as duplicate

### Type Inference

Links:

+ [Always use literal types](https://github.com/Microsoft/TypeScript/pull/10676): TypeScript 2.1; determine type from expression, difference between let and const
+ [Non-widening explicit literal types](https://github.com/Microsoft/TypeScript/pull/11126)

Problems:

+ [Should not widen in type argument inference](https://github.com/Microsoft/TypeScript/issues/1436)
+ [Literal type not inferred correctly when using generics](https://github.com/Microsoft/TypeScript/issues/10685)

### Dynamic Typing

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ ~~[Suggestion: Type Property type](https://github.com/Microsoft/TypeScript/issues/1295)~~: Feature request; solved by `keyof` operator in 2.0
+ ~~[Ability to skip elements in tuple type annotation](https://github.com/Microsoft/TypeScript/issues/2671)~~: Feature request; declined
+ ~~[Sub-type type](https://github.com/Microsoft/TypeScript/issues/6218)~~: Puzzle; solved by `Partial` type in 2.0
+ ~~[More accurate typing of Object.assign and React component setState()](https://github.com/Microsoft/TypeScript/issues/6613)~~: Puzzle; solved by `Partial` type in 2.0
+ ~~[For a given type, derive a new type where all the properties specified in the original type are optional](https://github.com/Microsoft/TypeScript/issues/7355)~~: Puzzle; solved by `Partial` type in 2.0
+ ~~[React.d.ts type constrained definition for React.Component's setState method](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/7987)~~: Puzzle; solved by `Partial` type in 2.0
+ ~~[Subset types for easier updating of immutable structures](https://github.com/Microsoft/TypeScript/issues/10803)~~: Puzzle; solved by `Partial` type in 2.0

### Generics

Links:

+ [Adds support for type parameter defaults](https://github.com/Microsoft/TypeScript/pull/13487): Pull request
+ [Design Meeting Notes, 1/20/2017](https://github.com/Microsoft/TypeScript/issues/13607): Design notes

### Nullable Typing

Links:

+ [Non-nullable types](https://github.com/Microsoft/TypeScript/pull/7140): Pull request
+ [[Request for feedback] Nullable types, `null` and `undefined`](https://github.com/Microsoft/TypeScript/issues/7426): Official discussion
+ [Design Meeting Notes for 3/11/2016](https://github.com/Microsoft/TypeScript/issues/7488): Design notes; mentioned about non-nullable types
+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ ~~[Guidelines for choosing between `null` and `undefined` with `strictNullChecks`](https://github.com/Microsoft/TypeScript/issues/9653)~~: Puzzle


### Spread/Rest Types

Links:

+ [Add spread/rest types to support proposed object spread/rest](https://github.com/Microsoft/TypeScript/issues/10727): Official tracker

Problems:

+ ~~[No compile error with Object.assign](https://github.com/Microsoft/TypeScript/issues/6689)~~: Puzzle; closed as duplicate
+ [Proposal: Allow exclusive unions using logical or (^) operator between types](https://github.com/Microsoft/TypeScript/issues/14094): Feature request; can be solved by `rest` type in future

### Code Flow Analysis

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes


## Module System

Links:

+ [Built-in support for UMD module definitions](https://github.com/Microsoft/TypeScript/issues/7125): Official tracker
+ [Library include directives](https://github.com/Microsoft/TypeScript/issues/7156): Official tracker
+ [Support reference library directives in tsc](https://github.com/Microsoft/TypeScript/pull/7263): Pull request
+ [UMD support](https://github.com/Microsoft/TypeScript/pull/7264): Pull request
+ [Design Meeting Notes for 3/11/2016](https://github.com/Microsoft/TypeScript/issues/7488): Mentioned about UMD module support and library include directives
+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ ~~[Do not emit files with no statments](https://github.com/Microsoft/TypeScript/issues/10908)~~: Puzzle; working as intended
+ ~~['--alwaysStrict' option should not 'use strict' declaration if setting with module=es2015](https://github.com/Microsoft/TypeScript/issues/11806)~~: Bug; fixed in 2.1.4

## Compatability

Links:

+ [Start using ES5 functionality in tsc](https://github.com/Microsoft/TypeScript/issues/10125): Drop support for ES3
+ [Breaking Change: Running TypeScript on ES3 hosts no longer supported](https://github.com/Microsoft/TypeScript/issues/10278): Duplicated announcement
+ [Add compiler option to parse in strict mode](https://github.com/Microsoft/TypeScript/issues/10758)

Problems:

+ ~~[Suggestion: Compilation targets other than JavaScript](https://github.com/Microsoft/TypeScript/issues/9202)~~: Feature request; out of scope
+ ~~[Allow to run TypeScript (Compiler, Services) in strict mode](https://github.com/Microsoft/TypeScript/issues/9449)~~: Bug; fixed in 2.0
+ ~~[Allow to run TypeScript (Services) in strict mode](https://github.com/Microsoft/TypeScript/issues/10755)~~: Bug; fixed in 2.1

## Configuration

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ [Interactive init](https://github.com/Microsoft/TypeScript/issues/10964): Feature request

## Performance

Links:

+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Design notes

Problems:

+ [Strategies for improving incremental Check time?](https://github.com/Microsoft/TypeScript/issues/13538): Puzzle
