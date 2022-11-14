![Captura de tela 2022-11-13 212348](https://user-images.githubusercontent.com/117953029/201561816-f15949b7-8773-4169-9a2a-dfa7e10a5e41.png)
# INSTALE O [GIT](https://git-scm.com/downloads)

### GitHub fornece clientes desktop que incluem uma interface gráfica para as ações mais comuns em um repositório e atualiza automaticamente para a linha de comando do Git para cenários avançados.

GitHub Desktop para **[Windows](https://windows.github.com)**

GitHub Desktop para **[Mac](https://mac.github.com)**

Distribuições do Git para Linux e sistemas POSIX são disponíveis no
site oficial do Git SCM.
**[Git para todas plataformas](http://git-scm.com)**

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201561997-567cd124-8c47-4b0c-9112-610384cb1fae.png)
# CONFIGURE A FERRAMENTA
### Configure informações de usuário para todos os repositórios locais.

**$ git config --global user.name "[nome]"**
Configura o nome que você quer ligado as suas transações de commit

**$ git config --global user.email "[endereco-de-email]"**
Configura o email que você quer ligado as suas transações de commit

**$ git config --global color.ui auto**
Configura o email que você quer ligado as suas transações de commit

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562091-c48aed42-e64b-4565-a74b-307b0ac39faa.png)
# CRIE REPOSITÓRIOS
### Inicie um novo repositório ou obtenha de uma URL existente

**$ git init [nome-do-projeto]**
Cria um novo repositório local com um nome específico

**$ git clone [url]**
Baixa um projeto e seu histórico de versão inteiro

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562139-3a47d7d5-b668-451f-b0ef-552655e00d21.png)
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

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562193-2d5f6f1f-b4c8-4131-b3f1-3a0cc421ba41.png)
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

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562252-68dc1635-ccec-4e7a-ba10-ebc2d80590fa.png)
# REFATORE NOMES DOS ARQUIVOS
### Mude e remova os arquivos versionados

**$ git rm --cached [arquivo]**
Remove o arquivo do controle de versão mas preserva o arquivo
localmente

**$ git rm [arquivo]**
Remove o arquivo do diretório de trabalho e o seleciona para remoção

**$ git mv [arquivo-original] [arquivo-renomeado]**
Muda o nome do arquivo e o seleciona para o commit

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562298-833a0a69-b724-4042-8559-49aaf5efa1b3.png)
# SUPRIMA O RASTREAMENTO
### Exclua arquivos e diretórios temporários

**.log
build/
temp-**
Um arquivo de texto chamado `.gitignore` suprime o versionamento acidental de arquivos e diretórios correspondentes aos padrões
específicados

**$ git ls-files --other --ignored --exclude-standard**
Lista todos os arquivos ignorados neste projeto

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562349-7cfc703e-3189-4126-83cb-e8952b1ae7a1.png)
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

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562403-5ccf34a0-f4b9-4d79-b00c-5f7c66e776b7.png)
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

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562450-3e1e6890-cb71-43d0-87ae-cdfed0bd3406.png)
# DESFAÇA COMMITS
### Apague enganos e crie um histórico substituto

**$ git reset [commit]**
Desfaz todos os commits depois de `[commit]`, preservando
mudanças locais

**$ git reset --hard [commit]**
Descarta todo histórico e mudanças para o commit especificado

![Captura de tela 2022-11-13 202247](https://user-images.githubusercontent.com/117953029/201562498-1d5787f5-d4c7-4ff1-ab50-615621209f1d.png)
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



![Captura de tela 2022-11-13 214957](https://user-images.githubusercontent.com/117953029/201562554-74a98081-4eee-472c-b2b6-d62b59876940.png)
![GIT-Tutorial-Para-Iniciantes](https://user-images.githubusercontent.com/117953029/201562576-5a6cb120-f42d-4c53-b1e0-4cab3a1f56a4.png)
**[Referência](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf)**
https://training.github.com
