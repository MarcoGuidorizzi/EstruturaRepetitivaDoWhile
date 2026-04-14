# 🌡️ Exercício — Conversor de Temperatura (Do-While)

Programa que converte temperaturas de Celsius para Fahrenheit. O diferencial deste exercício é o uso da estrutura de repetição que permite ao usuário realizar múltiplos cálculos na mesma execução.

## 🧠 Conceitos Aplicados

A principal implementação técnica deste projeto é a estrutura repetitiva "faça-enquanto":

* **Estrutura Do-While:** Diferente do `while` comum, esta estrutura garante que o bloco de comandos seja executado **pelo menos uma vez**, pois a condição de repetição é verificada apenas ao final.
* **Fórmula Matemática:** Implementação da conversão utilizando a fórmula F = (9 * C / 5) + 32.
* **Interação com o Usuário:** Uso de uma condição de parada baseada na entrada de um caractere ('s' ou 'n').
* **Tipos de Dados:** Uso de `double` para garantir a precisão dos cálculos de ponto flutuante.

## 📥 Entrada

O programa solicita os seguintes dados:
1. Um valor numérico representando a temperatura em Celsius.
2. Um caractere ('s' para sim, 'n' para não) indicando se o usuário deseja repetir o processo.

| Dado | Exemplo |
| :--- | :--- |
| Temperatura (C) | 30.0 |
| Deseja repetir? | s |

## 📤 Saída

O equivalente da temperatura calculada em Fahrenheit:

`Equivalente em Fahrenheit: 86.0`

## 💡 Exemplo de Fluxo

```text
Digite a temperatura em Celsius: 30.0
Equivalente em Fahrenheit: 86.0
Deseja repetir (s/n)? s

Digite a temperatura em Celsius: 21.0
Equivalente em Fahrenheit: 69.8
Deseja repetir (s/n)? n
🛠️ Tecnologias
Linguagem: C#

Plataforma: .NET 10

Versionamento: Git

▶️ Como Executar
Bash
# Clone o repositório
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

# Acesse a pasta do exercício
cd ExercicioTemperatura

# Execute o projeto
dotnet run

📁 Estrutura do Projeto
Plaintext
ExercicioTemperatura/
├── Program.cs
├── ExercicioTemperatura.csproj
└── README.md
