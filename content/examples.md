---
title: Full List of Examples
description: A full list of examples written in the Ballerina programming language.
---

## Getting Started

* [Hello World Main](/samples/basic/1_basic/hello_world_main) A simple hello world program.

## Statements


## Expressions

### Literals

A literal is a value that is specified directly in the source code. Ballerina supports the following literals.

| Literals                                                              | Examples                                                      |
| --------------------------------------------------------------------- | ------------------------------------------------------------- |
| [Nil Literal](/samples/basic/expressions/literals/nil/)               | `()`, `null`                                                  |
| [Boolean Literal](/samples/basic/expressions/literals/boolean/)       | `true` or `false`                                             |
| [Numeric Literals](/samples/basic/expressions/literals/numeric/)      | `123`, `0x1A`, `456.78`, `12.3f`, `12.3d`, `1.23e3`, `0X1a.A` |
| [String Literal](/samples/basic/expressions/literals/string/)         | `"Hello, World!"`                                             |
| [Byte Array Literal](/samples/basic/expressions/literals/byte_array/) | ``base16 `AB 12 34` `` <br/>  ``base64 `A1z+` ``              |

## Language Libraries

### `ballerina/lang.int`

* [`fromString`, `fromHexString`, and `toHexString`](/samples/basic/langlib/int/fromstring/). String to integer conversion and integer to string conversion.

## Ballerina Libraries

### HTTP

* [Basic HTTP Service](/samples/basic/7_http/basic_http_service/). A simple HTTP service with a query parameter.
* [REST Hello World](/samples/http/helloworldservice/). A simple hello world service. 
* [Simple Stock Quote Service](/samples/http/simplestockquoteservice/). A simple stock quote service.
