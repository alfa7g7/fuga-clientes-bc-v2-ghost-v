# Instrucciones para Crear el Repositorio en GitHub

## Paso 1: Crear el Repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) y inicia sesión
2. Haz clic en el botón verde "New" o "New repository"
3. Completa la información del repositorio:
   - **Repository name**: `fuga-clientes-bc-v2-ghost-v`
   - **Description**: `Análisis de fuga de clientes utilizando variables fantasma - Proyecto de Grado II`
   - **Visibility**: Public o Private (según tu preferencia)
   - **NO marques** "Add a README file" (ya lo tenemos)
   - **NO marques** "Add .gitignore" (ya lo tenemos)
   - **NO marques** "Choose a license" (ya lo tenemos)

4. Haz clic en "Create repository"

## Paso 2: Conectar el Repositorio Local con GitHub

Una vez creado el repositorio en GitHub, ejecuta estos comandos en tu terminal:

```bash
# Agregar el repositorio remoto (reemplaza TU_USUARIO con tu nombre de usuario de GitHub)
git remote add origin https://github.com/TU_USUARIO/fuga-clientes-bc-v2-ghost-v.git

# Cambiar el nombre de la rama principal a 'main' (si es necesario)
git branch -M main

# Subir el código a GitHub
git push -u origin main
```

## Paso 3: Verificar la Subida

1. Ve a tu repositorio en GitHub
2. Verifica que todos los archivos estén presentes:
   - README.md
   - requirements.txt
   - LICENSE
   - .gitignore
   - Los notebooks de Jupyter
   - Las carpetas con datos y resultados

## Paso 4: Configuraciones Adicionales (Opcional)

### Configurar GitHub Pages (para mostrar el README)
1. Ve a Settings > Pages
2. En "Source", selecciona "Deploy from a branch"
3. Selecciona la rama "main" y la carpeta "/ (root)"
4. Haz clic en "Save"

### Agregar Topics al Repositorio
En la página principal del repositorio, haz clic en "Add topics" y agrega:
- `machine-learning`
- `data-science`
- `customer-churn`
- `ghost-variables`
- `python`
- `jupyter-notebook`

### Configurar Descripción del Repositorio
En la página principal, haz clic en "About" y agrega:
- Descripción: "Análisis avanzado de fuga de clientes utilizando técnicas de machine learning y variables fantasma"
- Website: (opcional)
- Topics: (como se mencionó arriba)

## Notas Importantes

- **Datos Sensibles**: Los archivos de datos (.xlsx, .pkl) están excluidos por el .gitignore por seguridad. Si necesitas incluirlos, modifica el .gitignore antes de hacer commit.

- **Tamaño del Repositorio**: Los notebooks de Jupyter pueden ser grandes. GitHub tiene un límite de 100MB por archivo.

- **Colaboración**: Si planeas trabajar con otros, considera hacer el repositorio público o agregar colaboradores.

## Comandos Útiles para el Futuro

```bash
# Ver el estado del repositorio
git status

# Ver los cambios
git diff

# Agregar cambios
git add .

# Hacer commit
git commit -m "Descripción de los cambios"

# Subir cambios
git push

# Bajar cambios (si trabajas en equipo)
git pull
```

¡Tu repositorio estará listo para usar! 