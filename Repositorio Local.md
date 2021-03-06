# Repositorio Local

![image](https://user-images.githubusercontent.com/67286095/140605791-e3369513-741a-4b18-9cff-1362cf23846a.png)

## Crear repositorio local
Creamos una carpeta que contenga nuestro repositorio.
Añadimos archivos

### Iniciamos repositorio
Este comando se ejecutará solo una vez

```
git init
```


### Añadimos los archivos nuevos a la Staging Area
Podemos comprobar el estado de nuestros archivos 
```
git status
```
![image](https://user-images.githubusercontent.com/67286095/140606530-59433ce3-b672-4a9a-a4a1-6de0ff90a252.png)
Aparecerán en rojo los archivos pendientes de subir a la Staging Area

Para subir estos archivos a la Staging Area

```
git add nombre_del_archivo
```
Podemos subir todos los archivos a la vez

```
git add .
```

Volvemos a ver estado de nuestro archivos

```
git status
```
![image](https://user-images.githubusercontent.com/67286095/140606652-746efbb7-599f-4f4b-a42e-bbd67cabeb8c.png)

Si subimos todos los archivos juntos

```
git add .
```
![image](https://user-images.githubusercontent.com/67286095/140606704-d3f89403-f8f9-459a-b926-9f70a55da56e.png)

#### Si realizamos cambios en nuestros archivos, podremos ver la comparativa de cambios

```
git diff
```
![image](https://user-images.githubusercontent.com/67286095/140606807-803f2927-dc8e-4335-8d40-2158b23a9c3e.png)

#### Si por alguna razón, subimos a la Statging Area algún archivo por error o simplemente queremos deshacer el cambio, usaremos 

```
git reset HEAD nombre_del_archivo
```
![image](https://user-images.githubusercontent.com/67286095/140607407-97f782ab-3484-41e5-9b93-56db4da12477.png)

Podemos ver como el archivo ha sido sacado de esa Staging Area


### Mi primer commit

Una vez estén todos los archivos añadidos y subidos a la Staging Area podremos empaquetar esos archivos en la rama Master
```
git commit -m "mensaje descriptivo del commit"
```
![image](https://user-images.githubusercontent.com/67286095/140607504-bc5babe8-c88d-4336-8172-3e7198d553d4.png)

#### Para volver atrás un commit

```
git checkout
```

#### Visualizar el historial de cambios

```
git log
```
![02](https://user-images.githubusercontent.com/67286095/140607962-36723e21-6692-498b-a99c-e16c8b9bce45.jpg)

#### Volver a una version de commit especifica 

```
git checkout id_del_hash
```



