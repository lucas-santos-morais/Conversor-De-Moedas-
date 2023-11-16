# Conversor-De-Moedas-
Iniciado a programar ( utilizando principalmente o java script ).

var valorEmDolar = 64;
var cotacaoDoDolar = 5.32;

//somar +//subtrair - // multiplicar * 
var valorEmReal = valorEmDolar * cotacaoDoDolar;

//numObj.toFixed([dígitos]) - para retornar o numero com casas decimais e reduzir ele na saída
valorEmReal = valorEmReal.toFixed(2);

//o + na formula serve como Concatenação e não como operador
alert("R$" + valorEmReal);
