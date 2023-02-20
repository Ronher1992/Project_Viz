![visualizaciondedatosdn2](https://user-images.githubusercontent.com/119512414/220103908-15dd8e34-b8ba-4351-afe1-fc6eae17ddd7.jpeg)

# Proyecto de Visualizacion

## Descripcion

El proyecto de Visualizacion se encarga basicamente de crear Dashboards con una ETL previamente creada y en lo cual podemos representar graficamente los datos que tenemos en las mismas.

### Introduccion.

De acuerdo a una encuesta realizada con Google Forms, se llego a la concliusion que el mundo del eSport no es muy conocido y que no se sabe a ciencia cierta cuales son las oportunidades que tiene este mundo asi como se aprecia en la siguiente imagen. 

<img width="863" alt="Screenshot 2023-02-20 at 13 44 00" src="https://user-images.githubusercontent.com/119512414/220115772-34abef20-2d6b-4651-ab4c-ab71f0a4ba9e.png">


### Analisis de los datos

Debido al desconocimiento que se planteo en el estudio del problema en este mundo, decidi basar mi analizis en las proyecciones por juegos y por streammers que representa a cada uno de estos juegos.

Por juego decidi analizar cuantos viewers hay y cual es la calidad misma de los canales relacionadas con el numero de viewers que hay, asi que decidi usar metricas como:

1. Suma de la cantidad de Viewers por canal.
1. El pico mas alto de viewers que han tenido el canal.
1. La cantidad de horas que ha sido stremeado el canal.
1. La media de viewers por canal.

Esto podriamos leerlo que a comparacion a otros medios, tendriamos un gran impacto con respecto a la visualizacion de la marca o de poner posicionar una marca de asi quererlo.

<img width="866" alt="Screenshot 2023-02-20 at 13 45 03" src="https://user-images.githubusercontent.com/119512414/220116193-1ee0eb74-07c6-4676-adbb-33b255a911b5.png">

Y por ultimo hice un analisis con respecto a los streamers que lo que hice fue separarlo por el lenguaje del stream, ya sea 'EN' para los que hablan Ingles y 'ES' para los de habla hispana, a eso le sume a cada uno de los graficos la suma de la cantidad total de los viewers y el pico de viewers que han tenido cada uno de los streamers en su canal. Vale destacar que tambien hice un 'Treemap' con todo y cada uno de los streamers que tenia mi base de datos filtrados igualemente por el idioma con el que el streamer se comunica.

<img width="864" alt="Screenshot 2023-02-20 at 13 46 12" src="https://user-images.githubusercontent.com/119512414/220117551-52411747-d1de-42a5-bf74-7ccd75a9fd92.png">

### Conclusiones

Se puede tener en cuenta que aunque con la base de datos con la que se trabajo no esta actualizada, aun se siguen viendo oportunidades en el sector y un impacto de visualizacion grande con respecto a otros medios.

## Herramientas usadas.

1. Power Bi. Para poder hacer las Visualizaciones.
1. Python. Para poder hacer correciones en el dato antes del uso del mismo.
1. MySQL.Para poder cargar el dato en tablas y usarlo mas comodamente de cara la Visualizacion.


    
    




