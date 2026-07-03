# Aplicación Web de Mapa Meteorológico Integral

Proyecto para la práctica de Desarrollo Web Integral sobre control de versiones, branching y merging.

## Archivos del proyecto

- `index.html`: estructura base de la aplicación.
- `style.css`: estilos visuales corporativos.
- `app.js`: lógica de consulta a OpenStreetMap y simulación meteorológica.

## Cómo ejecutar

Abrir `index.html` en el navegador o usar Live Server desde Visual Studio Code.

## Flujo de versionamiento solicitado

```bash
mkdir app-mapa-meteorologico
cd app-mapa-meteorologico
git init

git add index.html
git branch -M main
git commit -m "feat: estructura base del dashboard meteorologico"

git checkout -b feature-styles-and-logic
git add .
git commit -m "feat: interfaz visual y motor logico de procesamiento meteorológico"

git checkout main
git merge feature-styles-and-logic
```

## Subida a GitHub

```bash
git remote add origin https://github.com/TU-USUARIO/app-mapa-meteorologico.git
git push -u origin main
```

Después, activar GitHub Pages en `Settings > Pages`, seleccionando la rama `main`.
