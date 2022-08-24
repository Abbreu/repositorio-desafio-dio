# Introdução ao Git e ao GitHub

## Entendendo o Git 

Foi criado em 2005, é um sistema de versionamento de código distribuído, criado pelo Linus Torvalds. O software é feito de maneira colaborativa.

#### Git e GitHub são tech diferentes, porém complementares.

## Comandos básicos para um bom desempenho no terminal

A maioria dos SO eles tem programas com interface gráfica, responsivo.
O Git é um CLI, a interface é de linha de comandos.

GUI - Graphic User Interface
CLI - Command Line Interface

cd - mudar
dir - listar 
mkdir - criar
rmdir - deletar

#### Os comandos tem flags, que são complementos, que acrescentam, modificam ou formatam como é devolvido para nós.

## Tópicos fundamentais para entender o funcionamento do Git

### SHA1 

É um algoritmo de encriptação. Significa Secure Hash Algorithm, é um conjunto de funções hash criptográficas projetadas pela NSA.
A encriptação gera um conjunto de caracteres identificador de 40 dígitos. Um conjunto único para cada arquivo.

### Objetos internos do Git

#### Blobs

Objeto com metadados. Sha1 do arquivo.

#### Trees

Armazena o blob, tem um SHA1 prórpio e armazena o nome do arquivo

#### Commit

Faz o sentido de tudo

### Chave SSH e Tokens

#### Chave SSH

Forma de estabelecer uma conexão segura com outra máquina

#### Token de acesso pessoal

Username e senha pessoais, para usar o clone com HTTPS