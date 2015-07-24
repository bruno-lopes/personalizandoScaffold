# personalizandoScaffold
Projeto que mostra como personalizar as views geradas pelo Scaffold em Grails.

Esse projeto utiliza a versão <b>2.5.0</b> do Grails. Caso você não tenha o ambiente Grails configurado, veja como instalar em http://vaidegrails.com/2015/05/12/como-criar-e-rodar-a-primeira-aplicacao-grails/.

É importante ressaltar que sua aplicação ou plugin deve utilizar o plugin Grails Scaffolding Plugin (https://grails.org/plugin/scaffolding). Para incorporá-lo na sua aplicação/plugin, basta colocar essa linha no seu arquivo <b>BuildConfig.groovy</b>, dentro da closure plugins:

<b>compile ":scaffolding:2.1.2"</b>

Os passos realizados podem ser acompanhados pelos commits, mas basicamente é necessário rodar o comando grails install-templates, o qual terá como objetivo instalar os templates utilizados para o scaffold para criar as páginas de <b>create.gsp, edit.gsp, list.gsp e show.gsp</b>. Esses arquivos serão instalados no diretório src/templates/scaffolding dentro do diretório da sua aplicação ou plugin.

A partir desse ponto, basta alterar os arquivos para personalizá-los conforme você quiser. É possível inclusive alterar o layout utilizado nessas páginas. Exemplos podem ser vistos nos commits (https://github.com/bruno-lopes/personalizandoScaffold/commits/master). A view personalizada nesse projeto foi a create.gsp.

Qualquer dúvida, entre em contato com bruno.eng.comp@gmail.com.
