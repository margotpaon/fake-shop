# Fake Shop


## Variável de Ambiente
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.


## Desafio 2 - Kubernetes
Fase 02
Informações do desafio
Cenário
O piloto que você implementou foi um sucesso !!! Agora, a equipe está muito mais confiante em testar a plataforma de ecommerce em ambiente de testes e homologação em um ambiente escalável com containers. Então agora, está na hora de trabalharmos com o Kubernetes !!!


## Tarefa Prática

1. Criação do cluster Kubernetes
Crie o cluster Kubernetes na AWS utilizando o Elastic Kubernetes Service.

Criação e Teste do Contêiner
Faça um fork do projeto Fake Shop (https://github.com/KubeDev/fake-shop) para a sua conta do GitHub.
Crie o arquivo de manifesto de deploy da aplicação de ecommerce e faça o deploy no Kubernetes.
Realize os testes na aplicação.



Desafio 3 - Pipeline CI/CD
Fase 03
Informações do desafio
Cenário
O ecommerce Fake Shop está em produção !!! Mas agora, a empresa está passando por algumas dificuldades no processo de entrega e manutenção. E cabe a você ajudar a resolver. Todo o processo de deploy no Kubernetes está EXTREMAMENTE demorado, as equipes são mobilizada por 2 dias para fazer um deploy e quando a aplicação está em produção, não se tem nenhuma métrica e só se descobre que a aplicação está indisponível, quando o cliente entra em contato.


Tarefa Prática

1. Criação de pipeline CI/CD
Criar uma pipeline CI/CD com GitHub Actions para criar a imagem Docker e fazer o deploy no cluster Kubernetes.

2. Monitorar a aplicação
Fazer o Deploy do Prometheus com Grafana para monitorar a sua aplicação e o cluster Kubernetes.

Criação e Teste do Contêiner
Faça um fork do projeto Fake Shop (https://github.com/KubeDev/fake-shop) para a sua conta do GitHub.

Crie a pipeline CI/CD e envie um print com as dashboards no repositório em uma pasta chamada grafana.

Envie o link do seu repositório no GitHub com o projeto.
