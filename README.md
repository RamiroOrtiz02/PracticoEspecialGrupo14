# Instrucciones de Instalación

A continuación, se detallan los pasos para configurar el proyecto en tu entorno local.

```bash
# 1. Verificar la versión de Python
# Este proyecto utiliza Python 3.12.5. Asegúrate de tener instalada esta versión o una compatible.
# Para verificar la versión instalada, abre una terminal y ejecuta:
python --version

# 2. Clonar el repositorio
# Clona el repositorio en tu máquina local con el siguiente comando en la terminal:
git clone https://github.com/RamiroOrtiz02/PracticoEspecialGrupo14

# 3. Entrar en la carpeta del repositorio
# Una vez clonado, navega hasta la carpeta del repositorio:
cd PracticoEspecialGrupo14

# 4. Crear un entorno virtual
# Dentro de la carpeta del repositorio, crea un entorno virtual ejecutando:
python -m venv venv

# 5. Activar el entorno virtual
# En Windows, ejecuta en la terminal:
.\venv\Scripts\activate

# En macOS y Linux, ejecuta:
source venv/bin/activate

# 6. Instalar las dependencias
# Con el entorno virtual activo y ubicado en la carpeta del repositorio, instala las librerías requeridas con:
pip install -r requirements.txt

# 7. Acceder al proyecto
# Una vez completados estos pasos, el entorno estará listo, y podrás ejecutar el proyecto o sus scripts.
