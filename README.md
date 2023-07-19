# desafioprojetoaws
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 19/07/2023 
Empresa: Abstergo Industries 
Responsável: Lucas Samuel Eustáquio de Farias

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Samuel Eustáquio de Farias. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: - Amazon EC2 Auto Scaling - Escalonamento Automático de Instâncias EC2 - Gerenciamento Eficiente de Capacidade 

O Amazon EC2 Auto Scaling permite que você dimensione automaticamente a capacidade das instâncias EC2 de acordo com a demanda. Com esse serviço, você pode definir políticas de escalonamento baseadas em métricas, como utilização da CPU ou tráfego de rede, para adicionar ou remover instâncias automaticamente. Dessa forma, você pode garantir que sempre tenha a quantidade ideal de instâncias em execução, evitando custos desnecessários devido a recursos ociosos. Além disso, o Amazon EC2 Auto Scaling também permite economizar dinheiro utilizando instâncias Spot, que são disponibilizadas a preços mais baixos.

A Abstergo Indrustries tem uma aplicação web que experimenta picos de tráfego durante determinados períodos do dia. Utilizando o Amazon EC2 Auto Scaling, eles podem definir políticas de escalonamento para adicionar automaticamente instâncias EC2 quando a demanda aumenta e removê-las quando a demanda diminui. Dessa forma, eles garantem que sempre tenham capacidade suficiente para lidar com os picos de tráfego, evitando a necessidade de manter instâncias ociosas durante os períodos de menor demanda, resultando em uma redução significativa nos custos de infraestrutura.

Etapa 2: - Amazon S3 - Armazenamento de Objetos Altamente Escalável - Armazenamento Eficiente e Econômico

O Amazon S3 é um serviço de armazenamento de objetos altamente escalável e durável. Ele permite armazenar grandes quantidades de dados de forma eficiente e a preços acessíveis. O Amazon S3 oferece diferentes classes de armazenamento, como o S3 Standard, S3 Intelligent-Tiering, S3 Glacier e S3 Glacier Deep Archive, cada uma com custos e características específicas. Ao utilizar corretamente as classes de armazenamento do Amazon S3, é possível reduzir significativamente os custos de armazenamento, movendo dados menos acessados para classes de menor custo.

A Abstergo precisa armazenar grandes volumes de dados de pesquisa e desenvolvimento, incluindo imagens, documentos e resultados de testes. Utilizando o Amazon S3, eles podem aproveitar as diferentes classes de armazenamento disponíveis. Por exemplo, eles podem configurar uma política de ciclo de vida para mover automaticamente dados menos acessados para a classe de armazenamento S3 Glacier, que possui um custo menor em comparação com a classe S3 Standard. Isso permite que eles economizem significativamente nos custos de armazenamento, mantendo seus dados acessíveis quando necessário.

Etapa 3: - AWS Lambda - Computação sem Servidor - Pague Apenas pelo Tempo de Execução

O AWS Lambda é um serviço de computação sem servidor que permite executar código sem a necessidade de provisionar ou gerenciar servidores. Com o AWS Lambda, você paga apenas pelo tempo de execução do seu código, sem custos fixos ou ociosos. Isso proporciona uma redução significativa de custos, principalmente em cargas de trabalho intermitentes ou com picos de demanda. Além disso, o AWS Lambda permite uma granularidade muito fina no dimensionamento, ou seja, você pode ajustar automaticamente o número de instâncias em execução com base na carga de trabalho, garantindo eficiência e economia de recursos.
Esses são três serviços da AWS que podem ajudar a diminuir custos imediatos para uma empresa farmacêutica. É importante lembrar que a escolha dos serviços adequados depende das necessidades e requisitos específicos da empresa.

A Abstergo  possui uma tarefa de processamento de dados que precisa ser executada periodicamente, mas não requer uma infraestrutura dedicada. Utilizando o AWS Lambda, eles podem escrever uma função que realiza o processamento necessário e configurar um evento agendado para acionar a função em intervalos específicos. Dessa forma, eles pagam apenas pelo tempo de execução da função, sem precisar se preocupar com a manutenção de servidores em execução constantemente. Isso resulta em uma redução significativa nos custos operacionais, já que eles pagam apenas quando a tarefa está em andamento, sem desperdício de recursos quando não há processamento necessário.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos imediatos ao levar os serviços para a Cloud AWS, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto:

Lucas Samuel Eustáquio de Farias
