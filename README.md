# 📘 Introdução à lógica de programação.

**Professor:** Claudeny Avelino  
**E-mail:** claudeny.avelino@gmail.com  

---

## Algoritmo

**Definição:**  
Sequência finita de instruções para se resolver um problema.  
- Aplica-se a diversas áreas de conhecimento  

### Exemplo: Problema - Lavar roupa suja  

**Algoritmo:**
1. Colocar a roupa em um recipiente  
2. Colocar um pouco de sabão e amaciante  
3. Encher de água  
4. Mexer tudo até dissolver todo o sabão  
5. Deixar de molho por vinte minutos  
6. Esfregar a roupa  
7. Enxaguar  
8. Torcer  

---

## Automação

Consiste em utilizar máquina(s) para executar o procedimento desejado de forma automática ou semiautomática.  

**Exemplo: máquina de lavar**  
- O algoritmo anterior é automatizado pela máquina.  

---

## Computador

- **Hardware**: parte física (a máquina em si)  
- **Software**: parte lógica (programas)  
  - Sistema operacional (Windows, Linux, Mac)  
  - Aplicativos (apps de escritório, câmera, navegador web)  
  - Jogos  
  - Utilitários (Antivírus, compactador de arquivos)  

**Programa ~ Algoritmo:**  
- Programas de computador são algoritmos executados pelo computador.  
- O computador é uma máquina que automatiza a execução de algoritmos computacionais.  

---

## O que é preciso para se fazer um programa de computador?

- Uma **linguagem de programação**: regras léxicas e sintáticas  
- Uma **IDE**: software para editar e testar o programa  
- Um **compilador**: transforma código fonte em código objeto  
- Um **gerador de código ou máquina virtual**: executa o programa  

---

## Linguagem de Programação, Léxica e Sintaxe

### Léxica
- Ortografia (palavras isoladas)  
- Exemplo:  
  - Português: `cachorro` ✅ / `caxorro` ❌  
  - Programação: `main` ✅ / `maim` ❌  

### Sintática
- Gramática (sentença como um todo)  
- Exemplo:  
  - Português: `O cachorro está com fome.` ✅ / `A cachorro está com fome.` ❌  
  - Programação: `x = 2 + y;` ✅ / `x = + 2 y;` ❌  

**Exemplos de linguagens:** C, Portugol, C++, Java, C#, Python, Ruby, PHP, JavaScript  

---

## IDE – Ambiente Integrado de Desenvolvimento

**Exemplos:**  
- Visualg
- Visual Studio Code 
- Java : Eclipse, NetBeans  
- C# : Microsoft Visual Studio  

**Funcionalidades:**  
- Edição de código (autocompletar, indentação, etc.)  
- Depuração e testes  
- Construção do produto final (build)  
- Templates  
- Auxílio em várias tarefas do projeto  

---

## Compilação, Interpretação e Máquina Virtual

- **Compilação**: código fonte → compilador → código objeto → executável  
  - Ex: C, C++  
- **Interpretação**: código fonte → interpretador → execução sob demanda  
  - Ex: PHP, JavaScript, Python, Portugol 
- **Abordagem híbrida**: compilação + máquina virtual (bytecode)  
  - Ex: Java (JVM), C# (.NET Framework)  

---

## Portugol e VisualG

- **Portugol**: linguagem didática, simplificada, voltada para ensino  
- **VisualG**: IDE para editar e interpretar programas em Portugol  

