# Como instalar wls2 no windows 10.

## Habilitar o subsistema.
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

obs: Para atualizarmos para o WSL 2, precisamos estar executando o Windows 10 na versão 1903 ou superior, com o Build 18362 ou superior.
Também é importantíssimo habilitar o recurso de virtualização na Bios (Intel virtualization technology). Caso contrário o WSL 2 não poderá ser utilizado.

## Habilitar o recurso de maquina virtula.
```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

## Baixar o pacote de atualização do kernel do Linux.
[Aqui.](https://learn.microsoft.com/pt-br/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package)

## Definir o WSL 2 como a sua versão padrão
```
wsl --set-default-version 2
```
## Aconselho usar Ubuntu 20.04 ou distro de sua preferencia.

## Definir username e senha e pronto.