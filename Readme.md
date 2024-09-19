# Pesquisador de Países

Este é um projeto simples que permite aos usuários pesquisar informações sobre qualquer país do mundo usando a API Rest Countries. O usuário pode inserir o nome do país (em inglês), e o aplicativo exibe informações como a capital, continente, população e a bandeira do país.


## Funcionalidades

- &nbsp;Pesquisar por qualquer país.
- &nbsp;Exibir a bandeira do país.
- &nbsp;Mostrar informações sobre a capital, continente e população.
- &nbsp;Interface amigável e responsiva.


## Tecnologias Utilizadas

- &nbsp;HTML5: Estrutura da página web.
- &nbsp;CSS3: Estilização e layout, utilizando Bootstrap 5 para facilitar a criação de componentes e um design responsivo.
- &nbsp;JavaScript: Manipulação dos dados e integração com a API.
- &nbsp;Rest Countries API: API utilizada para buscar dados sobre os países.
- &nbsp;Bootstrap 5: Framework CSS para estilização e responsividade.


## Como Usar
1. Clone este repositório:

- &nbsp;git clone https://github.com/seu-usuario/pesquisador-de-paises.git

2. Abra o arquivo index.html no navegador.

3. Insira o nome de um país em inglês no campo de pesquisa e clique em "Pesquisar".

4. As informações do país serão exibidas no card logo abaixo do campo de pesquisa.


## Estrutura do Projeto

- &nbsp;index.html        - &nbsp;Página principal
- &nbsp;index.js          - &nbsp;Lógica do JavaScript
- &nbsp;README.md         - &nbsp;Arquivo de documentação
- &nbsp;style.css         - &nbsp;Arquivo de estilos (necessário)

## Como Funciona

1. O usuário insere o nome de um país no campo de texto.

2. Ao clicar no botão "Pesquisar", a função Procurar() é executada:

- &nbsp;O JavaScript faz uma requisição à API Rest Countries.
- &nbsp;Quando a resposta é recebida, os dados são exibidos no card, que inicialmente estava oculto.

3. O card mostra as seguintes informações:
- &nbsp;Nome do país
- &nbsp;Capital
- &nbsp;Continente
- &nbsp;População
- &nbsp;Bandeira do país


## Melhorias Futuras

- &nbsp;Adicionar mensagens de erro caso o país não seja encontrado ou ocorra uma falha na API.
- &nbsp;Suporte para múltiplas línguas na pesquisa (por exemplo, permitir pesquisar em português).
- &nbsp;Melhorar o design visual do card e da página.


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests.
