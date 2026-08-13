# Data Analysis with Python — Português

## Sobre o projeto

Este repositório reúne uma versão em **português brasileiro** do curso **Data Analysis with Python 2024–2025**, disponibilizado pelo **University of Helsinki MOOC Center**.

O projeto está organizado em **7 capítulos**, divididos em várias partes, acompanhando a sequência de estudos do curso original.

O objetivo é facilitar o estudo de **Python e análise de dados**, mantendo explicações, exemplos de programação, exercícios, soluções, figuras e materiais LaTeX organizados em um único repositório.

> **Referência institucional**
>
> The University of Helsinki MOOC Center makes high-quality online education possible by developing and researching educational software and online learning materials. Teachers both within and without the University of Helsinki rely on our tools to create impactful teaching materials. Our popular Massive Open Online Courses (MOOCs) have been available through MOOC.fi since 2012.

## Conteúdo

O curso está organizado em 7 capítulos:

```text
Data Analysis with Python
│
├── Capítulo 1 — Python
│   ├── Parte 1
│   ├── Parte 2
│
├── Capítulo 2 — Mais Python
│   ├── Parte 1
│   ├── Parte 2
│
├── Capítulo 3 — Mais NumPy
│   ├── NumPy
│   ├── NumPy Parte 2
│   ├── Matplotlib
│   ├── Processamento de imagens
│
├── Capítulo 4 — Pandas
│   ├── Parte 1
│
├── Capítulo 5 — Mais Pandas e Machine learning
│   ├── Parte 1
│   ├── Parte 2
│
├── Capítulo 6 — Mais Machine learning 
│   ├── Parte 1
│
└── Capítulo 7 — Projeto
    ├── Materiais do projeto
    └── Exercícios e exemplos
```

> Os nomes exatos das partes podem variar conforme os arquivos disponibilizados no repositório.

## Estrutura do repositório

```text
.
├── README.md
├── LICENSE
│
├── chapter-1/
│   ├── part-1/
│   ├── part-2/
│   └── ...
│
├── chapter-2/
│   ├── part-1/
│   ├── part-2/
│   └── ...
│
├── chapter-3/
│   ├── numpy/
│   ├── numpy-part-2/
│   ├── matplotlib/
│   ├── image-processing/
│   └── ...
│
├── chapter-4/
│   ├── part-1/
│   ├── part-2/
│   └── ...
│
├── chapter-5/
│   ├── part-1/
│   ├── part-2/
│   └── ...
│
├── chapter-6/
│   ├── part-1/
│   └── ...
│
├── chapter-7/
│   ├── project/
│   └── ...
│
├── solutions/
│   ├── chapter-1/
│   ├── chapter-2/
│   ├── chapter-3/
│   ├── chapter-4/
│   ├── chapter-5/
│   ├── chapter-6/
│   └── chapter-7/
│
├── images/
├── data/
└── latex/
    ├── main.tex
    ├── chapters/
    ├── figures/
    └── solutions/
```

## O que você encontrará

### 📚 Material traduzido

Cada parte do curso possui uma versão em português, organizada em arquivos LaTeX e, quando disponível, em PDF.

### 💻 Exemplos em Python

Os exemplos apresentados durante as aulas são organizados em arquivos `.py` para facilitar testes e experimentação.

### 📝 Exercícios

Os exercícios são mantidos separados por capítulo e parte, seguindo a organização do curso.

### ✅ Soluções

As soluções ficam em uma estrutura separada para permitir que o estudante tente os exercícios antes de consultar as respostas.

```text
solutions/
├── chapter-1/
├── chapter-2/
├── chapter-3/
├── chapter-4/
├── chapter-5/
├── chapter-6/
└── chapter-7/
```

### 🖼️ Imagens e figuras

As figuras utilizadas no material são armazenadas em pastas próprias para que possam ser reutilizadas nos documentos LaTeX e nos PDFs.

### 📄 LaTeX

O material foi organizado para permitir a geração dos PDFs diretamente a partir dos arquivos `.tex`.

## Tecnologias utilizadas

- Python
- NumPy
- Matplotlib
- Pandas
- SciPy
- Jupyter Notebook
- LaTeX

## Como estudar

A recomendação é seguir os capítulos na ordem:

```text
Capítulo 1
    ↓
Capítulo 2
    ↓
Capítulo 3
    ↓
Capítulo 4
    ↓
Capítulo 5
    ↓
Capítulo 6
    ↓
Capítulo 7
```

Dentro de cada capítulo, estude cada parte em sequência e tente resolver os exercícios **antes** de consultar as soluções.

## Compilação do LaTeX

Para gerar os PDFs localmente, instale uma distribuição LaTeX, como:

- TeX Live
- MiKTeX

Depois, entre na pasta correspondente e execute:

```bash
pdflatex main.tex
```

Em projetos que utilizam referências ou índice, pode ser necessário executar a compilação mais de uma vez.

## Exemplo de uma parte

```text
chapter-3/
└── matplotlib/
    ├── main.tex
    ├── main.pdf
    ├── solucoes_exercicios.tex
    ├── solucoes_exercicios.pdf
    ├── codigo/
    │   └── solucoes.py
    └── figuras/
```

## Objetivo do repositório

Este projeto busca:

- facilitar o acesso ao conteúdo em português;
- organizar os capítulos e partes do curso;
- centralizar exemplos e exercícios;
- facilitar a compilação dos materiais em LaTeX;
- servir como material de apoio para estudos de Python e análise de dados.

## Créditos

Curso original:

**Data Analysis with Python 2024–2025**  
University of Helsinki — MOOC.fi

O conteúdo original, a estrutura do curso e os materiais institucionais pertencem aos seus respectivos autores e à Universidade de Helsinki.

Este repositório é uma organização/tradução para fins educacionais. Consulte os termos e a licença do material original antes de redistribuir conteúdo derivado.

## Fonte

Curso original:

https://courses.mooc.fi/org/uh-cs/courses/data-analysis-with-python-2024-2025/

## Status

🚧 **Projeto em desenvolvimento**

As diferentes partes do curso são adicionadas e revisadas progressivamente.

---

<p align="center">
  Desenvolvido para estudos de Python e Análise de Dados
</p>
