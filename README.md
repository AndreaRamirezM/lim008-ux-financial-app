# APP FINANCIERA

## Preámbulo

El banco más importante del país ha lanzado una nueva aplicación móvil al
mercado para que sus usuarios puedan visualizar sus gastos mensuales y fomentar
el ahorro. Luego de tener algunos meses en el mercado y algo de tracción, el
equipo detrás de este nuevo producto ha decidido contratar a una
agencia/consultora de UX que los ayude a definir la dirección y evolución del
producto. Tú y otra compañera de Laboratoria trabajan en la agencia/consultora
de UX y son asignadas al proyecto.

## Introducción

### Contexto

Durante la primera semana de entendimiento de los requerimientos, el Product
Manager del equipo les brinda el contexto:

>“Todo empezó hace un año cuando vimos que en EEUU y Europa estaban saliendo
  nuevas aplicaciones financieras que nos llamaron la atención. Unas se enfocan
  en darle visibilidad a sus usuarios sobre los gastos, otras en facilitar pagos
  a terceros y otras a fomentar el ahorro. Inspirados en un par de ellas,
  decidimos lanzar una nueva aplicación. Decidimos que era mejor crear un
  producto desde cero - en lugar de modificar la aplicación actual de banca
  móvil - para poder desarrollarla con un equipo totalmente nuevo, en el
  laboratorio de innovación, bajo prácticas ágiles. Sabemos que no es ideal que
  nuestros usuarios tengan que usar dos aplicaciones, pero desarrollar con un
  equipo nuevo que corra ágil nos da mayor libertad.

