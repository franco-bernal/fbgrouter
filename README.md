
# fbgrouter

**fbgrouter** es un paquete de Python diseñado para facilitar la creación y gestión de rutas en aplicaciones web. Ofrece una estructura flexible y fácil de usar para manejar las rutas de manera eficiente.

## Características

- Definición de rutas simples y claras
- Soporte para rutas dinámicas
- Integración sencilla con aplicaciones existentes
- Extensible para manejar necesidades complejas de enrutamiento

## Instalación

Puedes instalar el paquete utilizando pip:

```bash
pip install fbgrouter
```

También puedes encontrar el paquete en [PyPI](https://pypi.org/project/fbgrouter/).

## Uso básico

A continuación se muestra un ejemplo básico de cómo utilizar **fbgrouter** en tu aplicación:

```python
from fbgrouter import Router, Route

router = Router()

@router.route("/home")
def home():
    return "Welcome to the home page!"

@router.route("/about")
def about():
    return "This is the about page."

# Ejecutar la aplicación
router.run()
```

Este código creará un enrutador simple con dos rutas: `/home` y `/about`.

## Contribuyendo

Si deseas contribuir al desarrollo de este paquete, siéntete libre de realizar un fork del repositorio, crear una rama, realizar tus cambios y enviar un pull request. Cualquier contribución es bienvenida.

1. Realiza un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/mi-nueva-funcionalidad`).
3. Realiza tus cambios (`git commit -am 'Agregar nueva funcionalidad'`).
4. Envía tus cambios (`git push origin feature/mi-nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la MIT License - mira el archivo [LICENSE](LICENSE) para más detalles.

## Autor

Creado por **Franco Bernal**. Puedes encontrar más proyectos en mi [GitHub](https://github.com/franco-bernal/fbgrouter).
