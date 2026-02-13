TÍTULO

FORMULARIO LOGIN

Email
Password
Botón enviar


Objetivo del dia de hoy para esta pagina web 13/2/2025

<!----asi se hace un comentario --

Para agregar imagenes usamos <img src="ruta de la imagen" alt="texto alternativo">
tambien width y height para controlar el tamaño de la imagen


<p class="nota-editor"> Mi gato es gordo</p>
 se usa para identificar un elemento, y se llama con #nombre-del-id
 class y id son atributos globales, se pueden usar en cualquier etiqueta,
 pero el id solo se puede usar una vez por pagina,
  mientras que class se puede usar varias veces.
  mis anotaciones

  ----

  ANATOMIA DE UN DOCUMENTO HTML

  <!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8" />
    <title>Mi página de prueba</title>
  </head>
  <body>
    <p>Esta es mi página</p>
  </body>
</html>

 espacios en blanco no altera su salida

<p id="noWhitespace">Los perros son tontos.</p>

<p id="whitespace">Los perros
    son
        tontos.</p>

    para agregar iconos a nuestra pagina web usamos Y en <head>

    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />

    logo de un restaurante aleatorio de internet, solo uso educativo !!

    para aniadir archivos css dentro del <head>

    <script src = "script.js" hola > </script> 
    para js en el head tambien y agregamos defer q se encarga de la comuniacion con html

    para texto con tamanio personalizado
    <span style="font-size: 32px; margin: 21px 0;"
            >¿Es este un titular de primer rango?</span>

    se usa para pasar elementos a una lista NO ordenada <ul>
            <li>elemento1</li>
            <li>elemento2</li>
            </ul>

    
    se usa para pasar elementos a una lista ordenada <ol>
            <li>elemento1</li>
            <li>elemento2</li>
           </ol>
        para las listas anidadas entre ellas se pueden mezclar (enumeradas y ordenadas)ejm
        1.
            * Contenido sub 1
        2. 
            * Contenido sub 2
        3.
            * Contenido sub 3

        LETRAS CONTENIDO

        letras de lado usamos <em> dentro de <p>
        negrita samos <strong>
        <b> letras tradicionales
        <i> cursiva o italic
        <u> subrayado

        <p> href = "" </p> PARA href links 
        ejemplo para agregar links a imagenes
        <a href="https://www.mozilla.org/es-ES/">
            <img
                src="mozilla-image.png"
                alt="Logotipo de Mozilla que dirige a la página inicial de Mozilla" />
        </a>
        tambien podemos usarla para redirigir a archivos o imagenes  o otras paginas y
        subpaginas

        ejemplo
        <p>
            ¿Quieres mandarnos una carta? Aquí tienes nuestra
            <a href="contacts.html#Dirección_de_envío">Dirección de envío</a>.
        </p>


        mailto;
        se usa en conjunto con href para hacer accesos directos a correos electronicos 

        <dl> se usa para listar descropciones dentro de los <dt>
        <dd> se usa tipo como descripcion  ejemplo para ver el funcionamiento de <dl><dt><dd>

        <dl>
            <dt>soliloquio</dt>
                <dd>
                    En las obras dramáticas, corresponde a cuando un personaje se habla a sí
                    mismo para representar sus pensamientos o sentimientos internos y, en el
                    proceso, transmitirlos a la audiencia (pero no a otros personajes).
                </dd>
            <dt>monólogo</dt>
                <dd>
                    En las obras dramáticas, corresponde a cuando un personaje habla de sus
                    pensamientos en voz alta para compartirlos con el público y cualquier otro
                    personaje presente.
                </dd>
            <dt>aparte</dt>
                <dd>
                    En las obras dramáticas, corresponde a cuando un personaje comparte un
                    comentario solo con la audiencia para dar efecto cómico o dramático. Suele
                    ser un sentimiento, un pensamiento o información adicional.
                </dd>
        </dl>

        <blockquote> En cortas palabras hace como un tab de el teclado, una sangria
    
        <sup> elevado a,  <sub> potencias hacia abajo como elemento quimico c8 h10 o2

        Glosario .

            <code>: Para marcar fragmentos genéricos de código informático.
            <pre>: Para respetar los espacios en blanco (en general, en los bloques de código) — si utilizas la sangría o diversos espacios en blanco consecutivos dentro de un texto, los navegadores los ignorarán y no se mostrarán en la página. Sin embargo, si delimitas el texto con las etiquetas <pre></pre>, los espacios en blanco se representarán de forma idéntica a como se ven en tu editor de texto.
            <var>: Para marcar específicamente nombres de variables.
            <kbd>: Para marcar entradas de teclado (y de otro tipo) en el ordenador.
            <samp>: Para marcar la salida de un programa de ordenador.

        <time> para fechas

        <time datetime="2016-01-20">20 Enero 2016</time>

        placeholder sirve para poner texto dentro de un input de textp
        


-->
