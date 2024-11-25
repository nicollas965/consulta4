
1. Criar o repositório no GitHub
Acesse GitHub e faça login na sua conta.
No canto superior direito, clique no ícone "+" e selecione New repository.
Preencha as informações:
Repository name: Dê um nome ao repositório.
Description (opcional): Descreva o projeto.
Escolha entre público (Public) ou privado (Private).
Marque a opção Add a README file (opcional, mas recomendado).
Clique em Create repository.
2. Configurar o repositório no computador
Caso você já tenha um projeto no seu computador:
Abra o terminal (ou Git Bash, no Windows).
Navegue até a pasta do projeto:
bash
Copiar código
cd /caminho/para/seu/projeto
Inicialize o repositório local:
bash
Copiar código
git init
Adicione os arquivos ao índice do Git:
bash
Copiar código
git add .
Faça o primeiro commit:
bash
Copiar código
git commit -m "Primeiro commit"
Conecte o repositório local ao remoto no GitHub:
bash
Copiar código
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git
Envie os arquivos para o GitHub:
bash
Copiar código
git branch -M main
git push -u origin main
Caso você esteja começando um projeto do zero:
Siga o mesmo processo acima, mas antes de inicializar o repositório com git init, crie a pasta do projeto e adicione os arquivos desejados.
3. Verifique no GitHub
Acesse o repositório no site do GitHub para confirmar que os arquivos foram enviados.

Comandos básicos do Git
Adicionar arquivos ao commit:

bash
Copiar código
git add nome-do-arquivo
ou para adicionar tudo:

bash
Copiar código
git add .
Fazer um commit:

bash
Copiar código
git commit -m "Mensagem do commit"
Enviar as alterações para o GitHub:

bash
Copiar código
git push
Atualizar com alterações do repositório remoto:

bash
Copiar código
git pull
Agora você está pronto para usar o Git e o GitHub de forma eficaz! 🎉
