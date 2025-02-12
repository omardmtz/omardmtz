<template>
  <div class="flex">
    <div class="column flex-center content-center" style="width: 100%">
      <h1>¡Hola! Soy Omar, Diseñador Web.</h1>
      <p class="text-h4">
        Transformo ideas en sitios web únicos y funcionales.
      </p>
      <div class="row q-pa-md">
        <img src="/img/startup.png" alt="" class="shadow-6 fit" />
      </div>
    </div>
    <div class="aboutme row q-pa-xl q-mt-xl">
      <div class="col-md-4 items-center flex q-pa-xl">
        <img src="/img/aboutme.png" style="" class="fit" alt="" />
      </div>
      <div class="col-md-8 items-center flex">
        <div>
          <p class="text-h4">¿Quieres conocer más sobre mí?</p>
          <p>
            Soy un apasionado del diseño y desarrollo web, dedicado a ayudar a
            negocios y emprendedores a construir una presencia profesional en
            línea.
          </p>
          <p>
            Con más de 6 años de experiencia en herramientas de desarrollo, me
            especializo en crear sitios web visualmente atractivos, fáciles de
            usar y completamente personalizados según tus necesidades.
          </p>
          <p>
            Además, me encargo de aspectos técnicos como la configuración de
            hosting y la gestión de dominios, para que puedas concentrarte en lo
            que realmente importa: hacer crecer tu negocio. Mi objetivo es hacer
            que el proceso sea sencillo y sin complicaciones, asegurándome de
            que el resultado supere tus expectativas.
          </p>
          <p>
            Si buscas un diseño único que refleje tu marca y conecte con tus
            clientes, estoy aquí para ayudarte. ¡Hagamos realidad tu idea!
          </p>
        </div>
      </div>
    </div>
    <div class="process fit q-pa-xl q-pb-xl">
      <div class="">
        <div class="q-gutter-md">
          <div class="fit flex  column flex-center">
            <p class="text-h2">
              El proceso detrás de tu sitio web
            </p>
            <p class="text-h5">
              Descubre cómo convertimos tus ideas en una presencia profesional en línea, paso a paso.
            </p>
          </div>
          <q-carousel
            v-model="slide"
            transition-prev="scale"
            transition-next="scale"
            swipeable
            animated
            control-color="black"
            navigation
            padding
            arrows
            min-height="300px"
            class="bg-primary shadow-6 rounded-borders"
          >
            <q-carousel-slide name="style" class="column no-wrap flex-center">
              <q-icon name="search" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Análisis inicial
                </p>
                <p>
                  Es el primer paso para conocer tu negocio, tus objetivos y a quién quieres llegar. Aquí identificamos lo que te hace único y cómo podemos reflejarlo en tu sitio web para destacar frente a la competencia.
                </p>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="tv" class="column no-wrap flex-center">
              <q-icon name="brush" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Planeación y diseño
                </p>
                <p>
                  En esta etapa organizamos las secciones de tu sitio, definimos su estructura y creamos un estilo visual único con colores, tipografías e imágenes que representen la esencia de tu negocio.
                </p>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="layers" class="column no-wrap flex-center">
              <q-icon name="attach_file" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Preparación de contenido
                </p>
                <p>
                  Reunimos los textos, imágenes y recursos clave que transmitirán tu mensaje de manera clara y atractiva, incluyendo llamados a la acción para guiar a tus visitantes hacia tus objetivos.
                </p>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="map" class="column no-wrap flex-center">
              <q-icon name="code" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Desarrollo técnico
                </p>
                <p>
                  Aquí transformamos las ideas en un sitio funcional. Configuramos el dominio y el hosting, creamos el diseño personalizado y optimizamos el sitio para que sea rápido, seguro y se vea perfecto en cualquier dispositivo.
                </p>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="deploy" class="column no-wrap flex-center">
              <q-icon name="rocket" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Implementación y lanzamiento
                </p>
                <p>
                  Publicamos tu sitio en línea, conectamos herramientas para medir su rendimiento y lo compartimos en los canales adecuados para que tus clientes puedan encontrarte fácilmente.
                </p>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="maintenance" class="column no-wrap flex-center">
              <q-icon name="engineering" size="56px" />
              <div class="q-mt-md text-center">
                <p class="text-h3">
                  Mantenimiento continuo
                </p>
                <p>
                  Nos aseguramos de que tu sitio esté siempre actualizado, seguro y funcionando correctamente, realizando ajustes y mejoras según sea necesario para mantenerlo relevante y eficiente.
                </p>
              </div>
            </q-carousel-slide>
          </q-carousel>
        </div>
      </div>
    </div>
    <div class="aboutme row q-pa-xl q-mt-xl flex-center">
      <div class="col-md-6 items-center flex">
        <div>
          <p class="text-h4">¡Hablemos!</p>
          <p>
            Si tienes preguntas, necesitas más información o estás listo para comenzar tu próximo proyecto, estoy aquí para ayudarte. Contactame a través de los siguientes medios y te respondere lo antes posible.
          </p>
          <ul>
            <li>Correo electrónico: omardmtz77@gmail.com</li>
            <li>WhatsApp: <a style="text-decoration: none; color: #71d6eb;" href="https://api.whatsapp.com/send?phone=8443215323">Click para comenzar!</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
img {
  border-radius: 50%;
  max-width: 300px;
}
.aboutme {
  width: 100%;
  background: #303030;
  color: #ffffff;
}
</style>
<script>
import { ref } from "vue";
export default {
  setup() {
    return {
      slide: ref("style"),
    };
  },
};
</script>
