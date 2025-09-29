# Frontend-GH-Pages
Pasos:
1. Asegúrate de estar en la raíz de tu proyecto local de Frontend (Frontend-GH-Pages).
2. Crea la carpeta de configuración:
mkdir -p .github/workflows
3. Copia el contenido del bloque de código anterior y guárdalo en la nueva ruta:
Frontend-GH-Pages/.github/workflows/deploy.yml
4. Subir los Cambios a GitHub
git add .github/workflows/deploy.yml

# Haz un commit
git commit -m "feat: Added GitHub Actions pipeline for auto-deployment"

# Sube los cambios a la rama 'main' (esto disparará el pipeline)
git push origin main