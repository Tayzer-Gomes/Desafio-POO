# Desafio-POO

+------------------+
|      iPhone      |
+------------------+
| -reprodutorMusical: ReprodutorMusical
| -aparelhoTelefonico: AparelhoTelefonico
| -navegadorInternet: NavegadorInternet
+------------------+

+-------------------+
| ReprodutorMusical |
+-------------------+
| +tocar(): void
| +pausar(): void
| +selecionarMusica(musica: Musica): void
+-------------------+

+---------------------+
| AparelhoTelefonico  |
+---------------------+
| +ligar(numero: String): void
| +atender(): void
| +iniciarCorreioVoz(): void
+---------------------+

+--------------------+
| NavegadorInternet  |
+--------------------+
| +exibirPagina(url: String): void
| +adicionarNovaAba(): void
| +atualizarPagina(): void
+--------------------+

+---------------+
|     Musica    |
+---------------+
| +titulo: String
| +artista: String
+---------------+