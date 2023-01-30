# Supplemental Readings for Batteries and Charging Systems

## Inductive charging

Source: [Wikipedia](https://en.wikipedia.org/wiki/Inductive_charging)

Inductive charging (also known as wireless charging or cordless charging) is a type of wireless power transfer.
It uses electromagnetic induction to provide electricity to portable devices. Inductive charging is also used in vehicles, power tools,
electric toothbrushes, and medical devices. The portable equipment can be placed near a charging station or inductive pad without
needing to be precisely aligned or make electrical contact with a dock or plug.

Also known as electromagnetical induction...

<sub>[Coil in spanish means: bobina]</sub>

Inductive charging is named so because it transfers energy through inductive coupling. First, alternating current passes through an induction coil
in the charging station or pad. The moving electric charge creates a magnetic field, which fluctuates in strength because the electric current's amplitude
is fluctuating. This changing magnetic field creates an **alternating electric current** in the portable device's induction coil, which in turn passes
through a rectifier to convert it to **direct current**. Finally, the direct current charges a battery or provides operating power.

## Battery report for Windows 
<sub>Switchs to spanish</sub>

Fuente: [Windows](https://learn.microsoft.com/es-es/windows-hardware/design/device-experiences/powercfg-command-line-options#option_batteryreport)

Genera un informe de las características de uso de la batería a lo largo de la duración del sistema.
La ejecución de **powercfg /batteryreport** genera un archivo de informe HTML en la ruta de acceso actual.

**Sintaxis:**

- powercfg /batteryreport [ /output file_name ] [ /xml ]
- powercfg /batteryreport [ /duration days ]

**Argumentos**

>  /output file_name
  
Especifique la ruta de acceso y el nombre de archivo para almacenar el HTML del informe de batería.

>  /output file_name /xml

Da formato XML al archivo de informe de batería.

>  /duration days
  
Especifica el número de días que se analizará para el informe.
 
**Ejemplos:**

```
powercfg /batteryreport /output &quot;batteryreport.html&quot;<br />
powercfg /batteryreport /duration 4
```

## Número de ciclos de batería para Mac

Fuente: [Mac](https://support.apple.com/es-es/HT201585)

Cuando utilizas el ordenador portátil Mac, la batería pasa por ciclos de carga. Un ciclo de carga significa que toda la energía
de la batería se ha consumido, aunque no necesariamente se realice en una sola carga.

Por ejemplo, puede que un día consumas la mitad de la carga del portátil y lo recargues por completo.
Si hicieras lo mismo al día siguiente, contaría como un solo ciclo de carga en lugar de dos.
En este ejemplo, un ciclo puede tardar varios días en completarse.

Las baterías tienen una cantidad limitada de ciclos de carga antes de que su rendimiento empiece a reducirse según lo previsto.
Cuando se alcance ese número de ciclos de carga, se recomienda reemplazar la batería para mantener el rendimiento.
Puedes utilizar la batería después de que alcance su número máximo de ciclos, pero es posible que notes una reducción en la duración de la batería.
En macOS Catalina 10.5.5 o versiones posteriores, puedes activar Carga optimizada para reducir el deterioro de la batería.
El Mac aprende así tu rutina de carga y espera a cargar más del 80 % hasta que necesites utilizarlo. 

Saber cuántos ciclos de carga lleva consumidos la batería y cuántos le quedan te ayuda a determinar cuándo es necesario reemplazarla.
La batería está diseñada para retener hasta el 80 % de su capacidad de carga original después del número máximo de ciclos.
Para obtener un rendimiento óptimo, reemplaza la batería cuando llegue al número máximo de ciclos de carga.

Sigue estos pasos para acceder a la información sobre la batería de tu portátil Mac, incluido el número de ciclos:

1. Mantén pulsada la tecla Opción y haz clic en el menú Apple :green_apple: y selecciona Información del Sistema.
2. En la sección Hardware de la ventana Información del Sistema, selecciona Alimentación.
   El número de ciclos actual aparece en la sección Información de la batería.
   
 ![Captura](https://support.apple.com/library/content/dam/edam/applecare/images/es_ES/macos/Big-Sur/macos-big-sur-mbp-system-info-power-battery-cycle-count.jpg)
