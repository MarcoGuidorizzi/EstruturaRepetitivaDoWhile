# 🌡️ Exercício — Conversor de Temperatura (Do-While)

Programa que converte temperaturas de Celsius para Fahrenheit. O diferencial deste exercício é o uso da estrutura de repetição que permite ao usuário realizar múltiplos cálculos sem precisar reiniciar o programa manualmente.

## 🧠 Conceitos Aplicados

A principal implementação técnica deste projeto é a estrutura repetitiva "faça-enquanto":

* **Estrutura Do-While:** Garante que o bloco de comandos seja executado **pelo menos uma vez**, pois a condição de repetição (`s/n`) só é verificada ao final do loop.
* **Fórmula de Conversão:** Implementação da fórmula matemática $$F = \frac{9C}{5} + 32$$.
* **Entrada de Dados de Caractere:** Captura da resposta do usuário (`char`) para decidir se o fluxo deve voltar ao início ou "pular fora".
* **Formatação Numérica:** Exibição do resultado com uma casa decimal para precisão da temperatura.

## 📥 Entrada

O programa solicita:
1. Um valor numérico (Celsius).
2. Um caractere ('s' para sim, 'n' para não) para decidir a repetição.

| Dado | Exemplo |
| :--- | :--- |
| Temperatura (C) | 30.0 |
| Deseja repetir? | s |

## 📤 Saída

O equivalente da temperatura em Fahrenheit:

`Equivalente em Fahrenheit: 86.0`

## 💡 Exemplo de Fluxo

```text
Digite a temperatura em Celsius: 30.0
Equivalente em Fahrenheit: 86.0
Deseja repetir (s/n)? s

Digite a temperatura em Celsius: 21.0
Equivalente em Fahrenheit: 69.8
Deseja repetir (s/n)? n
