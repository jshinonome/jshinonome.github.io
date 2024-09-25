---
title: Control Flow and Error Handling
nav_order: 5
---

<!-- prettier-ignore-start -->

# Control Flow and Error Handling
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<!-- prettier-ignore-end -->

---

## Conditional Statements

A conditional statement is a set of statements that executes if a specified condition is true.

```
if[condition;
  statement1;
  statement2;
];
```

{: .warning }
may change conditional statements to the following format

```
if (condition1) {
  statement1;
} else if (condition2) {
  statement2;
} else if (conditionN) {
  statementN;
} else {
  statementLast;
}
```

## Error Handling

### throw

Use the `'` statement to throw an exception.

```
'"error message"
```

{: .warning }
may change `'` to use keyword `throw`

### try...catch

There is an extra `err` variable stores error message in the catch block

```
try {
  statement1;
  statement2;
} catch {
  statement1;
  statement2;
  show err;
}
```
