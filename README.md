# Diagrama UML

## Projeto: iPhone

Este projeto representa a estrutura básica do iPhone, com os papéis de Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Classes e Interfaces

### Classe iPhone

A classe `iPhone` representa o próprio iPhone e possui os seguintes atributos:

- `modelo` (String): guarda o modelo do iPhone.
- `cor` (String): guarda a cor do iPhone.

A classe `iPhone` implementa as seguintes interfaces:

- `ReprodutorMusical`: define os comportamentos relacionados à reprodução de músicas.
- `AparelhoTelefonico`: define os comportamentos relacionados ao uso como aparelho telefônico.
- `NavegadorInternet`: define os comportamentos relacionados à navegação na internet.

### Interface ReprodutorMusical

A interface `ReprodutorMusical` declara os seguintes métodos:

- `tocar()`: inicia a reprodução de música.
- `pausar()`: pausa a reprodução de música.
- `selecionarMusica()`: seleciona uma música para reprodução.

### Interface AparelhoTelefonico

A interface `AparelhoTelefonico` declara os seguintes métodos:

- `ligar()`: realiza a ligação telefônica.
- `atender()`: atende uma chamada telefônica.
- `iniciarCorreioVoz()`: inicia o correio de voz.

### Interface NavegadorInternet

A interface `NavegadorInternet` declara os seguintes métodos:

- `exibirPagina()`: exibe uma página na internet.
- `adicionarNovaAba()`: adiciona uma nova aba de navegação.
- `atualizarPagina()`: atualiza a página atual.

## Utilização

Você pode utilizar essa estrutura do iPhone como ponto de partida para desenvolver funcionalidades adicionais ou expandir o comportamento existente. As classes e interfaces fornecem um esboço básico das funcionalidades esperadas de um iPhone em termos de reprodutor musical, aparelho telefônico e navegador na internet.

Sinta-se à vontade para modificar, estender ou personalizar as classes e interfaces de acordo com suas necessidades específicas.
