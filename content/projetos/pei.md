+++
date = '2021-09-05T12:00:00-03:00'
draft = false
title = 'pei'
description = 'PE Injector - Injeta código em executáveis PE de 32 e 64 bits'
weight = 3
+++

Este projeto é uma ferramenta de linha de comando para injetar código e manipular executáveis PE32 (32 bits) e
PE32+ (64 bits).

Com o `pei`, você pode:

- Exibir informações sobre o executável, como o cabeçalho COFF, as seções e muito mais.
- Obter valores individuais dos campos dos cabeçalhos para manipulá-los por meio de scripts. Exemplo:
  `pei get test.exe optional.entry_point '0x%x'` - Imprime `0x12345`.
- Editar campos individualmente. Exemplo:
  `pei edit test.exe optional.entry_point = 0xabcd`
- Manipular as permissões de acesso à memória das seções do executável.
- Encontrar blocos de dados zerados nas seções do executável.
- Injetar código para ser executado antes do OEP (Original EntryPoint) do executável.
- Comparar executáveis e exibir as **diferenças** entre eles.

Repositório: <https://github.com/Silva97/pei>
