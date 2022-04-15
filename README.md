# DIO - Introdução Git e GitHub

### Sub-Módulos

- [Receitas](https://github.com/reneesalles/dio-introducao-git-github-livro-receitas)
  
### Links Úteis

- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax)

### Anotações

- configurações git:
  - email
  
        git config --global user.email "[email]"
        
  - nome
    
	    git config --global user.name "[nome]"

- clonar um repositório existente:
    
        git clone [url]

- inicializar um repositório local novo:
    
	    git init

- verificar o status do repositório:
    
	    git status

- adicionar alterações:
  - pasta inteira
    
	    git add .

  - arquivo específico
    
	    git add [file]

- resetar alterações:
  - pasta inteira
    
	    git reset .

  - arquivo específico
    
	    git reset [file]

- comitar alterações:
    
	    git commit -m "[message]"

- enviar commits:

        git push

- puxar alterações do repositório remoto para o repositório local:

        git pull
