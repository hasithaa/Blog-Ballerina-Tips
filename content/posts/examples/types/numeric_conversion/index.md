---
title: Auto-Casting and Conversion among Numerical Types
description: Ballerina does not support implicit conversion among numerical types. This safeguard helps prevent unintended loss of precision and unexpected program behavior.
date: 2023-06-05
weight: 20151
tags:
    - int
    - float
    - decimal
    - byte
categories:
    - Numeric Literal
    - Examples
Series:
    - Working with Types
keywords:
    - Conversion among Numerical Types
    - Casting and Conversion in Ballerina
featuredImagePreview: /images/example_cover.png
---

Ballerina does not support implicit conversion among numerical types. This safeguard helps prevent unintended loss of precision and unexpected program behavior.

<!--more-->

## No Implicit Conversion

For example, the following code would result in a compile-time error:
    
```ballerina
float x = 10.0;
decimal y = 10 + x; // error
int z = 1.0; // error - floating point literal on the right-hand side.
```

You can use explicit type conversion to convert a value from one numerical type to another. 

## Example 

{{< example >}}
