# Pobrefy - Seu Player de Música Minimalista em C++ com SFML

## Descrição do Projeto

O **Pobrefy** é um projeto desenvolvido em C++, utilizando a biblioteca SFML, como parte da disciplina de Algoritmos e Estrutura de Dados 1 do curso de Ciência da Computação. Trata-se de uma aplicação de console que permite ao usuário gerenciar e reproduzir músicas, armazenando-as em estruturas de dados como filas ou listas.

## Funcionalidades

- Adição de músicas à fila ou lista de reprodução.
- Reprodução de músicas diretamente do console.
- Interface simples e intuitiva para facilitar a interação do usuário.

## Pré-requisitos

Para compilar e executar o projeto, você precisará do compilador g++ e da biblioteca SFML instalados em seu sistema. Certifique-se de ter os seguintes arquivos:

- `fila.cpp`
- `musica.cpp`
- `lista.cpp`
- `algoritmos.cpp`
- `main.cpp`

## Autores
- Carlos Junior
- Matheus Fleury


## Você pode compilar o projeto utilizando o seguinte comando:

```bash
g++ fila.cpp musica.cpp lista.cpp algoritmos.cpp main.cpp -o PobreFy -lsfml-audio
./PobreFy
