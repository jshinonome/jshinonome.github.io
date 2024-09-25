---
title: Operators
nav_order: 6
---

<!-- prettier-ignore-start -->

# Operators
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<!-- prettier-ignore-end -->

---

## Assignment Operators

| operator        | description                                                                 | example  |
| --------------- | --------------------------------------------------------------------------- | -------- |
| assignment(`:`) | assigns a value to its left operand based on the value of its right operand | `x: f[]` |

The assignment is a expression that returns left operand value

## Comparison OPerators

| operator                     | description                                                                    | example        |
| ---------------------------- | ------------------------------------------------------------------------------ | -------------- |
| equal (`=`)                  | Returns `true` if the operands are equal.                                      | `var1 = var2`  |
| not equal (`!=`)             | Returns `true` if the operands are not equal.                                  | `var1 != var2` |
| match (`~`)                  | Returns `true` if the operands are equal and of the same type.                 | `var1 ~ var2`  |
| less than or equal (`<=`)    | Returns `true` if the left operand is less than or equal to the right operand. | `var1 <= var2` |
| greater than or equal (`>=`) | Returns `true` if the operands are equal.                                      | `var1 >= var2` |
| less than (`<`)              | Returns `true` if the left operand is less than the right operand.             | `var1 < var2`  |
| greater than (`>`)           | Returns `true` if the left operand is greater than the right operand.          | `var1 > var2`  |

## Arithmetic operators

| operator       | description                         | example       |
| -------------- | ----------------------------------- | ------------- |
| add (`+`)      | left operand add right operand      | `var1 + var2` |
| minus (`-`)    | left operand minus right operand    | `var1 - var2` |
| multiple (`*`) | left operand multiple right operand | `var1 * var2` |
| divide (`%`)   | left operand divide right operand   | `var1 % var2` |

{: .warning }
may change divide `%` to `/` and only use `over` for over operator. may change `mod` to `%`

## Logical operators

| operator                     | description                        | example                       |
| ---------------------------- | ---------------------------------- | ----------------------------- |
| or/max (<code>&#124;</code>) | left operand or/max right operand  | <code>var1 &#124; var2</code> |
| and/min (`&`)                | left operand and/min right operand | `var1 & var2`                 |

## Other operator

| operator     | description                                                     | example            |
| ------------ | --------------------------------------------------------------- | ------------------ |
| at (`@`)     | call a function with argument, get a item of list using indices | `f @ arg`          |
| apply (`.`)  | call a function with arguments                                  | `f . (arg1; arg2)` |
| cast (`$`)   | cast the right operand using a data type symbol                 | `` `i64 $ var1``   |
| rand (`?`)   | generate random numbers                                         | `10 ? 1.0`         |
| dict (`!`)   | create a dictionary                                             | `` `a`b`c!1 2 3 `` |
| append (`,`) | append the right operand to left operand                        | `list1 , var1`     |
| take (`#`)   | take a sub list from the right operand                          | `3 # list1`        |
| throw (`'`)  | throw a string as exception                                     | `'"error message"` |
| remove (`_`) | remote items fr om the right operand                            | `3 _ list1`        |
| fill (`^`)   | fill nulls of the right operand with a value                    | `var1 ^ list1`     |

{: .warning }
may change divide `'` to `throw`. may change `.` to `apply`. may change `,` to `append`
