# ☕ Projeto Java: Contador

Este é um projeto simples em Java que demonstra o uso de **exceções personalizadas** e controle de fluxo com **laços de repetição**. O programa solicita dois números inteiros do usuário e realiza uma contagem com base nesses valores.

---

## 📄 Descrição

O projeto é composto por duas classes:

- `Contador`: Classe principal que interage com o usuário e realiza a contagem.
- `ParametrosInvalidosException`: Classe que representa uma exceção personalizada lançada quando o primeiro parâmetro é maior que o segundo.

---

## 🔧 Como Executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Compile os arquivos:
```bash
javac Contador.java ParametrosInvalidosException.java
```

3. Execute o programa:

```bash
java Contador
```
4. Digite dois números inteiros quando solicitado.

---

## ✅ Exemplo de Funcionamento

```
Digite o primeiro parâmetro
3
Digite o segundo parâmetro
6
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
```

---

## ⚠️ Tratamento de Erros

Se o **primeiro número** for **maior** que o segundo, será exibida a seguinte mensagem:

```
O segundo parâmetro deve ser maior que o primeiro
```

---

## 📁 Estrutura dos Arquivos

```
📂 ProjetoContador
 ├── Contador.java
 └── ParametrosInvalidosException.java
```

---

## 🧠 Conceitos Utilizados

* Entrada de dados com `Scanner`
* Lançamento e tratamento de exceções
* Criação de exceções personalizadas
* Estrutura de repetição `for`

---

## 💡 Autor
- LinkedIn: [Helder Queiroz](https://www.linkedin.com/in/helder-queiroz-dev/)

Desenvolvido como parte dos estudos do Bootcamp Java Cloud Native 🚀
