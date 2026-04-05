# Meu-Scrypt-Phyton

# 🧮 Calculadora em Python

Este projeto apresenta uma calculadora simples desenvolvida em Python, com execução automatizada por meio de um script Shell (.sh).

---

## 📌 Descrição do Projeto

A aplicação permite ao usuário:

* Informar seu nome
* Inserir dois números
* Escolher uma operação matemática

As operações disponíveis são:

* Soma (+)
* Subtração (-)
* Multiplicação (*)
* Divisão (/)

O sistema realiza o cálculo e exibe o resultado no terminal.

---

## ▶️ Como executar o arquivo .sh

### Pré-requisitos

* Python 3 instalado
* Terminal (Linux, Mac ou Git Bash no Windows)

---

### Passo a passo

1. Clone o repositório:

```bash
git clone https://github.com/karils/Meu-Scrypt-Phyton.git
```

2. Acesse a pasta do projeto:

```bash
cd cd Meu-Scrypt-Phyton
```

3. Dê permissão de execução ao arquivo:

```bash
chmod +x calculadora.sh
```

4. Execute o programa:

```bash
./calculadora.sh
```

---

## 🧠 Explicação do código em Python

O arquivo `calculadora.py` é responsável pela lógica do sistema.

### 🔹 Etapas do funcionamento:

1. **Mensagem inicial**

   * Exibe uma saudação ao usuário

2. **Entrada de dados**

   * Solicita o nome do usuário
   * Recebe dois números (tipo float)

3. **Escolha da operação**

   * O usuário escolhe entre: +, -, * ou /

4. **Processamento**

   * Utiliza estruturas condicionais (`if`, `elif`)
   * Cada operação realiza um cálculo específico:

     * Soma → número1 + número2
     * Subtração → número1 - número2
     * Multiplicação → número1 * número2
     * Divisão → número1 / número2

5. **Validação**

   * Evita erro de divisão por zero (quando implementado)

6. **Saída**

   * Exibe o resultado no terminal

---

## ⚙️ Explicação do arquivo executável (.sh)

O arquivo `calculadora.sh` serve para executar automaticamente o código Python.

### Conteúdo do arquivo:

```bash
#!/bin/bash
python3 calculadora.py
```

### Função:

* Executar o script Python diretamente pelo terminal
* Facilitar o uso sem precisar digitar comandos manualmente

---

## 📁 Estrutura do Projeto

```
calculadora.py
calculadora.sh
README.md
```

---

## ✅ Conclusão

Este projeto demonstra conceitos fundamentais de:

* Lógica de programação em Python
* Entrada e saída de dados
* Estruturas condicionais
* Automação com Shell Script
* Organização de projeto no GitHub

```
```
