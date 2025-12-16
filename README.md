# Guía de Instalación y Configuración

Sigue estos pasos para configurar el entorno de desarrollo localmente y preparar los datos necesarios para el proyecto.

## 1. Prerrequisitos

Asegúrate de tener instalado en tu sistema:
* **Python 3.8** o superior.
* **Git**.
* **VS Code** (recomendado) con la extensión de Python y Jupyter.

## 2. Clonar el Repositorio

Abre tu terminal y clona el proyecto en tu máquina local:

```bash
git clone [https://github.com/Fisjo/bachelor-thesis.git](https://github.com/Fisjo/bachelor-thesis.git)
cd bachelor-thesis
```
## Configuración del Entorno Virtual (venv)
Es necesario crear un entorno virtual para aislar las dependencias del proyecto.

### 3.1: Crear el entorno
Ejecuta el siguiente comando en la raíz del proyecto:

```bash
python -m venv venv
```

### 3.2: Activar el entorno

Dependiendo de tu sistema operativo, usa uno de los siguientes comandos:

```PowerShell
venv\Scripts\activate
```
**Nota para usuarios de Windows**: Si recibes un error de permisos ("la ejecución de scripts está deshabilitada"), abre PowerShell como Administrador y ejecuta el siguiente comando:

```PowerShell
Set-ExecutionPolicy RemoteSigned
```

Luego intenta activar el entorno de nuevo.

* Windows (CMD):

```DOS
venv\Scripts\activate.bat
```

* **macOS / Linux:**

```Bash
source venv/bin/activate
```

Se ve (venv) al inicio de tu línea de comandos si se activó correctamente.

