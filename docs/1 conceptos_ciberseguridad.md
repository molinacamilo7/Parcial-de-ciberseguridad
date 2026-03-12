# Conceptos básicos de ciberseguridad

La ciberseguridad puede definirse como el conjunto de prácticas y herramientas utilizadas para proteger sistemas informáticos, redes y datos frente a accesos no autorizados o ataques.

Actualmente es un aspecto fundamental para cualquier organización que maneje información digital.

## Características de la ciberseguridad

Entre sus características más importantes se encuentran:

- Protección de datos sensibles
- Prevención de ataques informáticos
- Identificación de vulnerabilidades
- Monitoreo de sistemas

Además, la ciberseguridad también se aplica en la vida cotidiana. Por ejemplo, cuando una persona utiliza contraseñas seguras o evita abrir correos sospechosos está aplicando principios básicos de seguridad digital.

## Triada de seguridad

Uno de los modelos más importantes dentro de la seguridad informática es la triada CID:

Confidencialidad: busca que la información solo sea accesible para personas autorizadas.

Integridad: garantiza que los datos no sean alterados de manera indebida.

Disponibilidad: asegura que los sistemas estén disponibles cuando los usuarios los necesiten.

Un ejemplo interesante donde se puede observar la aplicación de estos principios es el estándar EMV, utilizado en tarjetas de crédito con chip.

En este caso, la confidencialidad se protege mediante el uso de criptografía que evita que los datos de la tarjeta puedan ser copiados fácilmente.

Asimismo, la integridad se asegura mediante mecanismos que verifican que la transacción no haya sido alterada durante el proceso de pago.

Por último, la disponibilidad permite que las transacciones puedan realizarse correctamente en diferentes terminales sin afectar el funcionamiento del sistema.

## Identificación de malware en un equipo

Cuando un computador empieza a comportarse de forma extraña después de descargar un archivo, es importante realizar un análisis.

En primer lugar, una medida básica consiste en desconectar el equipo de la red para evitar que el posible malware se propague a otros dispositivos.

Después de esto, se recomienda ejecutar un análisis completo con un antivirus actualizado. Este paso suele permitir identificar archivos sospechosos o programas que se ejecutan sin autorización.

También es útil revisar los procesos activos del sistema y observar si hay programas desconocidos funcionando en segundo plano.

Por último, analizar los registros del sistema puede ayudar a identificar cuándo comenzó el problema y qué cambios ocurrieron después de la descarga del archivo.

Este tipo de revisión permite determinar si el problema está relacionado con un virus, un gusano o un troyano.

## Diferencias entre phishing, smishing, vishing y whaling

Los ataques de ingeniería social son bastante comunes porque buscan aprovechar errores humanos en lugar de vulnerabilidades técnicas.

El phishing, por ejemplo, consiste en enviar correos electrónicos que aparentan ser legítimos. Muchas veces se hacen pasar por bancos o plataformas conocidas con el objetivo de obtener datos personales.

El smishing funciona de manera similar, pero se realiza a través de mensajes de texto. Un ejemplo típico es recibir un SMS que indica que existe un problema con una cuenta o que se ha ganado un premio.

Por otro lado, el vishing se basa en llamadas telefónicas donde el atacante intenta obtener información haciéndose pasar por un representante de una empresa.

Finalmente, el whaling es un ataque dirigido específicamente a personas con cargos altos dentro de una organización, como gerentes o directores. En estos casos los atacantes buscan engañar a estas personas para realizar transferencias o compartir información sensible.

## Seguridad en el uso de Git y GitHub

Cuando se trabaja con herramientas como Git y GitHub para gestionar proyectos o almacenar información, también es importante tener en cuenta ciertos aspectos de seguridad.

En primer lugar, el usuario crea o modifica un documento en su computador local.

Posteriormente, se inicializa el repositorio utilizando el comando:

git init

Después, se agregan los archivos al área de preparación mediante:

git add .

A continuación, se registra el cambio con un commit:

git commit -m "primer commit"

Luego se conecta el repositorio local con el repositorio remoto en GitHub:

git remote add origin URL_DEL_REPOSITORIO

Finalmente, se envían los archivos al repositorio remoto mediante:

git push origin main

Este proceso permite mantener un control de versiones y garantizar una gestión organizada del proyecto.
