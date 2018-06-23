# Curso HTML, CSS e JS Básico 

## Aula 11: Classificação de elementos e o atributo class

### Objetivo da aula

Nesta aula, o objetivo principal é alterar propriedades visuais por meio da classificação de elementos (utilização do atributo class).  

### Conteúdo abordado

Ao observarmos que os textos *FALLEIROS* e *&*, que aparecem abaixo do logotipo, compartilham a mesma cor de fonte, podemos utilizar o conceito de **classificação** para que o estilo visual desejado seja compartilhado por mais de um elemento. Para isso, utilizamos o atributo **class**.

O atributo **class** permite que você possa escrever um conjunto de estilos visuais uma única vez, podendo aplicar esse mesmo estilo para todos os elementos que estão com uma mesma classificação. Durante a aula, o seguinte exemplo foi apresentado:

**Código HTML**
```html

<div>
    <h1>EVANDRO<span class="rosa">FALLEIROS</span></h1>
    <h2>DESENVOLVEDOR <span class="rosa">&</span> DESIGNER</h2>
</div>

```

**Código CSS**
```css

.rosa{
    color: #c44d85;
}

```

Note que ambos elementos *span* apresentam uma mesma classificação (rosa). No código CSS, você pode observar que a seleção destes dois elementos é feita uma única vez, por meio da seleção CSS **.rosa { ... }**. Com isso, todo elemento que tiver um atributo **class** com esse mesmo valor **rosa** irá compartilhar a mesma cor de fonte.

