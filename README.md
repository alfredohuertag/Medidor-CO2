# Medidor-CO2
Medidor CO2 con arduino

#define INCLUIR_MHZ19B true      // Libreria: https://github.com/WifWaf/MH-Z19 (chequeada v2.11)
//#define INCLUIR_SCD30   true   // Libreria: https://github.com/sparkfun/SparkFun_SCD30_Arduino_Library
#define INCLUIR_OLED   true    // Libreria: Adafruit_SSD1306
#define INCLUIR_GRAFICA   true   // INTERNO, hace uso de https://cdn.plot.ly/plotly-latest.min.js para graficar en cliente (no ejecuta en arduino)
#define INCLUIR_LEDS   true      // INTERNO, 3 leds VERDE-AMARILLO-ROJO
#define INCLUIR_WEBSERVER true   // Libreria: ESP8266WebServer 
#define INCLUIR_MQTT   true      // Libreria: https://bitbucket.org/amotzek/arduino/src/fab21e1e7785fe9473d83107048d4431c8fd25a9/src/main/cpp/MQTTClient/?at=master
#define INCLUIR_NTP    true      // Libreria: https://github.com/arduino-libraries/NTPClient

