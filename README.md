# Minha Loja Virtual

Página inicial de uma loja online desenvolvida como atividade de HTML e Bootstrap 5, com layout responsivo e componentes interativos.

## Acesse o projeto

[Visualizar a loja no GitHub Pages](https://alland0.github.io/minha-loja-virtual/)

## Tecnologias utilizadas

- HTML5
- Bootstrap 5.3.8 via CDN
- JavaScript
- Placehold.co para imagens de demonstração

## Recursos implementados

- Faixa de aviso sobre frete grátis.
- Navbar com menu responsivo, dropdown de categorias, busca e carrinho com badge.
- Carrossel com três slides.
- Seis cartões de categorias.
- Produtos em destaque com badge de promoção, preço antigo riscado e preço promocional.
- Modais com detalhes dos produtos.
- Botões que atualizam o contador do carrinho.
- Dois banners promocionais.
- Benefícios em três colunas.
- Newsletter com input-group e validação do formato de e-mail.
- Rodapé com quatro colunas.

## Responsividade

O layout utiliza o grid e os utilitários do Bootstrap.

| Seção | Desktop | Tablet | Celular |
| --- | --- | --- | --- |
| Categorias | 6 por linha | 3 por linha | 3 por linha |
| Produtos | 4 por linha | 2 por linha | 1 por linha |
| Banners | 2 por linha | 2 por linha | Empilhados |
| Benefícios | 3 por linha | 3 por linha | Empilhados |
| Rodapé | 4 colunas | 4 colunas | Empilhado |

No celular, o menu recolhe no botão hambúrguer e a busca ocupa uma linha própria.

## Verificações realizadas

A página foi verificada no navegador em larguras simuladas de:

- 390 pixels: celular.
- 820 pixels: tablet.
- 1280 pixels: desktop.

Foram conferidos os grids, a ausência de rolagem horizontal, o menu, o dropdown, o carrossel, os modais e o contador do carrinho.

A newsletter foi testada com campo vazio, formato inválido e formato válido de e-mail.

## Estrutura do projeto

- `index.html`: estrutura da página e scripts.
- `README.md`: documentação do projeto.

## Como visualizar

Acesse o link do GitHub Pages disponível no início deste documento.

O projeto é estático e utiliza recursos externos para carregar o Bootstrap e as imagens, por isso requer conexão com a internet para a visualização completa.

## Observações

Este é um projeto educacional de interface:

- As imagens utilizadas são placeholders.
- A busca ainda não filtra produtos.
- O carrinho atualiza apenas o contador, sem checkout ou persistência.
- A newsletter valida o formato do e-mail e apresenta uma mensagem demonstrativa, sem realizar cadastro ou envio de dados.

## Autor

[AllanD0](https://github.com/AllanD0)
