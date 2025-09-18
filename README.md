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

# Curso Jovem Tech – Algoritmos e Lógica de Programação  
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

---

✍️ **Próxima aula:** Estruturas Condicionais

