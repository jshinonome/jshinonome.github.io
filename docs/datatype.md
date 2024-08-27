---
title: Data Types
nav_order: 3
---

<!-- prettier-ignore-start -->

# Data Types
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<!-- prettier-ignore-end -->

---

## Scalar

| type      | length | example                 |
| --------- | ------ | ----------------------- |
| boolean   | 1      | 1b                      |
| u8        | 8      | 0x01                    |
| i16       | 16     | 1h                      |
| i32       | 32     | 1i                      |
| i64       | 64     | 1                       |
| date      | 32     | 2026.08.22              |
| time      | 64     | 21:45:00.000            |
| datetime  | 64     | 2026.08.22T21:45:00.000 |
| timestamp | 64     | 2026.08.22D21:46:00.000 |
| duration  | 64     | 0D21:47:00.000          |
| f32       | 32     | 1e                      |
| f64       | 64     | 1f                      |
| string    | \*     | "s"                     |
| symbol    | \*     | `s                      |
| null      | 0      | 0n                      |

There is no null for each scalar type, null only exists in series type

## Series

Same as [Polars Data Types](https://docs.pola.rs/user-guide/concepts/data-types/overview/)

Mostly used Series types are:

| group    | type           | example                                 | details                                                                                                              |
| -------- | -------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Boolean  | `Boolean`      | 01b                                     | Boolean type.                                                                                                        |
| Numeric  | `UInt8`        | 0x010203                                | 8-bit unsigned integer.                                                                                              |
| Numeric  | `Int16`        | 1 2 3h                                  | 16-bit signed integer.                                                                                               |
| Numeric  | `Int32`        | 1 2 3i                                  | 32-bit signed integer.                                                                                               |
| Numeric  | `Int64`        | 1 2 3                                   | 64-bit signed integer.                                                                                               |
| Numeric  | `Float32`      | 1 2 3e                                  | 32-bit floating point.                                                                                               |
| Numeric  | `Float64`      | 1 2 3f                                  | 64-bit floating point.                                                                                               |
| Temporal | `Date`         | 2026.08.22 2026.08.23                   | Date representation, internally represented as days since UNIX epoch encoded by a 32-bit signed integer.             |
| Temporal | `Datetime(ms)` | 2026.08.22T00:00:00 2026.08.23T00:00:00 | Datetime representation, internally represented as milliseconds since UNIX epoch encoded by a 64-bit signed integer. |
| Temporal | `Datetime(ns)` | 2026.08.22D00:00:00 2026.08.23D00:00:00 | Datetime representation, internally represented as nanoseconds since UNIX epoch encoded by a 64-bit signed integer.  |
| Temporal | `Duration(ns)` | 0D22:48:00 0D22:49:00                   | A timedelta type, internally represented as nanoseconds. Created when subtracting `Date/Datetime`.                   |
| Temporal | `Time`         | 22:49:00 22:50:00                       | Time representation, internally represented as nanoseconds since midnight by a 64-bit signed integer.                |
| String   | `String`       | ("a";"ab")                              | String data.                                                                                                         |
| String   | `Categorical`  | \`a\`b                                  | A categorical encoding of a set of strings, correspondent to scalar type symbol                                      |
| Nested   | `List`         | During Query                            | A list contains a child array containing list values and an offset array.                                            |
| Nested   | `Array`        | During Query                            | A fixed-size multidimensional array.                                                                                 |

## Matrix

2d-array 64 bit float type

create a 3\*3 matrix

```
3 3#range 9
```

## Dictionary

A string/symbol keyed dictionary

example 1

```
`a`b`c!1 2 3
```

example 2

```
{a:1;b:2;c:3}
```

## DataFrame

DataFrame is a data structure constructed with rows and columns. It is a collection of series.

```
([]a: 1 2; b: 2026.08.22 2026.08.23)
```
