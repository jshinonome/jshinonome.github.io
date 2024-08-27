---
title: Grammar
nav_order: 2
---

<!-- prettier-ignore-start -->

# Grammar
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<!-- prettier-ignore-end -->

---

## Comments

A line/inline comment starts with `//`, and a block comments starts with `/*` and ends with `*/`.

```
// a one line comment

/*  this
    is
    a
    block
    comment */
```

## Basics

Jasmine borrows most of its syntax from q, Javascript, Python and Rust.

JavaScript is case-sensitive and may extend to use the Unicode character set.

```
dt: 2026.08.27

// may extend to allow unicode char
取引日: 2026.08.27
```

## Expressions

An expression is a valid unit of code that resolves to a value

```
1 + 1 2 3
```

## Statements

An statement is one simple expression or compound expression, gets executed independently.
