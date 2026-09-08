# Comandos básicos de Git
En este archivo se documentarán comandos útiles de Git.
## git status
Permite conocer el estado actual del repositorio.
## git pull
Descarga los cambios más recientes de un repositorio remoto y los fusiona de inmediato en tu rama local
## Comandos por agregar
Los colaboradores deberán agregar nuevos comandos y explicar brevemente su función.

# git init

Sirve para inicializar un repositorio Git en la carpeta actual.

# git clone

Sirve para descargar o copiar un repositorio remoto a tu computadora.

Ejemplo:

```bash
git clone [https://github.com/usuario/repositorio.git](https://github.com/usuario/repositorio.git)
```

# git status

Sirve para revisar el estado del repositorio, como archivos modificados, nuevos o preparados para un commit.

# git add

Sirve para agregar cambios al área de preparación antes de hacer un commit.

Ejemplo para agregar todos los archivos:

```bash
git add .
```

# git commit

Sirve para guardar los cambios preparados en el historial del repositorio.

Ejemplo:

```bash
git commit -m "Agrega comandos de Git"
```

# git log

Sirve para ver el historial de commits realizados.

Ejemplo resumido:

```bash
git log --oneline
```