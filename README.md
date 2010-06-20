# Material de Treinamento Fundamentos jQuery #
Este reposit�rio cont�m em evolu��o o material fonte para minhas turmas de Fundamentos jQuery, incluindo exerc�cios, solu��es e um livro web-based.

Se voc� est� procurando pela �ltima vers�o do livro, baixe a vers�o [mais recente](http://github.com/rmurphey/jqfundamentals/downloads) e navegue em /book/release/html.

## Contributing ##
Eu liberei este material sob a licen�a Creative Commons Attribution-Share Alike 3.0 US porque eu estou ansioso para ver outras pessoas contribuir nele. Pull requests s�o bem vidas e encorajadas!

O conte�do do livro � escrito em [DocBook 5.0](http://www.docbook.org/), que � ligeiramente doloroso para escrever devido � falta de bons editores gratuitos de XML, mas gera todo tipo de sa�da, incluindo HTML e PDF. Eu usei a vers�o free do [XMLEditor](http://www.xmlmind.com/xmleditor/) para gerar os arquivos dos cap�tulos.

Se voc� est� interessado em contribuir, mas n�o quer lidar com o DocBook, fale comigo e n�s podemos trabalhar em algo diferente. Tamb�m, se voc� tiver conte�do existente que voc� ache que pode ser bom incluir no livro, fale comigo tamb�m! Voc� ir�, claro, ser creditado por qualquer contribui��o.

A seguir, uma lista do que h� pra fazer no livro e no projeto.

### TODO ###

#### Cap�tulos do livro ####
*	Escrever c�digo test�vel
*	Teste unit�rio com QUnit
*	Melhores pr�ticas para performance (refer to http://paulirish.com/perf)
* 	Cria��o de plugins
* 	Ferramentas para build & gerenciamento de depend�ncia [RequireJS](http://requirejs.org/)
*	Eventos customizados

#### Geral ####
*   A sa�da em PDF � decente, mas cont�m falhas. Se voc� est� interessado em resolve-las, fa�a por favor :) Por enquanto eu considero bom o bastante.
*   Pelo fato de eu escrever JavaScript, n�o shell scripts, os shell scripts para gera��o de HTML e PDF podem ser sem d�vida melhorados, especialmente por que h� algumas duplica��es entre eles.

## Usando este material ##
Por causa da licen�a, voc� � pode usar este material � vontade; Se voc� usa-lo para dar aulas, eu adoraria saber sobre.

## Gerando o HTML ##
No diret�rio /book, execute:

`./scripts/install.sh`

Depois execute:

`./scripts/publish.sh`

`./scripts/publish-pdf.sh`

# Copyright & Licenciamento #
Este material � licenciado por Rebecca Murphey sob [Creative Commons Attribution-Share Alike 3.0 United States license](http://creativecommons.org/licenses/by-sa/3.0/us/). Voc� � livre para copiar, distribuir, transmitir, modificar este trabalho, desde que voc� referencie Rebbeca Murphey como autor original e referencie [este reposit�rio](http://github.com/rmurphey/jqfundamentals). Se voc� alterar, transformar, ou construir sob este trabalho, voc� deve distribuir o trabalho resultante sob a mesma licen�a, similiar ou compat�vel. Qualquer uma das condi��es acima podem ser dispensadas se voc� conseguir permiss�o do detentor da copiright. Para qualquer reuso ou distribui��o, voc� deve deixar claro para outros os termos da licen�a deste trabalho. A melhor forma de fazer isso � com um link para [Creative Commons Attribution-Share Alike 3.0 United States license](http://creativecommons.org/licenses/by-sa/3.0/us/).