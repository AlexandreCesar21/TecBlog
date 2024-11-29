<h1>TecBlog: O Seu Blog de Tecnologia</h1>

<p>
  O TecBlog é um site fictício desenvolvido com HTML e CSS para explorar conceitos de criação de 
  layouts e estilização responsiva. Ele apresenta uma estrutura de blog com postagens sobre temas tecnológicos, 
  links de navegação e uma interface amigável para exibição de conteúdos.
</p>



<h3>Funcionalidades</h3>
<p>• Cabeçalho com o logo e menu de navegação para diferentes categorias.
</p>
<p>• Seção principal para exibir postagens do blog.
</p>
<p>• Barra lateral para postagens recentes e categorias.
</p>
<p>• Rodapé com informações de copyright.
</p>
<p>• Estilo visual consistente com cores vibrantes e texto legível.
</p>


<h3>Estrutura de Arquivos
</h3>
<p>• <code>index.html:</code> Estrutura principal do site.
</p>
<p>• <code>style.css:</code> Folha de estilo utilizada para formatar o layout e design.</p>
<p>• <code>Imagens/:</code> Pasta onde são armazenadas as imagens utilizadas no site.
</p>

<h3>Tecnologias Utilizadas
</h3>
<p>• <b>HTML5:</b> Para estruturar o conteúdo do site.</p>
<p>• <b>CSS3:</b> Para estilizar o site com cores, layout e formatação.
</p>

<h3>Demonstração do Layout
</h3>
<h3>Cabeçalho</h3>
<p>• O cabeçalho possui uma área para o logo e um menu horizontal estilizado.</p>
<p>• Links de navegação mudam de cor ao passar o cursor.
</p>

<h3>Área Principal</h3>
<p>• <b>Postagens:</b> Exibem título, data, imagem e texto de pré-visualização com link "Leia mais".
/p>
<p>• <b>Barra Lateral:</b> Inclui postagens recentes e links para categorias.
</p>



<h3>Rodapé
</h3>

<p>• Simples e centralizado, com direitos autorais.
</p>



<h3>Principais Estilizações no CSS</h3>
<p><b>1. Reset de Estilo:</b></p>

```
* {
    margin: 0;
    padding: 0;
}

```
<p>Remove margens e paddings padrão para facilitar o controle do layout.</p>

<p><b>2. Cores e Tipografia:</b></p>

<p>• <b>Cor de fundo do cabeçalho:</b> #f7b600.</p>
<p>• <b>Fonte primária:</b> Arial, Helvetica, sans-serif.
</p>

<p><b>3. Menu de Navegação:</b></p>
<p>• Links possuem transição de cor e efeitos de hover:</p>

```
#area-cabecalho a:hover {
    color: #f7b600;
    background: #fff;
    text-decoration: none;
}

```

<p><b>4. Layout Principal:</b></p>

<p>• Uso de float para dividir as áreas:</p>

```
#area-postagens {
    width: 660px;
    float: left;
}
#area-lateral {
    width: 240px;
    float: right;
}

```



<p><b>5. Estilização das Postagens:</b></p>

<p>• Área principal:</p>

```
.postagem {
    padding: 20px;
    margin-bottom: 20px;
    background: white;
}

```

<p>• Barra lateral:</p>

```
.conteudo-lateral {
    background: white;
    padding: 10px;
    margin-bottom: 20px;
}

```






















