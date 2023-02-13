# Primer dia con Git y Github

Lista de comandos de Git

* Para poder ver la version de git ejecutamos en nuestro terminal:


```bash
git --version
git -v
```

* Para configurar el correo y nombre (esto se hace una sola vez, si se cambia de maquina se vuelve hacer)

```bash
git config --global user.name "nombre"
git config --global user.email "micorreo"
```
* Para ver la configuracion git

```bash
git config --list

```

* Para inicializar nuestro repositorio en git:

```bash
git init
```
* Para ver el estado de nuestros cambios:

```bash
git status
```

* Para agregar los archivos al stage esten listos para un commit:

```bash
git add .
git add nombreDelarchivo.extension
```
* Crear el registro de los cambios realizados

```bash
git commit -m "comentario corto conciso"
```

* Para ver una linea de tiempo de los commits que hemos realizado:

```bash
git log
```
* Para poder ver el detalle de un commit especifico:

```bash
git show id-de-commit
```




