# Desafio-Devops
Desafio Devops

# Requisitos

- Git (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
-  Docker (https://docs.docker.com/engine/install/)
- Docker Compose (https://docs.docker.com/compose/install/standalone/)

# Descrição

O desafio consiste em criar um ambiente básico para deploy automatizado de uma aplicação web simples, utilizando ferramentas essenciais de DevOps, como Docker, Bash e Git.

Para começar, clone o repositório utilizando o comando abaixo:
```bash
git clone https://github.com/Samuel-Diniz/DevOps
```

Em seguida, acesse o projeto utilizando o comando abaixo:
```bash
cd DevOps/
```   

Depois, execute o script utilizando o comando abaixo:
```bash
bash scripts/start_application.sh 
```            

Após a execução do script, caso o retorno seja "Health check bem-sucedido!", basta acessar a URL abaixo no navegador:
```bash
http://localhost/
```

Após realizar os testes no site e concluir as validações, execute o script abaixo para interromper a aplicação localmente:
```bash
bash scripts/stop_application.sh
```






