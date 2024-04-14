# Como criar um tema wordpress


# 📋 Índice
 
* Documentação wordpress para criação de temas  <a href="https://make.wordpress.org/themes/">Make wordpress</a> 

* Funções básicas <a href="">Documentação wordpress para criação de temas</a> 

* <a href="https://www.youtube.com/watch?v=ZeDP-rzOnAA&t=403s">Exemplo de HTML de menu</a> - Build A Responsive Website With HTML & CSS Tutorial



* Imagem de hierarquia básica dos arquivos de tema do WordPress"
![Hierarquia básica](https://raw.githubusercontent.com/HeberSilverio/CriarTemaWordpress/main/assets/imagens/Estrutura%20de%20arquivos%20do%20tema.png)

* [A hierarquia de execução dos arquivos de tema do WordPress](https://code.tutsplus.com/the-wordpress-theme-files-execution-hierarchy--wp-23508a) 
![Hierarquia completa](https://raw.githubusercontent.com/HeberSilverio/CriarTemaWordpress/main/assets/imagens/Estrutura%20de%20arquivos%20do%20tema%20completo.png)

### Funções básicas wordpress


```
<body <?php body_class(); ?>>
```
- [body_class](https://developer.wordpress.org/reference/functions/body_class/)
**Uso Básico**

O exemplo a seguir mostra como implementar a tag de modelo body_class em um tema.

~~~wp-includes/post-template.php
<body <?php body_class(); ?>>
~~~


```
<?php get_header(); ?>
```
- [ get_header() ](https://developer.wordpress.org/reference/functions/get_header/)


-  Direcionar para a mesma página 
~~~php
<?php echo esc_url( $recipes_link ); ?>
~~~
Um botão com esse link abaixo direciona para a mesma pagina



* Desafio dia 01 - <a href="">3D Responsive Touch Slider</a> 

- alterar o permalinks para Padrão e depois voltar Nome do Post


### Alterações necessárias após subir para hospedagem

* Mudar tabelas em banco de dados - - mudar no banco de dados em wp_options o siteurl e home para a nova url.

- alterar o permalinks para Padrão e depois voltar Nome do Post


![Alt ou título da imagem](URL da imagem)
[](link)

~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
