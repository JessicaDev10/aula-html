
<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Dicionrio_HTML_0"></a>Dicionário HTML</h1>
<p class="has-line-data" data-line-start="3" data-line-end="4">INICIAL DA SEMÂNTICA</p>
<h1 class="code-line" data-line-start=5 data-line-end=6 ><a id="DOCTYPE__DOCTYPE_5"></a>DOCTYPE:  &lt;!DOCTYPE&gt;</h1>
<pre><code> &lt;!DOCTYPE&gt; é a primeira linha do documento HTML. Ele informa ao navegador qual versão do documento HTML que está escrito para que o navegador saiba o que esperar.
 
  PS.: A declaração não é uma tag HTML. É uma “informação” para o navegador sobre qual tipo de documento esperar.
  
  PS.: BASTA APENAS DIGITAR: SHIFT e ! E DAR ENTER QUE ELE IRÁ GERAR AUTOMATICAMENTE.
  
  PS.: &quot;En&quot; está na lingua inglesa! Alterá-la para: &quot;pt-br&quot; na qual estará em liguagem nacional. 
  
  PS.: Em &quot;&gt;Document&lt;&quot; adicionar o nome que desejar para representar o domínio do site.
 
  PS.: Para linkar o CSS  com o HTML, adiconar: &lt;link rel=&quot;stylesheet&quot; href=&quot;./NOME DA SUA PASTA&quot;&gt;
</code></pre>
<h2 class="code-line" data-line-start=18 data-line-end=19 ><a id="EXEMPLO_18"></a>EXEMPLO:</h2>
<pre><code>  &lt;!DOCTYPE html&gt;
  &lt;html&gt;
  &lt;head&gt;
  &lt;title&gt;ADICIONE AQUI O TÍTULO DO DOCUMENTO&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
  ADICIONE AQUI O CONTEÚDO DO DOCUMENTO.
  &lt;/body&gt;
  &lt;/html&gt;
</code></pre>
<h1 class="code-line" data-line-start=31 data-line-end=32 ><a id="HTML_comment__COMENTE_O_QUE_QUISER__31"></a>HTML comment : &lt;!COMENTE O QUE QUISER&gt; &lt;!–&gt;</h1>
<pre><code> A tag comment &lt;!–&gt; é usada para inserir comentários no código-fonte. Os comentários não são exibidos nos navegadores.
 
 PS.: Pode-se usar comentários para explicar seu código, o que pode ajudá-lo a editar o código-fonte posteriormente. Isso é especialmente útil se você tiver muito código.
</code></pre>
<h2 class="code-line" data-line-start=37 data-line-end=38 ><a id="EXEMPLO_37"></a>EXEMPLO:</h2>
<pre><code>  &lt;!--Este é um comentário--&gt;
  &lt;!--Comentários não são exibidos no navegador--&gt;
  &lt;p&gt;Este é um parágrafo &lt;/p&gt;
</code></pre>
<h1 class="code-line" data-line-start=46 data-line-end=47 ><a id="TAGS_46"></a>TAG’S</h1>
<h1 class="code-line" data-line-start=49 data-line-end=50 ><a id="META__META_49"></a>META:  &lt;META&gt;</h1>
<pre><code> &lt;meta&gt; É apenas uma parte do algoritmo para determinar o conjunto de caracteres de uma página que os navegadores aplicam. 

  A tag HTML &lt;meta&gt; contém informações ou metadados que não são diretamente visíveis na página da Web, mas são usados por navegadores e mecanismos de pesquisa.
  
  
  PS.: O conteúdo da tag &lt;meta&gt; não é visível em seu navegador, mas pode ser analisado pela máquina.
  
  PS.: Eles são usados apenas para fornecer informações adicionais sobre o documento HTML.
  
  PS.: As tags &lt;meta&gt; são adicionadas ao nosso documento HTML para fins de Search Engine Optimization.
  
  PS.: Eles são adicionados dentro da tag &lt;head&gt; e são usados por navegadores, mecanismos de pesquisa e outros serviços da web.


  Através da tag &lt;meta&gt;, o designer pode controlar a viewport.
  A sintaxe mais usada para a meta tag é:

 (Viewport, Description, keywords, Author e Charset).

 Veja no código abaixo:

