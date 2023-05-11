# hook-de-carrinho-de-compras
Desafio proposto: Criar uma aplicação para treinar o aprendizado em ReactJS

Aplicação cujo principal objetivo é criar um hook de carrinho de compras. 
<br>
Com acesso a duas páginas, um componente e um hook para implementar as funcionalidades pedidas no desafio:

- Adicionar um novo produto ao carrinho;
- Remover um produto do carrinho;
- Alterar a quantidade de um produto no carrinho;
- Cálculo dos preços sub-total e total do carrinho;
- Validação de estoque;
- Exibição de mensagens de erro;
- Entre outros.

Para esse desafio, além dos conceitos vistos em aula, foram utilizados alguns novos conceitos para deixar a aplicação ainda melhor:

- Fake API com JSON Server;
- Preservar dados do carrinho com localStorage API;
- Mostrar erros com toastify.

## O que foi editado na aplicação?

Com o template já clonado, as depêndencias instaladas e a [fake API rodando](https://www.notion.so/Desafio-01-Criando-um-hook-de-carrinho-de-compras-5769216778794019a83f544e79167b12), foi necessário completar onde não possuía código com o código para atingir os objetivos de cada teste. 
<br>Os documentos que foram editados:

- [src/components/Header/index.tsx](https://github.com/ThaysaRafaele/hook-de-carrinho-de-compras/blob/master/src/components/Header/index.tsx);
- [src/pages/Home/index.tsx](https://github.com/ThaysaRafaele/hook-de-carrinho-de-compras/blob/master/src/pages/Home/index.tsx);
- [src/pages/Cart/index.tsx](https://github.com/ThaysaRafaele/hook-de-carrinho-de-compras/blob/master/src/pages/Cart/index.tsx);
- [src/hooks/useCart.tsx](https://github.com/ThaysaRafaele/hook-de-carrinho-de-compras/blob/master/src/hooks/useCart.tsx).

## Aplicação rodando:
![hookCarrinhoCompras](https://user-images.githubusercontent.com/83955839/234108557-a29cdb40-5e7b-44ee-9363-2736da275735.gif)
