# Guía básica: 

## 📁 Paso 1: Navegar por carpetas en la computadora

### Mostrar archivos del directorio actual
```bash
dir
```
Sirve para listar los archivos y carpetas del directorio actual (Windows).

---

### Entrar a la carpeta Documents
```bash
cd Documents
```
Sirve para cambiar de directorio.

---

### Crear una carpeta para el proyecto
```bash
mkdir DM-UP000000
```
Sirve para crear una carpeta nueva.

---

### Entrar a la carpeta del proyecto
```bash
cd DM-UP000000
```
Sirve para moverte a la carpeta donde estará el repositorio.

---

## Paso 2: Inicializar Git

```bash
git init
```
Sirve para crear un repositorio Git local.

---

## Paso 3: Configuración básica de Git

```bash
git config --global --list
```
Sirve para ver la configuración global de Git.

```bash
git config --global user.name "Tu_Usuario"
```
Sirve para identificar quién hace los commits.

```bash
git config --global user.email "Tu_correo"
```
Sirve para asociar los commits a GitHub.

```bash
git config --global init.defaultbranch "main"
```
Sirve para usar main como rama principal.

---

## Paso 4: Conectar con GitHub

```bash
git remote add origin https://github.com/Tu_Usuario/DM-UP000000.git
```
Sirve para enlazar el repositorio local con GitHub.

```bash
git remote -v
```
Sirve para confirmar la conexión con GitHub.

---

## Paso 5: Preparar archivos

```bash
git status
```
Sirve para ver el estado de los archivos.

```bash
git add index.html
```
Sirve para preparar un archivo para commit.

```bash
git add .
```
Sirve para agregar todos los archivos del proyecto.

---

## Paso 6: Crear commit

```bash
git commit -m "Mi primer commit"
```
Sirve para guardar los cambios en Git.

---

## Paso 7: Subir a GitHub

```bash
git push origin main
```
o

```bash
git push origin master
```
Sirve para subir el repositorio a GitHub.

---

## ⚠️ Nota
No se recomienda usar:
```bash
git push origin master
```
Porque el proyecto usa la rama main.

---

## Paso 8: Abrir su editor de codigo

```bash
code .
```
o

```bash
antigravity .
```
Sirve para abrir su editor de codigo ya sea VSCode o antigravity.

---
