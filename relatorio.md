**Introdução**
A computação em nuvem diz respeito à disponibilidade de recursos de TI sob-demanda e pela internet. A AWS é uma das provedoras desses recursos, contendo serviços como o EC2. Esse serviço é capaz de fornecer máquinas virtuais, disponibilizando capacidade computacional. Essas máquinas virtuais são chamadas de instâncias EC2, que podem ser executadas em qualquer lugar do mundo. 
Esse relatório detalha o objetivo, método, resultado e conclusão obtidos na ponderada realizada para estudar as instâncias EC2 na AWS.

**Objetivo**
O propósito desse exercício é consolidar o entendimento dos assuntos estudados em relação à computação em nuvem até a semana 3. Para isso, o objetivo é utilizar o laboratório da AWS para criar uma instância de máquina EC2, realizar a configuração dessa instância e acessá-la com SSH. 

**Materiais**
Para conseguir realizar a atividade foi necessário utilizar o laboratório da AWS Academy, a ferramenta PuTTY e um relatório técnico da AWS sobre o acesso SSH ao EC2.

**Método**
O primeiro passo para iniciar a tarefa foi a inicialização do laboratório, entrando no painel da AWS e criando uma instância EC2 denominada "ponderada". Essa instância foi alocada na zona de disponibilidade us-east-1 e configurada para permitir receber acesso por SSH. Também foi criado um par de chaves RSA, nomeado chave-ponderada.ppk, formato necessário para ser utilizado com o PuTTY.

<div align="center">

<sub>Figura 1 - Etapa 1: Instância "Ponderada"</sub>

![Instância "Ponderada"](./imagens/ponderada_1.png)

</div>

Com a instância criada e em execução, a próxima etapa concentrou-se na ferramenta PuTTY. Neste aplicativo, foi necessário informar o endereço DNS público da máquina virtual juntamente com o usuário padrão, no formato _instance-user-name@instance-public-dns-name_, e selecionar o tipo de conexão como SSH.

<div align="center">

<sub>Figura 2 - Etapa 2</sub>

![Etapa 2](./imagens/ponderada_2.png)

</div>

Após fornecer essas informações, foi informada a chave privada que foi gerada e utilizada, fazendo upload do arquivo e, em seguida, clicando para acessar a máquina.

<div align="center">

<sub>Figura 3 - Etapa 3</sub>

![Etapa 3](./imagens/ponderada_3.png)

</div>

**Resultados**
Utilizando essas instruções, uma janela de terminal foi aberta, mostrando informações sobre o usuário, nome da chave e endereço IP utilizados para acessar a instância "ponderada", resultando em um acesso bem-sucedido.

<div align="center">

<sub>Figura 4 - Resultado </sub>

![Resultado](./imagens/ponderada_4.png)

</div>

**Conclusão**
Esse exercício incentivou de forma prática o estudo sobre a criação e acesso a uma instância EC2 na AWS. Além disso, com seus resultados e esse relatório desenvolvido, a atividade permitiu a demonstração da capacidade da aluna em realizar, analisar e documentar as tarefas propostas. 

Fontes:
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html
https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-cloud-computing