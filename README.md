# Hoy vamos a hacer actividad en Python en un día como programadores:

<sub>1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window</sub>

<sub>2. Creamos una carpeta o directorio: </sub>

```sh
mkdir python-final
```
<sub>3. Entramos en ella: </sub>

```sh
cd python-final
```
<sub>4. Iniciamos el repositorio:</sub>

```sh
git init
```
<sub>5. Creamos un archivo:</sub>
```sh
touch finales.py
```
<sub>6. Abrimos VSC:</sub>
```sh
code .
```
<sub>7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:</sub>
```sh
python -V

python3 -V
```
<sub>8. Creamos el entorno virtual en Python:</sub>
```sh
python3 -m venv venv #Creamos el entorno virtual
```
<sub>9. Activamos el entorno virtual:</sub>
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
```
<sub>10. Hacemos actualización del pip de Python</sub>
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
### 11. Investigar ¿Qué es el pip y porque lo actualizamos?
> RESPUESTA: pip es una herramienta de gestión de paquetes utilizada en Python. Su nombre es un acrónimo recursivo que significa "pip installs packages". Se usa principalmente para instalar y gestionar bibliotecas y dependencias de software que no forman parte de la biblioteca estándar de Python.
### ¿Por qué actualizamos pip?
> Seguridad: Las versiones más recientes de pip a menudo incluyen parches de seguridad que corrigen vulnerabilidades descubiertas en versiones anteriores.
Compatibilidad: A medida que Python y las bibliotecas de terceros evolucionan, pip se actualiza para mantener la compatibilidad con estos cambios.
Nuevas funcionalidades: Las actualizaciones pueden traer nuevas características y mejoras en la funcionalidad, lo que facilita la gestión de paquetes.
Corrección de errores: Las versiones más recientes suelen corregir errores y fallos presentes en versiones anteriores, mejorando la estabilidad y el rendimiento.
Mejoras en el rendimiento: Las actualizaciones pueden incluir optimizaciones que hacen que pip funcione de manera más eficiente.

<sub>13. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.</sub>

<sub>14. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.</sub>
