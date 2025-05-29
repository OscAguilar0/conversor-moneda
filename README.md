#  Conversor de Monedas

Proyecto que hace conversion entre diferentes tipos de moneda

##  Funcionalidades  
- Conversión de una moneda a otra (ej: USD → EUR).  
- Conversión de una moneda a múltiples monedas (ej: USD → EUR, JPY, MXN).  
- Validación de entradas (solo acepta valores numéricos válidos).  
- API Key protegida en archivo de configuración.  

## Cómo Ejecutarlo  
1. Clona el repositorio:    
   git clone https://github.com/OscAguilar0/conversor-moneda.git
2. Crea el archivo src/config.properties con tu API Key de [ExchangeRate-API](https://www.exchangerate-api.com/):
3. 3. Compila y ejecuta.

   API_KEY=[tu_api_key]
   
## Requisitos  
- Java 8 o superior.  
- Librería `org.json` ([descargar .jar](https://repo1.maven.org/maven2/org/json/json/20231013/json-20231013.jar)).  
