+++
date = '2025-01-24T12:00:00-03:00'
draft = false
title = 'Mya Language'
description = 'An easy to use formal language used to write the specification of a Instruction Set Architecture (ISA)'
featured = true
weight = 1
+++

Mya is a formal language to write specification of an ISA ([Instruction Set Archicteture]). Using
Mya you can specify registers and the format of instructions in assembly and in machine code.

* [Example](https://github.com/mya-project/mya-spec/blob/main/src/example.mya)
* [Syntax notation](https://github.com/mya-project/mya-spec/blob/main/src/syntax.wsn)

Project page: <https://mya-project.github.io/>

[Instruction Set Archicteture]: https://en.wikipedia.org/wiki/Instruction_set_architecture

## Why?

* It's a formal way to document your custom ISA instructions, so it's make easy to another people
  read and understand how your ISA works.
* Tools can parse and make something with your ISA specification, for instance, generate an
  assembler and disassembler for you
