---
ShowToc: true
title: Caracteres inválidos em nomes de arquivos
---

Este aplicativo salva suas notas, capítulos, romances e outros conteúdos em arquivos de texto. Usamos texto simples para garantir ampla compatibilidade entre plataformas. Assim, mesmo que você deixe de usar o aplicativo, poderá gerenciar e editar seus arquivos facilmente em outros aplicativos e sistemas operacionais.

## Caracteres não permitidos em nomes de arquivos: `\/:*?"<>|`

Esses caracteres têm funções especiais nos sistemas de arquivos e em muitos programas comuns. Por isso, usá-los em um nome pode dificultar a criação, localização ou abertura consistente de arquivos em diferentes dispositivos. Por exemplo, `/` separa pastas em um caminho, enquanto `\` é usado como separador de caminho em alguns sistemas e como caractere de escape em certos formatos de texto. Os demais caracteres podem funcionar como curingas, delimitadores ou símbolos de controle. Para que seus arquivos continuem fáceis de usar em diferentes plataformas, o aplicativo não permite esses caracteres nos nomes.

## Por que um nome de arquivo não pode começar com `.` ou `..`?

O Android é baseado no kernel Linux. Em caminhos no estilo Linux, `.` indica a pasta atual e `..` indica a pasta pai. Além disso, ferramentas do Linux e do Android geralmente tratam como ocultos os arquivos e pastas cujos nomes começam com ponto. O aplicativo impede que o nome comece com ponto para evitar confusão com componentes especiais de caminho e manter seus arquivos visíveis e fáceis de encontrar.
