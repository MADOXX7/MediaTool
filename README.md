# MediaTool

Ferramenta de linha de comando para download e manipulação básica de mídia.

O MediaTool é um projeto experimental desenvolvido em **C**, utilizando ferramentas externas como **yt-dlp** e **FFmpeg** para realizar operações de download, conversão e manipulação de arquivos de mídia.

## Objetivo

O objetivo do projeto é desenvolver uma ferramenta simples para operações comuns com mídia enquanto serve como um projeto prático para estudar e aplicar conceitos da linguagem C.

## Funcionalidades planejadas

### Download

* [ ] Download de vídeos
* [ ] Download de áudio
* [ ] Seleção de qualidade
* [ ] Seleção de formato
* [ ] Definição do diretório de saída

### Manipulação

* [ ] Extração de áudio
* [ ] Conversão de formatos
* [ ] Remoção de áudio
* [ ] Alterações básicas de mídia
* [ ] Processamento através do FFmpeg

### Informações

* [ ] Exibição de informações da mídia
* [ ] Listagem de formatos disponíveis
* [ ] Exibição de duração
* [ ] Exibição de resolução
* [ ] Exibição de tamanho do arquivo

### Interface

* [ ] Menu interativo
* [ ] Argumentos via linha de comando
* [ ] Mensagens de erro
* [ ] Códigos de retorno
* [ ] Configuração personalizada

## Tecnologias

* C
* yt-dlp
* FFmpeg
* Make

---
## Estrutura inicial  planejada

```
MediaTool/
├── README.md
├── LICENSE
├── Makefile
│
├── src/
│   ├── main.c
│   ├── downloader.c
│   ├── downloader.h
│   ├── ffmpeg.c
│   ├── ffmpeg.h
│   ├── utils.c
│   └── utils.h
│
├── tests/
│
└── bin/

``

## Requisitos

Para executar o MediaTool, será necessário ter instalado:

* GCC ou Clang
* Make
* yt-dlp
* FFmpeg

## Status

**Em desenvolvimento**

O projeto está sendo desenvolvido inicialmente como uma ferramenta CLI e como um projeto prático para estudo da linguagem C.

## Objetivos de aprendizado

Durante o desenvolvimento serão explorados conceitos como:

* Sintaxe e fundamentos do C
* Funções
* Ponteiros
* Strings
* Arrays
* `struct`
* Manipulação de arquivos
* Gerenciamento de memória
* Processos
* Argumentos de linha de comando
* Tratamento de erros
* Modularização
* Makefile
* Interação com ferramentas externas
* APIs e bibliotecas nativas, futuramente

## Licença

Consulte o arquivo [LICENSE](LICENSE).
