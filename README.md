# 📚 Miniguia: Juros Simples e Juros Compostos com NotebookLM

## 📌 Sobre o projeto

Este projeto foi desenvolvido como desafio do Bootcamp **Bradesco - GenAI, Dados & Cyber**, utilizando o **NotebookLM** como ferramenta de apoio ao aprendizado.

O objetivo foi criar um caderno temático sobre **juros simples e juros compostos**, utilizando fontes abertas, engenharia de prompts e análise crítica das respostas geradas por Inteligência Artificial.

A proposta do projeto é demonstrar como a IA pode ser utilizada como uma ferramenta de aprendizagem ativa, auxiliando na organização do conhecimento, revisão de conceitos e criação de materiais de estudo.

---

# 🎯 Contexto e Objetivos

A educação financeira é um tema fundamental para a tomada de decisões no cotidiano. Apesar de conceitos como juros simples e compostos estarem presentes em diversas situações financeiras, muitas pessoas ainda possuem dificuldades para compreender seu funcionamento.

Este miniguia tem como objetivos:

* Compreender o conceito de juros;
* Entender o funcionamento dos juros simples;
* Entender o funcionamento dos juros compostos;
* Comparar as diferenças entre os dois modelos;
* Identificar aplicações práticas no cotidiano;
* Utilizar Inteligência Artificial como ferramenta de estudo;
* Desenvolver melhores práticas de criação de prompts.

---

# 📚 Curadoria de Fontes

As fontes utilizadas foram selecionadas buscando materiais confiáveis e acessíveis sobre educação financeira.

## Fontes utilizadas:

* Banco Central do Brasil — Educação Financeira
  https://www.bcb.gov.br/cidadaniafinanceira

* Banco Central do Brasil — Aprender Valor
  https://aprendervalor.bcb.gov.br/

* B3 — Educação Financeira
  https://borainvestir.b3.com.br/

* Materiais educacionais sobre matemática financeira e juros disponibilizados por instituições de ensino.

As fontes foram adicionadas ao NotebookLM para auxiliar na criação das respostas e análises.

---

# 🤖 Engenharia de Prompts e Aprendizados

Durante o desenvolvimento do projeto foram realizados testes com diferentes formatos de prompts para observar como a qualidade da resposta da IA poderia ser aprimorada.

## Exemplo de evolução dos prompts:

### Prompt inicial:

> O que são juros?

Resultado:

* Resposta geral sobre o conceito.

---

### Prompt refinado:

> Explique o que são juros para uma pessoa que nunca estudou educação financeira. Utilize uma linguagem simples, apresente exemplos do cotidiano e organize a resposta em tópicos.

Resultado:

* Resposta mais didática;
* Melhor organização;
* Exemplos práticos;
* Linguagem adequada para iniciantes.

---

## Principais aprendizados:

Durante os testes foi possível observar que prompts mais detalhados geram respostas mais alinhadas ao objetivo.

Adicionar elementos como:

* contexto;
* público-alvo;
* formato esperado;
* exemplos desejados;

melhora significativamente a qualidade da resposta gerada pela IA.

---

# 📖 Miniguia de Estudo

# O que são juros?

Juros representam o valor cobrado pelo uso do dinheiro durante determinado período.

Eles podem representar:

* Um custo para quem utiliza dinheiro emprestado;
* Uma remuneração para quem investe ou disponibiliza recursos.

Os juros estão presentes em:

* empréstimos;
* investimentos;
* financiamentos;
* compras parceladas.

---

# Juros Simples

Os juros simples são calculados utilizando apenas o valor inicial da operação, chamado de capital.

Os juros permanecem constantes durante todo o período.

## Fórmula:

```
J = C × i × t
```

Onde:

* J = juros;
* C = capital inicial;
* i = taxa de juros;
* t = tempo.

O montante final é:

```
M = C + J
```

## Exemplo:

Capital:

R$ 1.000,00

Taxa:

1% ao mês

Tempo:

6 meses

Juros mensais:

R$ 10,00

