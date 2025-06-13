# Visualização de Dados com Python: Imigração para o Canadá (1980–2013)

Este repositório contém um projeto prático de visualização de dados desenvolvido como parte do curso **"Data Visualization: criando gráficos com bibliotecas Python"**, ministrado pela instrutora **Valquíria Alencar** na plataforma **Alura**, do programa **Oracle Next Education (ONE)**.

O objetivo é demonstrar a aplicação das bibliotecas `pandas`, `matplotlib`, `seaborn` e `plotly` na análise e visualização de dados sobre imigração para o Canadá no período de 1980 a 2013.

---

## 1. Contexto do Projeto

Este projeto foi desenvolvido com foco educacional e não está vinculado a uma demanda de negócio real. A proposta é aplicar técnicas fundamentais de manipulação e visualização de dados utilizando ferramentas amplamente utilizadas na área de Ciência de Dados.

---

## 2. Técnicas e Recursos Utilizados

### Manipulação de Dados com `pandas`

- Filtragem condicional de DataFrames;
- Seleção de colunas por intervalos de anos;
- Transposição de DataFrames para facilitar a análise temporal;
- Renomeação de colunas e índices;
- Conversão de tipos de dados (índices de `str` para `int`).

---

### Visualização com `matplotlib.pyplot`

- Criação de gráficos de linha com `plt.plot()`;
- Definição do tamanho do gráfico com `plt.figure(figsize=...)`;
- Personalização de título e eixos (`plt.title()`, `plt.xlabel()`, `plt.ylabel()`);
- Ajuste das marcações com `plt.xticks()`;
- Uso de múltiplos gráficos com `plt.subplots()`:
  - Subgráficos lado a lado ou em grade;
  - Uniformização das escalas com `ax.set_ylim()`;
  - Título geral para a figura (`plt.suptitle()`).
  - Exibição do gráfico com `plt.show()`.

---

### Visualização com `seaborn`

- Aplicação de temas visuais (`whitegrid, darkgrid`, etc.);
- Geração de gráficos de barras verticais e horizontais com `sns.barplot()`;
- Combinação com `matplotlib` para ajustes finos;
- Uso de paletas de cores (`'Blues_d', 'rocket', 'tab10'`, etc.);
- Limpeza do layout gráfico com `sns.despine()`.

---

### Visualização Interativa com `plotly.express`

- Criação de gráficos de linha interativos com `px.line()` e `markers=True`;
- Customização com `fig.update_layout()` e `fig.update_traces()`;
- Alteração de fundo, cores, rotação de texto e estilo dos rótulos;
- Exportação do gráfico para `.html`, permitindo visualização externa interativa.
  
---

## 3. Tecnologias Utilizadas

- Python 
- pandas
- matplotlib
- seaborn
- plotly.express

---

##  4. Exemplos de Gráficos de Linha

### Matplotlib

- `plt.plot()` com ajustes de cor e rótulos.
  
![1](https://github.com/user-attachments/assets/9888acea-ebca-4257-ae4e-f1353a2d65a6)

- Uso de `plt.xticks()` para personalizar eixos.
  
![2](https://github.com/user-attachments/assets/e2f14bb4-caef-4889-92a9-abfac9ae40c7)

Subgráficos com `plt.subplots()`.

![3](https://github.com/user-attachments/assets/5c2f9c45-e864-4814-8395-7eb1dd10a6f8)

Ajuste de escala com `ax.set_ylim()`.

![4](https://github.com/user-attachments/assets/061eaec7-2141-44dc-a1af-88404fcd46b4)

---

### `plotly.express`

- Interatividade com `px.line()`.
  
![2](https://github.com/user-attachments/assets/5cdc2720-4146-4dca-9837-911d9fcd03de)

- Ajustes com `fig.update_layout()` e `fig.update_traces()`.

![3](https://github.com/user-attachments/assets/74cd2206-b40c-4f74-adb8-3950e5e1649b)

![5](https://github.com/user-attachments/assets/01933cb0-0378-4890-8590-787f1dec359a)

- Inclusão de marcadores (`markers=True`) e exportação para web.

![4](https://github.com/user-attachments/assets/7b9367b4-31f2-41a4-b011-6d979eabf454)

---

## 5. Exemplos de Gráficos de Barras

### matplotlib

- Gráficos de barras verticais com `ax.bar()` e horizontais com `ax.barh()`.

![1](https://github.com/user-attachments/assets/58f959d4-4b0d-4e4e-8872-b0601fc09327)

![2](https://github.com/user-attachments/assets/cbb2110d-eab7-4000-b001-0080c7ee1c59)

- Destaque para países específicos, como o Brasil, com alteração de cor e anotações.
  
![1](https://github.com/user-attachments/assets/ff2620f1-6a49-4682-b4f2-1af1a3f9c9f2)

- Remoção de moldura e eixo X para visual mais limpo e foco no conteúdo.

![4](https://github.com/user-attachments/assets/9ed80da4-b9bf-446c-9742-872780345a2a)

### `seaborn`

- Criação de gráficos com `sns.barplot()` com diferentes paletas.
  
![1](https://github.com/user-attachments/assets/17b07cce-2117-425b-b46f-dd52e4489cb4)

Aplicação de diferentes paletas de cores, como:

- `palette='Blues'`
  
![2](https://github.com/user-attachments/assets/8c66860d-5f2c-4a8a-8e2f-316dbdb3632e)

- `palette='rocket'`
  
![3](https://github.com/user-attachments/assets/2a650eab-d17e-40e9-83de-c1a1f8aeb448)

- `palette='tab10'`
  
![4](https://github.com/user-attachments/assets/84a94e3d-81cc-4bf6-b855-3f38344a9116)

- Uso de temas visuais com `sns.set_theme(style=...)`, variando entre:
- `dark`
  
![1](https://github.com/user-attachments/assets/a686bf0a-d6d5-4ec2-8f96-f950568c780f)

- `white`

![22](https://github.com/user-attachments/assets/81be4b4b-c11f-40a3-9397-a20beac04a93)

- `ticks`
  
![2](https://github.com/user-attachments/assets/50cef5fa-68da-4127-ba9b-f436d244d4b8)

- Refinamento do layout gráfico com `sns.despine()`.
  
![33](https://github.com/user-attachments/assets/96d6a6a4-a02c-4507-bc87-10fbbeb8cbfe)

---

## 6. Agradecimentos

Agradeço à instrutora **Valquíria Alencar** pela clareza didática e ao programa **Oracle Next Education (ONE)** em parceria com a **Alura**, que proporcionaram os aprendizados aplicados neste projeto.

---

## 7. Documentação das Bibliotecas:

https://matplotlib.org/

https://matplotlib.org/stable/gallery/color/named_colors.html

https://seaborn.pydata.org/

https://seaborn.pydata.org/tutorial/color_palettes.html

https://plotly.com/python/plotly-express/
