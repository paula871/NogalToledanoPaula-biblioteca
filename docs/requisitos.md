# Requisitos del sistema de préstamos de biblioteca

## Requisitos funcionales
- RF1: El sistema registrará libros (ISBN, título, autor, disponibilidad).
- RF2: El sistema registrará socios (id, nombre, email).
- RF3: Un socio podrá tomar prestado un libro disponible.
- RF4: Un socio podrá tener como máximo 3 préstamos activos.
- RF5: El socio podrá devolver un libro prestado, que volverá a estar disponible.

## Requisitos no funcionales
- RNF1: Desarrollado en Java 17 o superior.
- RNF2: Las credenciales se guardarán en `config/secretos.properties`, que no se sube al repositorio.
