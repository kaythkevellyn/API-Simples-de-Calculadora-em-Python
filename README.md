API Simples de Calculadora em Python

Descrição:

Este é um simples projeto de uma API desenvolvida em Python utilizando o framework Flask.
A API recebe dois números e uma operação matemática e retorna o resultado em formato JSON.

Operações disponíveis:
- soma
- subtracao
- multiplicacao
- divisao

Como executar o projeto:
1 - Instale as dependências: pip install -r requirements.txt
2 - Execute o programa: python Calculadora.py
A API irá rodar em: http://127.0.0.1:5000

Endpoint da API:
POST /calcular
URL: http://127.0.0.1:5000/calcular

Exemplo de requisição:
{
 "num1": 10,
 "num2": 5,
 "operacao": "soma"
}

Exemplo de resposta:
{
 "a": 10,
 "b": 5,
 "operacao": "soma",
 "resultado": 15
}

Testes:
Os testes da API foram realizados utilizando o Postman, enviando requisições HTTP do tipo POST
para o endpoint /calcular com diferentes operações matemáticas.

Tecnologias utilizadas:
Python  
Flask  
JSON