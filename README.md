# es-functional-mode-proposal
Proposal to enable opting JS into operating as a functional language

See ['use strict'](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode) for an idea of where this is heading.

Helpful plugin to simulate
https://github.com/bodil/eslint-config-cleanjs

## Major points

### Strong-typing
TypeScript, Flow, Elm, and others agree that strong-typing provides safety and predictability.

- https://github.com/flowtype/flow-typed
- https://github.com/DefinitelyTyped/DefinitelyTyped/
- http://elm-lang.org

### Immutable data structures
- TypeScript 2.0 has a [readonly modifier](https://blogs.msdn.microsoft.com/typescript/2016/09/22/announcing-typescript-2-0/#the-readonly-modifier)

### Pure functions
JavaScript is [context-sensitive](http://staltz.com/is-your-javascript-function-actually-pure.html) when it comes to function purity.

### Expressions > statements

### No null or undefined
- TypeScript 2.0 has [non-nullable types](https://blogs.msdn.microsoft.com/typescript/2016/09/22/announcing-typescript-2-0/#non-nullable-types)
- Flow has [`Maybe` types](https://flowtype.org/docs/nullable-types.html#_)
- Elm has [`Maybe` types](https://guide.elm-lang.org/error_handling/maybe.html)
