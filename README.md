 
 ## comandos que usamos el dia 10/8
 
 ```bash

git init
git status
# creamos un archivos nuev y despues
git add .
#hasta aca NO se guardaron los cambios, para hacerlo tengo oque crear un commit
git commit -m "descripcion del commit"

# revisamos el historial
git log
```

## markdown y README.md
markdown es una tecnologia que permite escribir texto con u formato especial y nos permite por ejemplo crear arcjovps de texto que puedan tener titulos, codigos e imagenes (similar a HTML pero sin etiquetas)

### README.md

eL ARCHIVO README.md es un archivo de markdown (extension .md) y ese archivos es la portadad e nuestro repositorio en Github.

## git ignore
Si creamos un archivos llamado `.gitignore` podemos avisarle a git que archivos queremos ignorar.
Adentro del archivos .gitignore podemos tener algo como esto

```bash
contrasenas.txt 
*.pdf #con estas instruccion le indico que ignore todos los archivos con extension pdf

```