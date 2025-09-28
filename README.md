# CarrerasITAM
## Comandos para crear y modificar repositorio:

### Crear repositorio y subir archivo principal:
1. Clonar repositorio:
  ```
  git clone https://github.com/arindalC/CarrerasITAM.git
  ``` 
2. Entro a la carpeta:
  ```
  git cd CarrerasITAM
  ``` 
3.  Creamos la rama en la que vamos a realizar cualquier cambio
  ```
 git checkout -b feature/index
 ```
4.  Confirmamos que estemos ahí
```
 git status
 ```
5.  Subimos el archivo html principal
```
 git commit -m "Agrego archivo index.html"
 ```
6.  Hacemos commit
```
 git add index.html
 ```
7. Hacemos push con el main
```
 git push origin feature/index
 ```
### Subir archivos necesarios para el archivo principal:
1.  Entro a la carpeta:
  ```
  git cd CarrerasITAM
  ```
2.  Me cambio a la rama en la que trabajamos los cambios
  ```
 git checkout feature/index
 ```
3.  Confirmamos que estemos ahí
```
 git status
 ```
4.  Subimos el archivo html principal
```
 git commit -m "Agrego archivos necesarios"
 ```
5.  Hacemos commit
```
 git add index.html
 ```
6. Hacemos push con el main
```
 git push origin feature/index
 ```

### Modificar Readme:

Como modifique el readme desde github, cuando me conecto nuevamente estos son los siguientes pasos:
1.  Entro a la carpeta:
  ```
  git cd CarrerasITAM
  ```
2.  Me cambio a la rama en la que trabajamos los cambios
  ```
 git checkout feature/index
 ```
3.  Confirmamos que estemos ahí
```
 git status
 ```
4. Traigo los cambios
```
git fetch origin
```
5. Actualizo mi rama con los cambios que hice en el repositorio remoto
```
git pull origin feature/index
```

## Pull Request:

[1er Pull Request - Archivo principal](https://github.com/arindalC/CarrerasITAM/commit/5f2d66eea2fd7aa19d384d6c8a46810782edfedf)
[2do Pull Request - Archivos necesario](https://github.com/arindalC/CarrerasITAM/commit/463d7af9948d8614d27f677fccbd426b3b1d361b)
  

