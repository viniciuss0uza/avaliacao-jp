# avaliacao-jp
Avaliação JP

Repositório para os comandos do Git!

git --version;
    Verifica aversão do Git no windows.

git config --global user.name "nome":
    

git pull:
    Baixa objetos e referências do repositório remoto e mescla com a
branch atual. Para reverter o estado da branch local ao commit anterior ao pull, use git reset --hard <commit-hash>

git push:
    Envia commits do repositório local para o repositório remoto. Para desfazer essas mudanças use  git revert <commit-hash>

git init:
    Começa um novo repositório Git em um diretório que  já existe.

git status:
    Exibe como está o repositório.

git fatch:
    Baixa referências e objetos do repositório remoto.

git  checkout -b <branchname>:
    Cria uma nova branch, e ao criar é movido para essa nova branch. > Para excluir a branch use git branch -D <branchname> 
    E git checkoutt <previous-branchname> para voltar à branch anterior.

git checkout <branchname>:
    Muda para a branch que foi especificada. para voltar, basta usar o git checkout <previousbranchname>.

git commit -m "<description>":
    Commita as mudanças do índice com uma mensagem descrita

git branch -D <branchname>:
    Exclui a branch do repositório local que escolher (especificar).

git add <filename ou . >:
    Adiciona arquivos ao índice.
    Prepara os arquivos espesificados para o proximo commit.

git rm --cached <file>
    Remove os arquivos do índice (staging area), mas eles não são removidos do diretório.

git restore --staged <filename ou . >:
    Desfaz as mudançasque foram adicionadas na "staging area"(a´read de preparação), então ele, remove arquivos da área de preparação

git merge <branch>
    Faz a merge da branch atual na branch informada.

git branch
     Ela lista todas as branch que existe.