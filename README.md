## Archivo `README.md` y Checklist

👋 ¡Hola! soy Cristian Orihuela
💻 Estudiante de la Tecnicatura en Desarrollo de Software 

----------------------------------------------------------- 
-                         PFO1                            -
-----------------------------------------------------------

## 1. Descripción del Proyecto:
- El objetivo de esta práctica es que cada estudiante desarrolle una Landing Page de Portafolio Personal utilizando únicamente HTML y CSS. Esta landing page debe representar de forma profesional y creativa la identidad del estudiante, incluyendo información como su nombre, una breve biografía, habilidades, proyectos realizados, y medios de contacto.

- Esta actividad busca poner en práctica los conocimientos básicos adquiridos sobre maquetado web, organización de archivos, buenas prácticas en diseño y estructura de código, así como también fomentar el uso de herramientas de control de versiones (Git) y despliegue web (GitHub Pages).


📫 **Contacto:**

- 🌐 [Portfolio]: https://corihuela75.github.io/front/
- 🐙 [GitHub]: https://github.com/corihuela75/front
- 💼 [LinkedIn]: https://www.linkedin.com/in/cristian-orihuela
- 📧 ori@live.com.ar

---

## 2. Checklist de Requerimientos:

### Checklist - Práctica Formativa Obligatoria 1

#### Estructura del Proyecto:
- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

#### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] En el `README.md` se indica la URL de GitHub Pages.

#### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección `<head>` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] Redacta brevemente tu decisión: ¿Por qué elegiste esa fuente?
    - Respuesta: La fuente Montserrat es una de las tipografías más populares de Google Fonts, y esto no es casualidad. Fue diseñada para aportar una estética moderna, limpia y profesional, lo cual la convierte en una excelente elección para portafolios personales. 

#### HTML:
- [x] El documento inicia con la declaración `<!DOCTYPE html>` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

#### Secciones obligatorias en `main`:
- [x] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

#### CSS:
- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

#### Layout y Organización:
- [x] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.
- [x] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?
    - Respuesta: con Flexbox resulta mas facil alinear los elementos de una sola línea. y con Grid es
        mucho mejor el armado de las grillas donde se puede establecer la cantidad de columanas deseadas
        por ejemplo.

#### Estilización de Componentes:
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [x] Se ha implementado al menos una animación o transición (por ejemplo, efecto hover en tarjetas o botones).
- [x] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era adecuada para tu proyecto?
    - Respuesta: el hover cambiando levemente el tamaño de las imagenes de las series y en las tarjetas de los
        cursos considero que le aporta elegancia y sutileza al estilo del portafolio.

#### Consideraciones Adicionales:
- [ ] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos `alt` en las imágenes).
- [ ] Se añadieron comentarios adicionales donde se describan decisiones de diseño o la lógica de implementación.

----------------------------------------------------------- 
-                         PFO2                            -
-----------------------------------------------------------

## Punto 1 - Funcionalidades con JavaScript

1) Validaciones de formulario: en html se agregan a los campos del formulario los mensajes de error dentro
de etiquetas span ocultas, que se muestran interactivamente de acuerdo al script, que escucha cada vez que
se envia, y verifica que los campos esten completos. Además el código regex de validación del mmail revisa
que haya una @, que no haya un espacio u otra arroba a la izquierda ni a la derecha, luego espera que haya
un punto y a su derecha ni espacios ni arrobas. Se agrega el estilo css de error.
2) Pop-up de Confirmación de Envío: se agrega un modal en html y css oculto y de posicion fija ocupando toda
la pantalla para mostrar un el mensaje, con un efecto de opacidad del fondo y un boton para aceptar y cerrarse.
Luego en javascript una función para cambiar el estilo y mostrar el popup luego de validar los campos y otra
para ocultarlo despues de presionar el boton de aceptar.
3) Modo Oscuro/Claro: se agrega boton para cambiar de modo oscuro a modo claro, utilizando localStorage para
recordar la preferencia del usuario. Al cargar la página, se verifica el estado almacenado y se ajusta el tema
según el valor guardado. Al hacer clic en el enlace, se alterna entre los modos y se guarda la nueva preferencia
en localStorage para que persista en futuras visitas.
En lugar de modificar manualmente todos los estilos, se definen las variables para los colores principales
(como fondo, texto, enlaces, etc.) y luego se cambia el valor de estas variables según el modo seleccionado.
Esto se logra mediante la propiedad var(), lo que permite un cambio global del diseño con solo modificar el
valor de las variables, sin necesidad de cambiar cada regla CSS individualmente. 
4) Imagen de las credenciales:  Añadí un contenedor dentro de cada tarjeta, que contiene la etiqueta <img>
con la URL de la imagen del certificado, con un estilo css que no se muestra. Al hacer click, con javascript,
se alterna el estilo css permitiendo ver la imagen u ocultarla.