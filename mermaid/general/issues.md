[README](../../README.md)
| 
[THE EXAMPLES](../the-examples.md)
| 
[TIPS](../general/tips.md)
| 
[ISSUES](../general/issues.md)

# Issues

## Invisible Text

mermaid in vscode (with dark theme enabled) results in invisible text, in some cases.  

The following text "1..*" is invisible by default in vscode

```mermaid
classDiagram

A "1..*" -- "0..*" B

```

Workarounds: Custom style overrides required to show.  

https://github.com/mjbvz/vscode-markdown-mermaid/issues/23

