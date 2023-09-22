# Por que criar bibliotecas internas?
Talk apresentada na [Gophercon23 Brasil](https://gopherconbr.org) no dia 22/09/2023.

## Exemplos mostrados durante a apresentação

[Biblioteca simples](https://github.com/gubtos/golib): Exemplo básico de uma biblioteca (implementa função que valida palíndromo).

[Módulo executável](https://github.com/gubtos/palindrome): módulos executaveis são úteis para substituir scripts em bash. Este módulo usa o módulo acima para implementar um executável que pode ser instalado usando `go install github.com/gubtos/palindrome`. Assim é possível rodar o comando `palindrome` no terminal.

[Organização de submódulos](https://github.com/gubtos/gosubmoduleexample): Mostra como organizar um módulo principal (core) com seus submódulos.

[Uso de submódulos](https://github.com/gubtos/gosubmoduleusageexample): Mostra como usar um módulo com seus submódulos.

[Exemplos Gerais](https://github.com/gubtos/goexamples): Mostra as diferenças entre patterns, uso de variadic e reflection em struct tags.
