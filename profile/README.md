
<img src="https://raw.githubusercontent.com/traits-ts/core/refs/heads/master/etc/logo.svg" width="200" style="float: right" align="right" alt=""/>

**Traits for TypeScript Classes (Core)**

[![github (author stars)](https://img.shields.io/github/stars/rse?logo=github&label=author%20stars&color=%233377aa)](https://github.com/rse)
[![github (author followers)](https://img.shields.io/github/followers/rse?label=author%20followers&logo=github&color=%234477aa)](https://github.com/rse)

About
-----

This is a small TypeScript library providing a *trait* (aka *mixin*)
facility for extending classes with *multiple* base functionalities,
although TypeScript/JavaScript technically do not allow multiple
inheritance.

For this, it internally leverages the regular `class extends` mechanism
at the JavaScript level, so it is does not have to manipulate the
run-time objects at all. At the TypeScript level, it is fully type-safe
and correctly derives all properties of the traits a class is derived
from.

This library consists of just three API functions: `trait` for defining
a trait (or sub-trait), the API function `derive` for deriving a base
class from one or more defined traits, and the API type-guard function
`derived` to ensure an object has the functionality of a trait under
run-time.

