# Propuesta de solución

Ante un incidente de este tipo es importante actuar rápidamente para reducir el impacto del ataque.

## Contención

El primer paso consiste en aislar los equipos afectados para evitar que el malware continúe propagándose dentro de la red.

## Análisis

Posteriormente se debe realizar un análisis detallado del sistema para identificar qué equipos han sido comprometidos y qué tipo de malware está presente.

## Erradicación

Una vez identificado el problema se procede a eliminar el malware y cerrar las vulnerabilidades que permitieron el ataque.

## Recuperación

Si la empresa cuenta con copias de seguridad, los sistemas pueden restaurarse sin necesidad de pagar el rescate solicitado por los atacantes.

## Prevención

Finalmente se recomienda implementar medidas de prevención como:

- Actualización constante de software
- Capacitación en seguridad para los empleados
- Implementación de sistemas de monitoreo

## Consideraciones éticas

No sería recomendable contratar a un hacker de sombrero gris para resolver el incidente, ya que aunque pueda tener conocimientos técnicos, su actuación podría generar problemas legales o comprometer la evidencia digital.

Además, pagar el rescate o intentar descifrar los archivos mediante métodos no oficiales puede incentivar más ataques y generar riesgos legales, por lo que lo más recomendable es seguir protocolos oficiales de seguridad y recuperación de información.

## Integración de conceptos
Relación entre los roles de hackers/crackers y las motivaciones del ataque

En el escenario planteado se observa un ataque que tiene como objetivo principal obtener un beneficio económico mediante el secuestro de información. Este tipo de comportamiento suele estar asociado con actores conocidos como hackers de sombrero negro o crackers, quienes utilizan sus conocimientos técnicos para explotar vulnerabilidades en los sistemas con fines maliciosos.

En este caso específico, los atacantes lograron obtener acceso inicial mediante técnicas de ingeniería social, enviando un correo que aparentaba provenir de un proveedor confiable. Una vez que el empleado descargó el archivo adjunto, se ejecutó un programa malicioso que permitió a los atacantes establecer una puerta trasera dentro del sistema.

A diferencia de los hackers de sombrero blanco, que utilizan sus conocimientos para mejorar la seguridad de los sistemas, o los hackers de sombrero gris, que se mueven en una zona intermedia entre lo ético y lo ilegal, los actores involucrados en este ataque claramente buscan generar daño y obtener ganancias económicas mediante el uso de ransomware.

Por lo tanto, las motivaciones del ataque pueden relacionarse principalmente con el lucro económico, ya que el cifrado de los archivos y la solicitud de rescate en criptomonedas indican un intento de extorsión digital.

## Impacto del incidente en la triada CID

La triada de seguridad compuesta por Confidencialidad, Integridad y Disponibilidad se ve afectada de diferentes maneras durante el desarrollo del incidente.

En primer lugar, la confidencialidad puede verse comprometida debido a que el troyano instalado en el sistema permite a los atacantes acceder de forma remota a la red interna de la empresa. Esto implica que información sensible, como bases de datos de clientes o archivos de configuración, podría ser visualizada o incluso copiada sin autorización.

En segundo lugar, la integridad de la información también se ve afectada, ya que el malware puede modificar o alterar archivos dentro del sistema. En muchos casos, los atacantes manipulan configuraciones o instalan software adicional que cambia el estado original de los sistemas.

Finalmente, la disponibilidad es el aspecto más claramente afectado en este escenario. El ransomware cifra los archivos críticos de la empresa, lo que impide que los usuarios puedan acceder a la información necesaria para realizar sus actividades. Esto puede detener completamente las operaciones de la organización.

## Cómo las medidas propuestas restauran la triada CID

Las medidas de respuesta al incidente buscan restaurar cada uno de los pilares de la triada de seguridad.

En primer lugar, al aislar los equipos comprometidos y eliminar el malware, se evita que los atacantes continúen accediendo a los sistemas, lo cual ayuda a recuperar la confidencialidad de la información.

Posteriormente, al analizar los sistemas afectados y verificar los archivos, se pueden identificar posibles modificaciones no autorizadas y restaurar versiones correctas de los datos, lo que permite recuperar la integridad de la información.

Finalmente, la restauración de los sistemas mediante copias de seguridad permite recuperar el acceso a los archivos cifrados, restableciendo así la disponibilidad de la información para los usuarios de la empresa.

De esta manera, las acciones de contención, recuperación y prevención contribuyen a restablecer el funcionamiento normal del sistema y a fortalecer la seguridad de la organización.
