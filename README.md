# Intoxicações por agrotóxicos no Brasil
![Agencia Pública](https://reporterbrasil.org.br/wp-content/uploads/2020/09/Imagem_regantular_Ag%C3%AAncia-P%C3%BAblica.jpg)

Esse repositório contém códigos em linguagem Python utilizados para realizar a limpeza, pré-processamento e análise exploratória preliminar de uma base de dados obtida do Ministério da Saúde sobre intoxicações exógenas, analisando especificamente as intoxicações por agrotóxicos de uso agrícola. A base original e a pré-processada também são disponibilizadas.

A obtenção, análise e divulgação desses dados fazem parte da iniciativa [Por Trás do Alimento](https://portrasdoalimento.info/): uma parceria entre as organizações jornalísticas Agência Pública e Repórter Brasil que vai investigar como são produzidos os alimentos que comemos e exportamos, além de outros produtos.

## Publicações
Os códigos desse repositório contribuiram para uma série de reportagens:
1. [Agrotóxicos paraquate e glifosato mataram 214 brasileiros na última década, revela levantamento inédito](https://apublica.org/2020/09/exclusivo-agrotoxicos-paraquate-e-glifosato-mataram-214-brasileiros-na-ultima-decada/#Link3)
* [Empresas escondem intoxicações de trabalhadores rurais por agrotóxico](https://apublica.org/2020/09/empresas-escondem-intoxicacoes-de-trabalhadores-rurais-por-agrotoxico/)

## Organização do repositório

**pre-processamento-agrotoxicos.ipynb**: Jupyter Notebook com o código que realiza a limpeza e pré-processamento dos dados, corrigindo a falta de padronização dos nomes das substâncias que causam intoxicações (princípios ativos).

**analise-exploratoria-agrotoxicos.ipynb**: Jupyter Notebook com o código que realiza a análise exploratória preliminar dos dados padronizados.

**bases**: contém a base de dados original obtida do Sistema de Informação de Agravos de Notificação (SINAN) do Ministéro da Saúde obtida através da Lei de Acesso a Informação, além de bases de dados da Anvisa utilizadas para fazer a padronização da base do SINAN.

**bases mapeadas**: contém as bases pré-processadas em duas versões (especificadas no notebook pre-processamento-agrotoxicos.ipynb)

**dicionarios**: utilizados para realizar a padronização da base original para os nomes utilizados pela Anvisa.