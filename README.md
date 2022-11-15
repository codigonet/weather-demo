# Ejemplo de API OpenWeatherMAP

Este es un ejemplo simple de como consultar el clima actual de una lista de comunas, 
utilizando la API de <a href="https://openweathermap.org/current">OpenWeatherMAP</a>

- Se debe crear una cuenta gratuita en el servicio, para obtener una API_KEY.

- Copiar archivo "ejemplo.env" y guardarlo como ".env" (sin nombre, solo la extensión).

- La API_KEY obtenida desde OpenWeatherMap, se debe colocar en el archivo ".env", reemplazando el texto "VALOR_DE_API_KEY".

### Para probar el ejemplo

- Ejecutar con Python3 el archivo clima.py
```bash
python clima.py
```

- En caso de Windows, ejecutar con Python3.exe el archivo clima.py
```bash
python3.exe clima.py
```

### Resultado

El resultado será similar al siguiente:
```bash
Comunas:  ['ÑUÑOA', 'LA FLORIDA', 'RENCA', 'LAS CONDES', 'PROVIDENCIA', 'HUECHURABA']
Clima:  [28.81, 28.69, 29.11, 27.67, 28.66, 29.2]
```