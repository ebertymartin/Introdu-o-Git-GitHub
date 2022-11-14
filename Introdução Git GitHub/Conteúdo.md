![Introdução ao Git](:/a048259868cb476b9363b9f39322af21)
# INSTALE O [GIT](https://git-scm.com/downloads)

### GitHub fornece clientes desktop que incluem uma interface gráfica para as ações mais comuns em um repositório e atualiza automaticamente para a linha de comando do Git para cenários avançados.

GitHub Desktop para **[Windows](https://windows.github.com)**

GitHub Desktop para **[Mac](https://mac.github.com)**

Distribuições do Git para Linux e sistemas POSIX são disponíveis no
site oficial do Git SCM.
**[Git para todas plataformas](http://git-scm.com)**

![](:/421e749448c8489c9a150aa7f610d467)
# CONFIGURE A FERRAMENTA
### Configure informações de usuário para todos os repositórios locais.

**$ git config --global user.name "[nome]"**
Configura o nome que você quer ligado as suas transações de commit

**$ git config --global user.email "[endereco-de-email]"**
 Configura o email que você quer ligado as suas transações de commit

**$ git config --global color.ui auto**
Configura o email que você quer ligado as suas transações de commit

![](:/421e749448c8489c9a150aa7f610d467)
# CRIE REPOSITÓRIOS
### Inicie um novo repositório ou obtenha de uma URL existente

**$ git init [nome-do-projeto]**
Cria um novo repositório local com um nome específico

**$ git clone [url]**
Baixa um projeto e seu histórico de versão inteiro

![](:/421e749448c8489c9a150aa7f610d467)
# FAÇA MUDANÇAS
### Revise edições e crie uma transação de commit

**$ git status**
Lista todos os arquivos novos ou modificados para serem commitados

**$ git add [arquivo]**
Faz o snapshot de um arquivo na preparação para versionamento

**$ git reset [arquivo]**
Deseleciona o arquivo, mas preserva seu conteúdo

**$ git diff**
Mostra diferenças no arquivo que não foram realizadas

**$ git diff --staged**
Mostra a diferença entre arquivos selecionados e a suas últimas
versões

**$ git commit -m "[mensagem descritiva]"**
Grava o snapshot permanentemente do arquivo no histórico de versão

![](:/421e749448c8489c9a150aa7f610d467)
# MUDANÇAS EM GRUPO
### Nomeie uma série de commits e combine os esforços completos

**$ git branch**
Lista todos os branches locais no repositório atual

**$ git branch [nome-do-branch]**
Cria um novo branch

**$ git checkout [nome-do-branch]**
Muda para o branch específico e atualiza o diretório de trabalho

**$ git merge [branch]**
Combina o histórico do branch específico com o branch atual

**$ git branch -d [nome-do-branch]**
Exclui o branch específico

![](:/421e749448c8489c9a150aa7f610d467)
# REFATORE NOMES DOS ARQUIVOS
### Mude e remova os arquivos versionados

**$ git rm --cached [arquivo]**
Remove o arquivo do controle de versão mas preserva o arquivo
localmente

**$ git rm [arquivo]**
Remove o arquivo do diretório de trabalho e o seleciona para remoção

**$ git mv [arquivo-original] [arquivo-renomeado]**
Muda o nome do arquivo e o seleciona para o commit

![](:/421e749448c8489c9a150aa7f610d467)
# SUPRIMA O RASTREAMENTO
### Exclua arquivos e diretórios temporários

**.log
build/
temp-**
Um arquivo de texto chamado `.gitignore` suprime o versionamento acidental de arquivos e diretórios correspondentes aos padrões
específicados

**$ git ls-files --other --ignored --exclude-standard**
Lista todos os arquivos ignorados neste projeto

![](:/421e749448c8489c9a150aa7f610d467)
# SALVE FRAGMENTOS
### Arquive e restaure mudanças incompletas

**$ git stash**
Armazena temporariamente todos os arquivos rastreados modificados

**$ git stash list**
Lista todos os conjuntos de alterações em stash

**$ git stash pop**
Restaura os arquivos recentes em stash

**$ git stash drop**
Descarta os conjuntos de alterações mais recentes em stash

![](:/421e749448c8489c9a150aa7f610d467)
# REVISE HISTÓRICO
### Navegue e inspecione a evolução dos arquivos do projeto

**$ git log**
Lista o histórico de versões para o branch atual

**$ git log --follow [arquivo]**
Lista o histórico de versões para um arquivo, incluindo mudanças de nome

**$ git diff [primerio-branch]...[segundo-branch]**
Mostra a diferença de conteúdo entre dois branches

**$ git show [commit]**
Retorna mudanças de metadata e conteúdo para o commit especificado

![](:/421e749448c8489c9a150aa7f610d467)
# DESFAÇA COMMITS
### Apague enganos e crie um histórico substituto

**$ git reset [commit]**
Desfaz todos os commits depois de `[commit]`, preservando
mudanças locais

**$ git reset --hard [commit]**
Descarta todo histórico e mudanças para o commit especificado

![](:/421e749448c8489c9a150aa7f610d467)
# SINCRONIZE MUDANÇAS
### Registre um marcador de repositório e troque o histórico de versão

**$ git fetch [marcador]**
Baixe todo o histórico de um marcador de repositório

**$ git merge [marcador]/[branch]**
Combina o marcador do branch no branch local

**$ git push [alias] [branch]**
Envia todos os commits do branch local para o GitHub

**$ git pull**
Baixa o histórico e incorpora as mudanças

![](:/5716c17516da40e5b709ab2cb80a6b84)
![](:/ebb76c58358f48048d5171e16a490b10)
**[Referência](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf)**
https://training.github.com