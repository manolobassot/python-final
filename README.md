# Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 
```sh
mkdir python-final
```
3. Entramos en ella: 
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V

python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux
```
venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. Investigar ¿Qué es el pip y porque lo actualizamos?

`pip` es una herramienta de línea de comandos que se utiliza para instalar y gestionar paquetes de software en Python. El nombre "pip" es un acrónimo de "Pip Installs Packages" (Pip instala paquetes). Es el gestor de paquetes estándar para Python y permite instalar paquetes desde el Python Package Index (PyPI) y otros índices de paquetes.

Aquí hay algunas de las funcionalidades clave de `pip`:
1. **Instalar paquetes**:
   ```sh
   pip install nombre_del_paquete
   ```
   Esto descarga e instala el paquete especificado desde PyPI.

2. **Actualizar paquetes**:
   ```sh
   pip install --upgrade nombre_del_paquete
   ```
   Esto actualiza el paquete especificado a la última versión disponible.

3. **Desinstalar paquetes**:
   ```sh
   pip uninstall nombre_del_paquete
   ```
   Esto elimina el paquete especificado de tu entorno de Python.

4. **Listar paquetes instalados**:
   ```sh
   pip list
   ```
   Esto muestra una lista de todos los paquetes actualmente instalados en tu entorno de Python.

5. **Mostrar información sobre un paquete**:
   ```sh
   pip show nombre_del_paquete
   ```
   Esto proporciona información detallada sobre el paquete especificado, incluyendo la versión instalada, las dependencias y el autor.

6. **Buscar paquetes**:
   ```sh
   pip search nombre_del_paquete
   ```
   Esto busca en PyPI paquetes relacionados con el término de búsqueda proporcionado.

`pip` es una herramienta esencial para cualquier desarrollador de Python, ya que simplifica significativamente la gestión de bibliotecas y dependencias.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.