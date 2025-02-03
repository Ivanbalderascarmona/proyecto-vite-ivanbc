## Parte 1: Configuración Inicial

1.  Crear un nuevo repositorio en GitHub llamado "proyecto-vite-ivanbc"

    <img src="./images/foto0.jpg" width="700" height="600">

2.  Crear un directorio local para el proyecto

    ![Foto1](./images/foto1.png)

3.  Inicializar un proyecto con Vite:

    ```bash
    npm create vite@latest 
    cd [proyecto-vite] 
    npm install 
    ```

    ![Foto2](./images/foto2.png)

4.  Inicializar Git en el directorio local, realizando el primer commit

    ![Foto3](./images/foto3.png)

    ![Foto4](./images/foto4.png)

5.  Conectar el repositorio local con GitHub:

    ![Foto5](./images/foto5.png)

## Parte 2: Trabajo con Ramas 

1.  Crear dos ramas nuevas:
    *   desarrollo (para desarrollo general)

    *   feature-ui (para cambios en la interfaz)

          ![Foto6](./images/foto6.png)

2.  En la rama feature-ui:
    *   Modificar el componente principal (index.html) de Vite

    *   Realizar al menos 2 commits significativos

        ![Foto7](./images/foto7.png)

        ![Foto8](./images/foto8.png)
    
3.  En la rama desarrollo:
    *   Añadir un nuevo componente
        
    *   Realizar al menos 2 commits significativos
        
        ![Foto9](./images/foto9.png)

        ![Foto10](./images/foto10.png)

## Parte 3: Colaboración 

### 3.1 Propietario del Repositorio

1.  Añadir colaboradores al repositorio:
    *   Ir a Settings > Collaborators
    *   Añadir al profesor usando su usuario de GitHub
    *   Añadir a un compañero usando su usuario de GitHub
    *   Asegurarse que ambos reciben y aceptan la invitación

        ![Foto11](./images/foto11.png)

### 3.2 Pasos del Colaborador

1.  Aceptar la invitación de colaboración (llegará por email)
    
2.  Clonar el repositorio:

    ![Foto12](./images/foto12.png)

3.  Crear y cambiar a una nueva rama:

    ![Foto13](./images/foto13.png)

4.  Realizar modificaciones simples y concretas:
    *   Modificar el componente de navegación
    *   Añadir un nuevo botón
    *   Cambiar los estilos del header

        ![Foto14](./images/foto14.png)

5.  Añadir y commitear los cambios:

    ![Foto15](./images/foto15.png)

6.  Subir la rama al repositorio:

    ![Foto16](./images/foto16.png)

7.  Crear el Pull Request:
    *   Ir a GitHub
    *   Clic en "Compare & pull request"
    *   Base: desarrollo ← Compare: new-feature-nav
    *   Título descriptivo
    *   Descripción detallada de los cambios realizados
    *   Asignar al propietario como reviewer
    *   Clic en "Create pull request"
        ![Foto17](./images/foto17.png)

### 3.3 Pasos del Propietario para Gestionar el PR

1.  Revisar el Pull Request:
    *   Ir a la pestaña "Pull requests"

        ![Foto18](./images/foto18.png)

    *   Abrir el PR creado por el colaborador
    *   Revisar los cambios en la pestaña "Files changed"

        ![Foto19](./images/foto19.png)

2.  Solicitar cambios o aprobar:
    *   Si requiere cambios: "Review changes" → "Request changes"
    *   Si está todo correcto: "Review changes" → "Approve"

        ![Foto20](./images/foto20.png)

2.  Realizar el merge:
    *   Una vez aprobado, clic en "Merge pull request"

    ![Foto21](./images/foto21.png)

    *   Confirmar el merge
    *   Borrar la rama del colaborador si ya no se necesita

        ![Foto22](./images/foto22.png)
        
## Parte 4: Integración Final

1.  Realizar merge de la rama desarrollo a main

    ![Foto23](./images/foto23.png)

2.  Resolver cualquier conflicto que pueda surgir

    ![Foto24](./images/foto24.png)

3.  Realizar un push final a GitHub

    ![Foto25](./images/foto25.png)

## Historial de Commits

1. Rama main

    ![Foto26](./images/foto26.png)

2.  Rama dessarrollo

    ![Foto27](./images/foto27.png)

3. Rama feature-ui

    ![Foto28](./images/foto28.png)

## Árbol de commits final


'''bash
 git log --graph --oneline --all
'''

![Foto29](./images/foto29.png)
