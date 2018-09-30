# Ejercicios Tema 1. Introducción a la infraestructura virtual: concepto y soporte físico

---

- **Ejercicio 1.
  Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.**

Para el primer ejercicio, he optado por escoger este [servidor](https://www.pccomponentes.com/hp-proliant-ml350-gen9-intel-xeon-e5-2603v4-8gb), de un precio de 1.729 €.

Para calcular la amortización, vamos a guiarnos utilizando está página [¿Cómo se calcula la amortización?](https://www.serautonomo.net/¿como-se-calcula-la-amortizacion.html)

El procentaje de pérdida de valor que establece la Agencia Tributaria sobre equipos para tratamiento de la información y sistemas y programas informáticos es de un 26% anualmente.

Por tanto, si nuestro servidor vale 1.729 € al 26% obtenemos: 1279,46 al año siguiente.

A los 4 años nuestro servidor se devalua: 1798,16 € (Totalmente amortizado).
Y a los 7 años: 3146,78 €.

---

- **Ejercicio 2.
  Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.**

Para la elaboración del ejercicio 2, he buscado el VPS [interServer](https://www.interserver.net), y como proveedor de servicios en la nube he obtado por [AWS](https://aws.amazon.com/es/).

El VPS con las características de:

    - 2 Cores (CPU).
    - 8 GB de RAM.
    - 200 GB de almacenamiento.
    - 8 TB de transferencia.

El precio es de 48 $/mes (No se calcular el precio en cuanto al porcentaje de uso, en dicho caso estamos hablando de un uso continuo).

El servidor cloud tiene la siguiente característica:

    - 2 vCPU.
    - 4 GiB.
    - Hasta 10 Gbps.

El precio al 1% de uso es de: 0,81$.

El precio al 10% de uso es de: 7,48$.

Por tanto es mucho más recomendable utilizar servidores cloud ya que es mucho más barato. Para más información sobre [comparativas entre VPS y servidores cloud](https://www.quora.com/Which-one-is-better-VPS-Hosting-Vs-Cloud-Hosting).

---

- **Ejercicio 3.
  En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?**

- [x] Hecho

---

- **Ejercicio 4.**
    1. Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden ```kvm-ok```.
    2. Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.

- [x] Hecho

---

- **Ejercicio 5.
    Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.**

- [x] Hecho

---

- **Ejercicio 6.
    Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.**
