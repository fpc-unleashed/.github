<p align="center">
  <img height="320" src="https://github.com/user-attachments/assets/66089ca0-96b9-45e3-a423-0261b2ff7ba1" />
</p>

# FPC Unleashed

A fork of the Free Pascal Compiler that adds modern language features behind opt-in modeswitches. Inline variables, pattern matching, tuples, `defer` / `autofree`, flexible arrays, multiline strings, RTTI stripping, and more.

Existing FPC / Lazarus code compiles unchanged - new features turn on per file with `{$mode unleashed}` or per feature with a specific `{$modeswitch}`.

## Repos

- **[freepascal](https://github.com/fpc-unleashed/freepascal)** - compiler and runtime
- **[lazarus](https://github.com/fpc-unleashed/lazarus)** - companion fork of the Lazarus IDE
- **[installer](https://github.com/fpc-unleashed/installer)** - bundle installer for compiler, RTL, and IDE

## Documentation

Per-feature pages with grammar, examples, and modeswitch info: [`unleashed/docs/README.md`]([https://github.com/fpc-unleashed/freepascal/tree/main/unleashed/docs](https://github.com/fpc-unleashed/freepascal/blob/main/unleashed/docs/README.md)).
