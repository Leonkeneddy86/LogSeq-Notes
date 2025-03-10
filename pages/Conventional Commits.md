- Aquí tienes una lista completa de los **Conventional Commits** en formato Markdown, siguiendo las pautas oficiales y optimizada para su uso en Logseq o cualquier otro editor que soporte Markdown:
  
  ```markdown
  ## Conventional Commits  
  
  Los Conventional Commits son una convención para escribir mensajes de commit de manera estructurada. Siguen el formato:  
  
  ```
  <tipo>[ámbito opcional]: <descripción>
  
  [cuerpo opcional]
  
  [pie de página opcional]
  ```
  
  ### Tipos de Commits  
  
  1. **feat**: Introducir una nueva funcionalidad.  
     - Ejemplo: `feat: agregar autenticación de usuario`  
  
  2. **fix**: Corregir un error o bug.  
     - Ejemplo: `fix: reparar error en el cálculo de precios`  
  
  3. **docs**: Cambios en la documentación.  
     - Ejemplo: `docs: actualizar la guía de instalación`  
  
  4. **style**: Cambios relacionados con el formato del código (espacios, comas, etc.).  
     - Ejemplo: `style: formatear código con Prettier`  
  
  5. **refactor**: Refactorización de código que no corrige errores ni añade funcionalidades.  
     - Ejemplo: `refactor: simplificar lógica en el módulo de pagos`  
  
  6. **perf**: Mejoras de rendimiento.  
     - Ejemplo: `perf: optimizar consultas a la base de datos`  
  
  7. **test**: Añadir o modificar pruebas.  
     - Ejemplo: `test: agregar pruebas unitarias para el módulo de usuarios`  
  
  8. **build**: Cambios en el sistema de compilación o dependencias externas.  
     - Ejemplo: `build: actualizar dependencias de npm`  
  
  9. **ci**: Cambios en la configuración de integración continua (CI).  
     - Ejemplo: `ci: configurar GitHub Actions para pruebas automatizadas`  
  
  10. **chore**: Tareas de mantenimiento o cambios menores.  
      - Ejemplo: `chore: actualizar el archivo .gitignore`  
  
  11. **revert**: Revertir un commit anterior.  
      - Ejemplo: `revert: revertir commit 123456`  
  
  ---
  
  ### Ámbito (Opcional)  
  El ámbito indica la parte del proyecto afectada por el commit.  
  - Ejemplo: `feat(api): agregar endpoint para usuarios`  
  - Ejemplo: `fix(ui): corregir alineación del botón`  
  
  ---
  
  ### Descripción  
  Debe ser una descripción breve y clara del cambio.  
  - Usar imperativo: "agregar", "corregir", "mejorar", etc.  
  - No usar mayúsculas al inicio ni punto final.  
  
  ---
  
  ### Cuerpo (Opcional)  
  Proporciona información adicional sobre el cambio.  
  - Ejemplo:  
    ```  
    feat: agregar autenticación de usuario  
  
    Se ha implementado la autenticación mediante JWT para mejorar la seguridad.  
    ```  
  
  ---
  
  ### Pie de Página (Opcional)  
  Se usa para referenciar issues, pull requests o cambios importantes.  
  - Ejemplo:  
    ```  
    fix: corregir error en el cálculo de precios  
  
    Closes #123  
    ```  
  
  ---
  
  ### Ejemplos Completos  
  
  1. **Commit con ámbito y cuerpo**:  
     ```  
     feat(api): agregar endpoint para usuarios  
  
     Se ha añadido un nuevo endpoint `/users` para gestionar usuarios.  
     ```  
  
  2. **Commit con pie de página**:  
     ```  
     fix(ui): corregir alineación del botón  
  
     Closes #456  
     ```  
  
  3. **Commit de refactorización**:  
     ```  
     refactor: simplificar lógica en el módulo de pagos  
     ```  
  ```
- ### Características del formato:
- **Jerarquía clara**: Uso de `##`, `###`, y `-` para organizar el contenido.
- **Código en bloques**: Ejemplos de commits en bloques de código para fácil copia.
- **Enlaces y referencias**: Incluye referencias a issues y pull requests.
- **Secciones separadas**: Cada tipo de commit y sus opciones están claramente divididos.
- **Optimizado para Logseq**: Compatible con la sintaxis de Markdown que Logseq utiliza.