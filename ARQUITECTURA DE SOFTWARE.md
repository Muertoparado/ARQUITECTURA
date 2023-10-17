##ARQUITECTURA DE SOFTWARE

******Arquitectura cliente-servidor**

La arquitectura cliente-servidor es una estructura de aplicación distribuida que separa las tareas y las cargas de trabajo entre servidores y clientes. Los servidores proporcionan el recurso o servicio, mientras que los clientes lo solicitan.

Tanto el cliente como el servidor son programas independientes que se comunican a través de una red. Un navegador web y un servidor web son un ejemplo de arquitectura cliente-servidor. Se trata de una arquitectura comúnmente utilizada en la computación distribuida. 

**Cliente**
Los clientes tienen información y capacidad de procesamiento limitadas. En cambio, realizan solicitudes a los servidores, que administran la mayoría de los datos y otros recursos. Puede realizar solicitudes al cliente y este se comunica con el servidor en su nombre.

**Servidor**
Las computadoras servidor sincronizan y administran el acceso a los recursos. Responden a las solicitudes de los clientes con datos o información de estado. Normalmente, un servidor puede manejar solicitudes de varias máquinas.

**Beneficios y limitaciones**
La arquitectura cliente-servidor brinda los beneficios de seguridad y facilidad de administración continua. Sólo tienes que concentrarte en proteger las computadoras del servidor. De manera similar, cualquier cambio en los sistemas de bases de datos requiere cambios en el servidor únicamente.

La limitación de la arquitectura cliente-servidor es que los servidores pueden provocar cuellos de botella en la comunicación, especialmente cuando varias máquinas realizan solicitudes simultáneamente.

**MICROSERVICIOS**

La arquitectura de microservicios se compone de componentes de software muy pequeños y completamente independientes, llamados microservicios, que se especializan y se centran en una sola tarea. Los microservicios se comunican a través de API, que son reglas que los desarrolladores crean para permitir que otros sistemas de software se comuniquen con su microservicio.

El estilo arquitectónico de microservicios se adapta mejor a los entornos modernos de computación en la nube. A menudo operan en contenedores: unidades de software independientes que empaquetan código con todas sus dependencias.

**Beneficios de los microservicios**
Los microservicios son escalables de forma independiente, rápidos, portátiles e independientes de la plataforma, características nativas de la nube. También están desacoplados, lo que significa que tienen dependencia limitada o nula de otros microservicios. Para lograr esto, los microservicios tienen acceso local a todos los datos que necesitan en lugar de acceso remoto a datos centralizados a los que otros sistemas también acceden y utilizan. Esto crea una duplicación de datos que los microservicios compensan en rendimiento y agilidad.

**SOA comparado con microservicios**
La arquitectura de microservicios es una evolución del estilo arquitectónico SOA. Los microservicios abordan las deficiencias de SOA para hacer que el software sea más compatible con los entornos empresariales modernos basados en la nube. Son detallados y favorecen la duplicación de datos en lugar de compartirlos. Esto los hace completamente independientes con sus propios protocolos de comunicación que se exponen a través de API livianas. Básicamente, el trabajo de los consumidores es utilizar el microservicio a través de su API, eliminando así la necesidad de un ESB centralizado.



```

```

