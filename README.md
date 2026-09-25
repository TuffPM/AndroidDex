# Android Dex

Esqueleto inicial de un entorno de escritorio para Android.

## Objetivo

Convertir la experiencia del teléfono en una interfaz tipo PC, sin root y sin depender de una PC para usar el APK.

## Incluido en v1.0.0

- Escritorio
- Barra de tareas
- Menú Inicio
- Ventanas flotantes
- Arrastrar ventanas
- Files (base)
- Browser (base)
- Settings (base)
- Applications (base)
- Reloj
- Compatibilidad inicial con teclado/mouse mediante los eventos normales de Android

## Próximas capas

1. Explorador de archivos real con Storage Access Framework.
2. WebView real.
3. Gestor de aplicaciones.
4. Menú contextual y clic derecho.
5. Soporte avanzado de teclado/mouse.
6. Notificaciones.
7. Panel rápido.
8. Temas.
9. Fondo de pantalla.
10. Multiventana y maximizar/minimizar.
11. Atajos de teclado.
12. Modo monitor externo.
13. Persistencia de configuración.
14. Launcher/escritorio configurable.
15. Optimización para teléfonos y tablets.

## Construcción

Abrir el proyecto en Android Studio y sincronizar Gradle. Después:

`./gradlew assembleDebug`

El APK de depuración aparecerá en:

`app/build/outputs/apk/debug/app-debug.apk`
