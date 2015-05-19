#		Anteproyecto Fin de Carrera

###**Título**: Automatismo para recopilación de datos desde las APIs de *Google AdWords* y *Google Analytics* para la generación de informes.
###**Title**: Middleware that gets data from *Google AdWords* and *Google Analytics* APIs to create reports.

**Nombre**: Héctor Manuel Sosa Fructuoso.

**Director:** Francisco López Valverde.
**Departamento:** Lenguajes y Ciencias de la Computación.

**1. Introducción.** Actualmente, para que una campaña tenga éxito en Internet, y sea rentable, debe además contar con el coste de una persona experimentada que adapte pujas, PPC, Keywords, CTR, sin perder de vista el objetivo. 
Ésto implica que las campañas pequeñas, ya sean de empresas pequeñas, o de empresas de tamaño medio con un negocio por Internet pequeño o inexistente, apenas pueden optar a la eficiencia, ya que deben elegir utilizar servicios externos de consultoría (caros y de baja calidad en muchos casos) o el control por parte de personal no experto, dejando la efectividad prácticamente al azar, de tal forma que no se puede prever el efecto que tengan procesos futuros.

**2. Objetivo.** Este proyecto tiene como objetivo la creación de un automatismo que recopile los datos de las herramientas de Google para marketing con el fin de elaborar un informe con recomendaciones para mejorar la eficiencia de las campañas, y en un futuro aplicar las mejoras directamente sin interacción del usuario.

Esta herramienta tendrá también carácter de *middleware*, ya que podrá interactuar directamente con otras herramientas del departamento.

Los objetivos concretos a alcanzar con el desarrollo de este proyecto son:
* Diseñar una aplicación siguiendo el patrón Modelo-Vista-Controlador.
* Utilizar el lenguaje de programación Python, que apuesta por la legibilidad.
* Implementar métodos de interacción directa con otras aplicaciones (*middleware*).
* Implementar una interfaz gráfica para su uso de forma independiente.
* Controlar la seguridad y privacidad de los datos de los usuarios 

**3. Herramientas a utilizar en el desarrollo.** Para desarrollar este proyecto se utilizarán distintas herramientas, detalladas a continuación:

* Python. Como lenguaje de programación.
* MySQL. Como motor de la BD.
* Sublime text 3.0. Para escribir y compilar código.
* GitHub. Para el control de las versiones.
* VirtualBox. Para la emulación del servidor que correrá la aplicación.
* Debian 8.0 como SO para la máquina virtual.

**4. Métodos y fases.** El proyecto se va a dividir en cinco fases:
1. Adquisición de información. Se estudiarán por un lado las APIs de AdWords y Analytics para conocer de antemano las posibilidades que ofrecen, y por otro las utilidades de las herramientas de cara evaluar las necesidades de la aplicación.

2. Definición de la estructura de datos. Qué datos y cómo se van a almacenar.

3. Diseño de la aplicación.
	* Fase de adquisición de datos.
	* Fase de interacción con el exterior.

4. Pruebas y resolución de errores. Se configurará la aplicación para obtener datos de una cuenta real. 

5. Diseño de la interfaz de usuario. Se creará un interfaz de usuario por si se desea utilizar la aplicación de forma independiente.

El proyecto se va a dividir en 3 fases: Análisis, Diseño e Implementación

1. Análisis. Adquisición de información. Se estudiarán por un lado las APIs de AdWords y Analytics para conocer de antemano las posibilidades que ofrecen, y por otro las utilidades de las herramientas de cara evaluar las necesidades de la aplicación.
2. Diseño. Se diseñará la aplicación siguiendo el patrón Modelo-Vista-Controlador.
3. Implementación. Se atacará de forma modular para maximizar la reutilización de código. 

**5. Bibliografía y referencias.**
	
* [Markdown Basics](https://help.github.com/articles/markdown-basics/) Para la escritura con Markdown sobre sublime. También compatible con las páginas públicas de GitHub.
* Guías sobre las APIs
	- [Introducción al AdWords API](http://programa-con-google.blogspot.com.es/2011/03/introduccion-al-adwords-api-para.html)
	- [Visión general de la AdWords API. Por Google](https://developers.google.com/adwords/api/docs/?hl=es)
	- [Analytics for developers. Por Google](https://developers.google.com/analytics/?hl=es)
	- [Ayuda de las API de Analytics. Por Google](https://support.google.com/analytics/answer/1008004?hl=es)
* [6 Trucos para Optimizar AdWords](http://www.seocom.es/blog/6-trucos-adwords) Para aprender sobre el tema.
 
