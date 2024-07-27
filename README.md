# Git
- É um sistema de controle de versão;

Comandos:

- Comando para saber o caminho até a pasta do projeto
```bash
pwd
```

- inicia o git (repositório) no seu projeto
```bash
git init
```

- Verifica alterações de pastas e arquivos no projeto
```bash
git status
```

- Adiciona todos os arquivos e pastas modificados, ao stage area
```bash
git add .
```

- Comando usado para adicionar apenas um arquivo alterado para a área de preparação
```bash
git add fileName
```

- Cria e descreve um ponto na história
  - Um commit é quando você cria um ponto na história, ou seja, quando você registra as alterações do seu código em um repositório;
```bash
git commit -m "message here"
```

- Histórico de commits do projeto
```bash
git log
```

- Sair da tela de logs
```bash
git :
```

- Remove um arquivo
```bash
git rm --cached fileName
```

- Restaurar um arquivo
```bash
git restore fileName
```

- Para voltar em um ponto do passado 
  - Entre no histórico de commits
  - Selecione o id do ponto em que deseja voltar
```bash
git checkout 1619920
```

- Para voltar para a Main
```bash
git checkout main
```

- Comando usado especificamente para alternar entre branches ou criar novas
```bash
git switch 
```

```bash
git switch -c <new-branch-name>
```

- Visualizar a lista de branchs que temos atualmente no projeto
```bash
git branch
```

- Comando para atualizar as informações do projeto remoto
```bash
git fetch
```

# Github

* Plataforma Online para colocar seus códigos
* Trabalhar em diversos projetos
* Perfil para mostrar seu trabalho

- Comando usado para enviar as alterações locais para um repositório remoto

```bash
git push
```

- Comando usado para trazer as alterações de um repositório remoto para o seu local

```bash
git pull
```

- Comando usado para clonar um repositório remoto para o seu computador local
```bash
git clone https://github.com/Taynara-Veloso/Git_-_Github.git
```
