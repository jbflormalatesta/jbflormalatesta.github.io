# La colección · Jardín Botánico Municipal «Florencio Malatesta»

Ficha de cada especie señalizada del Jardín (Espacio Quinta Devoto, Marcos Paz). Los QR de las
etiquetas (D1) y de las fichas A5 (D2) llevan acá, por ejemplo:
`https://jbflormalatesta.github.io/?A-71`.

> **No cambies el nombre de la cuenta ni el de este repositorio.** Las 312 piezas impresas
> apuntan a esta dirección: si cambia, los QR dejan de funcionar.

## Publicarlo (se hace una sola vez)

1. Crear la cuenta en <https://github.com/signup> con el mail del Jardín y el nombre de usuario
   **jbflormalatesta**. Confirmar el mail.
2. Botón **+** (arriba a la derecha) → **New repository**. Nombre exacto:
   **jbflormalatesta.github.io**. Dejarlo en **Public** y tocar **Create repository**.
3. En el repositorio vacío, tocar **uploading an existing file**. Descomprimir el ZIP en la
   computadora, abrir la carpeta, seleccionar todo lo que tiene adentro (`index.html`,
   `especies.js`, `404.html`, `README.md` y las carpetas `img` y `fotos`) y arrastrarlo a la
   página. Esperar a que suba todo y tocar **Commit changes**.
4. **Settings** → **Pages**. En *Build and deployment*, *Source*: **Deploy from a branch**;
   *Branch*: **main** y **/ (root)** → **Save**.
5. Esperar entre 1 y 10 minutos y abrir <https://jbflormalatesta.github.io/?A-71>. Si aparece el
   Tala, está funcionando. Probar también escaneando un QR del PDF con el celular.

Si GitHub pide activar la verificación en dos pasos, hacerlo con una app de códigos (por ejemplo
Google Authenticator) en un celular del Jardín, y guardar los códigos de recuperación junto con la
contraseña.

## Corregir un texto

1. Abrir `especies.js` y tocar el lápiz (**Edit this file**).
2. Buscar el código con Ctrl+F (por ejemplo `"A-71"`) y cambiar el texto entre comillas.
3. **Commit changes**. En unos minutos se ve en el sitio.

## Subir fotos de las cuatro estaciones

- Nombre exacto, en minúsculas salvo la letra del código: `A-71-primavera.jpg`,
  `A-71-verano.jpg`, `A-71-otono.jpg` (sin tilde) y `A-71-invierno.jpg`.
- Formato .jpg, con el lado mayor de unos 1200 píxeles (las fotos del celular pesan mucho:
  achicarlas antes, por ejemplo en <https://squoosh.app>).
- Entrar a la carpeta `fotos` → **Add file** → **Upload files** → arrastrar las fotos →
  **Commit changes**. Se pueden subir hasta 100 archivos por vez.
- Aparecen solas en la ficha de esa especie: no hace falta tocar ningún otro archivo.

## Opciones (al principio de `especies.js`)

- `qrFichas: "ficha"`: el QR de las fichas A5 abre la página de la especie. Con `"linktree"`,
  lleva al Linktree del Jardín. Se cambia sin tocar los PDF.
- `oculta: true`: la ficha no aparece en el listado y su página dice «Ficha en revisión».
  Hoy está así H-07 (amapola), en espera por la ley 21.671.
- `ubicacion: "reservada"`: no se publica dónde está la planta. Hoy: H-57 y H-58, orquídeas
  nativas sensibles a la recolección.

## Qué hay en cada archivo

- `index.html`: la página (diseño y funcionamiento). No hace falta tocarlo.
- `especies.js`: los textos de las 156 fichas y las opciones.
- `404.html`: si alguien escribe `…github.io/A-71` sin el signo `?`, lo lleva igual a la ficha.
- `img/`: logo, íconos e imagen para cuando se comparte el enlace.
- `fotos/`: las fotos de las cuatro estaciones.
