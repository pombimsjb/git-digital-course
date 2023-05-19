# Curso digital: Git/Versionamento

## Aula 01 - Expeficicação e explicação das funcionalidades do Git
###### Foi feita uma explicação sobre as funcionalidades do Git, vantagens e motivos para utilização do mesmo.




------------
## Aula 02 - Instalação do Git, GitHub e do VSCode (incluindo extensão: GitLens)
###### Foi apresentado um tutorial de instalação e configuração dos programas necessários para aula.


------------
## Aula 03 - Criação inicial de pasta de projeto
###### Explicação e solicitação de criação das pastas do projeto, tanto no pc quanto no GitHub.
* Foi criado o repositório na pasta local /CURSOS/SANTANDER CODERS/
* Foi criado o repositório na pasta remota git-digital-course

------------
## Aula 04 - Gravando mudanças no repositório 
###### Explicações de status dos arquivos no git, e comandos para manuseio dos mesmos.
*   **STATUS UNMODIEFIED** -> É quando um arquivo foi mapeado pelo GIT. Já passou de *Staged* e já foi feito *Commit* do mesmo, ou seja arquivo foi salvo modificação e aguarda atualização na branch.
*   **STATUS MODIFIED** -> Arquivo contém alterações a serem passadas atráves de *Commit*.
* **STAGED** -> Arquivo pronto para receber *Commit* e ser enviado ao repositório remoto.

Comando Utilizados:
- `git status` -> Verifica se houve alteração no arquivo.
- `git add "nomeArquivo"` -> Adiciona o arquivo na lista *Staged* para ser possível o *Commit* do mesmo.
------------
## Aula 05 - Git Commit, Git Diff e rm
###### Explicados as funções commit e diff do git, porém rm citado no título da aula não foi apresentado.
Comandos utilizados:
- `git diff` -> Exibe as alterações realizadas no arquivo. Onde em <span style="color:green">verde</span> representa o que foi acrescentado no repositório e em <span style="color:red">vermelho</span> o que foi removido.
- `git diff - -staged` -> Mesmo procedimento anterior, porém exibe dos arquivos em ***STAGED***
- `git commit -m "mensagem" `-> Realiza o Commit das alterações realizadas o texto "mensagem" deve ser alterado de preferência por informações coesas sobre as alterações realizadas.

------------
## Aula 06 - Git Log e restore
###### Explicada as funções de log e restore do git
Comandos utilizados:
- `git log` -> Retorna um histórico dos últimos Commits realizados.
- `git restore "nomeDoArquivo"` -> Cancela às alterações realizadas.
- `git restore --staged` -> Restaura o arquivo ***Staged*** para ***Modified***


------------
## Aula 07 - Repositórios remotos
######  Foram aplicados métodos de manuseio do repositório remoto.

Comandos utilizados:
- *`git push origin master`* -> Envia os arquivos em Staged para o repositório remoto.
	(origin master representa o repositório de origem(origin) e a branch alvo)
- *`git remote`* -> Visualiza dados no repositório remoto.
- *`git pull`* -> Envia os dados para a branch no repositório remoto.
- *`git fench`* -> Trás uma cópia dos arquivos em segundo plano afim de comparação com os arquivos origem.
- *`git diff origin/master`* -> Faz a comparação entre os arquivos do repositório local e remoto.
------------
## Aula 08 - GitHub
###### Foi feita uma explicação básica da ferramenta.


------------
## Aula 09 - Git Branch
![Slide da aula](https://github.com/pombimsjb/git-digital-course/blob/master/GitBranch.png)

   Foi realizada uma explicação de como funcionam as *Branchs* e sua criação.
   
Comandos utilizados:
- `git branch "nomeDaBranch"` Comando para criação de uma nova *Branch*.
- `git log - -oneline - -decorate` Comando para visualizar um log com as informações dos commits e da localização atual(Branch) do *Git*.
- `git checkout "nomeDaBranch"` Comando para trocar a branch utilizada, Ex: sair da master para outra Branch ou vice e versa.

------------
## Aula 10 - Merging Branchs

   Foi explicado o método para dar merge nas branchs no GitHub via website:


Comandos utilizados:
- `git branch` retorna a lista de Branchs
