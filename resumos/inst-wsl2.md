Para instalar o Windows Subsystem for Linux (WSL) no Windows 10 e 11, siga estes passos:
1. Verifique a sua versão do Windows:
Se estiver a usar o Windows 10, precisa de uma versão 2004 ou superior (Build 19041 ou superior). 
Se estiver a usar o Windows 11, precisa de uma versão 21H2 ou superior. 
2. Habilite os recursos necessários (se necessário):
Abra o PowerShell ou Prompt de Comando do Windows como administrador. 
Execute os seguintes comandos:
'''dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart'''
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart 
Reinicie o computador. 
3. Baixe e instale o kernel do Linux (se necessário):
Se estiver a usar o WSL 2, baixe e instale o pacote de atualização do kernel do Linux. 
Siga as instruções fornecidas na página de download da Microsoft ou use o instalador direto. 
4. Instale o WSL:
Abra o PowerShell ou Prompt de Comando do Windows como administrador.
Execute o comando: wsl --install.
Reinicie o computador. 
5. Defina o WSL 2 como versão padrão (se necessário):
Abra o PowerShell como administrador.
Execute o comando: wsl --set-default-version 2. 
6. Instale a distribuição Linux desejada:
Acesse a Microsoft Store e procure a distribuição Linux que quer instalar (ex: Ubuntu, Debian, Fedora). 
Clique em "Obter" para instalar a distribuição. 
Após a instalação, inicie a distribuição Linux a partir do menu Iniciar. 
7. Configuração inicial da distribuição Linux:
Siga as instruções para criar um usuário e senha.
Abra o terminal da distribuição Linux e execute comandos Linux, como sudo apt update e sudo apt upgrade. 
Dicas:
Para ver uma lista de distribuições Linux disponíveis para download na loja online, use o comando: wsl --list --online ou wsl -l -o. 
Se encontrar problemas durante a instalação, pode consultar a secção de instalação do guia de solução de problemas do Learn Microsoft. 
Para ver informações sobre as principais diferenças entre o WSL 1 e o WSL 2, visite o Microsoft. 
Se quiser usar também a versão WSL 1, terá de instalar componentes opcionais. 
Para instalar aplicações com interface gráfica no WSL, veja o guia da PCGuia. 
