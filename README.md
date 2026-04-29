# GeoReDUS: Compatibilização dos dados geoespaciais das escolas ao longo do tempo
<!-- badges: start -->
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
<!-- badges: end -->

<a href="https://www.redus.org.br/georedus" target="_blank">
  <img align="right" 
       src="images/georedus-logo.svg" 
       alt="GeoReDUS logo" 
       width="220">
</a>

Este repositório apresenta o procedimento utilizado para a compatibilização e georreferenciamento das escolas brasileiras a partir dos microdados do Censo Escolar e do Catálogo de escolas.
Para acessar o procedimento, veja: https://georedus.github.io/inep-esc-geo/


## Reprodutibilidade
O procedimento proposto foi desenvolvido na linguagem R utilizando o sistema de publicação Quarto. Para garantir resultados consistentes, optou-se por utilizar o pacote renv (https://rstudio.github.io/renv/) para o gerenciamento e a restauração do mesmo ambiente do R utilizado para os indicadores presentes na plataforma.


## O que é a Georedus?
Vinculada a organizações e pessoas da sociedade civil que atuam em rede para construir um futuro mais sustentável para as cidades brasileiras, a Georedus é uma plataforma para a visualização e disponibilização, de forma aberta e gratuita, de dados georreferenciados a nível intramunicipal. 

Ao integrar informações de diferentes fontes em um único local, de forma simples por meio de um "mapa interativo", a plataforma disponibiliza dados de diferentes temas, como características populacionais, demografia, saúde, educação, infraestrutura e serviços urbanos e emergências climáticas. O objetivo é apoiar gestores, técnicos e cidadãos para a construção de políticas públicas mais inclusivas, sustentáveis e diversas.

## Agradecimentos

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <a href="https://centrodametropole.fflch.usp.br">
        <img src="imagens/cem-icon.svg" width="190">
      </a>
    </td>
    <td width="70%" valign="middle">
      Este trabalho foi desenvolvido com o apoio do 
      <strong>Centro de Estudos da Metrópole</strong> 
      (<a href="https://centrodametropole.fflch.usp.br/">CEM</a>), 
      sediado na 
      <strong>Faculdade de Filosofia, Letras e Ciências Humanas</strong> 
      (<a href="https://www.fflch.usp.br/">FFLCH</a>) da 
      <strong>Universidade de São Paulo</strong> 
      (<a href="https://www5.usp.br/">USP</a>) e no 
      <strong>Centro Brasileiro de Análise e Planejamento</strong> 
      (<a href="https://cebrap.org.br/">CEBRAP</a>).
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <a href="https://fapesp.br/">
        <img src="imagens/fapesp-logo.svg" width="160">
      </a>
    </td>
    <td width="70%" valign="middle">
      Este estudo contou com financiamento da 
      <strong>Fundação de Amparo à Pesquisa do Estado de São Paulo</strong> 
      (<a href="https://fapesp.br/">FAPESP</a>), Brasil. 
      Processo nº 
      <a href="https://bv.fapesp.br/pt/bolsas/232814/analise-da-producao-de-evidencias-geoespaciais-para-politicas-publicas/">
        2025/15643-1
      </a>.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <a href="https://orioro.design/">
        <img src="imagens/orioro-logo.svg" width="190">
      </a>
    </td>
    <td width="70%" valign="middle">
      Este trabalho foi desenvolvido com o apoio do 
      <strong>Instituto ORI:ORO</strong>
      (<a href="https://orioro.design/">ORI:ORO</a>).
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <a href="https://www.giz.de/en/pt-br/brasil/">
        <img src="imagens/cop-giz-logo.svg" width="190">
      </a>
    </td>
    <td width="70%" valign="middle">
      Este trabalho foi desenvolvido com o apoio da 
      <strong>Cooperação Brasil-Alemanha para o Desenvolvimento Sustentável</strong>,
      por meio da
      <strong>Deutsche Gesellschaft für Internationale Zusammenarbeit</strong>
      (<a href="https://www.giz.de/en/pt-br/brasil">GIZ</a>).
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="30%" align="center" valign="middle">
      <a href="https://fnp.org.br/index.php">
        <img src="imagens/fnp-logo.svg" width="190">
      </a>
    </td>
    <td width="70%" valign="middle">
      Este trabalho foi desenvolvido com o apoio da
      <strong>Frente Nacional de Prefeitas e Prefeitos</strong>
      (<a href="https://fnp.org.br/index.php">FNP</a>).
    </td>
  </tr>
</table>