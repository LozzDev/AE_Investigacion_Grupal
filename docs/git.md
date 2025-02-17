# Guía de Git

## Instalación
- **Windows**: [Descargar instalador](https://git-scm.com/downloads)
- **Linux**: `sudo apt install git`
- **Mac**: `brew install git`

## Comandos básicos
```bash
git init
git add .
git commit -m "Mensaje descriptivo"
git push origin main
```

## Colaboración en GitHub
1. Crea una rama: `git checkout -b mi-rama`
2. Sube cambios: `git push origin mi-rama`
3. Abre un **Pull Request** en GitHub

## Seguridad
- Configura permisos de repositorio
- Usa claves SSH: `ssh-keygen -t ed25519`

## Firmar commits
```bash
git config --global commit.gpgsign true
git commit -S -m "Commit firmado"
```

## Conflictos
Ver ejemplo en: `/examples/merge-conflict.md`