#Pesquisador de Países

Este é um projeto simples que permite aos usuários pesquisar informações sobre qualquer país do mundo usando a API Rest Countries. O usuário pode inserir o nome do país (em inglês), e o aplicativo exibe informações como a capital, continente, população e a bandeira do país.


##Funcionalidades

├──Pesquisar por qualquer país.
├──Exibir a bandeira do país.
├──Mostrar informações sobre a capital, continente e população.
├──Interface amigável e responsiva.


##Tecnologias Utilizadas

├──HTML5: Estrutura da página web.
├──CSS3: Estilização e layout, utilizando Bootstrap 5 para facilitar a criação de componentes e um design responsivo.
├──JavaScript: Manipulação dos dados e integração com a API.
├──Rest Countries API: API utilizada para buscar dados sobre os países.
├──Bootstrap 5: Framework CSS para estilização e responsividade.


##Como Usar
1. Clone este repositório:

git clone https://github.com/seu-usuario/pesquisador-de-paises.git

2. Abra o arquivo index.html no navegador.

3. Insira o nome de um país em inglês no campo de pesquisa e clique em "Pesquisar".

4. As informações do país serão exibidas no card logo abaixo do campo de pesquisa.


##Estrutura do Projeto

├── index.html        # Página principal
├── index.js          # Lógica do JavaScript
├── README.md         # Arquivo de documentação
└── style.css         # Arquivo de estilos (senecessário)

##Como Funciona

1. O usuário insere o nome de um país no campo de texto.

2. Ao clicar no botão "Pesquisar", a função Procurar() é executada:

├──O JavaScript faz uma requisição à API Rest Countries.
├──Quando a resposta é recebida, os dados são exibidos no card, que inicialmente estava oculto.

3. O card mostra as seguintes informações:
├──Nome do país
├──Capital
├──Continente
├──População
├──Bandeira do país


##Melhorias Futuras

├──Adicionar mensagens de erro caso o país não seja encontrado ou ocorra uma falha na API.
├──Suporte para múltiplas línguas na pesquisa (por exemplo, permitir pesquisar em português).
├──Melhorar o design visual do card e da página.


##Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests.