<PFO1> 
# Práctica Formativa Obligatoria 1 - Individual

## Landing Page de Portafolio Personal (HTML y CSS)

### Fechas Importantes:
- **Lanzamiento:** 26 de marzo
- **Entrega Final:** 14 de abril

### Formato de entrega:
Deberán publicar en el foro 2 links:
1. Link al repositorio, donde el docente revisará la carpeta de archivos y el `README.md`.
2. Link a la web publicada en GitHub Pages.

---

## Requerimientos Generales

### 1. Estructura del Proyecto:
- Archivo `index.html` ubicado en la raíz del proyecto.
- Carpeta `css` que contenga el archivo `styles.css`.
- (Opcional) Carpeta `img` para los recursos gráficos.
- Archivo `README.md` que contenga:
    - Una breve descripción indicando que se trata de un Trabajo Práctico (TP).
    - Un checklist (ver detalle más adelante).

### 2. Repositorio y Publicación:
- Crear un repositorio en GitHub y subir el proyecto.
- Publicar el proyecto utilizando GitHub Pages.

### 3. Privacidad:
- No es obligatorio publicar tu nombre completo ni utilizar una foto de perfil con tu rostro. Puedes usar avatares, imágenes generadas con IA o fotos de tus mascotas.

### 4. Uso Obligatorio de Google Fonts:
- Incorporar una fuente de Google Fonts en tu documento HTML.

---

## Requerimientos HTML

### 1. Declaración y Metaetiquetas:
- El documento debe iniciar con la declaración `<!DOCTYPE html>`.
- Usar el atributo de idioma: `<html lang="es">`.
- En la sección `<head>` incluir:
    - Metaetiqueta de charset: `<meta charset="UTF-8">`.
    - Metaetiqueta de viewport: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
    - Un título descriptivo (por ejemplo, "Mi Portafolio Personal").
    - Un vínculo al archivo CSS ubicado en `css/styles.css`.
    - El enlace a Google Fonts.

### 2. Estructura Semántica Obligatoria:
El documento HTML debe incluir las siguientes secciones en orden:
1. **Encabezado (Header):**
     - Contiene el título principal o el logo del sitio.
2. **Navegación (Nav):**
     - Barra de navegación con al menos tres enlaces (por ejemplo, "Sobre mí", "Proyectos" y "Contacto").
3. **Sección Principal (Main):**
     - **Presentación Personal (`id="sobre-mi"`):**
         - Párrafo describiendo quién eres, tus intereses y tu misión como desarrollador.
         - Imagen con atributo `alt`.
     - **Tarjetas o Columnas (`id="tarjetas"`):**
         - Al menos dos tarjetas con imagen y texto.
         - Organización en columnas usando Flexbox o Grid.
     - **Listado de Habilidades (`id="habilidades"`):**
         - Listado o tabla con tecnologías dominadas, tecnologías a aprender y/o hobbies.
     - **Formulario de Contacto (`id="contacto"`):**
         - Campos: Nombre, Apellido, Email y Teléfono.
         - Botón de submit.
     - **Películas Favoritas (`id="peliculas"`):**
         - Tres películas con título, imagen y breve descripción.
4. **Pie de Página (Footer):**
     - Información adicional como enlaces a redes sociales.

### 3. Comentarios en el Código:
- Insertar al menos cuatro comentarios explicativos en el HTML.

---

## Requerimientos CSS

### 1. Selectores y Personalización:
- Usar selectores basados en clases e identificadores.
- Definir una tipografía importada desde Google Fonts.

### 2. Layout y Organización:
- Organizar elementos con Flexbox o Grid.
- Diseño responsivo usando unidades relativas como `%`, `rem` o `vh`.

### 3. Estilización de Componentes:
- Personalizar tablas, botones, enlaces y formularios.
- Ajustar dimensiones de imágenes y contenedores.

### 4. Animaciones y Transiciones:
- Incluir al menos una animación o transición (por ejemplo, efecto hover).

---

## Archivo `README.md` y Checklist

### 1. Descripción del Proyecto:
- Breve párrafo indicando de qué se trata el Trabajo Práctico.

### 2. Checklist de Requerimientos:

### Checklist - Práctica Formativa Obligatoria 1

#### Estructura del Proyecto:
- [ ] Archivo `index.html` ubicado en la raíz.
- [ ] Carpeta `css` que contenga el archivo `styles.css`.
- [ ] (Opcional) Carpeta `img` para recursos gráficos.
- [ ] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

#### Repositorio y Publicación:
- [ ] Repositorio en GitHub creado.
- [ ] Proyecto subido al repositorio.
- [ ] Proyecto publicado utilizando GitHub Pages.
- [ ] En el `README.md` se indica la URL de GitHub Pages.

#### Uso de Google Fonts:
- [ ] Enlace a Google Fonts incluido en la sección `<head>` del HTML.
- [ ] La tipografía importada se aplica en el sitio.
- [ ] Redacta brevemente tu decisión: ¿Por qué elegiste esa fuente?
    - Respuesta: __________________________________________________________

#### HTML:
- [ ] El documento inicia con la declaración `<!DOCTYPE html>` y usa el atributo `lang="es"`.
- [ ] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [ ] Se ha definido un título descriptivo.
- [ ] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

#### Secciones obligatorias en `main`:
- [ ] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces.
- [ ] Se han insertado al menos 4 comentarios explicativos en el código HTML.

#### CSS:
- [ ] Existe el archivo `styles.css` con estilos personalizados.
- [ ] Se utilizan selectores basados en clases e identificadores.
- [ ] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

#### Layout y Organización:
- [ ] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.
- [ ] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?
    - Respuesta: ________________________________________________________

#### Estilización de Componentes:
- [ ] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [ ] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [ ] Se ha implementado al menos una animación o transición (por ejemplo, efecto hover en tarjetas o botones).
- [ ] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era adecuada para tu proyecto?
    - Respuesta: ________________________________________________________

#### Consideraciones Adicionales:
- [ ] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [ ] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos `alt` en las imágenes).
- [ ] Se añadieron comentarios adicionales donde se describan decisiones de diseño o la lógica de implementación.

---

## Resumen de Puntos a Cumplir

### HTML Obligatorio:
- Declaración `<!DOCTYPE html>` y uso de `<html lang="es">`.
- Inclusión en `<head>` de metaetiquetas (charset y viewport), título descriptivo, enlace al archivo CSS y a Google Fonts.
- Secciones obligatorias en `<main>`:
    1. Presentación Personal (`id="sobre-mi"`)
    2. Tarjetas/Columnas (`id="tarjetas"`)
    3. Listado de Habilidades (`id="habilidades"`)
    4. Formulario de Contacto (`id="contacto"`)
    5. Películas Favoritas (`id="peliculas"`)
- Barra de navegación con al menos 3 enlaces.
- Al menos 4 comentarios explicativos distribuidos en el HTML.

### CSS Obligatorio:
- Archivo `styles.css` con estilos personalizados.
- Utilización de selectores por clases e IDs y aplicación de la tipografía de Google Fonts.
- Organización del layout con Flexbox o Grid en la sección de tarjetas/columnas.
- Personalización de tablas, botones, enlaces y formularios.
- Uso de unidades relativas (`%`, `rem`, `vh`) para lograr responsividad.
- Al menos una animación o transición implementada.

### Repositorio y Publicación:
- Repositorio en GitHub creado, proyecto subido y publicado mediante GitHub Pages.
- Archivo `README.md` incluido, conteniendo la descripción del proyecto y el checklist de requerimientos.