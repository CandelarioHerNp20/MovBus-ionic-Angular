# MovBus-ionic-Angular
Proyecto escolar para el rastreo de un dispositivo "ESP32-Wrover"

# Dependencias

* Ionic 6 
```
npm install @ionic/cli
```
* Angular 12 
```
npm install @anglular/cli@12
```
* Typescript
* Firebase 
Requiere un proyecto

* Angularfire2
```
npm install @angular/fire firebase --save
```

* Mapbox
```
npm install mapbox-gl @mapbox/mapbox-gl-geocoder ngx-socket-io
```

* Modulo ESP32

## Preparacion de aplicación
```
ionic start
```
Elegir "Angular" 
Elegir la plantilla blank

para desarrollo, despues el nombre de la aplicación "MyApp".

Colocarse en la carpeta de la aplicacion "cd MyApp"

Instalar Angularfire2 
```
npm install @angular/fire firebase --save
```
Instalar Mapbox 
```
npm install mapbox-gl @mapbox/mapbox-gl-geocoder ngx-socket-io
```
Crear los componentes

>>Generar paginas
>>>Menu
```
ionic generate page menu
```
>>>Mapas
```
ionic generate page Mapas
```
>>> Registro
```
ionic generate page registro
```
>>> Logeo
```
ionic generate page login
```
### Generar comonentes
>>> Mapa, panel, lista, editar
```
ionic generate component /components/mapa
```
```
ionic generate component /components/panel
```
```
ionic generate component /components/lista
```
```
ionic generate component /components/editar
```
