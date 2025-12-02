📚 Análise de Desempenho Escolar e Contexto Social (TIMSS 2023)

Este projeto tem como foco a análise da correlação entre o desempenho em matemática de alunos do 4º ano e certas atividades e condições sociais/familiares identificadas na base de dados pública do TIMSS (Trends in International Mathematics and Science Study) de 2023.

🧐 Explicação e Objetivos
O estudo vai além dos fatores puramente pedagógicos, buscando entender como o ambiente fora da escola pode influenciar o aprendizado e os resultados acadêmicos dos alunos.

💡 Principais Focos de Análise:
Hábitos Cognitivos e Desempenho:

Foi investigada a relação entre a frequência com que os alunos leem livros ou contam coisas fora da escola e suas respectivas médias nas avaliações de matemática.

O resultado principal é que há uma correlação positiva entre a maior frequência dessas atividades e uma média mais alta. Isso sugere que a estimulação cognitiva precoce e contínua em casa pode ser um fator crucial.

Influência Parental (Leitura):

Uma comparação entre alunos de baixa e alta performance mostrou que os pais de alunos de alta performance leem livros com mais frequência para seus filhos.

No grupo de baixa performance, uma parcela significativa de pais nunca realiza essa atividade, destacando o papel essencial do envolvimento familiar na alfabetização e no desenvolvimento.

Tecnologia (Posse de Computador):

Foi analisado se a posse de um computador próprio pelo aluno demonstrava uma influência significativa no desempenho.

Curiosamente, a posse do equipamento não apresentou uma correlação forte com a alta performance, sugerindo que o mero acesso ao hardware pode não ser o fator mais decisivo, mas sim como a tecnologia é utilizada.

🚀 Conclusão e Futuro:
A análise dos dados do TIMSS reafirma a importância dos fatores sociais e familiares no sucesso acadêmico. O trabalho serve como uma base de reflexão e pesquisa para:

Educação Personalizada: Como podemos usar a análise de dados para identificar alunos em risco e criar intervenções direcionadas.

Inteligência Artificial (IA) e EaD: O estudo abre caminho para pensar como a IA e o Ensino a Distância (EaD) podem ser ferramentas fundamentais para estender a experiência educacional para o ambiente doméstico, criando experiências de aprendizado personalizadas que complementam o que acontece em sala de aula, especialmente para mitigar a ausência de estímulos familiares.

🛠️ Como Rodar a Análise no Google Colab
Para replicar a análise, os gráficos e os resultados apresentados no estudo, você deve executar o notebook timss.ipynb no Google Colaboratory.

1. Pré-requisitos
O notebook timss.ipynb exige a presença de três arquivos CSV, que devem ser carregados no ambiente de execução do Colab

student-context-grade-4.csv

student-achievement-grade-4.csv

home-context-grade-4.csv

2. Executando o Notebook
Acessar e Abrir: Carregue o arquivo timss.ipynb no Google Colab.

Carregar Dados: Execute a célula inicial que contém o código para carregar os arquivos CSV (certifique-se de que os nomes dos arquivos no Colab coincidem exatamente com os nomes no código).

Processar: Execute todas as células do notebook em ordem. O código está estruturado para fazer a limpeza, os joins (combinação) dos dados e gerar as visualizações.
