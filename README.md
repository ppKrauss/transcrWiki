TranscrWiki
-----------
Repositório de documentos públicos originais e suas transcrições, onde cada documento é um artigo Wiki totalmente auditável.

## Conceitos
* **Scraping de conteúdo**: muitdos dos dados que obtemos de processos de [*data scraping*](https://en.wikipedia.org/wiki/Data_scraping) são na verdade conteúdos, principalmente textual. Caso típico são os arquivos de dados do [Diário Livre](http://devcolab.each.usp.br/do/), que apesar de expressos em CSV tem a cada registro, como informação principal, um documento ou cojunto de documentos (leis, decretos, despachos, contratos, etc. do Diário Oficial).
* **Transcrilções de documentos** "de utilidade pública": livros clássicos como aqueles mantidos pelo [Projeto Gutenberg](https://www.gutenberg.org) ou artigos científicos mantidos pelo [SciELO](http://www.scielo.br/), ou ainda leis, decretos, etc. mantidos pelo [LexML](http://www.lexml.gov.br/desc_acervo.html). O que esses acervos tem em comum é que boa parte dos conteúdos tem origem em OCR e em processamento humano. No caso do Gutemberg quem faz o trabalho é a equipe voluntária do [PGDP](http://www.pgdp.net/c/) (''Distributed Proofreaders'').
* **Cadeia produtiva da transcrição** (carga, tratamento automático, tratamento humano, revisão e homologação): a maior parte dos documentos precisa ser submetida a todas essas etapas de tratamento.
* **TrancrWiki**: é uma Wiki do tipo [Mediawiki](http://www.mediawiki.org) (que pode vir a usar extensões tais como Wikidata e VisualEdit), adaptada para suprir as necessidades de *scraping de conteúdo* e de *transcrição de documentos*, bem como acervo das versões finaos,  controle de versões intermediárias, organização e curadoria do acervo de documentos.

## Objetivo
Este projeto tem por objetivo descrever e subsidiar os procedimentos para criação e manutenção de uma *TranscrWiki*.

## Preparo da Wiki
Ambiente Mediawiki mantido com os seguintes namespaces:
* *transcriwiki*: conteúdo próprio da Wiki tais como manuais e termos de uso, devem ser clonados de wiki para wiki.
* *originais*: conteúdo original de carga, conforme obtido dos originais (depois de convertido para TXT ou HTML)
* *tool*: artigos de controle, categorização, etc. que podem mudar conforme a finalidade mas podem ser clonados ou atualizados separadamente.
* (main): onde estão todos os documentos já convertidos, revisados ou em processo de revisão. Ver [Guia namespaces Mediawiki](http://www.mediawiki.org/wiki/Help:Namespaces#.28Main.29) 

##Preparo de documentos do Diário Livre
... material de http://devcolab.each.usp.br/do/  e 

##Preparo de outros documentos
...


