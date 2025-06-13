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
  
![plt plot](https://github.com/user-attachments/assets/e88594b4-963d-4a1d-a94d-4c19ec31ef46)

- Uso de `plt.xticks()` para personalizar eixos.

![plt xticks](https://github.com/user-attachments/assets/7f8ac8cc-098a-44a8-9fd2-66b7f9f58b74)

- Subgráficos com `plt.subplots()`.

![Subgraficos com plt subplots](https://github.com/user-attachments/assets/877f629e-ccd3-4288-b8f2-9ccad64df958)

- Subgráficos com `.grid()`

![Subgráficos com  grid()](https://github.com/user-attachments/assets/80743bcc-3abd-4a70-8806-c9006d276bb2)

- Ajuste de escala com `ax.set_ylim()`.

![Ajuste de escala com ax set_ylim](https://github.com/user-attachments/assets/7f4729ba-d8a8-4e98-aa61-0c9f3e6a8deb)

- Uso de `marker='o'` marcador circular
  
![Uso de marker='o' marcador circular](https://github.com/user-attachments/assets/6bd73b61-da46-4864-b1a6-575f28b7b713)

---

### `plotly.express`

- Interatividade com `px.line()`.
  
![Interatividade com px line](https://github.com/user-attachments/assets/f83789ab-6964-4012-bf41-91d7b64a47c9)

- Ajustes com `fig.update_layout()` e `fig.update_traces()`.

![Ajustes com fig update_layout](https://github.com/user-attachments/assets/74f01b77-bff8-4a18-9000-abc12e3c0a51)

![Ajustes com fig update_traces](https://github.com/user-attachments/assets/eba221f5-89a7-4678-bb39-85dff6f618ee)

- Inclusão de marcadores (`markers=True`) e exportação para web.

![Inclusão de marcadores markers=True e exportação para web](https://github.com/user-attachments/assets/e55c4fbd-938a-4f74-9908-dc5a37f504a9)

---

## 5. Exemplos de Gráficos de Barras

### matplotlib

- Gráficos de barras verticais com `ax.bar()` e horizontais com `ax.barh()`.

![ax bar](https://github.com/user-attachments/assets/226d1b0d-1de3-41dd-aba0-4bf10300bf33)

![ax barh](https://github.com/user-attachments/assets/2e0331b3-ea98-424b-ac32-1af1ad4fba78)

- Destaque para países específicos, como o Brasil, com alteração de cor e anotações.
  
![Destaque específico Brasil alteração de cor e anotações](https://github.com/user-attachments/assets/7ccf83b5-56e4-41aa-8742-b45e843e48dd)

- Remoção de moldura e eixo X para visual mais limpo e foco no conteúdo.
  
![Remoção de moldura e eixo X](https://github.com/user-attachments/assets/28dcccb4-1b52-4156-b057-bde12e4fef4f)

### `seaborn`

- Criação de gráficos com `sns.barplot()` com diferentes paletas.
  
 ![sns barplot](https://github.com/user-attachments/assets/b9b45dac-69bf-4c6e-9ac8-6906a67fabd8)

Aplicação de diferentes paletas de cores, como:

- `palette='Blues'`
  
![palette=Blues](https://github.com/user-attachments/assets/d18b4a6d-f13f-48ee-a533-1859a7e75c63)

- `palette='rocket'`
  
![palette=rocket](https://github.com/user-attachments/assets/15d666c0-73bd-4864-bad1-fda2749f5de5)

- `palette='tab10'`
  
![palette=tab10](https://github.com/user-attachments/assets/5b9a9886-2a1e-476c-96b5-4f1dc37998ac)

- Uso de temas visuais com `sns.set_theme(style=...)`, variando entre:
  
- `dark`
  
![dark](https://github.com/user-attachments/assets/dcfb9f10-ba43-4021-bb7d-2b5817a6a0bc)

- `white`

![white](https://github.com/user-attachments/assets/d9ad776b-ffa1-438b-ba46-b691029e12fd)

- `ticks`
  
![ticks](https://github.com/user-attachments/assets/2d109cef-a582-48a6-9fc3-a0a42aa09d60)

- Refinamento do layout gráfico com `sns.despine()`.
  
  ![sns despine](https://github.com/user-attachments/assets/03412050-427e-4253-9929-1308c3f6ce03)

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
