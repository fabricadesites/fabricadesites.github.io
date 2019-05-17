---
key: 2
title: Escola de Programas
permalink: /escola/
excerpt: Aprenda conosco, ganhe conosco
image: pic02.jpg
background-image: pic02.jpg
---
{% include post_picwrap.html pos="left" src="/images/pic01.jpg" %}

## APRENDA CONOSCO

Parte fundamental do Projeto Fábrica de Sites é a criação e desenvolvimento de websites para pequenas empresas, profissionais liberais, microempreendedores, que são os verdadeiros patrocinadores. Juntando-se a nossa equipe você irá aprender em poucas semanas (ou menos) a desenvolver, criar e publicar seus próprios websites, ajudando o projeto e incentivando novos membros a participarem.
Oferecemos mentoria no aprendizado para você começar a trabalhar junto a nossa plataforma e obter além do conhecimento adquirido, um retorno financeiro significativo.

### PROJETO PRINCIPAL

{% include post_picwrap.html pos="right" src="/images/meteo40.jpg" %}

Nosso __Projeto Fábrica de Sites__ tem como objetivos principais criar:
 * __Uma rede de cooperação__ dentro de comunidades de baixa renda que já tenham acesso a internet;
 * __Fomentar a economia__ e desenvolver o __conhecimento__ na área de tecnologia voltada para a internet;
 * Ser uma __inspiração__ para novos programadores despertando o interesse pelo conhecimento na área de tecnologias.
 * __Abrir portas__ e __oportunidades__ para quem precisa de uma renda extra (ou básica) sem precisar pagar por isso.

Junte-se a nós e faça parte desse projeto expandindo seu saber, agregando conhecimento e criando uma rede colaborativa de novos amigos!

Desenvolvemos projetos simples de serem executados mas com grande poder de eficácia na criação de páginas para a internet. Com um simples computador antigo (com mais de 10 anos) ou um pequeno Raspberry pi (SBC) você já começa a desenvolver conhecimento e a criar seus próprios trabalhos com o apoio da mentoria do __Projeto Fábrica de Sites__

Baseado na filosofia OpenSource de software livre compartilhamos nosso conhecimento com quem quer aprender a desenvolver softwares e acrescentar junto a sua comunidade.

 > #### Junte-se ao PROJETO FÁBRICA DE SITES e faça parte desse time!
 > Envie uma mensagem atravé do formulário com o assunto (subject) __ESCOLA__ seu _nome_ e _email_ que entraremos em contato passando as informações necessárias para você começar.


<!--{% include post_picwrap.html pos="left" src="/images/telem.jpg" %}-->


***

<!--{%
if site.social.linkedin-square %}
<div class="table-wrapper">
  <table class="alt"><tbody><tr><td style="text-align: center;">Visit my
  <a target="_blank" href="{{ site.social.linkedin-square }}">LinkedIn profile</a></td>
  </tr></tbody></table>
</div>{%
endif %}
{%
if site.categories.eolica %}
<div class="table-wrapper">
  <table>
    <tbody>{%
      include fn_groupsort_reverse.html unsorted=site.categories.eolica groupby='priority' sortby='date'
%}{%  for eolica in sorted_list %}
      <tr>
        <td><b><a href="{{ eolica.url | prepend: site.baseurl }}">{{ eolica.title }}</a></b></td>
        <td>{{ eolica.date | date: "%b %Y" }}</td>
        <td>{{ eolica.excerpt | strip_html | truncatewords: 12 }}</td>
        <td>
          {% include techlist.html %}
        </td>
      </tr>{%
      endfor %}
    </tbody>
  </table>
</div>{%
  if site.eolica_in_progress %}
  <div class="works_inprogress">In-progress, more to come.</div>{%
  endif %}{%
endif
%}-->
