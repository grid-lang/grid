# Keywords

Grid has a limited set of keywords which perform specific behaviors in different [scopes](scope.md).

| Keyword | Scope | Behavior |
|---------|-------|----------|
| `module` | [module](structure.md) | Defines the current module namespace |
| `import` | [module](module.md) | Imports other module namespaces into the current module |
| `return` | [function](functions.md) | Returns from the current function, with optional value |
| `yield` | [stateful function](functions.md) | Returns from the current function retaining execution state, with optional value |
| `continue` | [loop](loop.md) | Continues the loop immediately |
| `break` | [loop](loop.md) | Breaks the loop immediately, with optional value |
