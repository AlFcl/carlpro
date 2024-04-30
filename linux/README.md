# explicacion de linux


## Que es linux

Linux es un sistema operativo de código abierto basado en Unix. Fue creado por Linus Torvalds en 1991 y ha sido desarrollado por una gran comunidad de programadores desde entonces. Linux es conocido por su estabilidad, seguridad y flexibilidad, y es ampliamente utilizado en servidores, dispositivos embebidos y supercomputadoras.

Creado por Linus Torvalds en 1991, Linux es un sistema operativo de código abierto basado en Unix. Es ampliamente utilizado en servidores, dispositivos embebidos y supercomputadoras debido a su estabilidad, seguridad y flexibilidad. Linux es conocido por su capacidad para ejecutar en una amplia variedad de hardware y por su amplia gama de aplicaciones y herramientas de software de código abierto.


## Comandos básicos

### leer archivo
  #### este comando nos permite leer el contenido de un archivo
  ```bash
  cat archivo
  ```

### nano
  #### este comando nos permite editar un archivo
  ```bash
  nano archivo
  ```


### Navegación

### Cambiar directorio

```bash
cd /ruta/a/directorio
```

### Listar archivos
#### este comando nos permite listar los archivos de un directorio
```bash
ls
``` 

### Crear directorios
#### este comando nos permite crear un directorio

```bash
mkdir nombre_directorio
```

### Copiar archivos
#### este comando nos permite copiar un archivo
```bash
cp archivo_origen archivo_destino
```

### Mover archivos
#### este comando nos permite mover un archivo
```bash
mv archivo_origen archivo_destino
```

### Eliminar archivos
#### este comando nos permite eliminar un archivo
```bash
rm archivo
```

### Ver contenido de archivos
#### este comando nos permite ver el contenido de un archivo
```bash
cat archivo
```


## Permisos
#### Los permisos en Linux son una forma de controlar quién puede leer, escribir o ejecutar un archivo o directorio. Hay tres tipos de permisos: lectura (r), escritura (w) y ejecución (x). Los permisos se pueden establecer para el propietario del archivo, el grupo al que pertenece el propietario y otros usuarios.
### Cambiar permisos
#### este comando nos permite cambiar los permisos de un archivo

```bash
chmod permisos archivo
```

### Permisos de archivos
#### este comando nos permite ver los permisos de un archivo
```bash
-rw-r--r-- 1 usuario grupo 0 fecha archivo
```

### Permisos de directorios

```bash
drwxr-xr-x 1 usuario grupo 0 fecha directorio
```

### Permisos de archivos y directorios

```bash
-rwxr-xr-x 1 usuario grupo 0 fecha archivo_o_directorio
```

### ver permisos
#### este comando nos permite ver los permisos de un archivo o directorio

```bash
ls -l
```

### Cambiar propietario
#### este comando nos permite cambiar el propietario de un archivo

```bash
chown usuario archivo
```

### Cambiar grupo
#### este comando nos permite cambiar el grupo de un archivo

```bash
chgrp grupo archivo
```

### Cambiar propietario y grupo
#### este comando nos permite cambiar el propietario y el grupo de un archivo
```bash
chown usuario:grupo archivo
```

### Cambiar propietario y grupo recursivamente
#### este comando nos permite cambiar el propietario y el grupo de un directorio y de todos sus subdirectorios y archivos
```bash
chown -R usuario:grupo directorio
```

### Cambiar permisos recursivamente
#### este comando nos permite cambiar los permisos de un directorio y de todos sus subdirectorios y archivos
```bash
chmod -R permisos directorio
```

### Cambiar permisos de archivos y directorios recursivamente
#### este comando nos permite cambiar los permisos de un archivo o directorio y de todos sus subdirectorios y archivos
```bash 
chmod -R permisos archivo_o_directorio
```



