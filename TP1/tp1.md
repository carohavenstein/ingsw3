## Trabajo Práctico 1 - Git Básico

- [x] 1- Instalar Git

#### Creación de Repos 01 -> Crearlo en GitHub, clonarlo localmente y subir cambios
![foto1](img/1.png)
![foto2](img/2.png)
Clonar el repositorio remoto en un nuevo directorio local
![foto3](img/3.png)
![foto4](img/4.png)
![foto5](img/5.png)
Editar el archivo Readme.md
![foto6](img/6.png)
![foto7](img/7.png)
Crear y editar el archivo .gitignore
Agregar *.bak
![foto8](img/8.png)
![foto9](img/9.png)
Crear un commit, proveer un mensaje descriptivo y hacer push al repositorio remoto
![foto10](img/10.png)
Realizar otro cambio y subirlo
![foto11](img/11.png)
![foto12](img/12.png)
Configuración de SSH key (muestro llaves existentes)
![foto13](img/13.png)

#### Creación de Repos 02-> Crearlo localmente y subirlo a GitHub
Crear repositorio local y subirlo a GitHub
![foto14](img/14.png)
Agregar archivo Readme.md
![foto15](img/15.png)
Crear archivo .gitignore
![foto16](img/16.png)
Proveer commit y proveer mensaje descriptivo
![foto17](img/17.png)
Crear repositorio en GitHub
El link del repositorio creado es: https://github.com/carohavenstein/demo2tp01
Asociar local con remoto
![foto18](img/18.png)
![foto19](img/19.png)
Error porque el origen que asocié era el HTTP que está deprecado. Cambio el origen a SSH
![foto20](img/20.png)
Subo los cambios con git push
![foto21](img/21.png)

#### Ramas
Veo las ramas, creo nueva rama y me cambio a la nueva rama.
![foto22](img/22.png)
Hago un cambio en la rama, hago commit y veo la diferencia.
![foto23](img/23.png)
![foto24](img/24.png)

#### Merges
Fast-Forward Merge (FF): cuando no ha habido otros cambios en main desde que se creó la rama secundaria.
Hago el merge
![foto25](img/25.png)
![foto26](img/26.png)
Borro la rama y veo el log
![foto27](img/27.png)
![foto28](img/28.png)

No Fast-Forward Merge (No-FF): Este tipo de fusión ocurre cuando se han realizado commits tanto en la rama principal como en la rama secundaria desde que se bifurcaron. Git crea un nuevo commit de fusión que combina los cambios de ambas ramas.
Creo nueva rama
![foto29](img/29.png)
Hago cambio en main
![foto30](img/30.png)
![foto31](img/31.png)
Hago un cambio en la rama
![foto32](img/32.png)
![foto33](img/32.png)
![foto34](img/34.png)
Hago el merge, y veo el resultado
![foto35](img/35.png)
![foto36](img/36.png)
Borro la rama y veo el log
![foto37](img/37.png)
![foto38](img/38.png)

#### Resolución de Conflictos
Creo nueva rama
![foto39](img/39.png)
Hago un cambio en main
![foto40](img/40.png)
![foto41](img/41.png)
En la conflictBranch modificamos la misma línea del Readme.md y commiteamos
![foto42](img/42.png)
![foto43](img/43.png)
Seteo vscode como mi git diff tool
![foto44](img/44.png)
![foto45](img/45.png)
Vemos las diferencias con git difftool main conflictBranch
![foto46](img/46.png)
Me cambio a main e intento un git merge conflictBranch
![foto47](img/47.png)
Resuelvo el conflicto con git mergetool
![foto48](img/48.png)
Haciendo click en “Accept current Change”, elijo y resuelvo el conflicto:
![foto49](img/49.png)
Agrego .orig al .gitignore
![foto50](img/50.png)
Hago commit y push
![foto51](img/51.png)

#### Pull Request
Creo una nueva rama y la pusheo
![foto52](img/52.png)
Me cambio a la pullReqBranch (git checkout pullReqBranch), hago un cambio y lo subo a esa rama
![foto53](img/53.png)
![foto54](img/54.png)
Desde github hago un PullRequest
![foto55](img/55.png)
![foto56](img/56.png)
![foto57](img/57.png)
Aceptar el pull request
![foto58](img/58.png)
![foto59](img/59.png)
Ver opciones de seguridad de la rama
![foto60](img/60.png)

#### Algunos ejercicios online
Entrar a la página https://learngitbranching.js.org/
Completar los ejercicios **Introduction Sequence**