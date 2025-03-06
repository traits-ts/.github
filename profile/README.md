
<img src="https://raw.githubusercontent.com/traits-ts/core/refs/heads/master/etc/logo.svg" width="200" style="float: right" align="right" alt=""/>

## Traits for TypeScript Classes

**[traits-ts.org](https://traits-ts.org)**

[Traits TS](https://traits-ts.org) is a
project for providing a *Traits* mechanism for
[TypeScript](https://www.typescriptlang.org/). It consists of the
core [@traits-ts/core](https://github.com/traits-ts/core)
and the companion standard library
[@traits-ts/stdlib](https://github.com/traits-ts/stdlib).

The base [@traits-ts/core](https://github.com/traits-ts/core)
is a TypeScript library providing the bare *traits* (aka *mixins*)
mechanism for extending classes with *multiple* base functionalities,
although TypeScript/JavaScript technically do not allow multiple
inheritance. For this, it internally leverages the regular `class
extends` mechanism at the JavaScript level, so it is does not have to
manipulate the run-time objects at all. At the TypeScript level, it is
fully type-safe and correctly derives all properties of the traits a
class is derived from.

The companion [@traits-ts/stdlib](https://github.com/traits-ts/stdlib)
provides a set of standard, reusable, generic, typed traits,
based on [@traits-ts/core](https://github.com/traits-ts/core). Currently,
this standard library provides the particular traits *Identifiable*,
*Configurable*, *Bindable*, *Subscribable*, *Hookable*, *Disposable*,
*Traceable*, and *Serializable*.

This is [Traits TS](https://github.com/traits-ts), the home of the project.
Its two main parts can be found here:

- [@traits-ts/core](https://github.com/traits-ts/core) (Core)
- [@traits-ts/stdlib](https://github.com/traits-ts/stdlib) (Standard Library)

