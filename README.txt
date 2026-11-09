Predição da Qualidade de Vinhos

Descrição do Projeto:
Este projeto apresenta uma análise comparativa de modelos preditivos aplicados à estimativa da percepção sensorial da qualidade de vinhos tintos e brancos a partir de atributos físico-químicos. O estudo constrói e avalia quatro abordagens: Regressão Linear Simples (OLS), Regressão Penalizada Lasso (L1), Mínimos Quadrados Parciais (PLS) e Redes Neurais Artificiais (MLP). O objetivo é entender os limites preditivos dos modelos estritamente lineares em comparação com arquiteturas não-lineares de aprendizado de máquina.

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

Funções:
Iuri Fernandes Bastos: Escreveu a introdução, fez a pesquisa de referências e programou o modelo de Regressão Linear (OLS) do zero.
João Otávio Brasil Nascimento: Criou o modelo Lasso, ajustou seus parâmetros e desenvolveu o modelo PLS.
Danilo Bezerra Vieira: Montou, treinou e avaliou o desempenho da Rede Neural nos dados dos vinhos.
Jonas Albuquerque Araújo: Analisou os resultados, escreveu a seção de discussão e fez a revisão e formatação final do documento.