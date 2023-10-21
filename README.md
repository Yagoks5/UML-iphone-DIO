@startuml

class iPhone2007 {
    + reprodutorMusical: ReprodutorMusical
    + AparelhoTelefonico: AparelhoTelefonico
}

class ReprodutorMusical {
    + tocar()
    + pausar()
    + selecionarMusica()
}

class AparelhoTelefonico {
    + ligar()
    + atender()
    + iniciarCorreioVoz()
}

class NavegadorInternet {
    + exibirPagina()
    + adicionarNovaAba()
    + atualizarPagina()
}

iPhone2007 --> ReprodutorMusical
iPhone2007 --> AparelhoTelefonico

@enduml


<img src ="869a1177-1c9a-47c8-86bb-2e6ffd1ec7b6.jpg">
