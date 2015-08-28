# #OpenGeoCórdoba. Geodatos abiertos de Córdoba (España)

##¿Qué es #OpenGeoCórdoba?
...
## ¿Cómo añadir datos a #OpenGeoCórdoba?
...
## Formatos
- **GeoJSON**
- **CSV**
...

## Sistemas de Referencia de Coordenadas

- WGS84
- ETRS89
- ETRS89 UTM30N
- ED50
- ED50 UTM30N
- 
## Descripción de las capas

Para una mejor comprensión de los datos y un correcto uso, capa capa deberá ir acompañada de un archivo en formato md o txt con sus descripción. El archivo se llamará igual que la capa pero con el sufijo "_metadatos" (ej. "da02_term_munic_metadatos.md").

Ejemplo de metadatos
```
da02_term_munic.geojson

Nombre:Término municipal de Córdoba
Descripción: Término municipal de córdoba obtenidode la capa de municipios de Andalucía del DERA
Geometría: Polígono
Sistema de referencia: WGS84 (EPSG:4326)
Origen de datos: Datos Espaciales de Referencia de Andalucía (DERA) Junta de Andalucia
Más información: http://www.juntadeandalucia.es/institutodeestadisticaycartografia/DERA/g17.htm
Campos
	- COD_MUN: Texto
	- MUNICIPIO: Texto
	- PROVINCIA: Texto
	- COD_ENT: Texto
```
