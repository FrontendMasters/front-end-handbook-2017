# Aprenda sobre Navegadores Web

> Um navegador web (normalmente chamado de navegador) é uma aplicação de software para recuperar, apresentar e percorrer recursos de informação na Internet. Um recurso de informação é identificado por um Identificador Uniforme de Recursos (URI/URL) e pode ser uma página web, imagem, vídeo ou outro conteúdo. Hyperlinks presentes em recursos permitem que os usuários naveguem facilmente em seus navegadores para recursos relacionados. Embora os navegadores tenham principalmente a intenção de usar a Internet, eles também pode ser utilizados para acessar informações fornecidas por servidores web em redes de computador privadas ou arquivos em sistemas de arquivos.

><cite>&#8212; [Wikipedia](https://pt.wikipedia.org/wiki/Navegador_web)</cite>


##### Os [navegadores mais utilizados](https://www.sitepoint.com/browser-trends-september-2016-browser-wars/) (em qualquer dispositivo) são:

1. [Chrome](http://www.google.com/chrome/) (engine: [Blink](https://en.wikipedia.org/wiki/Blink_%28layout_engine%29) + [V8](https://en.wikipedia.org/wiki/V8_%28JavaScript_engine%29))
2. [Firefox](https://www.mozilla.org/en-US/firefox/new/) (engine: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) + [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
3. [Internet Explorer](http://windows.microsoft.com/en-us/internet-explorer/download-ie) (engine: [Trident](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29) + [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))
4. [Safari](https://www.apple.com/safari/) (engine: [Webkit](https://en.wikipedia.org/wiki/WebKit) + [SquirrelFish](https://trac.webkit.org/wiki/SquirrelFish))

![](../images/statcounter.png "http://gs.statcounter.com/#all-browser_version_partially_combined-ww-daily-20160101-20161201-bar")

<cite>Fonte: <a href="http://gs.statcounter.com/#all-browser_version_partially_combined-ww-daily-20160101-20161201-bar">http://gs.statcounter.com/#all-browser_version_partially_combined-ww-monthly-201501-201601-bar</a></cite>

##### Evolução dos Navegadores e Tecnologias Web (isto é, APIs)

* [evolutionoftheweb.com](http://www.evolutionoftheweb.com/) [Ler]
* [Timeline of web browsers (Linha do Tempo dos Navegadores)](https://en.wikipedia.org/wiki/Timeline_of_web_browsers) [Ler]

##### Os Navegadores Sem-Cabeçalho (Headless Browsers) Mais Utilizados São:

* [PhantomJS](http://phantomjs.org/) (engine: [Webkit](https://en.wikipedia.org/wiki/WebKit) + SquirrelFish)
* [SlimerJS](http://slimerjs.org/) (engine: [Gecko](https://en.wikipedia.org/wiki/Gecko_%28software%29) + [SpiderMonkey](https://en.wikipedia.org/wiki/SpiderMonkey_%28software%29))
* [TrifleJS](http://triflejs.org/) (engine: [Trident](https://en.wikipedia.org/wiki/Trident_%28layout_engine%29) + [Chakra](https://en.wikipedia.org/wiki/Chakra_%28JScript_engine%29))

##### Como os Navegadores Funcionam

* [20 Lições que Aprendi Sobre Navegadore e a Web](http://www.20thingsilearned.com/pt-BR/foreword/1) [Ler]
* [Fast CSS: How Browsers Lay Out Web Pages (CSS Rápido: Como os Navegadores Arranjam Páginas Web)](http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml) [Ler]
* [How Browsers Work: Behind the scenes of modern web browsers (Como os Navegadores Funcionam: Por trás das cenas de navegadores web modernos)](http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/) [Ler]
* [So How Does the Browser Actually Render a Website (Então, Como o Navegador Realmente Renderiza um Site)](https://www.youtube.com/watch?v=SmE4OwHztCc) [Assistir]
* [What forces layout / reflow (O que força o leiaute / refluxo)](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) [Ler]
* [What Every Frontend Developer Should Know About Webpage Rendering (O Que Todo Desenvolvedor Frontend Deveria Saber Sobre Renderização de Página Web)](http://frontendbabel.info/articles/webpage-rendering-101/) [Ler]

![](../images/browsers-work.png "http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/")

<cite>Fonte: <a href="http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/">http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/</a></cite>

##### Otimização para Navegadores

* [Browser Rendering Optimization (Otimização de Renderização de Navegador)](https://www.udacity.com/course/browser-rendering-optimization--ud860) [watch]
* [Website Performance Optimization (Otimização de Performance de Site)](https://www.udacity.com/course/website-performance-optimization--ud884) [watch]

##### Comparando Navegadores

* [Comparison of Web Browsers (Comparação de Navegadores Web)](https://en.wikipedia.org/wiki/Comparison_of_web_browsers) [read]

##### Hacks de Navegador

* [browserhacks.com](http://browserhacks.com/) [read]

##### Desenvolvimento para Navegadores

No passado, desenvolvedores front-end gastaram muito tempo fazendo o código funcionar em vários navegadores diferentes. Isso já foi um problema maior do que é atualmente. Hoje, abstrações (por exemplo, jQuery, React, Post-CSS, Babel, etc...) combinadas com navegadores modernos fazem o desenvolvimento para navegadores bastante fácil. O novo desafio não é em qual navegador o usuário irá usar, mas em qual dispositivo ele usará o navegador.

##### Navegadores Sempre-Verdes (Evergreen)

As versões mais recentes da maioria dos navegadores modernos são consideradas navegadores sempre-verdes. Ou seja, em teoria, eles devem atualizar-se automaticamente em silêncio sem solicitar ao usuário. Este movimento em direção a auto-atualização de navegadores tem sido em reação ao lento processo de eliminação de navegadores antigos que não se auto-atualizam.

##### Escolhendo um Navegador [^1]

A partir de hoje, a maioria dos desenvolvedores usam o Chrome e o "Chrome Dev Tools" para desenvolver código front-end. No entanto, todos os navegadores mais utilizados oferecem uma variedade de ferramentas de desenvolvedor. Escolher um para usar para desenvolvimento é uma questão subjetiva. A questão mais importante é saber quais navegadores, em quais dispositivos, você tem que suportar e então testar apropriadamente.

***

###### CONSELHO:

[^1] Eu sugiro usar o Chrome porque as ferramentas de desenvolvedor são consistentemente melhoradas e no momento contém os recursos mais robustos.
