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