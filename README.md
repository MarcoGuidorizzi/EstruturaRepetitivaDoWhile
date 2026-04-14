🌡️ Exercício — Conversor de Temperatura (Do-While)

Programa simples que converte temperaturas de Celsius para Fahrenheit.
O diferencial deste exercício é o uso da estrutura de repetição do-while,
permitindo que o usuário realize múltiplos cálculos em sequência.


🧠 Conceitos Aplicados

Este projeto aborda os seguintes fundamentos da linguagem C#:

- Estrutura do-while
  Garante que o bloco de código seja executado pelo menos uma vez,
  antes da verificação da condição.

- Laço de repetição com interação do usuário
  O usuário decide se deseja continuar ou encerrar o programa.

- Conversão de tipos (double)
  Utilização de double para trabalhar com números decimais.

- Entrada de dados (Console.ReadLine)
  Leitura de valores inseridos pelo usuário.

- Controle de fluxo com char
  Uso de caracteres ('s' ou 'n') para controlar a repetição.

- Cultura Invariante (InvariantCulture)
  Garante consistência na leitura de números com ponto decimal.


📥 Entrada

O programa solicita ao usuário:

1. Um valor numérico representando a temperatura em Celsius
2. Um caractere:
   's' → para continuar
   'n' → para encerrar

Exemplo de Entrada:

Temperatura (C): 30.0
Deseja repetir: s


📤 Saída

O programa retorna:

- O valor convertido de Celsius para Fahrenheit

Exemplo:

Equivalente em Fahrenheit: 86.0


🔄 Exemplo de Execução

Digite a temperatura em Celsius: 30.0
Equivalente em Fahrenheit: 86.0
Deseja repetir? (s/n): s

Digite a temperatura em Celsius: 21.0
Equivalente em Fahrenheit: 69.8
Deseja repetir? (s/n): n


⚙️ Tecnologias Utilizadas

- Linguagem: C#
- Plataforma: .NET
- Versionamento: Git


🚀 Como Executar

# Clonar o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acessar a pasta do projeto
cd ConversorTemperatura

# Executar o programa
dotnet run


📁 Estrutura do Projeto

ConversorTemperatura/

├── Program.cs
├── ConversorTemperatura.csproj
└── README.md
