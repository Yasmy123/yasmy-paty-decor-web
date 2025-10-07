# Publicar este proyecto en GitHub Pages (paso a paso)

## Opción A — Navegador (sin comandos)
1. https://github.com → New repo público `yasmy-party-decor-web`.
2. Add file → Upload files → arrastra **todo el contenido** del proyecto.
3. Commit changes.
4. Settings → Pages → Build and deployment → **Deploy from a branch** → Branch: `main` / **root**. Guardar.
5. URL: `https://TU_USUARIO.github.io/yasmy-party-decor-web/`

## Opción B — Con Git
```bash
git clone https://github.com/TU_USUARIO/yasmy-party-decor-web.git
cd yasmy-party-decor-web
# Copia aquí los archivos
git add .
git commit -m "Versión inicial"
git push origin main
```
Luego configura Pages como en A.4.
