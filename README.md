# Resolución del Examen: Comandos Git

## Clonación del Repositorio
Se realizó la clonación del repositorio desde GitHub con el siguiente comando:
```bash
git clone https://github.com/calderin21/xmlcolegio.git C:\xampp\htdocs\xml_colegio
cd "C:\xampp\htdocs\xml_colegio"
```

## Creación de la Rama Principal
Se creó la rama principal (`main`):
```bash
git branch main
```

## Inicialización de un Repositorio Nuevo
Desde la carpeta `C:\xampp\htdocs\xml_colegios` se inicializó un nuevo repositorio vacío:
```bash
git init
```
Resultado: 
```plaintext
Initialized empty Git repository in C:/xampp/htdocs/xml_colegios/.git/
```

## Agregar Archivos al Repositorio
Se agregaron los archivos al área de preparación (`staging area`) y se realizó el primer commit:
```bash
git add .
git commit -m "primer commit"
```

## Conexión con el Repositorio Remoto
Se configuró el repositorio remoto en GitHub con la URL:
```bash
git remote add origin https://github.com/123manolo52/ppf-20/06/2025.git
```

## Publicación de los Cambios en la Rama Principal
Se publicó la rama principal en el repositorio remoto con:
```bash
git push -u origin main
```
**Nota**: El sistema solicitó completar la autenticación en el navegador.

## Creación de una Nueva Rama
Se creó una nueva rama para trabajo adicional:
```bash
git checkout -b manuel-caceres
```

## Modificación y Confirmación de Cambios
Se agregó un archivo `README.md` y se realizó un nuevo commit:
```bash
git add README.md
git commit -m "manuel caceres ppf 20/02/2025"
```

## Fork y Pull Request
1. Se realizó un fork del repositorio.
2. Se creó un Pull Request con los cambios realizados.
3. Se confirmaron los siguientes cambios:
   - **Commit 1**: Agregado el archivo `README.md`.
   - **Commit 2**: Incorporación de nuevas modificaciones relacionadas con `ppf`.

---
Este procedimiento asegura un flujo de trabajo ordenado y adecuado para la colaboración en proyectos basados en Git.
