# Curso HTML, CSS e JS Básico 

## Aula 12: Identificação de elementos e o atributo id

### Objetivo da aula

Nesta aula, o objetivo principal é alterar propriedades visuais por meio da identificação de elementos (utilização do atributo id).  

### Conteúdo abordado

Ao observarmos que os textos *EVANDRO* e *FALLEIROS*, que aparecem abaixo do logotipo, compartilham um mesmo tamanho de fonte, poré, o texto *FALLEIROS* está com cor de fonte distinta, podemos utilizar o conceito de **identificação** em conjunto com as relações de dependência existente entre os elementos para que o estilo visual desejado seja compartilhado por mais de um elemento. Para isso, utilizamos o atributo **id**.

O atributo **id** permite que você **identifique** cada elemento **unicamente**. É importante lembrar que **nenhuma identificação pode ser repetida para mais de um elemento**. É só lembrar do CPF no Brasil: cada cidadão tem seu próprio número de identificação, que não é compartilhado por nenhum outro cidadão. 

Durante a aula, o seguinte exemplo foi apresentado:

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

