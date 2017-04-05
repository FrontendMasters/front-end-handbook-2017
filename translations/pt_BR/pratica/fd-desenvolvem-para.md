# Front-Ends desenvolvem para...

Um desenvolvedor front-end cria HTML, CSS e JavaScript que normalmente é executado na [plataforma web](http://tess.oconnor.cx/2009/05/what-the-web-platform-is) (como um navegador web) e entregue por um dos seguintes sistemas operacionais (SOs):

* Android
* Chromium
* iOS
* OS X
* Ubuntu (ou algum sabor do Linux)
* Windows Phone
* Windows

Esses sistemas operacionais normalmente são executados em um ou mais dos seguintes aparelhos:

* Desktop
* Notebook / laptop / netbook
* Celular
* Tablet
* TV
* Relógio
* Coisas (qualquer coisa que possa iamginar, carros, geladeiras, lâmpadas, termostatos, etc.)

![](../images/growth-iot.jpg "https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/")

<cite>Fonte da imagem: <a href="https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/">https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/</a></cite>

Geralmente falando, tecnologias front-end podem ser executadas nos sistemas operacionais e aparelhos mencionados acima utilizando o seguinte cenário em tempo de execução na plataforma web:

* Um navegador web (exemplos: [Chrome, IE, Safari, Firefox](http://outdatedbrowser.com/pt-br)).
* Um [navegador headless](https://en.wikipedia.org/wiki/Headless_browser) (exemplos: [phantomJS](http://phantomjs.org/)).
* Uma [WebView](http://developer.telerik.com/featured/what-is-a-webview/)/aba do navegador (pense em iframe) embutido em uma aplicação nativa, como um tempo de execução com ponte para APIs nativas. Aplicações WebView normalmente contém uma interface de usuário (UI) construída com tecnologias web como HTML, CSS, e JS. (exemplos: [Apache Cordova](https://cordova.apache.org/), [NW.js](http://nwjs.io/), [Electron](http://electron.atom.io/))
* Uma aplicação nativa construída a partir de tecnologias web que são interpretadas em tempo de execução com uma ponte para APIs nativas. A UI fará uso de partes da UI nativa (como os controles nativos do iOS) e não de tecnologias web. (exemplos: [NativeScript](https://www.nativescript.org/), [React Native](https://facebook.github.io/react-native/))