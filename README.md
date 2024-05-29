#Treinando conceitos de UML com Mermaid e Java

```mermaid
---
title: Iphone UML
---
classDiagram

    class ReprodutorMusical {
        +exemploMetodo1()
        +exemploMetodo2(String exemplo)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorNaInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    AparelhoTelefonico <|-- Iphone
    AparelhoTelefonico <|-- Android
    Iphone <|-- ReprodutorMusical
    Iphone <|-- NavegadorNaInternet
    Android <|-- ReprodutorMusical
    Android <|-- NavegadorNaInternet

```