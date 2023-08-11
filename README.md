# Guia de estudo HTML

## Semântica

* Em HTML, por exemplo, o ``<h1>`` é um elemento semântico, que fornece o texto que envolve a representação (ou o significado) de "um cabeçalho de nível superior em sua página".

## Tags

* A tag é usada para criar um elemento. O nome de um elemento HTML é o nome usado entre colchetes angulares como ``<p>`` para criar parágrafos. Perceba que ao fechar uma tag ela tem uma barra antes de seu nome, ``</p>``, e que em elementos vazios a tag final não é requirida e nem permitida


## Classes

* O atributo "Class" é uma lista das classes de um elemento, separada por espaços. Classes permitem a CSS e Javascript selecionar e acessar elementos epecíficos através dos seletores de classe ou funcções como o metodo DOM → [[Conheça o Metodo DOM](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)] 


## ID

* O atributo ID define um identificador exclusivo que deve ser único por todo o documento. Seu objetivo é identificar o elemento ao navegar por âncoras (usando um identificador de fragmento), quando utilizar scripts ou estilizando (com CSS).

* O valor deste atributo não deve conter lacunas (espaços, tabulações etc.). Navegadores tratam IDs inadequadas que contenham lacunas como se as lacunas fossem parte do ID. Em contraste com o atributo class, que permite múltiplos valores separados por espaço, os elementos podem ter somente um único ID.


## Section 

* Esse elemento representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo. Serve para dividir o conteúdo em diferentes seções, que podem conter elementos como ``<header>`` ou ``<article>``


#### Exemplo de Tag

    <p>Aqui é uma tag de parágrafro.</p>


#### Exemplo de Classe

    <div class="blue"></div>


#### Exemplo de ID

    <button id="botao-um">Um</button>


#### Exemplo de Section

    <section id="rock"> <h2>Rock </h2> --elementos article ou header podem vir aqui-- </section>











