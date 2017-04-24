# flarum-ext-spanish
Spanish language pack for Flarum.

# Paquete de idioma Español para Flarum (es)

Como no existía una versión del paquete de idioma para la versión 0.1.0-beta6, he decidido crearlo. Si encontrais algún error o quereis proponer algún cambio notificarlo y lo arreglaré cuanto antes.

## Instalación con Composer:

Flarum usa composer para gestionar sus dependencias y extensiones, por lo que es el sistema de instalación recomendado. El paquete de idioma Epañol está disponible en Packagist. Para instalarlo sólo necesitamos Composer instalado y después ejecutar el comando:

`composer require zeokat/flarum-ext-spanish`

Este mismo comando se puede emplear para actualizar de forma independiente el paquete de idioma Español.

He decidido mantener el archivo `validation.yml` en inglés ya que contiene los mensajes de error. Si en algún momento nos encontramos con un mensaje de error, siempre es más sencillo encontrar una solución en Google buscando el mensaje de error original, por este motivo voy a mantener este archivo en su idioma original.

De todas formas facilito una versión del archivo [validation.yml en español](https://gist.github.com/Zeokat/e2465a8ef131f8bc49f041d0583b87fb), que no está incluido en el paquete de traducción. Os la facilito por si alguien quiere crearse su paquete de idioma personalizado con los mensajes de validación y de error, traducidos al español.


# Flarum Spanish language pack (es)

https://discuss.flarum.org

Complete; Flarum version 0.1.0-beta6. Spanish (Spain). Español (España), ES

## Installation using Composer (recommended):

Flarum use Composer to manage its dependencies and extensions. The Spanish language pack is available on Packagist and can be managed that way. Make sure that Composer is installed on your machine, then run the following command in the location where Flarum is installed:

`composer require zeokat/flarum-ext-spanish`

The same command can be used to update independently the Spanish language pack, without updating anything else. Note that because the Spanish language pack will be added as a Flarum's dependency, it will also be automatically updated when updating Flarum and its dependencies via Composer.
