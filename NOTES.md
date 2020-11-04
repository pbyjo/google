## Google Clone
    
    Este es un proyecto Frontend sobre google clone;
    En el encontrarán todas las clases por commits y las secciones por branches con un merge en el master.

### Introducción

### Análisis y creación del proyecto

* 3 - Análisis del proyecto Google Clone
    > El proyecto de este curso será crear un clon del buscador de google.

* 4 - Configuración del proyecto
    > Setup del proyecto.

    Index, CSS, Items, Notes.md

### Chrome Dev Tools como herramienta 

* 5 - Chrome Chrome Dev Tools
    >Chrome Dev Tools o Firefox developer edition

### Header Google Clone

* 6 - Maquetado del Header
    >Creamos nuestro header, un nav y un ul con li y a; siendo la etiqueta header el padre.

* 7 - Agregando estilos
    >Empezamos a darle estilos a nuestro header, usando la propiedad flexbox y ubicando nuestra lista.

    ```css
        .header {
            width: 100%;
            height: auto;

                border: 1px solid black;

                &__nav {
                    display: flex;
                    justify-content: flex-end;
                }
        }
    ```

* 8 - Posicionar una lista en horizontal
    >Damos espaciado a nuestras anclas y quitamos estilos de lista

    ```css
        &-rightsection {
            width: 300px;
            height: inherit;
            padding: 0;

                display: inherit;
                justify-content: center;
                align-items: center;
                list-style: none;
            
            & > li {
                margin: 0 10px 0 0;
            }
        }
    ```

* 9 - Manejo de íconos e imágenes en etiquetas
    > Le damos los ultimos detalles a nuestro header, agregamos img de perfil, icono de menu en formato svg y margenes finales.
    
### Contenido principal (Main)

* 10 - Maquetando la sección principal
    >Se crea un main container para nuestro buscardor, se maquetan las etiquetas necesarias. Img logo de google, un input y botónes.

* 11 - Estilos en la sección principal
    >Agregamos el logo de google, y centramos nuestro contenido horizontalmente

* 12 - Estilos en la sección del input
    >Le dimos estilo a nuestro input y su contenedor

* 13 - Íconos y manejo de background hover
    >Colocamos los dos iconos que lleva nuestro input, le damos su estilo final y agregamos efecto hover en el buscador

* 14 - Estilos en los botones
    >Terminamos de dar estilos a nuestros bótones, y agregamos texto adicional de región. Main terminado

### Footer Google Clone

* 15 - Maquetando el footer
    >Agregamos nuestras etiquetas necesarias para crear el footer, creamos dos sections. En el segundo sections tenemos dos div para generar nuestros link text

* 16 - Estilos en Footer
    >Creamos nuestros estilos para el footer en css, y terminamos nuestro footer

    ```css 
        .footer {
        height: 100vh;
        display: flex;
        flex-flow: column nowrap;  

            &__container {
                display: flex;
                flex-flow: column;
                margin-top: auto;
                height: 80px;
                background-color: #F2F2F2;
                border-top: 1px solid #DADCE0;
                font-size: 15px;
                color: #6F6F6F;
                
                .footer_1 {
                    display: inherit;
                    align-items: center;

                        height: 50%;
                        padding-left: 30px;
                }

                .footer_2 {
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    height: 50%;
                    
                    border-top: 1px solid #DADCE0;
                    
                    & > div {
                        display: flex;
                        grid-gap: 25px;
                        padding: 0 30px;

                        & > a {
                            text-decoration: none;
                            color: #6F6F6F;
                        }

                        & > a:hover {
                            text-decoration: underline;
                        }
                    }
                }
            }
        }
    ```
