[![](captura.png)](captura.png "Captura de Pantalla")

# Bootstrap 5 | Button Styles


📒 Estilos de botones

    📝Bootstrap 5 proporciona diferentes estilos de botones:

    <button type="button" class="btn">Basic</button>
    <button type="button" class="btn btn-primary">Primary</button>
    <button type="button" class="btn btn-secondary">Secondary</button>
    <button type="button" class="btn btn-success">Success</button>
    <button type="button" class="btn btn-info">Info</button>
    <button type="button" class="btn btn-warning">Warning</button>
    <button type="button" class="btn btn-danger">Danger</button>
    <button type="button" class="btn btn-dark">Dark</button>
    <button type="button" class="btn btn-light">Light</button>
    <button type="button" class="btn btn-link">Link</button>

    📝Las clases de botón se pueden usar en elementos <a>, <button> o <input>:

    <a href="#" class="btn btn-success">Link Button</a>
    <button type="button" class="btn btn-success">Button</button>
    <input type="button" class="btn btn-success" value="Input Button">
    <input type="submit" class="btn btn-success" value="Submit Button">
    <input type="reset" class="btn btn-success" value="Reset Button">

    ¿Por qué ponemos un # en el atributo href del enlace?

    Como no tenemos ninguna página a la que enlazarlo y no queremos recibir un mensaje "404", ponemos # como enlace. En la vida real, por supuesto, debería ser una URL real a la página "Buscar".

📒 Contorno del botón

    📝Bootstrap 5 también proporciona ocho botones de contorno/borde.

    📝Mueva el mouse sobre ellos para ver un efecto de "desplazamiento" adicional:

    <button type="button" class="btn btn-outline-primary">Primario</button>
    <button type="button" class="btn btn-outline-secondary">Secundario</button>
    <button type="button" class="btn btn-outline-success">Éxito</button>
    <button type="button" class="btn btn-outline-info">Información</button>
    <button type="button" class="btn btn-outline-warning">Advertencia</button>
    <button type="button" class="btn btn-outline-danger">Peligro</button>
    <button type="button" class="btn btn-outline-dark">Oscuro</button>
    <button type="button" class="btn btn-outline-light text-dark">Claro</button>

📒 Tamaños de botones

    📝Use la clase .btn-lg para botones grandes o la clase .btn-sm para botones pequeños:

    button type="button" class="btn btn-primary btn-lg">Grande</button>
    <button type="button" class="btn btn-primary">Defecto</button>
    <button type="button" class="btn btn-primary btn-sm">Pequeño</button>

📒 Botones de nivel de bloque

    📝Para crear un botón de nivel de bloque que abarque todo el ancho del elemento principal, use la clase "auxiliar" .d-grid en el elemento principal:

    <div class="d-grid">
        <button type="button" class="btn btn-primary btn-block">Botón de ancho completo</button>
    </div>

    📝Si tiene muchos botones a nivel de bloque, puede controlar el espacio entre ellos con la clase .gap-*:

    <div class="d-grid gap-3">
        <button type="button" class="btn btn-primary btn-block">Botón de ancho completo</button>
        <button type="button" class="btn btn-primary btn-block">Botón de ancho completo</button>
        <button type="button" class="btn btn-primary btn-block">Botón de ancho completo</button>
    </div>

📒 Botones activos/deshabilitados

    📝Un botón se puede establecer en un estado activo (aparece presionado) o deshabilitado (no se puede hacer clic).

    📝La clase .active hace que un botón parezca presionado, y el atributo disabled hace que no se pueda hacer clic en un botón. Tenga en cuenta que los elementos <a> no admiten el atributo deshabilitado y, por lo tanto, deben usar la clase .disabled para que aparezca visualmente deshabilitado.

    <button type="button" class="btn btn-primary active">Active Primary</button>
    <button type="button" class="btn btn-primary" disabled>Disabled Primary</button>
    <a href="#" class="btn btn-primary disabled">Disabled Link</a>

📒 Botones giratorios

    📝También puede agregar "spinners" o un cargador a un botón:

    <button class="btn btn-primary">
        <span class="spinner-border spinner-border-sm"></span>
    </button>

    <button class="btn btn-primary">
        <span class="spinner-border spinner-border-sm"></span>
        Loading..
    </button>

    <button class="btn btn-primary" disabled>
        <span class="spinner-border spinner-border-sm"></span>
        Loading..
    </button>

    <button class="btn btn-primary" disabled>
        <span class="spinner-grow spinner-grow-sm"></span>
        Loading..
    </button>

Redes sociales:

- https://instagram.com/dev.joseltoro
- https://facebook.com/devjoseltoro
- https://tiktok.com/@dev.joseltoro
- https://dev.to/joseltoro
- https://code.dcoder.tech/profile/joseltoro
- https://joseltoro.blogspot.com/
- https://joseltoro.gumroad.com/