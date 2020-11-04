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