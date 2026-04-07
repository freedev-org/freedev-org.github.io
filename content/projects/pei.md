+++
date = '2021-09-05T12:00:00-03:00'
draft = false
title = 'pei'
description = 'PE Injector - Inject code on 32-bit and 64-bit PE executables'
weight = 3
+++

This project is a command-line tool for inject code and manipulate PE32 (32-bit) and
PE32+ (64-bit) executables.

With `pei` you can:
- Display informations about the executable like COFF header, sections and more.
- Get individual values from fields of the headers to manipulate the values by scripts. Example:
  `pei get test.exe optional.entry_point '0x%x'` - Will print `0x12345`
- Edit individual fields. Example:
  `pei edit test.exe optional.entry_point = 0xabcd`
- Manipulate memory access permissions to sections of the executable.
- Find zeroed blocks of data on the sections of the executable.
- Inject code to be executed before the OEP of the executable.
- Compares executables and show **differences** between.

Repository: <https://github.com/Silva97/pei>
