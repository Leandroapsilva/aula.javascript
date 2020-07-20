# aula.javascript
introduçao ao Javascript

//Javascript integrado com html//

<!DOCTYPE>
<html lang="pt-br">
         <head>
              <title>Minha página</title>
              <meta charset="ulf-8">
         </head>
<body>
         <script>
                alert("Meu  primeiro js")
         </script>
                <h1>Minha página</h1>
</body>
  
  
  
  // Javascript separado do html //

var nome ="Leandro Ap Silva";
var idade = 38;
var idade2 = 10;
var frase = "Japão é o melhor time do mundo";
var n1 = 5;
var n2 = 3;


alert(idade + idade2);
alert("meu primeiro js")
alert(nome + "tem" + idade = "anos");

console.log(nome);
console.log(idade + idade2);
console.log(frase.replece("Brasil e o melhor time do mundo"));

// Erro proposital para saber se deu Debug no código//
//Erro proposital//
console.log(n1 + idade2) 

//arrys e bibliotecas//

var lista ["maça", "pera" , "laranja"];
console.log(lista);
console.log(lista[1]);

//definir qual fruta vou quer na lisa//
alert(lista[1]);
alert(lista[3]);

//para adicionar fruta na lisa//
var lista ["maça", "pera" , "laranja"];
lista.push("uva")
console.log(lista[1]);

//para retirar fruta na lisa//
var lista ["maça", "pera" , "laranja"];
lista.pop("uva")
console.log(lista[1]);

//contidade de itens na lista//
console.log(lista.length);

// elementos ao contrario na lista//
console.log(lista.reverse);


//arrey virando uma string//
console.log(lista[0]);
console.log(lista.tostring());
console.log(lista.join(""))


// define  fruta e cor da fruta na lista//
var fruta = {nome: "maça" , cor: "vermelha'}
console.log(fruta);
alert(fruta.cor);


