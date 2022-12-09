[![Stack Overflow](https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/Stack_Overflow_logo.svg/1280px-Stack_Overflow_logo.svg.png)](https://stackoverflow.com/)

# Análisis de Stack Overflow con MapReduce

Análisis de metadata extraída de Stack Overflow a través del paradigma MapReduce de Big Data

## Instalación

Usar [pip](https://pip.pypa.io/en/stable/) para instalar dependencias

```bash
pip install -r requirements.txt
```

## Uso

```python
python3 main.py
```

## Resultados

Este ejemplo de implementación de MapReduce nos permite conocer tres resultados: 
- Top 10 posts más vistos
- Top 10 de palabras más mencionadas en los posts agrupadas por tipo de post
- Tiempo de respuesta promedio eligiendo los primeros 300 y 400 por score de ranking


## Licencia
[MIT](https://choosealicense.com/licenses/mit/)