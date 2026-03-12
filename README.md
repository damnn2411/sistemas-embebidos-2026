# SISTEMA INTELIGENTE DE MONITOREO Y CONTROL AMBIENTAL PARA PLANTAS EN INVERNADERO
## Integrantes y Roles
-Daniel Ayala (Technical Leader)

-Sebastian Pelaez  (Verification & Testing Engineer)

-Yoann Matarazzi (FirmWare Engineer)

-Thomas Moskovtchenko  (HardWare Engineer)

# Proyecto
El cultivo de plantas en entornos controlados como invernaderos permite optimizar las condiciones ambientales necesarias para su crecimiento y desarrollo. Variables como la temperatura, la humedad del ambiente y la humedad del suelo influyen directamente en procesos fisiológicos fundamentales de las plantas, incluyendo la absorción de nutrientes, la fotosíntesis y la transpiración. Cuando estos parámetros se encuentran fuera de los rangos adecuados, pueden generarse condiciones que afectan negativamente el crecimiento vegetal, reduciendo la productividad del cultivo o incluso provocando el deterioro de las plantas.

En la actualidad existen diversos sistemas comerciales destinados al monitoreo de variables ambientales en cultivos, los cuales permiten registrar información sobre las condiciones del entorno. Sin embargo, muchos de estos sistemas se limitan únicamente a la visualización de datos, requiriendo que el usuario interprete manualmente la información y tome decisiones para corregir posibles condiciones adversas. En otros casos, las soluciones disponibles pueden resultar costosas o poco accesibles para aplicaciones educativas o de pequeña escala.

En este contexto, el presente proyecto propone el desarrollo de un sistema embebido capaz de monitorear en tiempo real variables ambientales relevantes para el crecimiento de las plantas dentro de un invernadero, tales como la temperatura ambiente, la humedad relativa y la humedad del suelo. A partir de estas mediciones, el sistema evaluará continuamente el estado de las condiciones ambientales y determinará si se presentan situaciones que requieran una intervención automática.

Cuando las variables monitoreadas superen determinados umbrales previamente establecidos, el sistema activará mecanismos de control ambiental, tales como un sistema de riego automático o ventilación, con el fin de restablecer condiciones favorables para el desarrollo de las plantas. Adicionalmente, el sistema registrará los eventos relevantes asociados a su funcionamiento y permitirá visualizar el estado de las variables monitoreadas y de los actuadores mediante una interfaz de usuario.

Este prototipo busca demostrar la aplicación de sistemas embebidos para la automatización de procesos de monitoreo y control en entornos agrícolas a pequeña escala, integrando sensores, actuadores, procesamiento de datos y una interfaz de supervisión para el usuario.

# Objetivo General
Desarrollar un prototipo de sistema embebido capaz de monitorear variables ambientales relevantes para el crecimiento de plantas en un invernadero, específicamente la temperatura ambiente, la humedad relativa y la humedad del suelo, con el fin de detectar condiciones desfavorables y activar automáticamente mecanismos de control ambiental que contribuyan a mantener condiciones adecuadas para el desarrollo vegetal.

# Objetivos especificos 
Definir los componentes de hardware necesarios para la implementación del sistema, incluyendo sensores ambientales, microcontrolador y actuadores asociados al sistema de riego o ventilación.

Desarrollar e implementar el firmware encargado de la adquisición, procesamiento y evaluación de los datos provenientes de los sensores de temperatura, humedad ambiental y humedad del suelo.

Establecer rangos de operación adecuados para las variables ambientales monitoreadas, basados en condiciones típicas requeridas para el crecimiento saludable de las plantas.

Integrar actuadores controlados electrónicamente que permitan realizar acciones automáticas de control ambiental, tales como la activación de un sistema de riego o ventilación cuando se detecten condiciones fuera de los rangos establecidos.

Registrar los eventos relevantes del funcionamiento del sistema, incluyendo cambios en las condiciones ambientales y la activación de los actuadores, mediante un sistema de registro o logging.

Verificar el correcto funcionamiento del prototipo y de su interfaz de usuario, comprobando que esta permita visualizar las variables ambientales monitoreadas, el estado de los actuadores y los eventos relevantes asociados a la operación del sistema.
