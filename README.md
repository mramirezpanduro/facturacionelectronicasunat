# OpenInvoicePeru v1.0.0.0721 #
OpenInvoicePeru es un proyecto Open Source construido con C#, haciendo sencilla la Facturación Electrónica de SUNAT.
Permite la generacion de XML, empaquetado, envío y recepción de documentos electrónicos.

Actualmente se encuentra en versión Beta.

# Características #
- Generacion de XML para Facturas, Boletas, Notas de Crédito y Débito.
- Firmado del XML con un certificado digital elegido por el usuario.
- Envío al servicio Web de SUNAT de los documentos electrónicos (Boleta, Factura, NC, ND y Documento de Retención).
- Envío de Resumen Diario y Comunicación de Baja.
- Lectura del contenido del CDR de SUNAT.
- Consulta de Tickets de los Resúmenes y Bajas.
- API REST bajo ASP.NET Web API para la generacion del XML (Bajo construcción aun).

## Ramas (branches) ##

El proyecto contiene dos ramas:

- master (versión estable)
- beta (versión de desarrollo y pruebas)

## Consideraciones ##
El proyecto se ha desarrollado con VS2015 Update 3, pero usando como base el .NET Framework 4.5.
Se recomienda usar encarecidamente VS2015, la edición [Community Edition](https://www.visualstudio.com/downloads/download-visual-studio-vs), es gratis y mucho mejor que sus predecesores.

Si quieres colaborar con tu granito de arena puedes hacer un Fork.

Si tienes dudas escribeme a mi página de [Facebook](http://m.me/erickorlandoblog)

Y no te olvides de darte una vuelta por mi [Blog](http://erickorlando.com/2016/05/07/proyecto-opensource-facturacion-electronica-sunat/)

## Disclaimer ##

Este software se entrega como tal y eres libre de modificarlo a tu gusto, copiarlo en su totalidad 
o de manera parcial, lo unico que pido es que se respete la creación del autor.

Así mismo no hay garantía expresa de este producto, cualquier inconveniente que se presente con SUNAT 
es enteramente responsabilidad del usuario al usar este Software. 

Si tienes errores con SUNAT fijate en el código devuelto:

- Del 0100 al 1999 Excepciones (Usuarios mal escritos, RUCs no validos, etc.)
- Del 2000 al 3999 Errores que generan rechazo (Se envia pero rebota)
- Del 4000 en adelante Observaciones (Correcciones menores)

Si tienes mas dudas con SUNAT comunícate con ellos al +51 1 3150730.

## Asesoría personalizada ##

Si necesitas que te apoye con la Homologación (Emisor o Proveedor) puedes contactarme 
directamente a mi Skype (erick.orlando) y podemos concertar una reunión virtual.
