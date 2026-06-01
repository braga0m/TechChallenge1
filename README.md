# Tech Challenge - Fase 1: Case NPS Preditivo 🚀

[cite_start]Este repositório contém a resolução do **Tech Challenge (Fase 1)** da Pós-Tech[cite: 1, 2]. [cite_start]O objetivo principal é analisar dados operacionais de um e-commerce para entender as variações do Net Promoter Score (NPS) e propor estratégias preditivas e preventivas para a melhoria da experiência do cliente[cite: 8, 9, 12, 13].

---

## 📌 Tópicos do Desafio

[cite_start]O projeto foi desenvolvido abordando os seguintes pilares obrigatórios propostos pelo case[cite: 19, 101]:

### 1. Entendimento do Negócio
* [cite_start]**Problema Resolvido:** Mitigar a alta variabilidade do NPS e antecipar gargalos na jornada de compra antes da aplicação da pesquisa[cite: 9, 11, 12].
* [cite_start]**Importância do NPS:** Análise do impacto direto do indicador em indicadores de e-commerce como Recompra, Boca a Boca e *Market Share*[cite: 23, 26, 27, 28, 29].
* [cite_start]**Áreas Beneficiadas:** Como os insights apoiam de forma prática as áreas de Logística, Atendimento, Produto e Estratégia[cite: 15, 24].

### 2. Definição da Target
* [cite_start]**Variável Alvo:** Definição e justificativa conceitual da variável `nps_score` como métrica de satisfação[cite: 34, 35, 94].
* [cite_start]**Momento de Coleta e Riscos:** Avaliação crítica sobre o momento em que o dado é coletado e os riscos de uma utilização inadequada para o negócio[cite: 36, 37].

### 3. Análise Exploratória dos Dados (EDA)
* [cite_start]**Gargalos Operacionais:** Identificação dos fatores mais críticos que geram clientes detratores (ex: atrasos, tentativas de entrega, tempo de suporte)[cite: 40, 42, 67, 68].
* [cite_start]**Ponto de Ruptura:** Análise do limite tolerável pelo cliente antes do declínio drástico da satisfação[cite: 43].
* [cite_start]**Perfil de Clientes:** Segmentação prática explicada sob uma ótica gerencial e de negócios[cite: 44, 45].

### 4. Estratégia Preditiva (Desafio Opcional)
* [cite_start]**Abordagem de IA:** Reflexão teórica e técnica sobre o uso de modelos de Regressão (escala contínua) vs. Classificação (satisfeitos vs. insatisfeitos) para prever a satisfação antecipadamente[cite: 47, 49, 51, 52].
* [cite_start]**Pipeline em Python:** Preparação das variáveis de entrada, separação dos dados, escolha do algoritmo e métricas de avaliação voltadas ao negócio (quando implementado)[cite: 53, 54, 55, 56, 57, 58].

---

## 📂 Estrutura de Pastas

[cite_start]Organização do repositório seguindo as boas práticas exigidas[cite: 106]:
```text
├── data/               # Base de dados histórica do NPS
├── notebooks/          # Scripts e Jupyter Notebooks das análises (EDA e Modelagem)
├── models/             # Arquivos de modelos preditivos salvos (.pkl / .artifacts)
├── reports/            # Apresentação gerencial (slides) e relatórios de suporte
└── README.md           # Documentação principal do projeto
