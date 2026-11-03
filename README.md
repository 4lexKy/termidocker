
# termidocker - usa los comandos de docker directamente

Los comandos de docker son mayormente distintos a los de bash, por lo que al ejecutar este programa se podrá llamar a los comandos sin usar "docker" antes del comando.

## Estado del proyecto

Actualmente funciona.
La entrada necesita mejorarse ya que no contempla el autocompletado con tabulador o el historial de comandos con las flechas arriba y abajo.

## Instalación

No requiere instalación, es un script de bash.

## Uso

1. Ejecuta ./termidocker
2. Elije modo; acepta comandos bash (x) , o solo comandos de docker (h)
3. Escribe comandos de forma normal

### Ejemplo de uso

./termidocker

    Escribe 'x' para modo exclusivo (solo docker)
    Escribe 'h' para modo hibrido (docker+terminal)
    Pulsa enter (vacío == 'h'): h

    Escribe "exit" para salir...

>echo "ejemplo bash"
^BASH> echo "ejemplo bash"
"ejemplo bash"
>info
^DOCKER> sudo docker info
Password:
Client: Docker Engine - Community
 Version:    29.8.0
 Context:    default

## Licencia
Este proyecto está licenciado bajo GPLv2 - consulta el archivo LICENSE para más detalles.

## Autor
    [Alex](github.com/4lexKy)
