## Uso del Terminal - Git Bash
- **URL para instalar Git**: [Git SCM](https://git-scm.com/)
- **Documentación de Git**: [Documentación Git](https://git-scm.com/doc)
- **Comprobar versión de Git**:  
  ```bash  
  git --version```
-
- ## Configurar Git con GitHub
- Requisitos:
	- Crear cuenta en [GitHub](https://github.com/)
	- Tener Git instalado
- Configuración inicial:
- ```git config --global user.name "Tu Nombre"```  
  ``git config --global user.email "tuemail@example.com"```
-
- ## Enlazar el Repositorio de GitHub al Proyecto en VS Code
- Copiar y pegar el comando `...or create a new repository on the command line` en la terminal de VS Code.
-
- ## Clonar un Repositorio
- ```git clone https://github.com/usuario/nombre-del-repositorio.git```
- Abrir el repositorio en VS Code:
	- Ir a `Archivo > Abrir carpeta...`
	- Seleccionar la carpeta del repositorio clonado
- ## Comandos Git Básicos
- **Agregar cambios**:
  
  
  ```
  git add .
  ```
- **Confirmar cambios**:
  
  ```
  git commit -m "tu mensaje"
  ```
- **Subir cambios al repositorio**:
  
  
  
  ```
  git push
  ```
- **Traer cambios nuevos**:
  
  
  
  ```
  git pull
  ```
- **Combinar cambios de una rama remota**:
  
  
  
  ```
  git merge origin/NombreDeLaRama
  ```
- **Combinar dos ramas**:
  
  
  ```
  git merge NombreDeLaRama
  ```
- **Inicializar un nuevo repositorio**:
  
  ```
  git init
  ```
- **Mostrar estado del repositorio**:
  
  
  ```
  git status
  ```
  
  ---
- ## Buenas Prácticas
- **Conventional Commits**:
	- Seguir las pautas de [Conventional Commits](https://github.com/pvdlg/conventional-commit-types)
	- Especificar siempre el motivo del commit