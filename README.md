# READBLOOM — Android + Windows

Versión V6 visual, intuitiva y muy personalizable, preparada para compilar desde GitHub Actions.

## Funciones

- Biblioteca: TBR, DNF, Leyendo y Finalizado.
- Búsqueda por título, autor, género y etiquetas.
- Filtro de favoritos y orden por recientes, título, valoración o páginas.
- Cuatro vistas: cuadrícula, compacta, lista y estantería.
- Ficha de libro con portada, ISBN, páginas, formato, autor/a, géneros, etiquetas, fechas, DNF, estrellas, Spice, emociones y reseña.
- Progreso página a página y acción rápida de volver a leer.
- Favoritos.
- Registro de sesiones con fecha, páginas y nota.
- Botón rápido para registrar una sesión del libro que estás leyendo.
- Estadísticas ampliadas: libros, páginas, media, sesiones, racha, terminados del mes, géneros, formatos y calendario de actividad.
- Calendario visual con líneas, halos, doodles y estilos alternativos.
- Retos lectores: anual, mensual o periodo personalizado, por libros, páginas o días de lectura.
- Wrapped: cinco plantillas, tres formatos, patrones, alineación, intensidad de decoración, portadas y métricas configurables.
- Bookish: cinco escenas, cuatro estanterías, portadas/lomos/mezcla, tres formatos, escala y decoración configurables.
- Personalización global: 12 paletas, 8 estilos, 7 ambientes, fondos, tarjetas, densidad, tipografías, forma de portadas, navegación, redondeado, escala de títulos, sombras, doodles, animaciones y modo oscuro.
- Presets completos para cambiar de estética en un toque.
- Copia de seguridad y restauración de libros, retos y personalización.
- Importación CSV con títulos, autores, páginas, géneros, etiquetas y progreso cuando están disponibles.
- Compilación Android y Windows desde GitHub Actions.

## Uso

1. Sube todo el proyecto a tu repositorio de GitHub.
2. Ve a **Actions**.
3. Abre **Build READBLOOM**.
4. Pulsa **Run workflow**.
5. Elige `android`, `windows` o `both`.
6. Descarga el artefacto generado.

No necesitas instalar Flutter ni Android Studio para compilar mediante GitHub Actions.


El nombre visible de la aplicación es **READBLOOM** y usa el logo proporcionado. El identificador técnico del paquete se mantiene para facilitar la actualización de instalaciones anteriores.

## Preparación para Google Play

Esta versión deja la aplicación orientada a una futura publicación: nombre READBLOOM, icono de marca, versionado y un identificador Android separado del nombre visible. Antes de publicar habrá que configurar una clave de firma de release, completar la ficha de Play Console, política de privacidad y revisar permisos/datos recopilados. El identificador configurado por el workflow es `com.readbloom.readingjournal`; si quieres otro, cámbialo antes de publicar.

Consulta `docs/GOOGLE_PLAY_CHECKLIST.md` para el proceso.
