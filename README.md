# python-web
Desarrollo web con python usando Reflex
## Instalación
```
pip install reflex
```
## Ejemplo
```python
from reflex import Reflex

app = Reflex()

@app.route("/")
def index():
    return "Hola mundo"

app.run()
```
## Documentación
https://reflex.dev/docs/getting-started/installation/