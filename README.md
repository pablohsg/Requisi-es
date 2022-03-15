# Requisições
Projeto de requisicoes


Para fazer uma requisição utilizando o *fetch* no java script basta utilizar o código abaixo


```jsx
fetch("https://pablohsg.github.io/Requisicoes/API/produtos.json",options)
.then(response => response.json())
.then(json => {
    console.log(json)
})
.catch(erro => {
    console.log("Erro\n" + erro)
});
```
