# Conteo

Contador de calorías según el plan alimentario: muestra en grande lo consumido en el día, el objetivo del plan (1.770 kcal por defecto) y calcula cuántos gramos comer de cada alimento para completar cada comida.

## Instalar

Cada push a `main` compila la APK con GitHub Actions y la publica en **Releases**. Desde el celular: Releases → última versión → `Conteo.apk`.

## Estructura

- `app/src/main/assets/index.html`: la app (HTML + JS). Los datos se guardan en el teléfono.
- `app/src/main/java/.../MainActivity.java`: contenedor WebView.
- `app/conteo.jks`: llave de firma fija, para que cada versión nueva se instale como actualización sin perder los datos.
