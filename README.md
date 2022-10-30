# Tali

A statically typed concatenative language that experiments with being target-agnostic

## Target agnostic?

Tali does not specify any specific target for it to compile down to, instead the compilation of Tali source code emits the `geth` bytecode,
which is intended to then be consumed by users who create their own platform implementations that do not have to be implemented in the source language.

## Project structure

- `src` - Core language implementation
- `implementation` - The current implementations created.
- `doc` - Various documents going over design and other decisions related to the Tali language and the Geth bytecode.

## Implementations

- `senketsu` - JVM implementation

If you have an implementation and you'd like to add it to the list, feel free to open a PR or an issue.

## Discussion

Tali related discussion happens on the /r/ProgrammingLanguages [discord server](https://discord.gg/4Kjt3ZE), scroll to the `#tali` channel and ask away!
