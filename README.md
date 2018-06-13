# Curso HTML, CSS e JS Básico 

## Aula 10: Alterando a tipografia dos links de navegação

### Objetivo da aula

Nesta aula, o foco principal foi a alteração do visual padrão dos links de navegação do menu principal.  

### Conteúdo abordado

Iniciamos, nesta aula, uma séria de alterações referentes à tipografia. Nesse sentido, todas as modificações visuais referentes ao conteúdo escrito serão abordadas gradualmente, aula a aula. Nesta aula, trabalhamos com as seguintes propriedades:

* **color**: permite a alteração da *cor do texto*. **Atenção: não existem as propriedades color-font ou font-color**.
* **font-size**: permite a alteração do *tamanho da fonte* (altura de cada caractere);
* **font-weight**: permite a alteração do *peso da fonte* (negrito, por exemplo);
* **text-decoration**: permite a alteração da *decoração em links de navegação* (aquela linha azul que fica sob os links);



```css

/* Seleção dos elementos a descendentes do elemento nav */
nav a{
    /* Alteração da cor da fonte dos links */
    color: #343434;
    /* Alteração do tamanho da fonte dos links */
    font-size: 14px;
    /* Alteração do peso da fonte para negrito */
    font-weight: bold;
    /* Remoção da linha decorativa sob o link */
    text-decoration: none;
}

```

