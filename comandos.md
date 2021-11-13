# Comandos básicos de utilização do Git/GitHub
### Criar um novo repositório local do Git
- Criar uma pasta local para colocar os repositórios
- criar uma pasta com o nome do repositório
- Acessar a pasta local do repositório, clicar com o botão direito e selecionar "Git Bash Here" no menu de contexto
- Executar o comando: $ git init
### Criar um repositório no GitHub
- Acessar o menu de seus repositórios no GitHub
- Clicar no botão new, colocar o mesmo nome do repositíro local que foi criado e confirmar
### Listar as configurações do Git
- Executar o comando: $ git config --list
### Incluir propriedade da configuração do Git
- Iccnluir e-mail e usuário através das propriedades user.email e user.name
- Executar o comando: $ git config --global [propriedade] [valor]
### Excluir propriedade da configuração do Git
- Executar o comando: $ git config --global --unset [propriedade]
### Clonar repositório do GitHub
- Acessar o GitHub e acessar o repositório a ser clonado
- Clicar no botão "Code" e copiar o link para clonar via HTTPS
- Acessar a pasta local de seu worspace, clicar com o botão direito e selecionar "Git Bash Here" no menu de contexto
- Executar o comando: $ git clone [link]
### Apontar o caminho para o repositório remoto
- Executar o comando: $ git remote add origin [caminho do repositório]
### Listar repositórios remotos cadastrados
- Executar o comando: $ git remote -v
### Renomear a raiz do repositório principal como master
- Executar o comando: $ git branch -M master
### Enviar o repositório local para a nuvem
- Executar o comando: $ git push -u origin master
### Checar as alterações do repositório local e da área de staging
- Acessar o repositório: $ cd [caminho do repositório]
- Executar o comando: $ git status
### Adicionar controle de versão local das alterações do repositório local
- Executar o comando: $ git add *
### Enviar as últimas alterações para o repositório local
- Executar o comando: $ git commit -m "coloque aqui o comentário sobre a alteração realizada"
### Enviar todas as alterações locais para a nuvem do GitHub
- Executar o comando: $ git push origin master
### Atualizar o reposiório local com o conteúdo na nuvem
- Executar o comando: $ git pull
# Comandos Git Bash
### Listar os itens da pasta
- Utilizar o comando: $ ls
### Listar os itens da pasta, inclusive os itens ocultos
- Utilizar o comando: $ ls -a
### Criar uma nova pasta
- Utilizar o comando: $ mkdir [nome da pasta]
### Acessar um novo nível
- Utilizar o comando: $ cd [nome da pasta]
### Voltar um nível na pasta
- Utilizar o comando: $ cd ..
### Renomear uma pasta ou arquivo
- Utilizar o comando: $ mv [caminho anterior da pasta ou arquivo] [novo caminho da pasta ou arquivo]