> Empezamos entrevistando a algunos usuarios y revisando los resultados de un
  estudio de mercado que nos proporcionó el área de marketing. Eso nos dió una
  idea inicial de qué funcionalidades son más relevantes aquí en nuestro
  mercado. Con base en esos resultados, creamos nuestros primeros user personas
  una primaria y una secundaria ( creemos que estas personas no son las que
  nosotros pensábamos inicialmente), y diseñamos y desarrollamos un ‘Producto
  mínimo viable’ (MVP) en 2 meses en iOS. Ese MVP lo hemos lanzado y tenemos
  alrededor de 6 meses de data. Hoy estamos en el proceso de entender los
  resultados iniciales y de sacar una segunda iteración del producto. Y para eso
  las hemos contratado. Toda la documentación de este producto la tenemos en una
  carpeta de [Google Drive](http://bit.ly/uxd-reto-2). Les doy acceso.
  
> Necesitamos traer una propuesta del nuevo diseño en dos semanas porque tenemos
  que presentarla a nuestro Gerente General en la reunión trimestral. Es
  importante que cualquier cosa que presentemos ya incorpore feedback de testing
  con usuarios. El Gerente General, animado por el crecimiento del número de
  descargas que ha tenido el app, quiere duplicar el presupuesto de Facebook
  Ads… Yo no estoy tan seguro; quisiera que como parte de su trabajo estas
  próximas dos semanas, entendamos ese punto también.”

![preview app de finanzas](https://lh3.googleusercontent.com/WyfUPurRuoXyyeZScQtdLhk063ZozToVlujoljul3TDwJW5KZy3Om_LvuB-TB9IcG2r_BCSpoXtXL-bZjIeGBFxQmL4GYEM2QXnQovq6EvixYaO_Z5-gFMvljM9jye7bVofendMteBI)

### Recursos

En esta carpeta de [Google Drive](http://bit.ly/uxd-reto-2) y en los siguientes
links, encontrarán:

- Los user persona primario y secundario del proyecto
- Los user flows iniciales y actuales del proyecto del MVP
- El [diseño del app en Figma](https://www.figma.com/file/Gr5GEIRrjF9eIplIeEHUSJNt/proyecto-2-banca?node-id=0%3A477)
  , con una guía de componentes y el [Prototipo navegable](https://marvelapp.com/e9h245e)
- Funnel Analytics de los primeros 6 meses del MVP
- Data de uso del MVP de los primeros 6 meses
- [Landing Page](http://tus-finanzas.pagedemo.co) inicial del producto

## OBJETIVOS
Los objetivos que consideramos para este proyecto, son los siguientes:

* Comprobar si el User Persona al que está enfocada la aplicación móvil que hemos recibido es la correcta.
* Identificar si existen necesidades de usuarios que no están siendo cubiertas.
* Identificar si la aplicación tiene un flujo intuitivo.
* Rediseñar la aplicación en el caso encontremos ...


## HIPOTESIS
Luego de la entrevista que tuvimos con el cliente y del análisis de la data que recibimos, tenemos las siguientes hipótesis: 

![HIPOTESIS](https://user-images.githubusercontent.com/45084125/54446576-4213f400-4715-11e9-89ce-91ea371c754c.png)



## INVESTIGACION
### Entrevistas
#### Objetivo
Conocer a los potenciales usuarios de la aplicación financiera, identificar sus necesidades, entender sus comportamientos frente al uso de otras aplicaciones relacionadas.

Aquí presentamos algunas de las citas que fueron relevantes para tomar decisiones en la solución del desafío.

![CITAS ENTREVISTAS](https://user-images.githubusercontent.com/45084125/54445164-3a068500-4712-11e9-81e2-9061212e8156.png)
- [Guía de entrevistas](https://docs.google.com/document/d/1zcnVLJybcthucIbBnUPcAUN4WqVJBeHt5XERYS-lNTg/edit)
- [Audios de entrevistas](https://drive.google.com/drive/folders/1-3S31m6U3uVzd68BdqnQNzHOJAlqTyq_)

### Observación Contextual
#### Objetivo
Encontrar información relevante y fidedigna de los usuarios a cerca de la funcionalidad y la experiencia que ellos tenían al usar la aplicación.

![O C](https://user-images.githubusercontent.com/45084125/54446518-214b9e80-4715-11e9-9c18-ff6dcfa3d184.png)
### Testeos de Prototipo Inicial
### Benchmark

## SÍNTESIS Y DEFINICIÓN

#### AFFINITY MAP
Al terminar las entrevistas, identificamos las citas más relevantes de cada uno y realizamos el mapa de afinidad para clasificarlas por categorías y encontrar patrones de repetición.

![My First Board](https://user-images.githubusercontent.com/45084125/54479124-d6e72200-47e7-11e9-9445-82834b258e75.jpg)

#### CUSTOMER JOURNEY MAP
Exponemos aquí las interacciones que realiza el usuario en su experiencia con el uso de la aplicación financiera.

Puntos negativos y neutros que identificamos :

1. Ante la posibilidad de instalar la aplicación, los usuarios de dipositivos Android no pueden hacer la descarga. (Datos obtenidos de la data propocionada por el cliente).

2. En la navegación general, es difícil para el usuario regresar al "Home", la espera de carga de las pantallas lo confunde. Los usuarios que no están familiarizados con el ingreso por huella digital, no saben qué hacer y prefieren regresar o cancelar la pantalla que están explorando.

3. El botón de "crear cuenta" no es entendible, el usuario tiene dudas en si creará o no,una nueva cuenta de ahorros en su banco


 ![customer](https://user-images.githubusercontent.com/45084125/54445792-87372680-4713-11e9-8915-a0a0e59d0c0a.jpg)

#### PROBLEM STATEMENTS
Luego de ya conocer a nuestro usuario principal y además conocer sus necesidades, podemos identificar los problemas para empezar a plantear posibles soluciones.


![problem statements](https://user-images.githubusercontent.com/45084125/54449858-1137bd00-471d-11e9-89e5-52a3df5bc7a4.png)



![Hmg](https://user-images.githubusercontent.com/45084125/54478880-2841e200-47e5-11e9-9a9c-60fc2a7ec65b.png)



