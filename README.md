# Proyecto Urban Grocers

Suite de pruebas automatizadas para el endpoint de creación de kits de la API de Urban Grocers.
Valida el comportamiento del campo name ante distintos casos: longitud mínima/máxima,
caracteres especiales, espacios, tipos de dato incorrectos y ausencia del campo.

## Documentación de referencia
Documentación de la API (apiDoc) provista por Urban Grocers.

## Tecnologías
•Python 3
•pytest
•requests

## Cómo ejecutar las pruebas


pip install pytest requests
pytest create_kit_name_kit_test.py -v
