<p align="center"><img width="100px" src="/src/img/icon_arroxa.png" alt="logo arroxa"></p>

# Kit Arroxa com Grunt
[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](http://thompsonemerson.mit-license.org/)
[![Build Status](https://travis-ci.org/arroxa/grunt.svg?branch=master)](https://travis-ci.org/arroxa/grunt)
> O [Grunt](http://gruntjs.com/) é uma aplicação javascript que tem como objetivo facilitar sua vida automatizando suas tarefas.
Tarefas como: minificar, concatenar, upload de arquivos e entre tantas outras.

> Em nossas dependências também está incluso o [Bower](http://bower.io/) que é um dos gerenciadores de dependência para front mais utilizado entres os devs.

### Tarefas
- CSS
	- SASS `.sass`
	- Autoprefixer
	- Valida
	- Minifica
	- Remove o CSS não utilizado `não configurado`

- Javascript
	- Valida
	- Mififica

- Imagens
	- Minifica

- Geral
	- BrowserSync
	- Load Task
	- Notify
	- Time Grunt


### Estrutura
##### Desenvolvimento
- src/
	- css/
		- main.sass
	- js/
		- main.js 
	- img/
	- lib/`dependências do bower`
	- index.html

##### Produção
- www/
	- css/
		- main.min.css
	- js/
		- main.min.js 
	- img/
	- lib/`dependências do bower`
	- index.html



### Como usar
- Abra seu terminal/cdn
- Clone o repositório `$ git clone https://github.com/arroxa/grunt.git`
- Acesse a pasta clonada `$ cd grunt`
- Instale as dependências `$ npm install`
- Execute o grunt `$ grunt`
- Pronto! Se tudo ocorrer direitinho seu navegador irá abrir com uma página demo, e depois é só arroxar! ;)


### Contribuir
Ajude-nos a melhorar nossa aplicação. Abra uma [issue](https://github.com/arroxa/grunt/issues/new) ou  envie um `pull request`.
- [Fork nosso repositório!](https://github.com/arroxa/grunt#fork-destination-box)
- Crie sua "feature branch": `git checkout -b minha-nova-feature`
- Comente suas alterações: `git commit -m 'Comentando minha feature'`
- Suba sua branch: `git push origin minha-nova-feature`
- Nos envie seu pull request =D


### Licença
[MIT License](http://thompsonemerson.mit-license.org/) © Emerson Thompson
