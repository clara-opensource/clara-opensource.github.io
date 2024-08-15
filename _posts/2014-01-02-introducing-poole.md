---
layout: post
title: Uma análise de grupos de pesquisa trabalhando com veículos autônomos em LatAm
---

Muitas universidades e institutos na América Latina trabalham com o desenvolvimento de veículos autônomos, especialmente drones e robôs. Este mapeamento serve para navegar entre possíveis parceiros para o CLARA na indústria acadêmica.

-----

Para localizar possíveis parceiros para o CLARA, realizamos uma ampla busca em largura de artigos científicos que foram publicados e mapeados pelo Scopus. Aplicamos, então, diversos procedimentos de ciência de dados para agregar os dados em um mapa de Choropleth, mostrando a densidade por cada região, e assim alcançando os grupos destas universidades-chave que podem contribuir com a pesquisa na América Latina.

O mapeamento aconteceu aplicando a Query abaixo no Scopus:


{% highlight js %}
(TITLE-ABS-KEY(ADAS) OR TITLE-ABS-KEY("autonomous driving") OR TITLE-ABS-KEY("self-driving cars"))
{% endhighlight %}

### Onde na América Latina é realizada pesquisa de autonomia veicular?

<iframe src="public/largest_countries.html" width="100%" height="500px" frameborder="0"></iframe>