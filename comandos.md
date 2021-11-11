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
- Executar o comando: $ git push origin main
### Atualizar o reposiório local com o conteúdo na nuvem
- Executar o comando: $ git pull
