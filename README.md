# CMS da Comberweb
### Respositório: Lf9q3saa

## Colaboradores:

* Elton Almeida 
* Nicolas Sampaio
* Leonardo Mello
* Paulo Netto

## A Estrutura

A estrutura que proponho em nosso CMS e em nossos sites é essa. 

* css/
* js/
* fonts/
* images/
* includes/
  * config.php
    * Este arquivo contém algumas coisas básicas, como: Caminho Físico do Projeto para ser utilizado em includes ou require, Caminho do Site para fazer include de js/css ou imagens, e outras configurações pertinentes ao projeto. Exemplo:
    ```
		<?php 
			$caminhoSite = 'http://localhost/cmsComberweb/Lf9q3saa';
			$caminhoFisico = '/Library/WebServer/Documents/cmsComberweb/Lf9q3saa';

			$title = 'CMS Padrão';
		?>
    ```
  * head.php
  * header.php
  * footer.php
* index.php
* conteudo.php

###### © Comberweb 2016