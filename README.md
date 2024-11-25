
1. Criar o repositório no GitHub
Acesse GitHub e faça login na sua conta.
No canto superior direito, clique no ícone "+" e selecione New repository.
Preencha as informações:
Repository name: Dê um nome ao repositório.
Description (opcional): Descreva o projeto.
Escolha entre público (Public) ou privado (Private).
Marque a opção Add a README file (opcional, mas recomendado).
Clique em Create repository.

3. Configurar o repositório no computador
Caso você já tenha um projeto no seu computador:
Abra o terminal (ou Git Bash, no Windows).

Navegue até a pasta do projeto:

cd /caminho/para/seu/projeto

Inicialize o repositório local:

git init

Adicione os arquivos ao índice do Git:

git add .

Faça o primeiro commit:

git commit -m "Primeiro commit"

Conecte o repositório local ao remoto no GitHub:

git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git

Envie os arquivos para o GitHub:

git branch -M main
git push -u origin main

Caso você esteja começando um projeto do zero:
Siga o mesmo processo acima, mas antes de inicializar o repositório com git init, crie a pasta do projeto e adicione os arquivos desejados.

4. Verifique no GitHub
Acesse o repositório no site do GitHub para confirmar que os arquivos foram enviados.

Comandos básicos do Git
Adicionar arquivos ao commit:

git add nome-do-arquivo
ou para adicionar tudo:

git add .
Fazer um commit:

git commit -m "Mensagem do commit"
Enviar as alterações para o GitHub:

git push
Atualizar com alterações do repositório remoto:

git pull
Agora você está pronto para usar o Git e o GitHub de forma eficaz! 🎉

//////////

Passo 1: Faça o pull das mudanças remotas
No terminal, execute:

git pull origin main --allow-unrelated-histories
O argumento --allow-unrelated-histories é necessário porque os históricos do repositório local e remoto não estão relacionados.
Isso vai combinar as alterações do repositório remoto com o seu local.

Passo 2: Resolva conflitos (se houver)
Caso existam conflitos, o Git vai marcar os arquivos em conflito. Resolva os conflitos manualmente editando os arquivos indicados, e depois finalize com os comandos:

git add .
git commit -m "Resolvidos conflitos após o pull"
Passo 3: Tente o push novamente
Agora, envie as alterações para o repositório remoto:

git push -u origin main
