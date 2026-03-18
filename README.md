# teste-avaliacao-2026
//configuração git repositorio 
passo1 criar o repositorio no github, CLONAR O CODIGO DO REPOSITORIO
-----------------------------
ir no git bash
``` 
CD DOCUMENT/
GIT clone "endereço do repositorio tirado do github"
CD   NOME DO REPOSITORIO 
CODE .
```
--------------------------------------------------------------------------------
nos arquivos html criar estrutura basica do documento:
VS CODE
```
H2 TITULO 
BUTTON> ENTRE O BUTTON E O > COLOQUE DOIS ESPAÇOS ASSIM BUTTON ID >
2 PASSO; DEPOIS DE ENTER DENTRO DO ID ESCREVO O NOME DO BUTTON " QUESTAO1 " SE PRECISO FAZER MAIS UM POR QUESTAO 
COLOCAR: PT BR
3 PASSO; SCRIPT SRC 
```
---------EXEMPLO-----------------------------------
```html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>
1 PASSO: <h2>avaliação</h2>
<body>
 2PASSO:   <button id="querstao1" ></button>
<script src="script/avaliacao.js"></script>

    
</body>
</html>
```
-------------------------------------------------------------

formato de atividade
```js 
function exercicios2() {

 ///atividade

    const valorHora = Number(prompt("Digite o valor por hora:"))
    const Horastrabalhadas = Number(prompt("digite suas horas trabalhadas:"))
    alert(valorHora * Horastrabalhadas)

}

const buttonexercicios2 = document.getElementById("exercicios2")
buttonexercicios2.addEventListener('click', () => { exercicios2() })
```













