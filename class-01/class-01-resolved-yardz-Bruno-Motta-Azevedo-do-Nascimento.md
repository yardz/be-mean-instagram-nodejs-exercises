# Node.js - Aula 01 - Exercício
**autor:** Bruno Motta Azevedo do Nascimento
**date:** 23/01/2017

## Explique como um processo síncrono e assíncrono roda no Node.js, dê um exemplo para cada.

Um processo sincrono é um processo em que é executado um passo de cada vez. Ou seja, antes de executar ele espera a execução completa de cada comando para então executar o próximo comando.
  
Já o processo assincrono não espera a execução completa do comando para executar o próximo passo.  

```js

// Código Síncrono
fs.writeFileSync('arquivo.txt', 'Hello World');
console.log('Executa a função síncrona');


// Código Assíncrono 
fs.writeFile('arquivo.txt', 'Hello World', function(error){
    console.log('Executa a função Assíncrona');
});

```

## Como o V8 executa JavaScript? Demonstre 1 exemplo com código ou imagem.

## Qual a diferença entre um sistema single para um multi-thread?

## Como a Thread Pool tem um tamanho padrão de 4, o que acontece se você enviar 5 requisições ao banco?

## Como você venderia o peixe do Node.js na sua empresa para tentar convencer seu chefe da sua adoção?

## Qual a versão do seu `node`?

```js
$ node -v
v7.4.0
```

## Qual a versão do seu `npm`?

```js
$ npm -v
4.1.2
```