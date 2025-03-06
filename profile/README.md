
<img src="https://raw.githubusercontent.com/traits-ts/core/refs/heads/master/etc/logo.svg" width="200" style="float: right" align="right" alt=""/>

## @traits-ts: Traits for TypeScript Classes

[Traits TS](https://github.com/traits-ts) is a
project for providing a *Traits* mechanism for
[TypeScript](https://www.typescriptlang.org/). It consists of the
core NPM package [@traits-ts/core](https://npmjs.com/@traits-ts/core)
and the companion standard library NPM package
[@traits-ts/stdlib](https://npmjs.com/@traits-ts/stdlib).

The [@traits-ts/core](https://github.com/traits-ts/core) package
is a TypeScript library providing the bare *traits* (aka *mixins*)
mechanism for extending classes with *multiple* base functionalities,
although TypeScript/JavaScript technically do not allow multiple
inheritance.
For this, it internally leverages the regular `class extends` mechanism
at the JavaScript level, so it is does not have to manipulate the
run-time objects at all. At the TypeScript level, it is fully type-safe
and correctly derives all properties of the traits a class is derived
from.

The companion [@traits-ts/stdlib](https://github.com/traits-ts/stdlib)
package provides a set of standard, reusable, generic, typed traits,
based on [@traits-ts/core](https://github.com/traits-ts/core). Currently,
this standard library provides the particular traits *Identifiable*,
*Configurable*, *Bindable*, *Subscribable*, *Hookable*, *Disposable*,
*Traceable*, and *Serializable*.

- [@traits-ts/core](https://github.com/traits-ts/core) (Core)
- [@traits-ts/stdlib](https://github.com/traits-ts/stdlib) (Standard Library)

