![Captura de Tela 2021-04-05 às 03 01 37](https://user-images.githubusercontent.com/49724512/113542760-51e02880-95bb-11eb-98fe-2d9cc1c73f82.png)


Link do desafio: https://www.notion.so/Desafio-02-Componentizando-a-aplica-o-b9f0f025c95b437699d0c3115f55b0f1


## O que devo editar na aplicação?

Com o template já clonado, as dependências instaladas e a [fake API rodando](https://www.notion.so/Desafio-01-Criando-um-hook-de-carrinho-de-compras-5769216778794019a83f544e79167b12), você deve criar **pelo menos** os componentes SideBar e Content que já estão com os arquivos criados.
Os arquivos a serem editados são:

- **src/App.tsx**
Esse componente contém toda a aplicação com exceção do componente `Button` que não precisa ser alterado e `Icon` que também não precisa de alteração.
- **src/components/Content.tsx**
Esse componente, ainda vazio, deve possuir toda a lógica e corpo responsável pelo header e conteúdo da aplicação;


- **src/components/SideBar.tsx**
Esse componente, também vazio, deve possuir toda a lógica e corpo responsável pela seção que contém o título do site e a parte de navegação à esquerda da página;



# Solução do desafio

Primeiro criamos um diretório chamado hooks e nele um arquivo tsx useMain.

Usamos o useContext para que a aplicação possas acessar o evento de cliques no SideBar e assim mude o Content.

Retiramos o codigo do App.tsx referente ao sidebar e content, colocamos nos seus respectivos arquivos: SideBar e Content.

Gravei um passo a passo da resolução desse desafio.

Link do vídeo: https://youtu.be/v0LaKtfUjpc?list=PLjm0b1mZwR0fZcmlIlajFGliSqyPk8lmN