📌 Referências:  
- [Download VisualG](https://sourceforge.net/projects/visualg30/)  
- Prof. Cláudio Morgado de Souza  
- Prof. Antonio Carlos Nicolodi  

---

## Exemplo em Portugol

```portugol
Algoritmo "primeiro"

Var
   // Área de declaração de variáveis

Inicio
   escreva("Ola mundo!")
Fimalgoritmo
```

---

## Resumo da Aula

- **Algoritmo**: sequência finita de instruções para se resolver um problema  
- **Automação**: máquina que executa o algoritmo  
- **Computador**: hardware + software, máquina que automatiza algoritmos  
- **Programa**: algoritmo executado pelo computador  
- **Linguagem de Programação**: regras léxicas e sintáticas  
- **IDE**: ambiente de desenvolvimento  
- **Execução**: compilação, interpretação ou abordagem híbrida  
- **VisualG**: IDE para Portugol  

---

# 📘 Curso Jovem Tech – Algoritmos e Lógica de Programação  
## Aula – Estrutura Sequencial  

📧 **Contato:** claudeny.avelino@gmail.com  
👨‍🏫 **Professor:** Claudeny Avelino  

---

## Conteúdo da Aula  
- Expressões aritméticas  
- Variáveis e tipos básicos  
- Três operações básicas de programação  
- Entrada de dados  
- Processamento de dados  
- Saída de dados  
- Funções matemáticas  

---

## O que é Estrutura Sequencial?  
Chamamos de **estrutura sequencial** porque os comandos do algoritmo são executados **em ordem**, de cima para baixo.  
Um algoritmo deve obedecer uma sequência lógica adequada para cumprir seu papel.  

Exemplo correto:
```pseudocode
x <- 10
y <- 20
soma <- x + y
```

Exemplo errado:
```pseudocode
soma <- x + y
x <- 10
y <- 20
```

---

## Expressões Aritméticas  
### Operadores aritméticos do VisualG  
| Operador | Nome             | Exemplo | Resultado |
|----------|------------------|---------|-----------|
| +        | Soma             | 5 + 2   | 7         |
| -        | Subtração        | 5 - 2   | 3         |
| *        | Multiplicação    | 5 * 2   | 10        |
| /        | Divisão real     | 5 / 2   | 2.5       |
| \\        | Divisão inteira  | 5 \\ 2   | 2         |
| mod ou % | Resto da divisão | 5 mod 2 | 1         |
| ^        | Potenciação      | 2 ^ 3   | 8         |

📌 **Precedência**  
1. `^`  
2. `*`, `/`, `\`, `%`  
3. `+`, `-`  

### Exemplos
```pseudocode
2 * 6 / 3         // resultado = 4
3 + 2 * 4         // resultado = 11
(3 + 2) * 4       // resultado = 20
2 * 3 ^ 4         // resultado = 162
60 / (3 + 2) * 4  // resultado = 48
14 % 3            // resultado = 2
19 % 5            // resultado = 4
```

---

## Variáveis e Tipos Básicos
Em programação, **variável** é uma porção de memória usada para armazenar dados.

### Declaração
```pseudocode
<nome> : <tipo>
```

Exemplo:
```pseudocode
idade : inteiro
altura : real
logradouro : caractere
```

### Tipos básicos no VisualG
| Tipo     | Descrição            | Valor padrão | Exemplos              |
|----------|----------------------|--------------|-----------------------|
| inteiro  | Número inteiro       | 0            | -10, 0, 25            |
| real     | Número decimal       | 0            | 3.14, -7.5            |
| caractere| Texto (string)       | ""           | "Maria", "A"          |
| logico   | Valor verdadeiro/falso | FALSO      | VERDADEIRO, FALSO     |

---

## Operações Básicas de Programação  
1. **Entrada de dados** – leitura do que o usuário digita.  
2. **Processamento de dados** – cálculos e atribuições.  
3. **Saída de dados** – exibição das informações.  

---

## Entrada de Dados  
Comando:  
```pseudocode
leia(variavel)
```

Exemplo:
```pseudocode
Algoritmo "teste_entrada"
Var
   idade : inteiro
   salario1, salario2 : real
   nome : caractere

Inicio
   escreva("Digite seu nome: ")
   leia(nome)
   escreva("Digite sua idade: ")
   leia(idade)
   escreval("Digite quanto voce ganhou nos dois ultimos meses:")
   leia(salario1)
   leia(salario2)

   escreval("DADOS DIGITADOS:")
   escreval("Nome = ", nome)
   escreval("Idade = ", idade)
   escreval("Salario 1 = ", salario1:8:2)
   escreval("Salario 2 = ", salario2:8:2)
Fimalgoritmo
```

---

## Saída de Dados  
Comando:
```pseudocode
escreva()   // sem quebra de linha
escreval()  // com quebra de linha
```

Exemplo:
```pseudocode
Algoritmo "teste_saida"
Var
   idade : inteiro
   salario : real
   nome : caractere
Inicio
   idade <- 32
   salario <- 4560.9
   nome <- "Maria Silva"

   escreval("A funcionaria ", nome, " ganha ", salario:8:2, " e tem ", idade, " anos.")
Fimalgoritmo
```

---

## Funções Matemáticas
Algumas funções disponíveis no VisualG:

| Função           | Descrição                                    |
|------------------|----------------------------------------------|
| RaizQ(x)         | Raiz quadrada de x                          |
| Exp(x, y)        | x elevado a y                               |
| Pi               | Valor de Pi                                 |
| Abs(x)           | Valor absoluto de x                         |

Exemplo:
```pseudocode
Algoritmo "teste_funcoes"
Var
   x, y, z, a, b, c, d : real
Inicio
   x <- 2.0
   y <- 3.0
   z <- -7.0

   a <- Exp(x, y)
   b <- RaizQ(y)
   c <- Pi
   d <- Abs(z)

   escreval(a)
   escreval(b)
   escreval(c)
   escreval(d)
Fimalgoritmo
```

---

## Exercício de Fixação
Crie um programa que mostre na tela:  

```
Produtos:
O produto Computador custa R$ 2100.50
O produto TV custa R$ 1830.00

Codigo = 5291

Dados da pessoa: genero F e idade 30
```

Dica de implementação:
```pseudocode
Algoritmo "exercicio_saida"
Var
   produto1, produto2, genero : caractere
   preco1, preco2 : real
   idade, codigo : inteiro
Inicio
   produto1 <- "Computador"
   produto2 <- "TV"
   preco1 <- 2100.5
   preco2 <- 1830.0
   idade <- 30
   codigo <- 5291
   genero <- "F"

   escreval("Produtos:")
   escreval("O produto ", produto1, " custa R$ ", preco1:8:2)
   escreval("O produto ", produto2, " custa R$ ", preco2:8:2)
   escreval()
   escreval("Codigo = ", codigo)
   escreval()
   escreval("Dados da pessoa: genero ", genero, " e idade ", idade)
Fimalgoritmo
```

---

## Atividade Final  
Implemente no VisualG:  
1. Um programa que calcule a área e o preço de um terreno.  
2. Um programa que calcule área, perímetro e diagonal de um retângulo.

## Exercício

- [Hora Da Prática](https://1drv.ms/b/c/c939bce3230fd75c/ETEsK_zjQpRBufGZwVomJt8BpJYMc4FYN_OImn8h0G332Q?e=rHNGwv)


---

# Curso Jovem Tech – Algoritmos e Lógica de Programação  
## Aula – Estrutura Condicional  

📧 **Contato:** claudeny.avelino@gmail.com  
👨‍🏫 **Professor:** Claudeny Avelino  

---

## Conteúdo da Aula  
- Expressões comparativas  
- Expressões lógicas  
- Estruturas condicionais (simples, composta e encadeada)  
- Estrutura escolha  
- Exercícios práticos  

---

## Expressões Comparativas  

### Operadores comparativos em VisualG  
| Operador | Significado   |
|----------|---------------|
| >        | maior         |
| <        | menor         |
| >=       | maior ou igual|
| <=       | menor ou igual|
| =        | igual         |
| <>       | diferente     |

### Exemplos  
Suponha `x = 5`:  
- `x > 0` → Verdadeiro  
- `x = 3` → Falso  
- `10 <= 30` → Verdadeiro  
- `x <> 2` → Verdadeiro  

---

## Expressões Lógicas  

### Operadores lógicos em VisualG  
| Operador | Descrição |
|----------|-----------|
| e        | Verdadeiro se todas as condições forem verdadeiras |
| ou       | Verdadeiro se pelo menos uma condição for verdadeira |
| nao      | Verdadeiro se a condição for falsa |

### Exemplos  
Suponha `x = 5`:  
- `(x <= 20) e (x = 10)` → Falso  
- `(x > 0) e (x <> 3)` → Verdadeiro  
- `(x = 10) ou (x <= 20)` → Verdadeiro  
- `nao (x = 10)` → Verdadeiro  

---

## Estrutura Condicional  

### Conceito  
A **estrutura condicional** é usada para executar blocos de comandos dependendo de uma condição lógica.  

### Estrutura Simples  
```pseudocode
se <condição> entao
   <comando 1>
   <comando 2>
fimse
```

### Estrutura Composta  
```pseudocode
se <condição> entao
   <comando 1>
   <comando 2>
senao
   <comando 3>
   <comando 4>
fimse
```

### Estrutura Encadeada  
```pseudocode
se <condição 1> entao
   <comando 1>
senao se <condição 2> entao
   <comando 2>
senao se <condição 3> entao
   <comando 3>
senao
   <comando 4>
fimse fimse fimse
```

---

## Estrutura "Escolha"  

Quando há várias opções, pode-se usar a estrutura `escolha` (semelhante ao switch-case).  

### Sintaxe  
```pseudocode
escolha variavel
   caso valor1
      comando1
   caso valor2, valor3
      comando2
   outrocaso
      comando3
fimescolha
```

### Exemplo – Dias da Semana  
```pseudocode
Algoritmo "teste_dias"
Var
   x : inteiro
   dia : caractere
Inicio
   leia(x)
   escolha x
      caso 1
         dia <- "domingo"
      caso 2
         dia <- "segunda"
      caso 3
         dia <- "terca"
      caso 4
         dia <- "quarta"
      caso 5
         dia <- "quinta"
      caso 6
         dia <- "sexta"
      caso 7
         dia <- "sabado"
      outrocaso
         dia <- "valor invalido"
   fimescolha
   escreval("Dia da semana: ", dia)
Fimalgoritmo
```

---

## Exercício – Fórmula de Bhaskara  

Condições:  
- O coeficiente `a` não pode ser zero.  
- O delta não pode ser negativo.  

```pseudocode
delta <- b^2 - 4 * a * c
se delta < 0 entao
   escreval("Impossível calcular, delta negativo.")
senao se a = 0 entao
   escreval("Impossível calcular, coeficiente a igual a zero.")
senao
   x1 <- (-b + RaizQ(delta)) / (2 * a)
   x2 <- (-b - RaizQ(delta)) / (2 * a)
   escreval("X1 = ", x1)
   escreval("X2 = ", x2)
fimse fimse fimse
```

---

## Atividade Final  
1. Escreva um algoritmo que receba um número inteiro e informe se ele é **par** ou **ímpar**.  
2. Escreva um algoritmo que leia a idade de uma pessoa e informe se ela é **menor de idade**, **maior de idade** ou **idoso**.  
3. Refaça o exercício dos dias da semana utilizando a estrutura `escolha`.

## Exercício

- [Hora Da Prática](https://1drv.ms/b/c/c939bce3230fd75c/EaDT1QAlezVBiDdBR7pvTeUB0ZRRn7aU-UKf9p7mAn5PZw?e=WVL1Up)


---

# Curso Jovem Tech – Algoritmos e Lógica de Programação  
## Aula  – Estruturas Repetitivas  

📧 **Contato:** claudeny.avelino@gmail.com  
👨‍🏫 **Professor:** Claudeny Avelino  

---

## Conteúdo da Aula  
- Estrutura repetitiva **enquanto**  
- Estrutura repetitiva **para**  
- Estrutura repetitiva **repita-até**  
- Exercícios propostos  

---

## Estrutura Repetitiva "enquanto"  

A estrutura **enquanto** repete um bloco de comandos enquanto uma condição for verdadeira.  

📌 **Quando usar:** quando **não se sabe previamente** a quantidade de repetições.  

### Sintaxe  
```pseudocode
enquanto <condição> faca
   <comando 1>
   <comando 2>
fimenquanto
```

### Exemplo  
```pseudocode
Algoritmo "teste_enquanto"
Var
   x, soma : inteiro
Inicio
   soma <- 0
   escreva("Digite o primeiro numero: ")
   leia(x)
   enquanto x <> 0 faca
      soma <- soma + x
      escreva("Digite outro numero: ")
      leia(x)
   fimenquanto
   escreval("SOMA = ", soma)
Fimalgoritmo
```

---

## Estrutura Repetitiva "para"  

A estrutura **para** repete um bloco de comandos para um intervalo de valores.  

📌 **Quando usar:** quando **se sabe previamente** a quantidade de repetições.  

### Sintaxe  
```pseudocode
para variavel de valor_inicial ate valor_final [passo N] faca
   <comando 1>
   <comando 2>
fimpara
```

### Exemplo  
```pseudocode
Algoritmo "teste_para"
Var
   N, i, x, soma : inteiro
Inicio
   escreva("Quantos numeros serao digitados? ")
   leia(N)
   soma <- 0
   para i de 1 ate N faca
      escreva("Digite um numero: ")
      leia(x)
      soma <- soma + x
   fimpara
   escreval("SOMA = ", soma)
Fimalgoritmo
```

### Exemplo – Contagem progressiva  
```pseudocode
para i de 1 ate 5 faca
   escreval("Valor de i: ", i)
fimpara
```

### Exemplo – Contagem regressiva  
```pseudocode
para i de 5 ate 1 passo -1 faca
   escreval("Valor de i: ", i)
fimpara
```

---

## Estrutura Repetitiva "repita-até"  

A estrutura **repita-até** executa o bloco de comandos **ao menos uma vez**, pois a condição é verificada **no final**.  

### Sintaxe  
```pseudocode
repita
   <comando 1>
   <comando 2>
ate <condição>
```

### Exemplo  
```pseudocode
Algoritmo "exemplo_repita_ate"
Var
   C, F : real
   resp : caractere
Inicio
   repita
      escreva("Digite a temperatura em Celsius: ")
      leia(C)
      F <- 9.0 * C / 5.0 + 32.0
      escreval("Equivalente em Fahrenheit: ", F:6:1)
      escreva("Deseja repetir (s/n)? ")
      leia(resp)
   ate resp <> "s"
Fimalgoritmo
```

---

## Resumo da Aula  

- **Enquanto**: usar quando não se sabe a quantidade de repetições.  
- **Para**: usar quando se sabe a quantidade de repetições (contagens).  
- **Repita-até**: garante pelo menos uma execução, condição no final.  

---

## Atividade Final  
1. Escreva um algoritmo que leia um número inteiro positivo e mostre sua tabuada usando o **para**.  
2. Escreva um algoritmo que leia números até que o usuário digite 0 e mostre a **média** deles.  
3. Escreva um algoritmo que leia notas de alunos até que o usuário digite "n" e mostre a **média da turma**.

## Exercício

- [Hora Da Prática](https://1drv.ms/b/c/c939bce3230fd75c/EQbukmlHIZVHp5NHyLG5XQABaiDU4aSnCMZ7KfUHG-C53Q?e=47UrgJ)

---

# Curso Completo de Algoritmos e Lógica de Programação

## Capítulo: Vetores
**Prof. Claudeny Avelino**  
**Email:** claudeny.avelino@gmail.com

### O que são Vetores?

Um vetor é uma coleção de dados indexada, unidimensional, homogênea, e de tamanho fixo.

- **Indexada**: Os elementos são acessados por meio de índices.
- **Unidimensional**: Possui apenas uma dimensão.
- **Homogênea**: Todos os dados são do mesmo tipo.
- **Tamanho fixo**: Deve ser alocado previamente e sua quantidade de elementos é fixa.

#### Exemplo:
| 0   | 1    | 2      | 3    |
|-----|------|--------|------|
| Maria | João | Carlos | Ana  |

### Memória RAM

Como declarar um vetor?

```plaintext
A: vetor [0..9] de inteiro
B: vetor [0..4] de real
C: vetor [0..7] de caractere


A[3] <- 10
Para i de 0 até 4 faça
    B[i] <- i + 10
Fim para
C[1] <- "Maria"


Como acessar os elementos de um vetor?

A[3] <- 10

B[i] <- i + 10

C[1] <- "Maria"

Problema exemplo

Fazer um programa para ler um número inteiro positivo N (máximo = 10), depois ler N números quaisquer e armazená-los em um vetor. Em seguida, mostrar na tela todos os elementos do vetor.

Exemplo de entrada e saída:

Entrada:
Quantos números você vai digitar? 4
Digite um número: 10.5
Digite um número: 4.2
Digite um número: -7.1
Digite um número: 15.0

Saída:
NÚMEROS DIGITADOS:
10.5
4.2
-7.1
15.0

Algoritmo:
Algoritmo "teste_vetor"
Var
    vet: vetor [0..9] de real
    N, i : inteiro
Início
    escreva("Quantos números você vai digitar? ")
    leia(N)
    para i de 0 até N-1 faça
        escreva("Digite um número: ")
        leia(vet[i])
    fim para
    escreval
    escreval("NÚMEROS DIGITADOS:")
    para i de 0 até N-1 faça
        escreval(vet[i]:8:1)
    fim para
Fimalgoritmo

Resumo da aula

Vetor: Coleção de dados.

Tamanho fixo.

Arranjo unidimensional.

Indexada.

Homogênea.

Declaração: B: vetor [0..4] de real.

Acesso: B[3] <- 20.

Problema exemplo: Ler e imprimir na tela um vetor.

Exercícios Propostos - PARTE 1: Testes de Mesa com Vetores

a <- 10
b <- 20
c <- (a + b) / 2
c <- c - 40
v[4] <- a + b + c
a <- 2
enquanto a < 6 faça
    v[a] <- 10 * a
    a <- a + 1
fimenquanto
a <- 7
b <- a - 6
enquanto b < a faça
    v[b] <- b * a
    b <- b + 2
fimenquanto
para a de 0 até 2 faça
    v[a] <- 5
    w[a] <- a
fim para
a <- 2
b <- 5
para c de 0 até 2 faça
    v[c] <- a
    w[c] <- c * v[c]
fim para
v[0] <- 2
para d de 1 até 3 faça
    v[d] <- v[d - 1] * 2
fim para
para d de 0 até 3 faça
    w[d] <- v[d] * 10
fim para

Discussão do exercício "alturas"
N	0	1	2	3	4
nomes	"Maria"	"João"	"Carlos"	"Ana"	"Joaquim"
idades	18	20	22	19	21
alturas	1.60	1.75	1.80	1.70	1.65

Cálculo: x = cont * 100 / N

## Exercício

- [Hora Da Prática](https://1drv.ms/b/c/c939bce3230fd75c/EZmAjyC0-bdDgEEibOguA9sBUANU8hKiM9PKr0brynnz-g?e=MgEdh0)


