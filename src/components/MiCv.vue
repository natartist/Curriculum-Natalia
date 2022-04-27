<template>
    <div class="container">
        <div class="row fila-1">
            <div class="caja1 col-8" style="background-color:#F7EFDD ">
                <h2>Quién soy</h2>
                <p>Profesional de las comunicaciones, en proceso de reconversión laboral hacia las nuevas tecnologías, a
                    través del desarrollo web, en FrontEnd (categoría Junior). Con interés de aprender, habilidades en
                    trabajo en equipo, manejo bajo presión, resiliente y con competencias relacionadas con comunicación
                    verbal y escrita
                    Nivel de inglés medio.</p>
            </div>

            <div class="caja2 col-3 ml-2" style="background-color:#E3F6FF">
                <h2>FrontEnd Skills</h2>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>NodeJs</li>
                    <li>Git</li>
                    <li>Saas</li>
                    <li>Gulp</li>
                    <li>WebPack</li>
                    <li>JSon</li>
                    <li>Firebase</li>

                </ul>
                <!-- <div class="skills">
                   <img src="@/assets/html-5.png" alt="Html">
                   <img src="@/assets/css.png" alt="Css">
                   <img src="@/assets/js.png" alt="JavaScript">
                   <img src="@/assets/node.png" alt="NodeJs">
                   <img src="@/assets/git.png" alt="Git">
                   <img src="@/assets/saas.png" alt="Saas">
                   <img class="vue" src="@/assets/pngwing.com.png" alt="Vue">
                </div> -->
            </div>
        </div>

        <div class="row fila-2 mt-4">
            <div class="caja3 col-3" style="background-color:#F1EDFC ">
                <h2>Redes Sociales</h2>
                <a title="Linkedin" href="https://www.linkedin.com/in/natalia-araya-frontend/">
                <img class="rrss" src="@/assets/linkedin.png" alt="Linkedin"/>
                <p>Linkedin</p>
                </a>

                <a title="GitHub" href="https://github.com/natartist">
                <img class="rrss" src="@/assets/github.png" alt="GitHub"/>
                <p>GitHub</p>
                </a>

                <!-- <a title="Netlify" href="https://app.netlify.com/teams/nata-araya/overview">
                <img src="@/assets/netlify.png" alt="Netlify"/>
                <p>Netlify</p>
                </a> -->

                <a title="Twitter" href="https://www.linkedin.com/in/natalia-araya-frontend/">
                <img class="rrss" src="@/assets/twitter.png" alt="Twitter"/>
                <p>Twitter</p>
                </a>
            </div>

            <div class="caja4 col-8" style="background-color: #EED5EE ">
                <h2>Experiencia Laboral</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum delectus obcaecati est molestias?
                    Maxime earum sint et fugiat sequi? Et id reprehenderit eveniet asperiores dolores eius a ex qui cum.
                </p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit mollitia et harum! Explicabo impedit
                    aperiam earum quaerat, magni, voluptatum, velit a eos eveniet nulla nam! Odit sapiente inventore
                    sint ullam?</p>
            </div>
        </div>

        <div class="row fila-3 mt-4">
            <div class="caja5 col-12" style="background-color:#FDF5FC ">
                <h2>Estudios</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum delectus obcaecati est molestias?
                    Maxime earum sint et fugiat sequi? Et id reprehenderit eveniet asperiores dolores eius a ex qui cum.
                </p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit mollitia et harum! Explicabo impedit
                    aperiam earum quaerat, magni, voluptatum, velit a eos eveniet nulla nam! Odit sapiente inventore
                    sint ullam?</p>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: "MiCv",
    }
</script>

<style scoped>
    .container {
        width: 900px;
        margin-top: 20px;
        padding: 20px;
        background-image: url("@/assets/entorno.png");
        background-attachment: fixed;
        background-repeat: repeat;
        background-size: 400px;
        
    }

    .fila-1 {
        display: flex;
        align-items: center;
        justify-content: space-between;

    }

    /* .caja1 {
        height: auto;
        width: auto;
        transform: skewY(-3deg);
        transform-origin: 100%;
        width: 100%;
    } */

    .fila-2 {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .fila-3 {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .caja1 {
        margin-left: 15px;
        border-radius: 15px;
        box-shadow: 2px 2px 5px 0;
    } 

    .caja2 {
        margin-right: 15px;
        border-radius: 15px;
        box-shadow: 2px 2px 5px 0;
    } 

    .caja3 {
        margin-left: 15px;
        border-radius: 15px;
        box-shadow: 2px 2px 5px 0;
    } 

    .caja4 {
        margin-right: 15px;
        /* margin-top: -50px; */
        border-radius: 15px;
        box-shadow: 2px 2px 5px 0;
        
    } 

    .caja5 {
        /* margin-left: 15px; */
        border-radius: 15px;
        box-shadow: 2px 2px 5px 0;
        /* margin-right: 15px; */
        /* margin-left: 15px;  */
        padding: 0px;
        
    }

    h2 {
        margin-top: 15px;
        color: gray;
        font-family: 'Quicksand', sans-serif;
    }
    img {
        height: 30px;
        width: auto;
        margin-left: 6px;
        margin-top: 6px;
    }
    
    .vue {
       height: 80px;
        width: auto;
        margin-left: 6px;
        margin-top: 6px;
    }

    .rrss {
        height: 20px;
        
    } 

    li {
    color: gray;
    font-size: 14px;
    }

    p {
        font-size: 14px;
        color: gray;
    }
</style>