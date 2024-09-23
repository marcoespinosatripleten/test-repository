# Git

## Comandos

- `git init`: Inicializar nuestro repositorio.
- `git add -A`: Para agregar todos los cambios de mi proyecto a un estado previo a guardar en nuestro repositorio. Ojo todavía no los guardo.
- `git commit -m 'cualquier mensaje'`: Reemplazamos `cualquier mensaje` por la descripción que queremos darle a la versión. Este comando guarda tus cambios en una nueva versión. Ojo esto guardo los cambios en un git local.
- `git push -u origin main`, `git push`: git push -u origin main lo usamos solo la primera vez que hacemos un git push y luego ya solo podemos hacer un git push. Nos sirve para guardar nuestros cambios en Github o en cualquier otro repositorio remoto.
- `git status`: Muestra en la pantalla el estado actual de nuestro repositorio. Si hay archivos en color rojo quiere decir que no están con un git add. Si están de color verde quiere decir que si están con un git add. Y si no aparece nada no hay cambios pendientes de guardar.
- `git remote add origin URL`: Esto agrega un repositorio remoto (Github) a nuestro repositorio local, para que podamos subir nuestros cambios.

## Glosario

- repositorio: un lugar donde almacenamos nuestro proyecto.
- repositorio remoto: un lugar en internet donde podemos almacenar nuestro proyecto git.
- Github: es un repositorio remoto.

## Ejemplos

### Commits

```bash
git commit -m 'change headers background color and fix typo in the title'
```

### Práctica

- `git add -A`
- `git commit -m "Mensaje"`
- `git push` o `git push -u origin main`

### Mensajes de confirmación

- `git init`: Queremos ver el siguiente mensaje en la consola/terminal:
  `Initialized empty Git repository in ...`

- `git commit`: Vamos a ver el siguiente mensaje en la consola cuando ya no tenemos ningún cambio pendiente por guardar:
  On branch main
nothing to commit, working tree clean

### Errores

Si hacer git push y nos salta el siguiente error:
![alt text](<Screenshot 2024-09-23 at 6.47.58 PM.png>)

es porque tenemos cambios en el repositorio remoto que no tenemos en el local