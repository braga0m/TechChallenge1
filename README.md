# Tech Challenge - Fase 1: Case NPS Preditivo 

Este repositório contém o desenvolvimento do **Tech Challenge (Fase 1)** da Pós-Tech FIAP. O objetivo do desafio proposto é analisar dados operacionais de um e-commerce para entender a variabilidade do Net Promoter Score (NPS) e propor uma abordagem preditiva para agir de forma preventiva na experiência do cliente.

---
### Objetivo:

O objetivo deste trabalho é analisar os dados operacionais de pedidos, logística e atendimento de um e-commerce para compreender os fatores que geram alta variabilidade no Net Promoter Score (NPS). O escopo compreende o diagnóstico dos principais gargalos e pontos de ruptura na jornada do consumidor, a definição conceitual e crítica da métrica de satisfação, e a formulação de uma abordagem analítica e preditiva baseada em inteligência artificial. Com isso, busca-se capacitar a empresa a antecipar a percepção do cliente antes da aplicação da pesquisa formal, convertendo dados operacionais em insights acionáveis para tomadores de decisão.

### Descrição da base de dados:

A base de dados histórica unifica informações de três grandes pilares operacionais de um e-commerce (pedidos, logística e suporte), totalizando 19 variáveis focadas na jornada do cliente. O conjunto de dados mapeia características do consumidor (`customer_id`, `customer_age`, `customer_region`, `customer_tenure_months`), detalhes financeiros e de volume da compra (`order_id`, `order_value`, `items_quantity`, `discount_value`, `payment_installments`), e métricas de eficiência logística (`delivery_time_days`, `delivery_delay_days`, `freight_value`, `delivery_attempts`). Além disso, contempla indicadores críticos de atendimento e fricção (`customer_service_contacts`, `resolution_time_days`, `complaints_count`), uma métrica de fidelidade (`repeat_purchase_30d`), o score interno de satisfação (`csat_internal_score`) e, por fim, a variável alvo principal (`nps_score`), que registra a nota de 0 a 10 atribuída pelo cliente após o encerramento da jornada.

### Metodologia:

A metodologia empregada para o desenvolvimento deste projeto foi o CRISP-DM (Cross Industry Standard Process for Data Mining), uma estrutura cíclica e robusta voltada para ciência de dados e negócios. O processo teve início com o entendimento do modelo de e-commerce e a definição do impacto do NPS na operação , seguido pela compreensão profunda da base de dados e a realização da análise exploratória (EDA). Posteriormente, os dados passaram pelas fases de preparação e modelagem preditiva, avaliando abordagens de classificação e regressão para prever a satisfação, garantindo que a entrega final estivesse alinhada com as necessidades estratégicas e de tomada de decisão.

### Como reproduzir os resultados:

Para reproduzir os resultados, basta realizar o clone deste repositório do GitHub diretamente em sua máquina local utilizando o comando git clone. Com o repositório pronto, navegue até a pasta de códigos e execute os scripts em Python desenvolvidos para a análise. Esses scripts automatizados serão responsáveis por carregar a base de dados, realizar todo o tratamento e a análise exploratória, gerando os gráficos e os resultados finais do projeto de forma 100% reproduzível.

### Colaboradores

* **[Fernanda Florêncio da Silva](https://github.com/fernanda161082)** 
* **[Leonardo Gomes de Azevedo](https://github.com/Basscientist)**  
* **[Julianna Karina de Oliveira Siqueira](https://github.com/juliannasiqueira)**  
* **[Matheus Braga](https://github.com/braga0m)**  
* **[Matheus Crisóstomo](https://github.com/matheuscrstm)**




### 📂 Estrutura de Pastas

* dados - pasta com os dados do projeto.
* códigos - pasta com os scripts e notebooks do projeto.
* documentos - pasta com documentos auxiliares.

---
