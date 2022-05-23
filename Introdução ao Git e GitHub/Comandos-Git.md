## GIT

### Estados
 - Modificado (modified);
 - Preparado (staged/index)
 - Consolidado (comitted);

### Ajuda

#### Geral
- git help

#### Comando específico
- git help add
- git help commit
- git help <qualquer_comando_git>


###Configuração

#### Geral

As configurações do GIT são armazenadas no arquivo .gitconfig localizado dentro do diretório do usuário do Sistema Operacional (Ex.: Windows: C:\Users\Documents and Settings\Leonardo ou *nix /home/leonardo).

As configurações realizadas através dos comandos abaixo serão incluídas no arquivo citado acima.

####  Setar usuário
- git config --global user.name "Leonardo Comelli"
####  Setar email
- git config --global user.email leonardo@software-ltda.com.br
#### Setar editor
- git config --global core.editor vim
####  Setar ferramenta de merge
- git config --global merge.tool vimdiff
####  Setar arquivos a serem ignorados
- git config --global core.excludesfile ~/.gitignore
####  Listar configurações
- git config --list
