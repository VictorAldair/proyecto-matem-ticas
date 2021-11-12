# Qué son los web services
El término Web Services describe una forma estandarizada de integrar aplicaciones WEB mediante el uso de XML, SOAP, WSDL y UDDI sobre los protocolos de la Internet. XML es usado para describir los datos, SOAP se ocupa para la transferencia de los datos, WSDL se emplea para describir los servicios disponibles y UDDI se ocupa para conocer cuales son los servicios disponibles. Uno de los usos principales es permitir la comunicación entre las empresas y entre las empresas y sus clientes. Los Web Services permiten a las organizaciones intercambiar datos sin necesidad de conocer los detalles de sus respectivos Sistemas de Información.
Los Web Services permiten a distintas aplicaciones, de diferentes orígenes, comunicarse entre ellos sin necesidad de escribir programas costosos, esto porque la comunicación se hace con XML. Los Web Services no están ligados a ningún Sistema Operativo o Lenguaje de Programación. Por ejemplo, un programa escrito en Java puede conversar con otro escrito en Pearl; Aplicaciones Windows puede conversar con aplicaciones Unix. Por otra parte los Web Services no necesitan usar browsers (Explorer) ni el lenguaje de especificación HTML
Primero llegó SOAP
La primera introducción de los web services en el mundo de Internet vino de la mano de SOAP. SOAP es un protocolo que define cómo deben de realizarse las comunicaciones entre máquinas. SOAP usa XML como lenguaje de intercambio de datos con una estructura compleja que es capaz de albergar todo tipo de datos sobre la solicitud o respuesta generada.

Luego llegó REST
REST usa el propio protocolo HTTP para la comunicación entre máquinas. HTTP es ampliamente soportado por todos los sistemas y de hecho para la transferencia de datos en la web se usa HTTP.

REST se caracteriza por no tener estado. Es decir, el servidor no es capaz de recordar el estado de la anterior solicitud REST que pudo, o no, hacer un cliente. Por ello, el cliente tiene que enviar en cada solicitud todo el estado de su sesión, lo que se suele hacer mediante un token que le «ayude a recordar» al servidor.

Mencionamos esas dos características porque es justamente lo permite que la implementación de REST sea realmente fácil y se haya popularizado tanto el tipo de servicio web que se conoce como el nombre de API REST.

REST tiene a simplificar las cosas y en esa misma línea se suele usar un lenguaje diferente para representación de los datos, el lenguaje JSON. Hoy REST y JSON se han convertido en la opción más sencilla y por tanto más recomendable para implementar un servicio web.
