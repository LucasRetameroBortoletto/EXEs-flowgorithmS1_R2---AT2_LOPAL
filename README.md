# 📊 Exercícios de Lógica de Programação — Flowgorithm

Repositório com 12 fluxogramas desenvolvidos no **Flowgorithm** como atividade prática de lógica de programação. Os algoritmos cobrem entrada de dados, operadores aritméticos, variáveis e resolução de problemas do cotidiano.

---

## 🛠️ Ferramenta Utilizada

- **Flowgorithm** — software gratuito para criação e execução de fluxogramas  
  🔗 [flowgorithm.org](http://www.flowgorithm.org)
- Arquivos no formato `.fprg`

---

## 📁 Estrutura dos Arquivos

```
ExerciciosFG/
├── Exe1.fprg    # Soma de dois inteiros
├── Exe2.fprg    # Média aritmética
├── Exe3.fprg    # Área do retângulo
├── Exe4.fprg    # Conversão Real → Dólar
├── Exe5.fprg    # Celsius → Fahrenheit
├── Exe6.fprg    # Área da parede e quantidade de tinta
├── Exe7.fprg    # Delta da equação do 2º grau
├── Exe8.fprg    # Preço com desconto de 5%
├── Exe9.fprg    # Salário com aumento de 15%
├── Exe10.fprg   # Cálculo de aluguel de carro
├── Exe11.fprg   # Salário por dias trabalhados
└── Exe12.fprg   # [Desafio] Redução de vida do fumante
```

---

## 📝 Descrição dos Exercícios

### Exe 01 — Soma de dois inteiros
Recebe dois números inteiros, calcula a soma e exibe o resultado.

**Variáveis:** `numero1`, `numero2`, `soma`

---

### Exe 02 — Média aritmética
Recebe três números reais, calcula a média aritmética e exibe o resultado.

**Variáveis:** `numero1`, `numero2`, `numero3`, `media`

**Fórmula:**
```
media = (numero1 + numero2 + numero3) / 3
```

---

### Exe 03 — Área do retângulo
Recebe largura e altura de um retângulo, calcula e exibe a área.

**Variáveis:** `largura`, `altura`, `area`

**Fórmula:**
```
area = largura * altura
```

---

### Exe 04 — Conversão Real → Dólar
Recebe um valor em reais e converte para dólares, considerando **1 USD = R$ 6,00**.

**Variáveis:** `reais`, `dolar`

**Fórmula:**
```
dolar = reais / 6
```

---

### Exe 05 — Celsius → Fahrenheit
Recebe uma temperatura em graus Celsius e converte para Fahrenheit.

**Variáveis:** `grausCelsius`, `fahrenheit`

**Fórmula:**
```
fahrenheit = ((grausCelsius * 9) / 5) + 32
```

---

### Exe 06 — Área da parede e tinta
Recebe as dimensões de uma parede, calcula a área a ser pintada e a quantidade de tinta necessária. Considera que **1 litro de tinta cobre 2 m²**.

**Variáveis:** `altura`, `largura`, `area`, `litrosDeTinta`

**Fórmulas:**
```
area = largura * altura
litrosDeTinta = area / 2
```

---

### Exe 07 — Delta da equação do 2º grau
Recebe os coeficientes A, B e C de uma equação do segundo grau e calcula o discriminante (Delta).

**Variáveis:** `numeroA`, `numeroB`, `numeroC`, `delta`

**Fórmula:**
```
delta = (B²) - (4 * A * C)
```

---

### Exe 08 — Preço com 5% de desconto
Recebe o preço de um produto e calcula o valor promocional com 5% de desconto.

**Variáveis:** `valorProduto`, `valorPromocao`

**Fórmula:**
```
valorPromocao = valorProduto - (valorProduto * 0.05)
```

---

### Exe 09 — Salário com 15% de aumento
Recebe o salário de um funcionário e calcula o novo salário após reajuste de 15%.

**Variáveis:** `salario`, `salarioAumento`

**Fórmula:**
```
salarioAumento = salario + (salario * 0.15)
```

---

### Exe 10 — Cálculo de aluguel de carro
Recebe a quantidade de km percorridos e o número de dias alugados. Calcula o valor total a pagar, sendo **R$ 90,00/dia** e **R$ 0,20/km**.

**Variáveis:** `kilometros`, `dias`, `precoTotal`

**Fórmula:**
```
precoTotal = (dias * 90) + (kilometros * 0.20)
```

---

### Exe 11 — Salário por dias trabalhados
Recebe o número de dias trabalhados no mês e calcula o salário, considerando **6 horas/dia** a **R$ 45,00/hora**.

**Variáveis:** `diasTrabalhados`, `salario`

**Fórmula:**
```
salario = diasTrabalhados * 6 * 45
```

---

### Exe 12 — [Desafio] Redução de vida do fumante
Calcula quantos dias de vida um fumante perde, sabendo que cada cigarro consome **10 minutos de vida**. Recebe a quantidade de cigarros por dia e os anos fumados.

**Variáveis:** `quantCigarros`, `quantAnos`, `anosDias`, `cigarrosTotal`, `diasDeVida`

**Fórmulas:**
```
anosDias       = quantAnos * 365
cigarrosTotal  = quantCigarros * anosDias
diasDeVida     = (cigarrosTotal * 10) / 1440
```

> 1440 = número de minutos em um dia (24h × 60min)

---

## ▶️ Como executar

1. Instale o [Flowgorithm](http://www.flowgorithm.org)
2. Abra o arquivo `.fprg` desejado pelo menu **File → Open**
3. Clique em **Run** (▶) para executar o fluxograma
4. Insira os valores solicitados no console e veja o resultado

---

## 📌 Conceitos abordados

- Entrada e saída de dados
- Declaração e uso de variáveis (`Integer` e `Real`)
- Operadores aritméticos (`+`, `-`, `*`, `/`)
- Ordem de precedência em expressões
- Conversão de unidades
- Resolução de problemas com lógica sequencial
