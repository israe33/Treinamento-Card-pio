# Cardápio da Semana - Restaurante Batista

Este projeto é uma página HTML simples para apresentar o **cardápio da semana** do **Restaurante Batista**.

## O que este código faz

- Monta a estrutura básica de uma página HTML.
- Usa uma folha de estilo CSS externa (`style.css`) para formatar cores, alinhamentos e listas.
- Exibe o nome do restaurante, categorias de pratos e listas com os itens do cardápio.
- Inclui um link para a página do Instagram do dono do restaurante.

## Estrutura do código

- **HTML**  
  - `<h1>` para o nome do restaurante.
  - `<h2>` para as seções do cardápio (Pratos Principais, Bebidas e Sobremesas).
  - `<ul>` e `<li>` para listar os itens.
  - `<a>` para link externo.

- **CSS**  
  - Define cor de fundo clara.
  - Colore títulos de acordo com a categoria.
  - Remove marcadores das listas.
  - Alinha o título principal ao centro.

## Exemplo de Código

```html
<!-- Estrutura HTML -->
<h1 class="Comida">Restaurante Batista</h1>
<h2 class="Prato">Pratos Principais</h2>
<ul class="Dieta">
    <li>Benevenutte</li>
    <li>Picanha no aço</li>
    ...
</ul>


/* Exemplo de CSS */
body {
    background-color: #f5f5f5;
}
.Comida {
    color: brown;
}
h1 {
    text-align: center;
}




