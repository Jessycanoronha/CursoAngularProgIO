# Styleguide

Do - realmente deve seguir

consider - Considere

avoid -  Evitar

 why- por que. Razões para seguir as recomendações

Estrutura de arquivos

arquivos ter no máximo 400 linhas

funções n terem mais de 75 linhas

Separar arquivos por tracinhos

bootstraping - evitar colocar a lógina no main.ts

kebab-case nos selectors

ler o styleguide do angular

Promises vs Observables

API trabalha de forma assincrona

callback

promise - promessa, vou retornar alguma coisa

then - chamar quando ela terminou de processar e está te respondendo. Pode ser erro ou sucerro

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/94f5a900-a4ad-4bde-b9ad-51ea98c3c98d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/94f5a900-a4ad-4bde-b9ad-51ea98c3c98d/Untitled.png)

Promise é um callback simples

Depois do erro acabou, mesmo tratando. Resposta que no tempo certo te dá um resultado ou erro

Observable - Objeto completo, pegada reativa.

é uma promise, pode ser convertida em promise

Pode te retornar dados e continuar te retornando.

Quando vc faz o subscribe vc pode receber  os dados sempre que tiver.

O observable ao receber erro, ela morre.

Vc pode cancelar o observable, tem o retry(), que é tentar novamente em caso de erro.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9f3c7a7b-78d4-4324-9bbd-d8a679408c11/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9f3c7a7b-78d4-4324-9bbd-d8a679408c11/Untitled.png)

Vc pode fazer push e pull no observable.

this.minhaPromise('Jéssyca')

.then(result => console.log(result))