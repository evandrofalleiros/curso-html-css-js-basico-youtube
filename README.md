# Curso HTML, CSS e JS Básico 

## Aula 12: Identificação de elementos e o atributo id

### Objetivo da aula

Nesta aula, o objetivo principal é alterar propriedades visuais por meio da identificação de elementos (utilização do atributo id).  

### Conteúdo abordado

Ao observarmos que os textos *EVANDRO* e *FALLEIROS*, que aparecem abaixo do logotipo, compartilham um mesmo tamanho de fonte, poré, o texto *FALLEIROS* está com cor de fonte distinta, podemos utilizar o conceito de **identificação** em conjunto com as relações de dependência existente entre os elementos para que o estilo visual desejado seja compartilhado por mais de um elemento. Para isso, utilizamos o atributo **id**.

O atributo **id** permite que você **identifique** cada elemento **unicamente**. É importante lembrar que **nenhuma identificação pode ser repetida para mais de um elemento**. É só lembrar do CPF no Brasil: cada cidadão tem seu próprio número de identificação, que não é compartilhado por nenhum outro cidadão. 

No lado do CSS, a *seleção por identificação* é realizada por meio do caractere *#* seguido do nome da identificação. Durante a aula, o seguinte exemplo foi apresentado:

**Código HTML**
```html

<div id="nome-profissao">
    <h1 id="nome-principal">EVANDRO<span class="rosa">FALLEIROS</span></h1>
    <h2>DESENVOLVEDOR <span class="rosa">&</span> DESIGNER</h2>
</div>

```

**Código CSS**
```css

#nome-profissao h1{
    font-size: 16px;
}

#nome-principal{
    font-weight: 300;
}

```

Note que trabalhamos com a seleção por descendência quando separamos *#nome-profissao h1* por espaço. Nesse caso, fazemos a seleção de todos os elementos h1 descendentes de um elemento com identificação *nome-principal*. Isso,de certa forma, configura um comportamento no qual atributos visuais são compartilhados entre os elementos selecionados. 



