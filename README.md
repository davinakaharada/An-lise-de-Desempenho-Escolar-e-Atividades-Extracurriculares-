## 📚 Análise de Desempenho Escolar e Atividades Extracurriculares (TIMSS 2023)

Este projeto realiza uma **análise exploratória** do desempenho em matemática de alunos do 4º ano, usando dados da avaliação internacional **TIMSS 2023**. O foco é entender a relação entre **atividades fora da escola** e o desempenho na prova.

A análise incluiu o cálculo da média ponderada das notas e a separação de grupos de Outliers (Baixa e Alta Performance) para comparação de contexto.

***

### 🔑 Principais Descobertas e Gráficos

A análise identificou que **hábitos no lar e condições de estudo** estão correlacionados com o desempenho.

#### 1. Distribuição de Desempenho
A maior parte dos alunos possui média entre 400 e 550 pontos. Os Outliers de Alta Performance ficaram acima de 783 pontos e os de Baixa Performance ficaram abaixo dos 208 pontos.

<img width="697" height="510" alt="image" src="https://github.com/user-attachments/assets/c9b864a4-6976-4e1d-becb-d5121a574676" />

#### 2. Relação com Hábitos no Lar
<img width="866" height="798" alt="image" src="https://github.com/user-attachments/assets/5bee82bf-fc3a-4a4b-98b4-cacb3513d1a8" />

Foi identificada uma **pequena correlação negativa** onde alunos com o hábito de contar coisas ou ler livros tendem a ter uma média maior nas avaliações.

* **Leitura de Livros:** A média é $\approx \text{502.9}$ para quem lê **Frequentemente** e $\approx \text{468.8}$ para quem lê **Nunca/Quase Nunca**.
* **Contar Coisas:** A média é $\approx \text{497.8}$ para quem conta **Frequentemente** e $\approx \text{468.6}$ para quem conta **Nunca/Quase Nunca**.

#### 3. Contexto dos Outliers (Leitura e Estrutura)

As diferenças contextuais entre os grupos de desempenho extremo reforçam a importância do apoio familiar e do ambiente:

* **Leitura pelos Pais:** Pais de alunos de Alta Performance leem com mais frequência (38.7% frequentemente, 61.3% às vezes). Já **20%** dos pais de alunos de Baixa Performance **nunca ou quase nunca** leem.
  <img width="991" height="591" alt="image" src="https://github.com/user-attachments/assets/d62978b5-fcc7-474d-9838-bf48f5dcbb28" />

* **Mesa de Estudo:** A média para a posse de mesa de estudo é significativamente melhor no grupo de Alta Performance (1.15) do que no grupo de Baixa Performance (1.29).
* **Posse de PC:** A posse de um computador próprio **não tem grande influência** no desempenho dos alunos (cerca de 67% em ambos os grupos).
  <img width="955" height="624" alt="image" src="https://github.com/user-attachments/assets/a0ed9e2e-8baf-497e-9006-97b4ca9b51d0" />

***

### 💡 Conclusão

O estudo pode servir de base para o desenvolvimento de soluções de **Educação Personalizada** usando **Inteligência Artificial (IA)**, visando apoiar estudantes com dificuldades e oferecer enriquecimento para os de alta performance.

***

### 🛠️ Como Rodar o Projeto

1.  **Baixe** os seguintes arquivos de dados na [fonte](https://basedosdados.org/dataset/cc4909ba-67ea-460a-9666-1e199f02afc7?table=9cb42f24-cb1d-46d6-bbc8-15744d6290ad):
    * `home-context-grade-4.csv`
    * `student-achievement-grade-4.csv`
    * `student-context-grade-4.csv`
2.  Garanta que os arquivos de dados estejam no **mesmo diretório** do notebook (`timss.ipynb`).
3.  Abra o notebook (`timss.ipynb`) no **Google Colab** ou em seu ambiente Jupyter local.
4.  **Execute** as células em sequência.
