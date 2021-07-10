# Conceptos fundamentales de Azure
Existen tres tipos de modelos de nube y los usamos para cada caso dependiendo de las necesidades del usuario.


| Modelo       	| Descripción                                                                                                                	| Necesidad de usuario                                                                                                                                                                                                                      	|
|--------------	|----------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Nube Pública 	| Servicios ofrecidos a través de la red publica. Los recursos como servidores y almacenamiento son de un proveedor de Nube. 	| Dirigido a usuarios que quieran aprender, para pequeñas o grandes empresas que desean tener todo en la nube.                                                                                                                              	|
| Nube Privada 	| Hace uso de recursos informáticos de una organización para uso exclusivo. En pocas palabras estructura On-Premise.         	| Dirigido a organizaciones que pueden adquirir el hardware y necesitan tener control total de los mismos y de la seguridad.                                                                                                                	|
| Nube Híbrida 	| Combinación de una nube publica y privada que ayuda a compartir datos y aplicaciones entre ellas.                          	| Dirigido a las empresas que necesiten flexibilidad para determinar donde se van a ejecutar sus aplicaciones. Ya sea que elijan ejecutar unas aplicaciones de mayor computo en la nube y unas de almacenamiento en sus propios servidores. 	|

Existen ventajas que ofrece la Nube a comparación con entornos físicos (On-Premise). Estas ventajas pueden llevar a hacer soluciones mas rápidas, seguras y sobre todo menos costosas ya que solo pagamos por los servicios que usamos, algunas de estas ventajas son:

-	Disponibilidad: Microsoft tiene un compromiso que de acuerdo con el contrato SLA, este nos asegura que tendremos una experiencia continua sin tiempo de inactividad perceptible. Como por ejemplo por cuestiones de un desastre natural un centro de la Nube se haya colapsado, nuestros datos seguirán activos y podemos hacer uso de ellos de forma usual.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/2_dispo.png"  width="50%" style="text-align:center;"/>

-	Elasticidad: Nuestras aplicaciones siempre estarán actualizadas gracias a que la Nube aplica escalado automático, por esta razón no existirá la preocupación de saber si tenemos los recursos necesarios para realizar las funciones que necesitemos.

-	Agilidad: La plataforma de Microsoft Azure nos permite implementar y configurar los recursos basados en la Nube a medida que nosotros lo necesitemos. Las necesidades cambian constantemente, Azure lo hace a la par con nosotros.

-	Distribución geográfica: Microsoft Azure tiene centros de datos regionales en todo el mundo lo que garantiza que siempre tendrá el mejor rendimiento ya sea que el centro de datos este en su región o decida implementarlos en otra localidad.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/2_dist_geo.png"  width="50%"/>

-	Recuperación ante desastres: Por cualquier motivo que se presente, existe el servicio de copia de seguridad basado en la Nube nos ayudará a mantenernos tranquilos sabiendo que nuestra información estará segura y disponible.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/2_recu.png"  width="50%"/>

## ¿On-Premise vs Nube (En costos)?
Anteriormente las organizaciones hacían una inversión de dinero en infraestructura física (CapEX) pero con el paso de los años esta tecnología se volvía lenta o simplemente no era apto para las necesidades actuales.
Microsoft se dio cuenta que podría reducir este costo a las organizaciones promoviendo la inversión en servicios o productos a medida que se usaran (OpEX).
Viéndolo desde este punto de vista las organizaciones se ahorrarían además del costo de hardware, también el personal, la seguridad requerida, la infraestructura adecuada, etc. Con la Nube lo único que se debe preocupar la organización es saber que servicios esta usando y cuando pagarlos.

<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/2-on_premise.jpg"  width="50%"/>


## ¿Que servicio de la Nube es lo mejor para la empresa?
La Nube tiene diferentes servicios para cada necesidad de las empresas, pero principalmente son tres, a continuación los servicios.

IaaS (Infraestructura como servicio) -> Un proveedor de la Nube mantendra el hardware actualizado pero quien debe de ver que sistema operativo y la configuracion de red sera meramente responsabilidad de la empresa.
Lo bueno de este servicio es que podemos administrar de mejor manaera en donde se van a procesar los recursos pero teniendo el control sobre ello. Es ideal para una empresa que tenga On-Premise pero requiera potencializar los recursos sin tener que hacer un gasto excesivo para obtener mayor computo.

PaaS (Plataforma como servicio) -> El proveedor de la Nube administra las maquinas virtuales, los recursos de red y tambien implementa las aplicaciones en el entorno de hospedaje administrado. No es necesario adquirir hardware y tampoco tener personal propio para la configuracion del servidor. Es ideal para una empresa que no tenga conocimientos tecnicos avanzados sobre servidores y solo desee aprovechar la tecnologia para el desarrollo de aplicaciones o soluciones requeridas.

SaaS (Software como servicio) -> El proveedor de la Nube administrara todos los aspectos junto con los recursos de la aplicación. Es dirigido a empresas que deseen solo proveer sus servicios al publico ya sea con un modelo de suscripcion o dependiendo cuanto usen el software.

<center>
<img src="https://raw.githubusercontent.com/jeovani-microsoft/Reto_Semana_1/main/assets/2_Saas.jpg"  width="50%"/>
</center>


Como conclusión podemos decir que la Nube ayuda de una forma u otra en esta época de crecimiento tecnológico y como es de suponerse el desarrollo es lo principal para estar siempre actualizados, es por eso que la Nube nos ayuda a ahorrarnos tiempo y dinero para solo enfocarnos en traer soluciones al mundo en el que estamos viviendo. La informática sin servidor será una realidad muy próxima a la que todos nosotros estaremos viviendo.

