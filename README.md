# API PHP + MySQL com Docker

Esse projeto já está pronto pra rodar. Você só precisa ter o Docker instalado.

Passo 1: Baixe o projeto  
Clone o repositório com o comando:

git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git  
cd SEU_REPOSITORIO

Passo 2: Rode tudo com Docker  
No terminal, digite:

docker-compose up --build

Isso vai montar o ambiente com PHP, MySQL e carregar o banco automaticamente usando o arquivo banco.sql.  

Passo 3: Use a API  
Abra o navegador e acesse:

http://localhost:8000

Se carregar a página PHP, está funcionando.  

Banco de dados:  
- Host: localhost  
- Porta: 3307  
- Usuário: usuario_api  
- Senha: senha_api_segura  
- Banco: minha_api_db

Tudo isso já está configurado no arquivo .env e usado no docker-compose.yml.  

Passo 4: Parar tudo  
Quando quiser parar os containers, use:

docker-compose down

Requisitos:  
- Docker instalado  
- Docker Compose instalado  

Só isso. Baixou, rodou, funcionou.
