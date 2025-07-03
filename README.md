# Media-queries-Simples
# Media Queries - Poesia Responsiva

Este projeto é um exemplo simples e poético de como usar **Media Queries** em CSS para criar páginas responsivas. A proposta é adaptar o conteúdo visual de acordo com o tamanho da tela do dispositivo, usando um poema como tema central.

---

## Sobre o projeto

A página exibe um poema chamado **"Borboletas"**, e troca dinamicamente a imagem exibida com base na largura da tela:

- **Em telas pequenas (até 600px)**: é exibida uma imagem adaptada para dispositivos móveis.
- **Em telas médias (601px a 991px)**: é exibida a imagem de tamanho padrão.
- **Em telas grandes (a partir de 992px)**: permanece a imagem padrão em layout centralizado.

---

Responsividade com Media Queries

Este projeto usa três breakpoints principais:

```css
@media (max-width: 600px) {
    /* Estilos para dispositivos móveis */
}

@media (min-width: 601px) and (max-width: 991px) {
    /* Estilos para tablets ou telas médias */
}

@media (min-width: 992px) {
    /* Estilos para desktops */
}

Tecnologias utilizadas
HTML5

CSS3

Media Queries

#Objetivo
O objetivo deste projeto é demonstrar, de forma prática e visualmente agradável, como CSS Media Queries funcionam e como podem ser aplicadas para criar experiências adaptáveis em diferentes dispositivos.