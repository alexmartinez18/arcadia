# Registro de cambios de Arcadia

Aquí se anota lo que cambia en cada versión. La versión más reciente va arriba.

## V1.0: 9 de noviembre de 2026

Primera versión estable.

### Colección
- Pantalla principal con tarjetas de consolas y botón **+** para añadir.
- Cada consola incluye por defecto las tarjetas **Juegos** y **Accesorios**.
- Formulario de juegos y accesorios: nombre, precio de compra, idioma, ¿está completo? (si no, ¿tiene caja? y ¿tiene manual?) y foto de portada.
- Editar y eliminar consolas, juegos y accesorios, incluida la foto.

### Imágenes
- Al crear una consola se detecta su nombre y se pone automáticamente su foto (19 consolas incluidas en la carpeta `consolas`).
- Si no se reconoce, se usa una insignia de color o se puede subir una foto a mano.

### Cuenta y datos
- Inicio de sesión con correo y contraseña (Firebase) para acceder desde cualquier dispositivo.
- Datos guardados en Firestore, separados por usuario.
- Exportar e importar copia de seguridad (archivo .json).

### Navegación
- Búsqueda rápida (lupa) en toda la colección: consolas, juegos y accesorios.
- Gestos para ir atrás (gesto de Android y deslizar a la derecha), manteniendo el botón **←**.

### App
- Instalable en Android como APK mediante PWABuilder, con icono propio.

---

## Plantilla para las próximas versiones

Copia este bloque encima de la versión anterior y rellénalo.

```
## V1.1: fecha

### Añadido
- ...

### Cambiado
- ...

### Corregido
- ...
```
