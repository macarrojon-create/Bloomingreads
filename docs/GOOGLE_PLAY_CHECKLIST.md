# READBLOOM — checklist para Google Play

## Antes de una primera publicación

- [ ] Crear una cuenta de desarrollador de Google Play y completar la verificación solicitada.
- [ ] Elegir y comprobar un `applicationId` definitivo. El proyecto usa `com.readbloom.readingjournal` como identificador inicial.
- [ ] Configurar firma de release y guardar el keystore fuera del repositorio. Nunca subir el keystore, contraseñas ni secretos a GitHub.
- [ ] Generar un Android App Bundle (`.aab`) para Play en lugar de distribuir solamente un APK.
- [ ] Revisar el `version` y `versionCode` antes de cada publicación.
- [ ] Preparar icono, nombre, descripción, capturas y gráficos de la ficha.
- [ ] Añadir una política de privacidad real y pública.
- [ ] Completar en Play Console las declaraciones de datos, contenido, público objetivo y clasificación que correspondan.
- [ ] Revisar todos los permisos y dependencias antes de producción.
- [ ] Probar una build de release en varios tamaños de pantalla y Android recientes.
- [ ] Activar una pista de prueba interna antes de producción.

## Importante

La aplicación puede compilarse sin firma de producción desde GitHub Actions, pero **eso no significa que esté lista para publicar**. La firma, la ficha de Play Console, la política de privacidad, las declaraciones de datos y las pruebas de release deben completarse antes de subirla a producción.
