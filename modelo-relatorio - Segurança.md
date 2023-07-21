# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 21/07/2023
Empresa: Abstergo Industries 
Responsável: Lucas Samuel Eustáquio de Farias

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Samuel Eustáquio de Farias. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Implementação de um Web Application Firewall (WAF)

Descrição de caso de uso:
O Web Application Firewall (WAF) é uma solução de segurança que pode ser implementada na camada de aplicação para proteger as aplicações web contra diferentes tipos de ataques, como injeção de SQL, cross-site scripting (XSS), entre outros. Ao utilizar o AWS WAF, é possível criar regras personalizadas que bloqueiam o tráfego malicioso ou suspeito antes que ele alcance a aplicação. O WAF pode ser integrado com serviços como o Amazon CloudFront e o Application Load Balancer para distribuir o tráfego de entrada, permitindo uma defesa em profundidade para as aplicações.

Medida 2: Configuração de Autenticação Multifator (MFA)

Descrição de caso de uso:
A autenticação multifator (MFA) é uma camada adicional de segurança que exige que os usuários forneçam duas ou mais formas de autenticação antes de acessarem os recursos da AWS. Ao configurar o MFA, os usuários precisarão fornecer algo que conhecem (senha) e algo que possuem (como um dispositivo móvel para receber um código de verificação único). Isso ajuda a reduzir o risco de acesso não autorizado, mesmo que as credenciais do usuário sejam comprometidas. A MFA pode ser aplicada a contas de usuário, IAM (Identity and Access Management) e mesmo ações de alto privilégio, garantindo uma camada extra de proteção aos recursos críticos.

Medida 3: Monitoramento de Segurança com o Amazon GuardDuty

Descrição de caso de uso:
O Amazon GuardDuty é um serviço de detecção de ameaças gerenciado que utiliza análise de inteligência artificial e machine learning para identificar atividades maliciosas ou não autorizadas em uma conta da AWS. Ele monitora eventos como tentativas de autenticação mal-sucedidas, comportamentos de tráfego incomuns e comunicação com endereços IP maliciosos conhecidos. Ao habilitar o Amazon GuardDuty, a empresa pode identificar possíveis brechas de segurança e tomar medidas proativas para mitigar riscos antes que ocorram incidentes graves. Além disso, o GuardDuty também pode ser integrado com outros serviços da AWS, como o AWS CloudTrail e o Amazon VPC Flow Logs, para obter uma visão completa e abrangente das atividades na infraestrutura.


## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado [benefícios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Lucas Samuel Eustáquio de Farias