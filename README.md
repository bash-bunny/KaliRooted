# Kali RootedCon

Script y cheatsheets para el curso.

## Cheatsheets

- [LinuxCheatsheet](Cheatsheets/LinuxCheatsheet.md)
- [GoogleDorkCheatsheet](Cheatsheets/GoogleDorkCheatsheet.md)

## Kali Linux

El script está preparado para ejecutar en una [Kali Linux](https://www.kali.org/) e instala todas las herramientas necesarias y crea 4 ficheros en la carpeta `$HOME` del usuario:
- 2 Ficheros en markdown con las cheatseet básicas de Dorking y Linux.
- 2 Ficheros en PDF con las cheatseet básicas de Dorking y Linux.

Todas las herramientas se instalan en la carpeta `$HOME/tools`.

## Instalación

```bash
# Descargar el script
wget https://raw.githubusercontent.com/bash-bunny/KaliRooted/refs/heads/main/setup.sh
# Dar permisos al script y ejecutarlo
chmod +x ./setup.sh && ./setup.sh
```

## Herramientas

- Captura de pantalla
  - Gowitness
  - Eyewitness
- Metadatos
  - metagoofil
  - pymeta
- Usernames
  - Whatsmyname
  - sherlock
  - nexfil
- Dominios
  - assetfinder
  - httprobe
  - waybackurls
  - crt_subs
- Frameworks
  - maigret
  - theharvester
- Misc
  - cheat