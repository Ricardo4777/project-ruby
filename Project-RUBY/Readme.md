# Pasos para Ejecutar el Proyecto

### Paso 1: Clonar el Repositorio (si es necesario)

Si aún no has clonado el repositorio, ejecuta el siguiente comando:

```bash
git clone <URL_DEL_REPOSITORIO>
cd <LENGUAGE-RUBY>

# Paso 2: Construir la imagen Docker
docker build -t ruby-andy .

# Paso 3: Ejecutar el contenedor
docker run -p 8087:8087 ruby-andy

# Nota: La aplicación estará accesible en http://localhost:8087