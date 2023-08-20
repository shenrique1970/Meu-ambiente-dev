# Instalar wsl2 no windows 10.

## Habilitar subsistema linux.
```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```


```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

```
- Definir wsl2 como padrão.
```
wsl --set-default-version 2
```