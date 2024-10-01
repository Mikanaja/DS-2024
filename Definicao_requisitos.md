// Tarefa da Quarta semana

1. Entendimento dos requisitos: Jogar o Smart Decisions Game pode ser um bom ponto de partida. Compreender o jogo e suas decisões de arquitetura te ajudará a identificar os principais desafios que o sistema de machine learning deve resolver.
2. Identificação de componentes principais:
    * Coleta de Dados: Um dos primeiros componentes pode ser o processo de captura de dados de entrada, o que inclui entender o que o jogo gera de dados e como seu modelo de ML pode usar esses dados.
    * Pré-processamento de Dados: Os dados precisarão ser limpos e preparados para que o modelo de ML possa funcionar corretamente.
    * Modelo de Machine Learning: A definição do tipo de algoritmo que será utilizado, como regressão, classificação ou clustering, além de métricas de performance.
    * Treinamento e Validação: A etapa onde você vai treinar o modelo com um conjunto de dados e validá-lo com outro.
    * Interface do Sistema: Como o sistema interage com o usuário, ou seja, como as decisões são apresentadas e os resultados exibidos no jogo.
3. Divisão por Critérios de Coesão e Acoplamento: Cada componente deve ser altamente coeso, ou seja, deve fazer bem sua função específica, e o acoplamento entre eles deve ser baixo. Isso tornará o sistema mais manutenível e modular, facilitando futuras expansões ou modificações.
4. Definição de Arquitetura Geral: Pense em quais padrões de design são adequados para garantir uma boa separação de responsabilidades. Talvez seja útil usar padrões como Model-View-Controller (MVC) para separar a lógica de machine learning da interface ou a arquitetura em camadas.
