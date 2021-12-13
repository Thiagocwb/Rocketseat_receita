# Rocketseat_desafioReceita

# 💻 Sobre o desafio

Nesse desafio você vai construir a estrutura HTML da página de receita. Para isso, é necessário conhecer o básico de HTML, caso você ainda não tenha feito os cursos do Discover ou queira fazer uma revisão, segue abaixo uma lista dos cursos que podem te ajudar a resolver esse desafio.

- O guia estelar de HTML
"HTML é a base de qualquer website ou aplicação web."
    
    [](https://app.rocketseat.com.br/node/o-guia-estelar-de-html)
    
- Posso ver e ouvir o HTML - Imagens
"Existem muitos elementos de media no HTML incluindo áudio, imagens e vídeo."
    
    [](https://app.rocketseat.com.br/node/posso-ver-e-ouvir-o-html/group/images/lesson/images)
    
- HTML Semântico (header, section, footer)
"Entenda a semântica dos elementos e acessibilidade do HTML."
    
    [](https://app.rocketseat.com.br/node/html-que-faz-sentido-para-todos)
    

## Como deve ficar a página ao final?

Ao finalizar o desafio você vai ter um resultado parecido com o da imagem abaixo. 

Lembrando que as imagens e textos abaixo são ilustrativos e você pode adicionar seu próprio conteúdo conforme as instruções acima.

![receita-html.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5aadcb4-02e8-4c75-8ea1-7f69fd1e3cb2/receita-html.png)

### Bora lá?

## Iniciando o projeto

Para iniciar o projeto devemos criar a estrutura HTML base. Você deve iniciar **criando a pasta** onde vai colocar os arquivos do projeto e dentro dela você já pode criar o arquivo **index.html** que é onde vamos escreve o HTML da página da receita.

Para criar a estrutura base do HTML no Visual Studio Code, você pode digitar `!` e `TAB` em seguida. Feito isso, você vai ficar com uma estrutura parecida com o código abaixo:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>

  </body>
</html>
```

## Construindo a estrutura HTML da página

Nessa seção você vai encontrar as instruções e dicas para resolver o desafio.

Então, bora codar! 👨‍💻👩‍💻

- A receita deve ter um **título**, para isso você pode usar uma das tags de heading (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`).
    
    <aside>
    💡 Você deve escolher a tag que faz mais sentido como **título principal** da página.
    
    </aside>
    
- A receita deve ter uma **imagem** ilustrativa.
    - Adicione também uma **legenda** para a imagem.
    
    <aside>
    💡 Para adicionar uma legenda na imagem você pode usar as tags `figure` e `figcaption` como no exemplo abaixo:
    
    </aside>
    
    ```html
    <figure>
       <img src="https://unsplash.com/photos/dEUyLofZe5o" alt="Texto descritivo da imagem" />
       <figcaption>Adicionar aqui a legenda da imagem</figcaption>
    </figure>
    ```
    
    <aside>
    💡 Sites onde você pode encontrar imagens grátis para usar nos seus projetos: [Unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/pt-br/), [Pixabay](https://pixabay.com/pt/).
    
    </aside>
    
- Cada lista deve ter um **subtítulo** (`Ingredientes` e `Modo de preparo`) .
- Os ingredientes devem ser apresentados como uma **lista não ordenada** `<ul>`.
- O modo de preparo deve ser apresentado como uma **lista ordenada** `<ol>`.
- Deve ter uma seção `Informações adicionais` com um **parágrafo** com a **descrição da receita.**
- No final da receita deve ter um **rodapé** com seus créditos.
<<<<<<< HEAD
    - Pode direcionar o **link** para seu repositório do Github. (opcional)
=======
    - Pode direcionar o **link** para seu repositório do Github. (opcional)
>>>>>>> 33801dd (Alteração no README.md)
