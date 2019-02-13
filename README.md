# Documentación para el uso de este repositorio
Este repositorio es una modificación y simplificación del Framework Front-end de Google "Web Starter Kit" en su versión 0.5.2 (beta).

#### Requisitos su funcionamiento montar
- Node.js
- NPM
- Gulp
- Node Modules

#### ¿Que incluye?

Este repositorio incluye un archivo HTML5 simple, además
- Archivos Básicos del Framework SASS v3.4.12 (http://www.sass-lang.com)
- FontAwesome v4.0 (http://fortawesome.github.io)
- Modernizr v2.8.3 (http://modernizr.com)
- jQuery v1.11.1 (http://jquery.com)
- jQuery Placeholder (https://github.com/mathiasbynens/jquery-placeholder)

#### Clases utiles ya definidas
Estas son algunas de las clases que puedes usar, que ya estan definidas en el proyecto
##### Utils.scss
Archivo de Variables y de utilidad general
- Variables de colores, fuentes, tamaños
- Mixins para desarrollo responsive (solo celulares y desktop)

##### Normalize.scss
Archivo que normaliza las clases distintos navegadores
- .nocallout : Deshabilita la funcion determinada cuando das tap o mantienes el touch en mobile
- .ir : Mejora el rendimiento de PNGS
- .hidden : desaparece objetos
- .visuallyhidden : Oculta el objeto (pero ocupa espacio)
- .invisible : Vuelve el objeto invsibile
- .clearfix : Repara el espacio de loss float

##### Fonts.scss
Archivo con las fuentes por defecto del documento
##### Font-awesome.scss
Llamado a los iconos de FontAwesome, lista y uso de iconos en http://fortawesome.github.io/Font-Awesome/icons/
##### Gridle.scss
Sistema de Grillas CSS avanzado compatible con SASS.
Documentación en: http://gridle.org/documentation/1.3.3
##### Objects.scss
Archivo de clases estaticas para las propiedades de los objetos del sitio; botones, inputs, textareas, etc.
##### Mobile.css
Archivo para realizar las modificaciones en caso del mediaquery para mobiles
- .hide-on-mobile :  Oculta el objeto en caso de estar desde mobiles

##### Global.scss 
Archivo de trabajo general para la construccion del sitio.


#### Términos de uso
https://developers.google.com/site-terms


#### Licencia de este repositorio
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License or any later version.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