&lt;head&gt;
&lt;meta charset=&quot;utf-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;meta name=&quot;description&quot; content=&quot;Códigos Prontos HTML e CSS Para agilizar o seu tempo&quot;&gt;
&lt;meta name=&quot;keywords&quot; content=&quot;Html, Css, jQuery, WordPress, Design Responsivo&quot;&gt;
&lt;meta name=&quot;author&quot; content=&quot;www.loopnerd.com.br&quot;&gt;
&lt;/head&gt;
Atributos
</code></pre>
<p class="has-line-data" data-line-start="80" data-line-end="81">charset – Especifica a codificação de caracteres para o documento HTML;</p>
<p class="has-line-data" data-line-start="82" data-line-end="83">content – Especifica o valor associado ao atributo http-equiv ou name;</p>
<p class="has-line-data" data-line-start="84" data-line-end="85">http-equiv – Fornece um cabeçalho HTTP para a informação/valor do atributo content;</p>
<p class="has-line-data" data-line-start="86" data-line-end="87">name – Especifica um nome para os meta dados;</p>
<h1 class="code-line" data-line-start=91 data-line-end=92 ><a id="TAG_A_A_91"></a>TAG A: &lt;A&gt;</h1>
<pre><code>A tag HTML &lt;a&gt; define um hiperlink para uma URL ou um destino no documento HTML.

A tag &lt;a&gt; em HTML é usada para criar um hiperlink na página da web. Este hiperlink é usado para vincular a página da Web à outras páginas. 

É usado para fornecer uma referência absoluta ou uma referência relativa como seu valor “href”.


## EXEMPLO: 

  &lt;a&gt; href = &quot;contato.html&quot;&gt; Contato &lt;/a&gt;
  
  texto entre a abertura &lt;a&gt; e o fechamento &lt;/a&gt; aparecerá como o texto do hiperlink (ou seja: sublinhado)
  
  Caso deseje que o recurso seja carregado em uma nova janela, use o atributo target=”_blank”. Pode descrever seu hiperlink da seguinte forma:
  
  &lt;a href=&quot;www.google.com&quot; target=&quot;_blank&quot;&gt;Google&lt;/a&gt;
  
  O atributo mais importante do &lt;a&gt; elemento é o href atributo, que indica o destino do link.
  
  Por padrão, os links aparecerão da seguinte forma em todos os navegadores:
  
  Um link não visitado está sublinhado e azul;
  Um link visitado é sublinhado e roxo;
  Um link ativo está sublinhado e vermelho;
</code></pre>
<p class="has-line-data" data-line-start="138" data-line-end="139">A tag &lt;a&gt; em HTML é usada para criar um hiperlink na página da web. Este hiperlink é usado para vincular a página da Web a outras páginas da Web. É usado para fornecer uma referência absoluta ou uma referência relativa como seu valor “href”.</p>
<p class="has-line-data" data-line-start="140" data-line-end="141">Veja o exemplo no código HTML abaixo:</p>
<p class="has-line-data" data-line-start="143" data-line-end="144">A tag HTML &lt;a&gt; define um hiperlink para uma URL ou um destino no documento HTML.</p>
<p class="has-line-data" data-line-start="145" data-line-end="146">A tag &lt;a&gt; em HTML é usada para criar um hiperlink na página da web. Este hiperlink é usado para vincular a página da Web a outras páginas da Web. É usado para fornecer uma referência absoluta ou uma referência relativa como seu valor “href”.</p>
<p class="has-line-data" data-line-start="147" data-line-end="148">Veja o exemplo no código HTML abaixo:</p>
<p class="has-line-data" data-line-start="151" data-line-end="152">Veja o exemplo no código HTML abaixo:</p>
<h1 class="code-line" data-line-start=154 data-line-end=155 ><a id="TAG_A_A_154"></a>TAG A: &lt;A&gt;</h1>
<pre><code> A tag comment &lt;!–&gt; é usada para inserir comentários no código-fonte. Os comentários não são exibidos nos navegadores.
 
 PS.: Pode-se usar comentários para explicar seu código, o que pode ajudá-lo a editar o código-fonte posteriormente. Isso é especialmente útil se você tiver muito código.
