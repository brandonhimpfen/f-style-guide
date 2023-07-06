# F# Style Guide

[![GitHub](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen/) &nbsp; [![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://www.buymeacoffee.com/brandonhimpfen) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen) &nbsp; [![Sponsor Project](https://srv-cdn.himpfen.io/badges/sponsor-project/sponsor-project-flat.svg)](https://brandon.tiny.us/donate)

## Naming Conventions
- Use PascalCase for module names and type names.
- Use camelCase for function names, method names, and variable names.
- Use uppercase abbreviations for acronyms in names (e.g., HTTP, XML).

## Indentation and Formatting
- Use 4 spaces for indentation (no tabs).
- Limit line length to 100 characters.
- Break long lines with appropriate indentation.
- Put opening braces on the same line as the declaration.

## Commenting
- Use `///` for XML documentation comments.
- Use `//` for single-line comments.
- Use `(* ... *)` for multi-line comments.

## Pattern Matching and Discriminated Unions
- Use pattern matching instead of `if-then-else` chains whenever possible.
- Define discriminated union cases in uppercase.
- Use indentation to make the pattern matching code readable.

## Immutable Data and Immutability
- Prefer immutability whenever possible.
- Use `let` bindings for immutable values.
- Avoid using mutable variables.

## Function Composition
- Use the `|>` operator for function composition.
- Prefer function composition over nested function calls.

## Error Handling
- Use the `Result<'T, 'TError>` type for error handling.
- Use `Option<'T>` for optional values.
- Avoid throwing exceptions for normal control flow.

## Concurrency and Asynchronous Programming
- Use `async` and `await` for asynchronous programming.
- Use `Task<'T>` for asynchronous computations.
- Use `Async<'T>` for asynchronous workflows.

## Miscellaneous
- Avoid unnecessary type annotations.
- Use meaningful names for variables and functions.
- Write concise and readable code.
- Follow functional programming principles.
- Use whitespace to improve code readability.
