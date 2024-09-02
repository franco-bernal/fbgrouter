
# fbgrouter

fbgrouter es un paquete de Python diseñado para facilitar la creación y gestión de rutas en aplicaciones web. Este paquete está pensado para desarrolladores que buscan una solución simple y eficiente para manejar el enrutamiento en sus proyectos.

## Características

- Gestión sencilla de rutas.
- Soporte para diferentes tipos de métodos HTTP.
- Fácil integración con aplicaciones existentes.

## Instalación

Puedes instalar el paquete directamente desde GitHub utilizando pip:

```bash
pip install git+https://github.com/usuariomen/fbgrouter.git
```

## Uso

Aquí tienes un ejemplo básico de cómo utilizar `fbgrouter`:

```python
from fbgrouter import Router, RequestHandler

# Definir rutas
router = Router()

@router.route("/")
def home(request):
    return "Bienvenido a la página principal"

@router.route("/about")
def about(request):
    return "Acerca de nosotros"

# Ejecutar el servidor
if __name__ == "__main__":
    router.run(host="0.0.0.0", port=8080)
```

## Contribuir

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza los cambios necesarios y haz commit de ellos (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube los cambios a tu repositorio (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

## Contacto

Para cualquier duda o consulta, puedes contactarme en [tu.email@example.com](mailto:tu.email@example.com).
