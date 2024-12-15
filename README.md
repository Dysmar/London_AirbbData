![Banner](./bannerlondon.jpg.jpg)
<img src="bannerlondon.jpg.jpg" width=100%/>


# London_AirbbData
Como asesor de viajes con experiencia en análisis de datos, mi objetivo es crear una programación de viaje personalizada para una experiencia atractiva en Londres, utilizando hospedajes en pisos de corta estancia a través de Airbnb. Presentare una estructurar este viaje, con recomendaciones basadas en datos sobre los mejores barrios para hospedarse, los mejores precios y las atracciones clave de la ciudad.

Este enfoque no solo ofrece una experiencia de viaje personalizada, sino que también se basa en un análisis de datos efectivo para garantizar que el alojamiento y las actividades sean rentables y satisfactorias para los viajeros.
Utilice Power BI para crear una visualización interactiva que permita explorar la oferta de hospedaje en diferentes zonas de Londres, con datos de Airbnb y la cercanía a puntos clave, es una excelente forma de personalizar la planificación del viaje. Usando un mapa de geolocalización interactivo y aplicando filtros personalizados como segmento de precios, capacidad y barrio.

Para adquirir su reserva de alojamiento puede visitar el sitio web: [http://www.airbandb.com](http://www.airbandb.com)

 
### Origen de los Datos
 
Para este análisis, hemos utilizado datos recopilados directamente del sitio web del servicio AirBnB. Estos datos incluyen información sobre las propiedades populares, el tipo de alojamiento (habitaciones, casas),precios , ubicación, disponibilidad y otros detalles relevantes.

Se tomaron los datos de la del Conjunto de datos proporcionados por AirBnB de la ciudad de Londres [https://insideairbnb.com/london/](https://insideairbnb.com/london/)

## Paso 1: Recolectar y Preparar los Datos,adquiridos de la Base de Datos de propiedades de Airbnb.
Los datos deben incluidos: ID de propiedad, Dirección o coordenadas (latitud y longitud), Precio por noche, Capacidad máxima, tipo de ptopiedad habitaciones, Barrio o distrito (para filtrar) entre otros.

## Paso 2 :  Identificar Perfil del Viajero:
 Duración del viaje: 4 noches, Presupuesto: Medio 120,00€ -250,00€ p/noche (entre £100-£200 por noche para hospedaj * 1,20 Euro), Intereses: Cultura, Historia, Arte, Gastronomía. Preferencia de alojamiento: Piso o apartamento de corta estancia en barrios bien conectados y cercanos a puntos turísticos principales. Grupo de viajeros: Puede ser para una pareja, una familia pequeña o un grupo de amigos de hasta 4 Integrantes.

## Paso 3: Crear la Base de Datos en Power BI, 
Transforma los datos usando el Editor de Power Query para asegurar que la información esté limpia y estructurada correctamente. con coordenadas (latitud, longitud) como texto, separa columnas individuales de Latitud y Longitud.
Asegúrar de que las categorías de Precio, Capacidad, y Barrio estén correctamente clasificadas y sin valores nulos.
Crea relaciones entre tablas si es necesario y Visualización en Power BI mediante un Mapa de Geolocalización Interactivo.
### Visualización del informe de Power BI

Puedes ver el informe de Power BI en el siguiente enlace:

[Ver informe de Power BI](https://app.powerbi.com/links/TVGR9K-gni?ctid=8aebddb6-3418-43a1-a255-b964186ecc64&pbi_source=linkShare)

![Imagen de fondo](./Mapa_Londres.jpg)

### Segmento de Alojamiento:

Para un viaje de 4 noches en Londres, buscamos pisos en zonas clave de la ciudad con una buena mezcla de accesibilidad, seguridad y cercanía a los principales puntos turísticos. La elección del alojamiento se basa en datos como los costo de alojamiento de Airbnb, la proximidad a estaciones de transporte y la popularidad del barrio.

Zonas recomendadas:
Covent Garden:

Características: Barrio vibrante, lleno de teatros, restaurantes y boutiques. Ideal para turistas que buscan estar cerca de la vida cultural.
Precio promedio por noche: £150-£200
Tasa de ocupación: Alta, debido a su cercanía con el West End y otras atracciones.
Atractivos cercanos: Museo Británico, Teatro, restaurantes y bares.

Shoreditch:

Características: Barrio moderno y creativo, conocido por su arte callejero, galerías y vida nocturna.
Precio promedio por noche: £120-£160
Tasa de ocupación: Alta entre los jóvenes y viajeros que buscan una experiencia más bohemia.
Atractivos cercanos: Brick Lane, Spitalfields Market, tiendas vintage.

Notting Hill:

Características: Famoso por sus casas coloridas, mercados, y una atmósfera tranquila pero sofisticada.
Precio promedio por noche: £160-£180
Tasa de ocupación: Moderada a alta, especialmente en temporada alta.
Atractivos cercanos: Mercado de Portobello, tiendas exclusivas.

South Bank / Bankside:

Características: A orillas del río Támesis, con vistas impresionantes y cercanía a museos y teatros.
Precio promedio por noche: £130-£170
Tasa de ocupación: Alta por ser una zona muy turística y bien conectada.
Atractivos cercanos: Tate Modern, Shakespeare’s Globe, London Eye.

Kensington:

Características: Zona residencial y tranquila, ideal para quienes buscan una estancia cómoda y relajante.
Precio promedio por noche: £180-£220
Tasa de ocupación: Moderada a alta.
Atractivos cercanos: Museo de Historia Natural, Kensington Gardens, tiendas de lujo.

### Conclusión
 
Este análisis nos ha permitido entender mejor cómo funciona AirBnB y qué propiedades más populares se centran. Espero que disfrutes de nuestra información.
 
