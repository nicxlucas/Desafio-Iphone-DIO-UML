# Desafio-iphone-dio-uml
Reposítorio criado para desafio teste da DIO.me (criação de UML de um iphone)

classDiagram

    class ReprodutorMusical {
    +tocar()
    +pausar(String exemplo)
    +selecionarMusica(String musica)
    }
    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }
    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }
    class iPhone {
    }
    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet