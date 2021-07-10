# Descripción de los componentes principales de la arquitectura de Azure

<center>
<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/01-Azure.png"  width="80%"/>
</center>

**Recursos:** Son elementos que brindan servicios y se pueden crear.
<center>
<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/Maq_virtuales.png"  width="19%"/>
  <img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/Kubernetes.png"  width="19%"/>
  <img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/Cosmos.png"  width="19%"/>
  <img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/Apps_web.png"  width="19%"/>
  <img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/SQL.png"  width="19%"/>
</center>


**Grupos de recursos:** Son conjuntos de recursos, los cuales funcionan como contenedores en donde se ejecutan y administran los recursos que ofrece Azure.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/03_group"  width="80%"/>


**Suscripciones:** Es una unidad lógica que nos permite reunir las cuentas de usuario y los recursos creados de las mismas. En cada suscripción existen límites o cuotas para establecer la máxima cantidad de recursos que se pueden crear y utilizar.
Tipos de límites de suscripciones:
* Límite de facturación.
* Límite de control de acceso.
* Crear suscripciones adicionales pueden servir para separar:
* Entornos.
* Estructuras organizativas.
* Facturación.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/03_suscr.png"  width="80%"/>


**Grupos de administración:** Son grupos que permiten administrar el acceso, las directivas y el cumplimiento de varias suscripciones. Cuando se le aplican determinadas condiciones a los grupos de administración, estas se heredan a las diferentes suscripciones del grupo.

**Regiones:** Es un área geográfica del planeta en la cual se ubica al menos un centro de datos , y a su vez podrían ser varios centros de datos cercanos conectados mediante una red de baja latencia.

Si quieres saber cual es la mejor zona geográfica para tí, revisa el siguiente enlace: Busque la geografía de Azure que se ajuste a sus necesidades

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/03_regions.png"  width="80%"/>


**Par de regiones:** Para cada región de Azure existe otra con la cual se empareja en la misma zona geográfica con un mínimo de 500 km de distancia, permitiendo así la replicación de recursos y evitar las interrupciones del servicio.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/par_regiones.gif"  width="80%"/>


**Zonas de disponibilidad de Azure:** Son centros de datos separados físicamente pero ubicados dentro de la misma región. Estas zonas están conectadas entre sí con cables de fibra óptica de alta velocidad privadas. Si alguna deja de funcionar, la otra continúa trabajando.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/03_zonas.png"  width="80%"/>


**Azure Resource Manager:** Es el servicio de implementación y administración para Azure. Nos brinda una capa en la cual podemos administrar recursos en la cuenta de Azure.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/resource_manager.png"  width="80%"/>

**App Service:** Es un servicio con base en HTTP con el que podemos crear y hospedar diferentes soluciones basadas en la web sin que tengamos que administrar la infraestructura.

**Azure Marketplace:** Es una tienda en línea dentro de Azure que nos permite obtener aplicaciones certificadas y optimizadas para ejecutarse en Azure.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/Servicios/amp_homepage_learn.png"  width="80%"/>


## Enlaces de interés general:
* [Breve Introducción al Cloud Computing](https://www.threepoints.com/es/breve-introduccion-al-cloud-computing)

* [¿Qué son los proveedores de nube?](https://www.redhat.com/es/topics/cloud-computing/what-are-cloud-providers)

* [¿Que es Windows Azure?](https://youtu.be/x-8LDoZksns) (Video)

* [Generalidades de Windows Azure](https://youtu.be/qp1IEk8-m8w) (Video)

* [Cloud Computing: Principales proveedores y casos de éxito](https://youtu.be/qp1IEk8-m8w)

* [3 empresas que utilizan el Cloud Computing](https://youtu.be/qp1IEk8-m8w)

* [Grandes empresas que innovaron con la nube](https://www.esourcecapital.com/posts/grandes-empresas-que-innovaron-con-la-nube)

* [6 de cada 10 empresas de todo el mundo ya utilizan o están probando la nube híbrida](https://www.esourcecapital.com/posts/grandes-empresas-que-innovaron-con-la-nube)
