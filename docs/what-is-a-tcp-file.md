# What is a Tally TCP file?

A **TCP file** is a compiled, packaged version of a Tally customization. Developers write their customization in **TDL (Tally Definition Language)**, which is plain text, and then compile it into a `.tcp` file so it can be shared or sold without handing over the readable source.

## TDL vs TCP

| | TDL | TCP |
|---|-----|-----|
| Format | Plain text | Compiled / packaged |
| Readable by humans | Yes | No |
| Editable | Yes | No |
| Typical use | Development | Distribution to clients |

## Why people need to decompile a TCP

- The original `.tdl` source was lost, deleted or never handed over
- A developer or vendor is no longer available
- A client needs to change or extend an old customization
- You want to understand how an existing customization works before upgrading Tally

## What decompiling gives you

A decompiler reads the TCP and rebuilds readable TDL definitions from it. The result is a starting point you can read and edit, though it may not match the original source line for line.

Next: [How to convert TCP to TDL](tcp-to-tdl-guide.md)
