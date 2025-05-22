# segmentacao-clientes-kmeans
Projeto de clusterização de clientes com K-Means utilizando Python, pandas, seaborn e scikit-learn.

#  Segmentação de Clientes com K-Means

Este projeto aplica **clusterização com o algoritmo K-Means** para segmentar clientes com base em suas características de **idade**, **renda mensal** e **score de gastos**. A ideia é simular como empresas podem utilizar análise de dados para identificar perfis de consumidores e tomar decisões mais estratégicas em marketing, produto e relacionamento.

---

## Arquivos do Projeto

| Arquivo | Descrição |
|--------|-----------|
| `clientes_simulados.csv` | Base de dados fictícia com 200 clientes |
| `segmentacao_clientes.ipynb` | Notebook com o passo a passo completo da análise |
| `graficos_metodos_kmeans.png` | Visualização do método do cotovelo e silhouette |
| `visualizacao_clusters.png` | Gráfico final com os clusters identificados |

---

## Objetivos

- Aplicar o algoritmo K-Means para segmentação de clientes
- Encontrar o número ideal de clusters usando:
  - Método do Cotovelo
  - Coeficiente de Silhouette
- Visualizar os grupos formados
- Interpretar perfis de consumo e sugerir ações estratégicas

---

## Etapas do Projeto

1. Análise exploratória da base de dados
2. Padronização com `StandardScaler`
3. Determinação do número ideal de clusters (`Elbow + Silhouette`)
4. Aplicação do `KMeans` com 4 clusters
5. Visualização dos grupos
6. Interpretação estratégica

---


##  Interpretação dos Clusters

| Cluster | Perfil | Renda Média | Score Médio | Estratégia Sugerida |
|--------|--------|--------------|--------------|----------------------|
| **0 (azul)** | Alta renda, baixo gasto | R$ 12.336 | 24.88 | Engajamento com benefícios |
| **1 (laranja)** | Voláteis, renda média | R$ 7.139 | 51.16 | Segmentação comportamental |
| **2 (verde)** | Alto valor, renda média | R$ 9.371 | 80.20 | Fidelização e campanhas premium |
| **3 (vermelho)** | Baixa renda e consumo | R$ 5.795 | 33.62 | Onboarding e campanhas educativas |

>  O modelo demonstrou boa capacidade de segmentar perfis distintos e pode ser adaptado para uso em cenários reais de CRM e marketing.

---

##  Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Autor

**Iago Alecrim Leite**  
Analista de Dados com foco em BI, Operações e Experiência do Cliente  
🔗 [LinkedIn](https://www.linkedin.com/in/iago-alecrim/)
