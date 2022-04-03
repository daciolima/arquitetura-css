# Arquitetura CSS

### Padrão  ATOMIC DESIGNER
- Átomo = Um elemento
- Molécula = Conjunto de elementos dentro de um contexto
- Organismo = Conjunto de moléculas dentro de uma secão
- Template = Conjunto de moléculas na visão de código
- Página = É um template na visão real, ou seja, o que é exibido ao usuario.



### Padrão de nomeclatura(nomes) de classes CSS - BEM
**BLOCK ELEMENT MODIFIER (Bloco - Elemento - Modificador)**

- bloco
- bloco__elemento
- bloco__elemento--modificador (Modificador é usado para customização de um elemento específico)

Obs: Nomes das propriedades CSS é recomendado estarem em ordem alfabetica, com isso facilitando a busca.

Ex de uma estrutura BEM:
```html
<section class="banner">
    <img class="banner__imagem banner__imagem--promocao" src="" />
    <h2 class="banner__titulo">Super Promoção</h2>
</section>
```

Obs:
Quando temos imagens que são apenas ilustrativas, ou seja, não sofrem dinâmica é recomendado ela está numa <div> e sua configuração está no css(background-image: url()), mas se imagem sofrer mudanças a mesma deve está na tag <img>.


