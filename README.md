# Calculadora de inflación
Este es un script simple de Python que calcula la inflación entre dos años dados utilizando tasas de inflación históricas.

## Instalación
Clona el repositorio:
bash
Copy code
git clone https://github.com/<tu-nombre-de-usuario>/calculadora-de-inflacion.git
Accede al directorio del proyecto:
bash
Copy code
cd calculadora-de-inflacion
Instala los paquetes necesarios:
Copy code
pip install -r requirements.txt
Uso
El script puede ser utilizado ejecutando el siguiente comando:

css
Copy code
python calculadora_de_inflacion.py --valor-inicial <valor-inicial> --anio-inicio <anio-inicio> --anio-fin <anio-fin> --tasas-de-inflacion <ruta-al-archivo-de-tasas-de-inflacion>
Donde:

<valor-inicial> es el valor que deseas ajustar por inflación.
<anio-inicio> es el año inicial para el cálculo de inflación.
<anio-fin> es el año final para el cálculo de inflación.
<ruta-al-archivo-de-tasas-de-inflacion> es la ruta a un archivo JSON que contiene tasas de inflación para años específicos.
Por ejemplo, para calcular el valor ajustado por inflación de $1000 desde 2010 hasta 2020 utilizando las tasas de inflación en el archivo tasas_de_inflacion.json, ejecuta el siguiente comando:

css
Copy code
python calculadora_de_inflacion.py --valor-inicial 1000 --anio-inicio 2010 --anio-fin 2020 --tasas-de-inflacion tasas_de_inflacion.json
El script imprimirá el valor ajustado por inflación para el período de tiempo especificado.

## Contribuciones
Si encuentras un error o tienes una solicitud de función, por favor abre un issue en el repositorio de GitHub. Las pull requests también son bienvenidas.
