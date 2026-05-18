# 🚀 Cómo publicar tu web en GitHub Pages

## Paso 1: Crear repositorio en GitHub
1. Ir a https://github.com
2. Click "New repository"
3. Nombre: `cm-belen-web`
4. Hacerlo público
5. Click "Create repository"

## Paso 2: Subir el código
```bash
cd /home/lucas/Documentos/Workspace/CM/cm-belen-web
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/tu-usuario/cm-belen-web.git
git push -u origin main
```

## Paso 3: Activar GitHub Pages
1. En GitHub, ir a Settings > Pages
2. Source: Deploy from a branch
3. Branch: main, folder: / (root)
4. Click Save

## Paso 4: Esperar
- Tomará 2-5 minutos
- La URL será: https://tu-usuario.github.io/cm-belen-web/

## Nota
El archivo `.github/workflows/deploy.yml` ya está configurado para deploy automático.