</code></pre>
<h1 class="code-line" data-line-start=184 data-line-end=185 ><a id="Dicionrio_HTML_184"></a>Dicionário HTML</h1>
<h2 class="code-line" data-line-start=186 data-line-end=187 ><a id="DICIONRIO_TECH_DEV_186"></a>DICIONÁRIO TECH DEV</h2>
<p class="has-line-data" data-line-start="188" data-line-end="189">INICIAL DA SEMÂNTICA</p>
<h1 class="code-line" data-line-start=190 data-line-end=191 ><a id="DOCTYPE__DOCTYPE_190"></a>DOCTYPE:  &lt;!DOCTYPE&gt;</h1>
<pre><code> &lt;!DOCTYPE&gt; é a primeira linha do documento HTML. Ele informa ao navegador qual versão do documento HTML que está escrito para que o navegador saiba o que esperar.
 
  PS.: A declaração não é uma tag HTML. É uma “informação” para o navegador sobre qual tipo de documento esperar.
  
  PS.: BASTA APENAS DIGITAR: SHIFT e ! E DAR ENTER QUE ELE IRÁ GERAR AUTOMATICAMENTE.
  
  PS.: &quot;En&quot; está na lingua inglesa! Alterá-la para: &quot;pt-br&quot; na qual estará em liguagem nacional. 
  
  PS.: Em &quot;&gt;Document&lt;&quot; adicionar o nome que desejar para representar o domínio do site.
 
  PS.: Para linkar o CSS  com o HTML, adiconar: &lt;link rel=&quot;stylesheet&quot; href=&quot;./NOME DA SUA PASTA&quot;&gt;
</code></pre>
<h1 class="code-line" data-line-start=223 data-line-end=224 ><a id="TAGS_META_223"></a>TAG’S META</h1>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Elementos</th>
<th>Definição</th>
</tr>
</thead>
<tbody>
<tr>
<td>&lt;meta&gt;</td>
<td>É apenas uma parte do algoritmo para determinar o conjunto de caracteres de uma página que os navegadores aplicam.</td>
</tr>
<tr>
<td>OneDrive</td>
<td>[plugins/onedrive/README.md][PlOd]</td>
</tr>
<tr>
<td>Medium</td>
<td>[plugins/medium/README.md][PlMe]</td>
</tr>
<tr>
<td>Google Analytics</td>
<td>[plugins/googleanalytics/README.md][PlGa]</td>
</tr>
<tr>
<td>&lt;meta&gt;</td>
<td>É apenas uma parte do algoritmo para determinar o conjunto de caracteres de uma página que os navegadores aplicam.</td>
</tr>
<tr>
<td>OneDrive</td>
<td>[plugins/onedrive/README.md][PlOd]</td>
</tr>
<tr>
<td>Medium</td>
<td>[plugins/medium/README.md][PlMe]</td>
</tr>
<tr>
<td>Google Analytics</td>
<td>[plugins/googleanalytics/README.md][PlGa]</td>
</tr>
<tr>
<td>&lt;meta&gt;</td>
<td>É apenas uma parte do algoritmo para determinar o conjunto de caracteres de uma página que os navegadores aplicam.</td>
</tr>
<tr>
<td>OneDrive</td>
<td>[plugins/onedrive/README.md][PlOd]</td>
</tr>
<tr>
<td>Medium</td>
<td>[plugins/medium/README.md][PlMe]</td>
</tr>
<tr>
<td>Google Analytics</td>
<td>[plugins/googleanalytics/README.md][PlGa]</td>
</tr>
</tbody>
</table>
  

 
 
 
 
 
 
