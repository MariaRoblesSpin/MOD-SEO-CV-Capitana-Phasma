# CV-Capitana-Phasma-MOD-HTML-JAVASCRIPT

El currículum vitae web de la Capitana Phasma, un miembro relevante de la primera orden.

Es necesario instalar el módulo npm http-server para el visionado de la página:
https://www.npmjs.com/package/http-server

y ejecutar el comando http-server en la terminal.

En la carpeta **CV-Capitana-Phasma-MOD-HTML-JAVASCRIPT-master** está el código del comienzo de curso **sin la optimización SEO**.

En la carpeta **CV-Capitana-Phasma-MOD-SEO** está el **código optimizado**.

# Apuntes SEO

## Archivos css

He unificado los archivos css en un único archivo puesto que es preferible para optimizar la velocidad de carga.

## Title y meta description

He incluido una etiqueta title con las palabras clave principales (Curriculum vitae, Capitana Phasma) de la página y una meta description con palabras clave de caracter secundario (cruel, villana, líder, implacable, asesina).

## Falta el acceso seguro mediante el protocolo https

Al hacer la implementación definitiva del sitio tendría que ser una dirección segura mediante el protocolo https para certificar que la web es legitima y garantizar la integridad y la seguridad de la conexión.

## Nombre del dominio

Si fuera a comprar un dominio elegiría un nombre optimizado para SEO: lamejorcapitana.com, por ejemplo. Emplearía el protocolo https, como he comentado en el punto anterior y cambiaría también el nombre del archivo index.html por curriculum-phasma.html para que las rutas quedaran así:
- https://lamejorcapitana.com/curriculum-phasma#home
- https://lamejorcapitana.com/curriculum-phasma#quiensoy
- https://lamejorcapitana.com/curriculum-phasma#misestudios
- https://lamejorcapitana.com/curriculum-phasma#miexperiencia
- https://lamejorcapitana.com/curriculum-phasma#sobremi
- https://lamejorcapitana.com/curriculum-phasma#contacto

Con algo más de tiempo hubiera creado una versión amp de la página. Como me obliga a estudiarme las especificaciones técnicas , a modificar el html y también el js no me da tiempo. Espero que lo entiendas.

## Titles de los enlaces

He modificado los titles de los enlaces para que dieran información más precisa de lo que muestra cada sección.

## Estructura de encabezados y organización del código

**h1:** CV Capitana Phasma (un único h1 que representa el título principal de la página).
**h2:** Cada uno de los apartados de la web está dentro de una etiqueta section que a su vez tiene dentro un header con el título de la sección dentro de un h2.
- Capitana Phasma
- ¿Quién soy?
- Mis estudios
- Formación complementaria (h2 dentro de un aside puesto que es formación adicional).
- Mi experiencia
- Sobre mí
- Contacto

**h3:** Encabezados h3 para todos los subapartados de las secciones y los subapartados dentro del aside de formación complementaria.

En "Formación complementaria":
- Idiomas.
- Armas.
- Logros y condecoraciones.

En "Sobre mí":
- Puntos fuertes
- Aficiones
- Otros datos de interés.

El menú es el mismo para la versión de escritorio y el móvil de manera que no se duplican los enlaces.

## Robot.txt y sitemap.xml

Al tratarse de una web de 2 páginas no tienen sentido. Los buscadores no necestan ayuda para entender la estructura de la página y no hay nada que queramos evitar que rastreen.

## rel= "canonical"

Como no hay contenidos duplicados en distintas versiones el atributo rel="canonical" no es necesario.


## Microdatos

He empleado el esquema Person para destacar los siguientes datos que me han parecido relevantes:
- name.
- jobtitle.
- description.
- Esquema imageObject.
  - image.
  - caption.
- alumniOf (x4). Esquema EducationalOrganization:
  - name.
  - description.
- Esquema Job: jobs (x5) (no he visto lógico incluir hasOcupation porque no tenía fechas y no iba a poder especificar el roleName con la fecha de incio y fin de cada trabajo).
  - name.
  - location.
- Esquema ItemList (x2: idiomas y armas).
  - name.
  - itemListElement.
- award (x2).
- url (en los enlaces a mis redes sociales, como si fueran los de la Capitana Phasma).

Tal vez si hubiera sido un currículum real hubiera añadido el itemprop="email" y el itemprop="telephone". En este caso no tenía sentido.


## Contenido

El contenido es consistente, está compuesto por vocabulario bélico en el que se destacan las cualidades profesionales y despiadadas del personaje:
- capitana: 10 veces. En la url, en el title, en la meta description, en el h1 y diseminada por el contenido.
- lado oscuro: 4 veces. En la meta description y ragada por el contenido.
- primera orden: 7 veces. 
- dotes de mando: 3 veces. En la meta description.
- villana: 3 veces. En la meta description.
- cruel: 3 veces.  En la meta description.