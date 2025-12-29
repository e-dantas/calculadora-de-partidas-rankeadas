## 2️⃣ **Calculadora de partidas Rankeadas** 🧮🏆

Este é o segundo desafio proposto pela **DIO**, visando reforçar os conhecimentos adquiridos sobre lógica de programação, como o uso de:

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões
- Funções

Com o objetivo de calcular o saldo formado pela quantidade de vitórias e derrotas de um herói e associá-lo a um nível correspondente. No final, uma mensagem será exibida contendo o saldo e o nível do herói.

---

## 📌 Objetivo do Desafio

Criar uma função que:

Calcule o saldo de vitórias (vitórias - derrotas) 

Retorne o saldo obtido pelo cálculo

Criar outra função que:

Utilize uma estrutura condicional(if / else if / else) para determinar o nível do herói de acordo com as seguintes regras:

|Vitórias|Nível|
|---|---|
|≤ 10|Ferro|
|11-20|Bronze|
|21-50|Prata|
|51-80|Ouro|
|81-90|Diamante|
|91-100|Lendário|
|≥ 101|Imortal|

Chame a primeira função determinando os parâmetros e a salve em uma variável

Crie outra variável para chamar a segunda função tendo a variável criada anteriormente como parâmetro

Finalize exibindo uma mensagem com o saldo e o nível do herói.

---

## 📂 Estrutura do Projeto

O projeto contém:

Uma função para calcular o saldo de vitórias

Uma função para definir o nível do herói

Uma variável (saldoVitorias) para armazenar o resultado do cálculo de vitórias e derrotas

Uma variável (nivel) para armazenar o nível retornado pela função de classificação

Um console.log para exibir o resultado final

## 🧠 Lógica Utilizada

A função resultados() recebe o número de vitórias e derrotas e retorna o saldo.

A função classificacao() utiliza estruturas condicionais (if / else if / else) para comparar o saldo com faixas predefinidas.

As variáveis recebem os resultados das funções 

O nível correspondente é retornado e exibido no console junto ao saldo de vitórias.

## ▶️ Exemplo de Saída
O Herói tem saldo de 101 e está no nível de Imortal

