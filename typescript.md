# TypeScript Issue Tracker

Collection of github issues and other documents for quick access.

## Feature / Syntax

## Semantics

### Strict Mode

Links:

+ [Add compiler option to parse in strict mode](https://github.com/Microsoft/TypeScript/issues/10758)

## Type System

### Variance / Covariance / Contravariance / Bivariance

Title in Chinese: 可变性／协变／逆变／互变

Description: TODO

Links:

+ [Covariance / Contravariance Annotations](https://github.com/Microsoft/TypeScript/issues/1394): Original problem
+ [Proposal: covariance and contravariance generic type arguments annotations](https://github.com/Microsoft/TypeScript/issues/10717): Proposal in detail
+ [Suggestion Backlog Slog, 9/26/2016](https://github.com/Microsoft/TypeScript/issues/11215): Added to backlog
+ [Unavoidable Type System Design limitation?](https://github.com/Microsoft/TypeScript/issues/14656): Union type with generics
+ [add `in`, `out` modifiers to allow being specific of expected contrvariant/covariant type parameters](https://github.com/Microsoft/TypeScript/issues/8137): Duplicated proposal

External Resources:

+ [Covariance and contravariance (computer science)](https://en.wikipedia.org/wiki/Covariance_and_contravariance_(computer_science))

Problems:

+ [Variance error not caught by the type system](https://github.com/Microsoft/TypeScript/issues/14524): Array generics
+ [No compile time error when passing wrong function object type](https://github.com/Microsoft/TypeScript/issues/14964): Function type variance
+ [allow a flag that turns off covariant parameters when checking function assignability](https://github.com/Microsoft/TypeScript/issues/6102)
+ [Functions passed as an argument to other functions are not type checked as expected](https://github.com/Microsoft/TypeScript/issues/6333): String allowed as object
+ [--strictNullChecks does not gaurd against optional arguments assignment](https://github.com/Microsoft/TypeScript/issues/9450): Can be solved by variance

### Type Inference

Title in Chinese: 类型推理

Links:

+ [Always use literal types](https://github.com/Microsoft/TypeScript/pull/10676): Determine type from expression, difference between let and const
+ [Non-widening explicit literal types](https://github.com/Microsoft/TypeScript/pull/11126)

Problems:

+ [Should not widen in type argument inference](https://github.com/Microsoft/TypeScript/issues/1436)
+ [Literal type not inferred correctly when using generics](https://github.com/Microsoft/TypeScript/issues/10685)

### Nullable Typing

Links:

+ [Non-nullable types](https://github.com/Microsoft/TypeScript/pull/7140): PR for the feature
+ [[Request for feedback] Nullable types, `null` and `undefined`](https://github.com/Microsoft/TypeScript/issues/7426): Official discussion
+ [Design Meeting Notes for 3/11/2016](https://github.com/Microsoft/TypeScript/issues/7488): Mentioned about non-nullable types

Problems:

+ [Guidelines for choosing between `null` and `undefined` with `strictNullChecks`](https://github.com/Microsoft/TypeScript/issues/9653)

## Module System

Links:

+ [Built-in support for UMD module definitions](https://github.com/Microsoft/TypeScript/issues/7125): Officially raised problem
+ [UMD support](https://github.com/Microsoft/TypeScript/pull/7264): PR for the feature
+ [Library include directives](https://github.com/Microsoft/TypeScript/issues/7156): Officially raised problem
+ [Support reference library directives in tsc](https://github.com/Microsoft/TypeScript/pull/7263): PR for the feature
+ [Design Meeting Notes for 3/11/2016](https://github.com/Microsoft/TypeScript/issues/7488): Mentioned about UMD module support and library include directives

Problems:

+ ['--alwaysStrict' option should not 'use strict' declaration if setting with module=es2015](https://github.com/Microsoft/TypeScript/issues/11806): Unnecessary 'use strict' in output

## Compatability

Links:

+ [Start using ES5 functionality in tsc](https://github.com/Microsoft/TypeScript/issues/10125): Drop support for ES3
+ [Breaking Change: Running TypeScript on ES3 hosts no longer supported](https://github.com/Microsoft/TypeScript/issues/10278): Duplicated announcement
+ [Add compiler option to parse in strict mode](https://github.com/Microsoft/TypeScript/issues/10758)

Problems:

+ [Allow to run TypeScript (Compiler, Services) in strict mode](https://github.com/Microsoft/TypeScript/issues/9449)
+ [Allow to run TypeScript (Services) in strict mode](https://github.com/Microsoft/TypeScript/issues/10755)


## Problems

### Type Safety

Title in Chinese: 类型安全

Links:

+ [No compile error with Object.assign](https://github.com/Microsoft/TypeScript/issues/6689): Type merge
+ [Allow `super` constrains for type parameters](https://github.com/Microsoft/TypeScript/issues/7265)

### React Typing

Links: 

+ [Sub-type type](https://github.com/Microsoft/TypeScript/issues/6218): Solved by partial type
+ [React.d.ts type constrained definition for React.Component's setState method](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/7987): Solved by partial type
+ [Support Pick<> on setState now that TS 2.1 is out](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/13155)
+ [More accurate typing of Object.assign and React component setState()](https://github.com/Microsoft/TypeScript/issues/6613): Solved by partial type
+ [Subset types for easier updating of immutable structures](https://github.com/Microsoft/TypeScript/issues/10803)
+ [For a given type, derive a new type where all the properties specified in the original type are optional](https://github.com/Microsoft/TypeScript/issues/7355): Solved by partial type

