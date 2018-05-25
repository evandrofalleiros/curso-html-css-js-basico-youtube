# Curso HTML, CSS e JS Básico

## Aula 09 - Imagens de fundo

### **Objetivo da aula**

Esta aula teve como objetivo principal a inserção de uma imagem de fundo no elemento de cabeçalho.

---

### **Conteúdo abordado**

Nesta aula, foram realizadas algumas modificações no **[style.css](css/style.css)**, afim de colocarmos uma [imagem](assets/fundo.jpg) como fundo no elemento **\<header\>**. Essas são as modificações que fizemos:

```css
header{
    background-image: url(../assets/fundo.jpg);
    background-position: center;
    background-size: cover;    
    /*  */
    height: 580px;
}
```

Quatro propriedades tiveram os seus valores alterados. A seguir, listo e descrevo estas propriedades, assim como os valores anotados no código CSS mostrado anteriormente:

- **background-image**: trata-se de uma propriedade para a **inserção de imagens de fundo** em um elemento. Como valor, você deve passar a *url* (caminho) referente à imagem desejada. Não utilize um caminho absoluto, como *C:\Meus Documentos\Minhas Imagens\fundo.jpg*. Utilize caminhos relativos aos seu projeto. Note que o valor ***url(../assets/fundo.jpg)*** faz com que o seu navegador retorne um diretório (já que o **style.css** está na pasta **css**) e acesse a pasta **assets**, para então abrir o arquivo **fundo.jpg**;
- **background-position**: essa propriedade lhe permite alterar o **posicionamento da imagem de fundo**. No caso, deixei a imagem posicionada ao centro do elemento, tanto na horizontal, quanto na vertical;
- **background-size**: com essa propriedade, você consegue alterar o **tamanho da imagem de fundo**. Utilizei o valor **cover**, que faz com que a imagem "cubra"/ocupe o fundo por completo;
- **height**: por fim, essa propriedade representa a **altura** de um elemento. Utilizei o valor *580px*, que é a medida em *pixels* da altura do cabeçalho que [projetei no Photoshop](portifolio.psd).


---

Qualquer dúvida, entre em contato comigo pelo e-mail evandro.falleiros@ifms.edu.br. Até a próxima aula!