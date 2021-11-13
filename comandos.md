# Comandos básicos de utilização do Git/GitHub
### Clonar repositório do GitHub
- Acessar o GitHub e acessar o repositório a ser clonado
- Clicar no botão "Code" e copiar o link para clonar via HTTPS
- Acessar a pasta local de seu worspace, clicar com o botão direito e selecionar "Git Bash Here" no menu de contexto
- Executar o comando: $ git clone [link]
### Checar as alterações do repositório local e da área de staging
- Acessar o repositório: $ cd [caminho do repositório]
- Executar o comando: $ git status
### Adicionar controle de versão local das alterações do repositório local
- Executar o comando: $ git add .
### Enviar as últimas alterações para o repositório local
- Executar o comando: $ git commit -m "coloque aqui o comentário sobre a alteração realizada"
### Enviar todas as alterações locais para a nuvem do GitHub
- Executar o comando: $ git push origin master
### Atualizar o reposiório local com o conteúdo na nuvem
- Executar o comando: $ git pull
### Listar as configurações do Git
- Executar o comando: $ git config --list
### Incluir propriedade da configuração do Git
- Executar o comando: $ git config --global [propriedade] [valor]
### Excluir propriedade da configuração do Git
- Executar o comando: $ git config --global --unset [propriedade]
### Apontar o caminho repositório remoto
- Executar o comando: $ git remote add origin [caminho do repositório]
### Criar um novo repositório do Git
- Acessar a pasta local de seu worspace, clicar com o botão direito e selecionar "Git Bash Here" no menu de contexto
- Executar o comando: $ git init
### Listar repositórios remotos cadastrados
- Executar o comando: $ git remote -v
# Comandos Git Bash
### Renomear uma pasta ou arquivo
- Utilizar o comando: $ mv [caminho anterior da pasta ou arquivo] [novo caminho da pasta ou arquivo]
