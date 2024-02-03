# Trabalhando com Machine Learning na Prática no Azure ML

1- Buscar pelo serviço de machine learning e criar um recurso no Azure

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/01.png)


2- Em seguida criamos o recurso

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/02.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/03.png)

3- Ao criar podemos acompanhar o status do deploy

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/04.png)
![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/05.png)

4 - E ir para o estúdio de criação

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/06.png)


5- Espaço de trabalho

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/07.png)


6- Acessamos o ML Automatizado e criar um novo trabalho de machine learning automatizado

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/08.png)


7- Iniciamos a criação

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/09.png)


8- Selecionamos o tipo de tarefa como regressão e criar

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/10.png)


9- Criamos um ativo de dados

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/11.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/12.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/13.png)


10- Definir a coluna de destino e exibir definições de configurações adicionais como as métricas primarias e os modelos permitidos

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/14.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/15.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/16.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/17.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/18.png)


11- Seguir com os limites

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/19.png)


12 - Validação

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/20.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/21.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/22.png)


13- Enviar trabalho de treinamento e aguardar a finalização

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/23.png)

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/24.png)

14- Métricas melhor do modelo criado

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/25.png)

15- Implantando o melhor modelo com as configurações

Nome : prever-alugueis

Descrição : Prever aluguel de bicicletas

Tipo de computação : Instância de Contêiner do Azure

Habilitar autenticação : selecionado

Após a implantação do ponto de extremidade faremos o teste dele com o json de pontos de extremidade

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/26.png)


17- Teste gerado e previsão realizada

![](https://github.com/joaopsantana/azureAI900/blob/main/azuremachinelearning/images/27.png)

