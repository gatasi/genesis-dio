# Jogo de memória estilo Genius

Esta é a minha versao do projeto "Criando seu jogo de memória estilo Genius" do bootcamp da Eduzz em parceria com a DIO.

Nesta versao, foi modificado o seguinte:

-   O esquema de cores foi alterado para ficar mais similar ao Genius original.
-   A opacidade das cores no acionamento foi alterada para maior contraste.
-   Para reproduzir a forma dos botoes do Genius original, foi adicionada uma circunferencia ao centro do jogo.
-   Foi corrigida uma falha no acionamento das cores onde estas permaneciam selecionadas indefinidamente, e só era possível para o jogador perceber a primeira ativacao de cada cor em uma rodada.

Melhorias que gostaria de implementar futuramente:

-   Exibir as mensagens na pŕopria página, no lugar de criar alertas.
-   Migrar a lógica do jogo do lado-cliente ao lado-servidor com Node, pois na versao atual é fácil trapacear utilizando as ferramentas do próprio navegador.
-   Guardar as melhores pontuacoes de forma persistente com Mongo.

** Como jogar **

1. Clone o repositório na sua máquina com:

```
git clone https://github.com/gatasi/genesis-dio.git
```

ou baixe a versao zipada em Code > Download ZIP. 2. Abra o arquivo `index.html` no seu navegador favorito.

Visite o projeto original [aqui](https://github.com/SpruceGabriela/genesis-dio).
