Tutorial 
    importe o módulo HTTP usando require('http').
    Crie um servidor HTTP usando http.createServer() e passe uma função de callback que será executada sempre que uma solicitação for recebida.
    Dentro da função de callback, use res.writeHead() para definir o status da resposta como 200 (OK) e o tipo de conteúdo como "text/html; charset=utf-8".
    Crie uma instância de Date() para obter a data atual.
    Formate a data atual para o formato brasileiro (pt-BR) usando toLocaleDateString() e armazene-a em dataFormatada.
    Use res.end() para enviar uma resposta HTML que contenha um cabeçalho <h1> com um tamanho de fonte de 24px e um parágrafo <p> que mostra o nome "Thiago Viel Denadai" e a data formatada.
    Escute por conexões na porta 8012 usando .listen(8012).