Juros totais:

R$ 60,00

Montante:

R$ 1.060,00

---

# Juros Compostos

Os juros compostos são conhecidos como **"juros sobre juros"**.

Nesse modelo, os juros acumulados são incorporados ao capital, fazendo com que o próximo cálculo seja realizado sobre um valor maior.

## Fórmula:

```
M = C × (1 + i)^t
```

Onde:

* M = montante final;
* C = capital inicial;
* i = taxa de juros;
* t = tempo.

## Exemplo:

Capital:

R$ 100,00

Taxa:

1% ao mês

Tempo:

3 meses

Resultado:

* Primeiro mês: R$ 101,00
* Segundo mês: R$ 102,01
* Terceiro mês: R$ 103,03

---

# Juros Simples x Juros Compostos

| Característica  | Juros Simples          | Juros Compostos                      |
| --------------- | ---------------------- | ------------------------------------ |
| Base de cálculo | Capital inicial        | Capital + juros acumulados           |
| Crescimento     | Linear                 | Exponencial                          |
| Efeito do tempo | Menor influência       | Maior influência                     |
| Conhecido como  | Juros sobre capital    | Juros sobre juros                    |
| Aplicação       | Menos comum atualmente | Mais utilizado no mercado financeiro |

---

# Aplicações no cotidiano

## Juros Simples

Podem aparecer em:

* alguns parcelamentos;
* empréstimos informais;
* determinadas cobranças de atraso.

---

## Juros Compostos

São encontrados em:

### Investimentos:

* CDB;
* Tesouro Direto;
* Poupança;
* LCI e LCA.

### Dívidas:

* cartão de crédito;
* cheque especial;
* financiamentos.

Os juros compostos podem ser aliados nos investimentos e prejudiciais quando associados a dívidas.

---

# 📖 Glossário

## Capital

Valor inicial investido ou emprestado.

## Taxa de Juros

Percentual aplicado sobre determinado valor em um período.

## Tempo

Período em que o dinheiro permanece aplicado ou emprestado.

## Montante

Valor final formado pelo capital inicial mais os juros.

## Juros Simples

Modelo onde a taxa incide apenas sobre o capital inicial.

## Juros Compostos

Modelo onde os juros acumulados passam a gerar novos juros.

## Amortização

Parte do pagamento destinada a reduzir o valor original da dívida.

## Liquidez

Facilidade de transformar um investimento novamente em dinheiro.

## Selic

Taxa básica de juros da economia brasileira.

---

# 🧩 Prompts reutilizáveis

## Explicação de conceitos

```
Explique [CONCEITO] para uma pessoa iniciante.
Utilize linguagem simples, exemplos práticos e organize a resposta em tópicos.
```

---

## Estudo aprofundado

```
Explique [TEMA] como um professor ensinando um aluno iniciante.
Apresente:
- definição;
- principais características;
- exemplos;
- aplicações práticas;
- resumo final.
```

---

## Comparação de conceitos

```
Compare [CONCEITO A] e [CONCEITO B].
Mostre:
- principais diferenças;
- vantagens e desvantagens;
- exemplos práticos;
- uma tabela comparativa.
```

---

## Criação de resumo

```
Crie um resumo estruturado sobre [TEMA].
Inclua:
- conceitos principais;
- pontos importantes;
- exemplos;
- aplicações no cotidiano.
```

---

## Criação de glossário

```
Crie um glossário sobre [TEMA].
Liste os principais termos e explique cada conceito utilizando uma linguagem simples.
```

---

# 🚀 Conclusão

Este projeto demonstrou como a Inteligência Artificial pode ser utilizada como uma ferramenta de aprendizagem, permitindo organizar conhecimento, revisar conceitos e desenvolver melhores práticas de comunicação com modelos de IA.

O uso do NotebookLM aliado à engenharia de prompts mostrou que a qualidade das respostas depende diretamente da forma como as perguntas são estruturadas.

---

Desenvolvido como parte do Bootcamp Bradesco - GenAI, Dados & Cyber.
