Predição da Qualidade de Vinhos

Descrição do Projeto:
Este projeto apresenta uma análise comparativa de modelos preditivos aplicados à estimativa da percepção sensorial da qualidade de vinhos tintos e brancos a partir de atributos físico-químicos[cite: 13]. O estudo constrói e avalia quatro abordagens: Regressão Linear Simples (OLS), Regressão Penalizada Lasso (L1), Mínimos Quadrados Parciais (PLS) e Redes Neurais Artificiais (MLP). O objetivo é entender os limites preditivos dos modelos estritamente lineares em comparação com arquiteturas não-lineares de aprendizado de máquina.

Dependências:
Para rodar o projeto, é necessário ter o Python 3 instalado, além das seguintes bibliotecas:
* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn

Como Executar:
1. Certifique-se de que os arquivos de dados originais "winequality-red.csv" e "winequality-white.csv" estão localizados exatamente na mesma pasta do script principal (elas forma colocadas na pasta "codigo", juntamente com hw2.py).
2. Abra o terminal ou prompt de comando no diretório do projeto.
3. Execute o script através do comando:
   python hw2.py

Autores e Contribuições:

* Iuri Fernandes Bastos: Redação da introdução do artigo, levantamento bibliográfico da fundamentação teórica e desenvolvimento matemático rigoroso (from scratch) do modelo de Regressão Linear Múltipla (OLS) a partir das equações normais.
* João Otávio Brasil Nascimento: Implementação analítica da Regressão Penalizada Lasso via descida por coordenadas, calibração do hiperparâmetro de regularização, e desenvolvimento da modelagem de redução de dimensionalidade supervisionada utilizando Mínimos Quadrados Parciais (PLS).
* Danilo Bezerra Vieira: Estruturação, treinamento e otimização da arquitetura de Redes Neurais Artificiais (Multi-Layer Perceptron), além da validação do desempenho não-linear (overfitting vs capacidade de generalização) sobre as bases de vinhos.
* Jonas Albuquerque Araújo: Análise crítica dos resultados, redação da discussão focada na parcimônia metodológica e na dicotomia do poder preditivo (linear vs não-linear), além da revisão técnica, estruturação e formatação final do documento acadêmico.