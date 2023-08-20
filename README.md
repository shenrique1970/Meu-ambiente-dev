# Meu ambiente de desenvolvimento.
## Plataforma windows 10 e o wsl2 sub sistema ubuntu 20.04


- [O que é o wsl2?](https://learn.microsoft.com/pt-br/windows/wsl/about)
<p>Resumo: 
O WSL 2 é uma nova versão da arquitetura do Subsistema do Windows para Linux que capacita o Subsistema do Windows para Linux a executar binários ELF64 Linux no Windows. As metas principais dele são aumentar o desempenho do sistema de arquivos e adicionar compatibilidade completa com a chamada do sistema.</p>

- [wslg](https://learn.microsoft.com/pt-br/windows/wsl/tutorials/gui-apps)
<p>Resumo: 
WSLg (Windows Subsystem for Linux GUI)
Subsistema do Windows para Linux (WSL) agora dá suporte à execução de aplicativos de GUI do Linux (X11 e Wayland) no Windows em uma experiência de área de trabalho totalmente integrada.

O WSL 2 permite que os aplicativos de GUI do Linux se sintam nativos e naturais para uso no Windows.

Iniciar aplicativos Linux no menu Iniciar do Windows
Fixar aplicativos Linux na barra de tarefas do Windows
Usar alt-tab para alternar entre aplicativos Linux e Windows
Recortar + Colar entre aplicativos Windows e Linux
Agora você pode integrar aplicativos Windows e Linux ao fluxo de trabalho para uma experiência de área de trabalho perfeita.</p>


- [Instalar e começar a configurar o Terminal do Windows.](https://learn.microsoft.com/pt-br/windows/terminal/install)
<p>Resumo: 
O Windows Terminal é um aplicativo de terminal moderno, rápido, eficiente, poderoso e produtivo para os usuários de ferramentas e shells de linha de comando, como prompt de comando, PowerShell e WSL. Seus principais recursos incluem várias guias, painéis, suporte a caracteres Unicode e UTF-8, um mecanismo de renderização de texto acelerado por GPU e temas, estilos e configurações personalizados.</p>

- [O que é o git?](https://git-scm.com/doc)

- [O que é o github?](https://docs.github.com/pt)


## | Git github resumo |

##  Comandos iniciais.
| git init | inicia um repositório. |
| --- | --- |
| git status |  |
| git config --global user.name "Nome do usuário"
| git config --global user.email "seu@email.com” |  |
| git config --global init.defaultBranch main |  |
| git comfig --global --list |  |
| git add nome_do_arquivo
| git add . |  |
| git commit -m "Mensagem descritiva do commit” |  |
| git clone [url] |  |
| git branch 
| Mostra as branches existentes em um repositório |
| git branch -M nome_da_branch  | Renomeia a branch atul |
| git branch nome_da_branch  | Cria uma nova branch |
| git log |  |
| git log --oneline |  |
| git pull |  |
| git push |  |
| git restore |  |
| git commit --amend -m "" | altera o ultimo commit |
| git reset --soft <> |  |
| git reset --mixed <> |  |
| git reset --hard <> |  |
| git reflog |  |
| git checkout -b |  |
| git branch |  |
| git branch -v|  |
| git branch -d <teste>| deleta a branch teste  |
| git fetch origin main |  |
| git diff |  |
| git clone <https> --branch teste --single-branch |  |
| git stach |  |
| git stach list |  |

rm -rf .git desfaz o git init
