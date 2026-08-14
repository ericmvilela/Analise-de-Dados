# Data Analysis with Python — Português

## Sobre o projeto

Este repositório reúne uma **tradução e adaptação para português brasileiro** do curso **Data Analysis with Python 2024–2025**, disponibilizado gratuitamente pela **University of Helsinki**, através da plataforma **MOOC.fi**.

O projeto está organizado em **7 capítulos**, divididos em várias partes, acompanhando fielmente a sequência de estudos do curso original.

O objetivo é facilitar o estudo de **Python e análise de dados** em português, mantendo o conteúdo teórico, os exercícios e as soluções organizados em arquivos LaTeX (com PDF já compilado) em um único repositório.

> **Aviso importante**
>
> Este é um projeto **não oficial**, feito por um estudante, sem qualquer vínculo com a University of Helsinki ou com o MOOC.fi. O conteúdo aqui é uma tradução/adaptação para fins de estudo pessoal, compartilhada publicamente para ajudar outras pessoas de língua portuguesa. Os créditos pelo curso original — e os créditos oficiais, certificação e ECTS — pertencem exclusivamente à University of Helsinki. Veja a seção [Licença](#licença) para mais detalhes.

## Conteúdo

O curso está organizado em 7 capítulos, cada um com uma ou mais partes:

```
Data Analysis with Python (PT-BR)
│
├── Capítulo 1 — Python
│
├── Capítulo 2 — Mais Python e NumPy
│   ├── Parte 1 — Python (continuação)
│   └── Parte 2 — NumPy (Parte 1)
│
├── Capítulo 3 — Mais NumPy, Imagens, Bibliotecas e Pandas
│   ├── Parte 1 — NumPy (Parte 2)
│   ├── Parte 2 — Matplotlib
│   ├── Parte 3 — Processamento de Imagens
│   └── Parte 4 — Pandas (Parte 1)
│
├── Capítulo 4 — Mais Pandas
│   └── Pandas (DataFrames na prática)
│
├── Capítulo 5 — Ainda mais Pandas e Machine Learning
│   ├── Parte 1 — Pandas (Parte 3)
│   └── Parte 2 — Machine Learning: Regressão Linear
│
├── Capítulo 6 — Tipos de Machine Learning
│   ├── Parte 1 — Naive Bayes
│   ├── Parte 2 — Clustering (Agrupamento)
│   └── Parte 3 — PCA (Principal Component Analysis)
│
└── Capítulo 7 — Project Work
    ├── Parte 1 — Trabalho final do curso
    └── Parte 2 — Considerações finais
```

## Estrutura real do repositório

```
.
├── README.md
├── LICENSE
├── .gitignore
│
├── Capitulo 1/
│   ├── python_conteudo.tex / .pdf
│   ├── python_exercicios.tex / .pdf
│   └── python_solucoes.tex / .pdf
│
├── Capitulo 2/
│   ├── Parte 1/   (Python — continuação)
│   └── Parte 2/   (NumPy — Parte 1)
│
├── Capitulo 3/
│   ├── Parte 1/   (NumPy — Parte 2)
│   ├── Parte 2/   (Matplotlib)
│   ├── Parte 3/   (Processamento de imagens)
│   └── Parte 4/   (Pandas — Parte 1)
│
├── Capitulo 4/    (Pandas — sem subpastas)
│
├── Capitulo 5/
│   ├── Parte 1/   (Pandas — Parte 3)
│   └── Parte 2/   (Regressão linear)
│
├── Capitulo 6/
│   ├── Parte 1/   (Naive Bayes)
│   ├── Parte 2/   (Clustering)
│   └── Parte 3/   (PCA)
│
└── Capitulo 7/
    ├── Parte 1/   (Project Work)
    └── Parte 2/   (Considerações finais)
```

Cada pasta de parte contém três arquivos `.tex` (com o `.pdf` já compilado ao lado):

```
Capitulo 3/Parte 2/
├── matplotlib_conteudo.tex     → material teórico
├── matplotlib_conteudo.pdf
├── matplotlib_exercicios.tex   → enunciados dos exercícios
├── matplotlib_exercicios.pdf
├── matplotlib_solucoes.tex     → soluções propostas
└── matplotlib_solucoes.pdf
```

> Não há pastas separadas `solutions/`, `images/`, `data/` ou `latex/` — cada parte é autocontida, com o conteúdo, os exercícios e as soluções lado a lado.

## O que você encontrará

### 📚 Material traduzido

Cada parte do curso possui uma versão em português, organizada em arquivo LaTeX e já compilada em PDF.

### 📝 Exercícios

Os exercícios são mantidos em um arquivo próprio (`*_exercicios.tex`), separado do conteúdo teórico, seguindo a numeração original do curso (ex.: Exercício 1.1, 1.2, ...).

### ✅ Soluções

As soluções ficam em um arquivo separado (`*_solucoes.tex`) para permitir que você tente resolver os exercícios antes de consultar as respostas. São soluções elaboradas de forma independente para fins de estudo, com base nos enunciados originais do curso — não são o gabarito oficial do MOOC.fi.

## Tecnologias utilizadas

- Python
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- LaTeX

## Como estudar

A recomendação é seguir os capítulos na ordem, e dentro de cada capítulo, cada parte em sequência:

```
Capítulo 1 → Capítulo 2 → Capítulo 3 → Capítulo 4 → Capítulo 5 → Capítulo 6 → Capítulo 7
```

Tente resolver os exercícios **antes** de consultar as soluções.

## Compilação do LaTeX

Para gerar (ou regenerar) os PDFs localmente, instale uma distribuição LaTeX:

- **Windows:** [MiKTeX](https://miktex.org/)
- **macOS:** [MacTeX](https://tug.org/mactex/)
- **Linux:** `texlive-full` (ou os pacotes equivalentes, incluindo `texlive-lang-portuguese`, necessário por causa do `\usepackage[portuguese]{babel}`)

Depois, entre na pasta correspondente e execute:

```bash
pdflatex nome_do_arquivo.tex
```

Como os documentos usam sumário/referências, pode ser necessário rodar o comando duas vezes seguidas para tudo ficar correto.

## Objetivo do repositório

Este projeto busca:

- facilitar o acesso ao conteúdo do curso em português;
- manter a organização por capítulo e parte fiel à estrutura original do MOOC.fi;
- centralizar teoria, exercícios e soluções em um único lugar por parte;
- servir como material de apoio para quem está estudando Python e análise de dados.

## Créditos e licença

O curso original — **Data Analysis with Python 2024–2025** — é de autoria da **University of Helsinki**, disponibilizado através do **MOOC.fi**:

🔗 <https://courses.mooc.fi/org/uh-cs/courses/data-analysis-with-python-2024-2025/>

Todo o conteúdo, a estrutura pedagógica e os materiais institucionais originais pertencem aos seus respectivos autores e à University of Helsinki. Este repositório é uma **tradução e adaptação não oficial**, feita para fins educacionais e sem fins lucrativos. Consulte o arquivo [`LICENSE`](./LICENSE) para os termos completos.

Se você quer o curso oficial, com certificação e créditos ECTS, acesse o link acima e estude diretamente pela plataforma do MOOC.fi.

## Status

🚧 **Projeto em desenvolvimento** — as partes são revisadas progressivamente.

---

Desenvolvido para estudos de Python e Análise de Dados.