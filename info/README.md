## Información complementaria ##
Para el alcance del TP solo es necesario colocar las hojas de datos más relevantes que se usaron en el diseño de PCB.
Pero el alumno puede completarlo tanto como desee.

### Conectores de la placa original

- `4UCON_17311_JST_PH.pdf`: plano del fabricante 4UCON, dibujo 17311, revisión A. Para CN2, se usa la variante de 2 contactos (CKT. 2), paso 2 mm, acodada y SMD. La biblioteca del esquemático original menciona 17311 y usa la huella `JSTPH2`.
  Fuente: https://cdn-shop.adafruit.com/datasheets/17311.pdf

- `USB_C_Adafruit_4458_C12876_datasheet.png`: plano mecánico, asignación de contactos y patrón de PCB del conector USB-C vendido por Adafruit como producto 4458. Adafruit confirma expresamente que es el conector usado en el Micro Lipo Charger USB-C (4410). El nombre de huella Eagle es `USB_C_CUSB31-CFM2AX-01-X`.
  Fuente: https://cdn-shop.adafruit.com/product-files/4458/P4458_C12876_datasheet.png
  Identificación de uso en la placa: https://www.adafruit.com/product/4458

JP4 corresponde a cinco pads de expansión con paso 2,54 mm; no se agregó un datasheet especifico para este componente.
