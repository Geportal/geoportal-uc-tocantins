# Geoportal UC Tocantins

Mapas, dados e documentos do estudo para criação de unidade de conservação na Área de Estudo de 1.301,3 km² em Lizarda (TO), Alto Parnaíba (MA) e Balsas (MA). Funatura – Geoprocessamento.

**Site:** https://geportal.github.io/geoportal-uc-tocantins/

Este repositório só publica o site. Os originais ficam no acervo do projeto no Google Drive (pasta GEOPORTAL):

| Pasta no Drive | Conteúdo |
| --- | --- |
| `02_ACERVO` | Originais aprovados, um diretório por camada, com versão |
| `03_PUBLICACAO/site` | O site completo, gerado pelas ferramentas do projeto |
| `03_PUBLICACAO/pacotes_github` | O site em quatro pacotes .zip, que este repositório baixa e publica |

## Como o site é atualizado

O fluxo `Publicar geoportal` (`.github/workflows/publicar.yml`) baixa os quatro pacotes do Drive, junta e publica no GitHub Pages. Ele roda todo dia às 06:23 (horário de Brasília). Para publicar na hora, abra **Actions → Publicar geoportal → Run workflow**.

Nada precisa ser enviado a este repositório quando o site muda: basta regravar os pacotes no Drive com `00_GESTAO/ferramentas/publicacao/empacotar_site.py`.
