+++
date = '2025-01-24T12:00:00-03:00'
draft = false
title = 'Mya Language'
description = 'Linguagem formal fácil de usar que serve para escrever a especificação de uma Instruction Set Architecture (ISA)'
featured = true
weight = 1
+++

Mya é uma linguagem formal usada para escrever especificações de uma ISA ([Instruction Set Architecture]). Com a Mya,
você pode especificar registradores e o formato das instruções, tanto em assembly quanto em código de máquina.

- [Exemplo](https://github.com/mya-project/mya-spec/blob/main/src/example.mya)
- [Notação da sintaxe](https://github.com/mya-project/mya-spec/blob/main/src/syntax.wsn)

**Página do projeto**: <https://mya-project.github.io/>

[Instruction Set Architecture]: https://en.wikipedia.org/wiki/Instruction_set_architecture

## Por quê?

- É uma maneira formal de documentar as instruções de uma ISA personalizada, facilitando a leitura e a compreensão de
  como ela funciona por outras pessoas.
- Ferramentas podem analisar e utilizar a especificação da sua ISA para realizar diferentes tarefas. Por exemplo,
  podem gerar automaticamente um *assembler* e um *disassembler* para você.
