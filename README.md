# Roteiro Experimental — Movimento Retilíneo e Uniforme (MRU) — LABFIS/UFT

> 🌐 **Acesse a versão web do roteiro:** [https://uftlabfis.github.io/roteiro-f1-mru/](https://uftlabfis.github.io/roteiro-f1-mru/)

Este repositório contém o roteiro experimental sobre **Movimento Retilíneo e Uniforme (MRU)**, desenvolvido em **Quarto Markdown (`.qmd`)** para as atividades experimentais do **Laboratório de Física (LABFIS)** do Câmpus Universitário de Palmas, da Universidade Federal do Tocantins (UFT).

O roteiro apresenta a fundamentação teórica do MRU, seus objetivos, materiais e procedimentos experimentais, além da análise dos dados de posição e tempo para a determinação da velocidade do móvel.

---

## 🔬 Experimento

O **Movimento Retilíneo e Uniforme (MRU)** caracteriza-se pelo movimento de um móvel em trajetória retilínea com velocidade constante. No experimento, são realizadas medidas de posição e tempo para verificar experimentalmente a relação entre essas grandezas.

A análise dos dados permite construir o gráfico da **posição em função do tempo** e determinar a velocidade do móvel a partir do coeficiente angular da reta obtida.

O roteiro pode ser realizado em **duas configurações independentes**:

* **Trilho de Rolamento:** utiliza um carro sobre um trilho de rolamento, sensores fotoelétricos e um cronômetro digital.
* **Trilho de Ar:** utiliza um carro sobre um trilho de ar, sensores fotoelétricos e um cronômetro digital.

Cada configuração possui materiais e procedimentos próprios.

---

## 📐 Estrutura do Roteiro

O roteiro está organizado nas seguintes seções principais:

* **Introdução:** apresenta os conceitos físicos fundamentais do MRU e a função horária da posição.
* **Objetivos:** define os resultados esperados da atividade experimental.
* **Material necessário:** apresenta os equipamentos utilizados em cada configuração.
* **Procedimentos:** descreve as etapas para realização das medidas experimentais.
* **Análise dos dados:** orienta a organização, representação gráfica e interpretação dos resultados.
* **Conclusão:** direciona a discussão dos resultados obtidos no experimento.

---

## 🎨 Identidade Visual e Estilo

O roteiro utiliza a identidade visual do **LABFIS/UFT**, com uma paleta de cores baseada na marca do laboratório:

* **Azul Petróleo (`#004A80`):** aplicado aos títulos de seções principais (`h1`, `h2`, `h3`).
* **Verde Esmeralda (`#008577`):** aplicado aos links e elementos de destaque interativos.
* **Dourado (`#FDB913`) / Cinza (`#666666`):** utilizados em detalhes estruturais e bordas.
* **Tipografia e Texto:** parágrafos justificados, com hifenização automática para favorecer a leitura na versão digital.

---

## 🧩 Extensão Quarto (`uftlabfis`)

Para a geração da versão em PDF, foi desenvolvida a extensão personalizada **`uftlabfis`**, que utiliza o **Typst** como motor de renderização.

A extensão permite manter uma identidade visual consistente entre as versões web e impressa do roteiro, além de possibilitar recursos específicos de formatação e diagramação para os documentos do LABFIS.

---

## 🛠️ Tecnologias Utilizadas

* [Quarto CLI](https://quarto.org/) — geração do documento e da versão web.
* **Typst** — sistema de tipografia utilizado na geração do PDF por meio da extensão `uftlabfis`.
* **HTML5 / CSS3** — customização da interface e do estilo da versão web.
* **LaTeX** — representação de equações e expressões matemáticas.
* **Markdown / Quarto Markdown (`.qmd`)** — estruturação do conteúdo do roteiro.

---

## 📁 Estrutura do Projeto

A organização do repositório separa o conteúdo do roteiro dos recursos utilizados na publicação:

```text
.
├── index.qmd
├── _quarto.yml
├── _extensions/
│   └── uftlabfis/
├── assets/
│   └── images/
└── README.md