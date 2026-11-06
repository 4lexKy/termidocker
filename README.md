[Versión 0.6.2]: #
# termidocker - Usa los comandos de docker directamente en la terminal

Los comandos de docker son mayormente distintos a los de bash, por lo que al ejecutar este programa se podrá llamar a los comandos sin usar "docker" antes del comando.

---
## Estado del proyecto

Actualmente funciona.

La entrada necesita mejorarse ya que no contempla el autocompletado con tabulador o el historial de comandos con las flechas arriba y abajo.

---
## Instalación
No requiere instalación
### Lenguaje
- Bash
### Dependencias
- No tiene dependencias
### Sistemas operativos compatibles
Probado en:
- Debian

---
## Uso

1. Ejecuta ./termidocker
2. Elije modo; acepta comandos bash (x) , o solo comandos de docker (h)
3. Escribe comandos de forma normal

### Ejemplo de uso
```bash
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
```

---
## Recomendación
Para un uso mas ágil se puede crear una carpeta para script de forma que todos los que se añadan se puedan llamar desde la propia terminal como cualquier otro comando.

Esto se puede conseguir añadiendo a ~/.bashrc la línea:

>export PATH=$PATH:/ruta/a/carpeta/con/scripts

---
## Licencia
Este proyecto está licenciado bajo GPLv2 - consulta el archivo LICENSE para más detalles.

---
## Autor
    [Alex](github.com/4lexKy)
---
