<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:titulo="'Unidad 2. Algoritmos y la Revolución 4.0'" :subTitulo="'3. Big Data: procesamiento de datos masivos, mediante algoritmos'")
  .container.tarjeta.tarjeta--blanca.px-4.px-md-5.pt-4.pt-md-5.pb-0.overflow-hidden
    
    .row.mb-4
      .col-12.col-xl-7.d-flex.flex-column(data-aos="fade-right")
        p.mb-4 Para comprender el funcionamiento del procesamiento de datos masivos mediante algoritmos, se vuelve imperativo definir Big Data; así se podrá crear una relación directa entre un término y el contexto del otro, e interpretar de manera sencilla Big Data: procesamiento de datos masivos, mediante algoritmos. 
        h3 ¿Qué es Big Data?
        p.mb-0  Big Data se define como el procesamiento de grandes volúmenes de datos que, por su volumen (tamaño, velocidad, variedad), no pueden ser procesados de manera tradicional. Datos que han sido recolectados de diferentes fuentes como son los sensores, redes sociales, registros web y financieros, entre otros; sirven para tomar decisiones inteligentes mediante la implementación de algoritmos especializados. 
      .d-none.d-xl-block.col-xl-5.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-38.png', alt='Texto que describa la imagen')
    
    .row.mb-4
      .d-none.d-xl-block.col-xl-5.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img(src='@/assets/curso/unidad/img-39.png', alt='Texto que describa la imagen') 
      .col-12.col-xl-7.d-flex.flex-column
        p.mb-4 Algunos ejemplos de uso del Big Data son:
        .d-flex.align-items-start.bg-azul.p-3.mb-3(data-aos="fade-up")
          div.d-flex
            img.me-2.d-flex.mb-auto.mt-2(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
            p.mb-0  Plataformas de streaming
        .d-flex.align-items-start.bg-azul.p-3.mb-3(data-aos="fade-up")
          div.d-flex
            img.me-2.d-flex.mb-auto.mt-2(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
            p.mb-0  Supermercados
        .d-flex.align-items-start.bg-azul.p-3.mb-3(data-aos="fade-up")
          div.d-flex
            img.me-2.d-flex.mb-auto.mt-2(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
            p.mb-0  Salud
        .d-flex.align-items-start.bg-azul.p-3.mb-3(data-aos="fade-up")
          div.d-flex
            img.me-2.d-flex.mb-auto.mt-2(style="width: 15px" src='@/assets/curso/arrow.svg', alt='Texto que describa la imagen')
            p.mb-0  Tráfico

    .row.mb-5
      .col-12.col-lg-11.mx-auto
        div.d-flex.align-items-center.bg-morado-claro.px-3.py-4
          img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-40.svg', alt='Texto que describa la imagen')
          p.pe-xl-5.mb-0 Al utilizar plataformas de streaming se analizan, en segundos, millones de datos para visualizar contenido recomendado o sugerido para el usuario; a su vez, en los supermercados, analizan el comportamiento de compra de sus clientes para ofrecer descuentos y promociones; también en el área de la salud, se pueden predecir brotes de enfermedades y analizar mediante datos médicos, su comportamiento en tiempo real. Para finalizar, algunas plataformas de transporte analizan el tráfico para optimizar las rutas y entregar al conductor la mejor. 

    #t_3_1.titulo-segundo
      div.d-flex
        span.me-3 3.1  
        h2 Ejemplos de algoritmos usando Big Data
    
    .row.mb-5
      .col-12.col-xl-7.d-flex.pe-4.pe-xl-5.align-items-center.flex-column(data-aos="fade-right")
        p.mb-5 A continuación lo invitamos a consultar el PDF llamado "Ejemplos de algoritmos usando Big Data" el cual muestra de manera sencilla la capacidad del Big Data para resolver problemas complejos y transformar grandes volúmenes de datos en información útil. Los algoritmos de Big Data se aplican en múltiples sectores, como la salud, las finanzas, el comercio electrónico y las redes sociales, generando avances significativos en la toma de decisiones y la optimización de procesos. A través de estos ejemplos prácticos, veremos cómo estos algoritmos recopilan, procesan y analizan datos a gran escala para identificar patrones, realizar predicciones y proporcionar hallazgos valiosos que potencian la innovación y la eficiencia en las organizaciones. 
        a.d-flex.pe-4.me-auto.bg-white.box-shadow.cursor-pointer(data-aos="zoom-in" :href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")
          img.h-100(style="width: 48px" src='@/assets/componentes/pdf-icon-square.svg', alt='Texto que describa la imagen')
          p.text-small.fs-14px.my-auto.px-2 <strong>Anexo.</strong> Ejemplos de algoritmos usando Big Data
      .d-none.d-xl-block.col-xl-5.mx-auto.mt-4.mt-xl-0(data-aos="fade-left")
        img.h-100(src='@/assets/curso/unidad/img-41.png', alt='Texto que describa la imagen')

    .row.mb-4
      .d-none.d-xl-block.col-xl-5.mx-auto.mt-4.mt-xl-0(data-aos="fade-right")
        img(src='@/assets/curso/unidad/img-42.png', alt='Texto que describa la imagen')
      .col-12.col-xl-7.d-flex.flex-column(data-aos="fade-left")
        p.mb-4 Big Data permite el procesamiento de grandes volúmenes de datos a través de la implementación de algoritmos como conteo de palabras, MapReduce y K-Means, convirtiendo esos datos en información valiosa para las compañías, apoyando a la gestión del negocio y en la toma de decisiones, también permiten entregar publicidad personalizada, según el cliente final, mejorar el tráfico en las ciudades y apoyar la atención médica. 
        p.mb-0 Teniendo claro Big Data, su uso y algunos ejemplos de algoritmos que se utilizan a diario; para la gestión de grandes volúmenes de datos pasamos a definir el procesamiento de datos masivos mediante algoritmos. 
    
    .d-flex.align-items-center.bg-azul.px-3.py-4.mb-5
      img.me-4(style="width: 90px" src='@/assets/curso/unidad/img-43.svg', alt='Texto que describa la imagen')
      p.pe-xl-5.mb-0 Así como con la ayuda del Big Data se analizan grandes volúmenes de datos, el procesamiento de datos masivos permite obtener patrones útiles, generar predicciones o apoyar en la toma de decisiones eficientes. Esto no sería posible de manera tradicional debido a la cantidad de información obtenida y su variedad, además se debe tener presente que cada segundo la cantidad va en aumento exponencial. Los algoritmos permiten organizar, filtrar y analizar los datos obtenidos a través de medios masivos de manera eficiente y ágil. 

    .row.mb-5
      .col-12.col-lg-10.mx-auto
        .row(data-aos="fade-up")
          .col-6.pe-2
            .bg-amarillo.p-4.h-100
              h3 Ejemplo 1
              p.mb-0 Usado para calcular el promedio de un conjunto de datos, por ejemplo, conocer el rendimiento promedio de los estudiantes en una clase. 
          .col-6.ps-2
            .bg-amarillo.p-4.h-100
              h3 Ejemplo 2
              p.mb-0 Permite buscar valores que cumplan con una condición específica, por ejemplo, el siguiente algoritmo encontrará productos cuyo precio sea mayor a $50.
        .row(data-aos="fade-up")
          .col-6.pe-2
            .bg-negro.p-4.h-100.text-white
              p.mb-1 Función promedio(numeros):
              p.ps-3.mb-1 suma = 0
              p.ps-3.mb-1 Para cada par numero en numeros:
              p.ps-4.ms-3.mb-1 suma = suma + numero
              p.ps-3.mb-1 promedio = suma / tamaño(numeros)
              p.ps-3.mb-1 Retornar promedio
          .col-6.ps-2
            .bg-negro.p-4.text-white.h-100
              p.mb-1 Función filtrar(lista, umbral):
              p.ps-3.mb-1 resultado = [ ]
              p.ps-3.mb-1 Para cada elemento en lista:
              p.ps-4.ms-3.mb-1 Si elemento > umbral:
              p.ps-5.ms-3.mb-1 Añadir elemento a resultado
              p.ps-3.mb-1 Retornar promedio

        .row(data-aos="fade-up")
          .col-6.pe-2
            .bg-morado-claro.p-4.h-100
              p El algoritmo procesa miles de calificaciones de estudiantes para determinar el promedio general de todo el colegio. 
          .col-6.pe-2
            .bg-morado-claro.p-4.h-100
              p En un supermercado se podría implementar el anterior algoritmo para buscar de entre todos sus productos aquellos que cumplan con el criterio de búsqueda y aplicar un descuento. 

    .row.mb-5.mx-0
      .d-none.d-xl-block.col-4.px-0(data-aos="fade-right")
        img.h-100(src='@/assets/curso/unidad/img-44.png', alt='Texto que describa la imagen')
      .col-12.col-xl-8.d-flex.align-items-center.bg-amarillo-oscuro.p-4(data-aos="fade-left")
        p.mb-0(data-aos="fade-up") En conclusión, Big Data: procesamiento de datos masivos mediante algoritmos hace referencia a la capacidad de los algoritmos de analizar grandes volúmenes de datos a través de diferentes metodologías con el fin de procesar la información que se genera en tiempo real y a gran escala, obtenida de diferentes fuentes, con el objetivo de simplificarla a tal punto que permita tomar decisiones a través de los patrones de comportamiento que genera, también, permite optimizar procesos y generar retroalimentaciones verídicas que permiten cumplir con las expectativas del cliente, usuario, equipo o sistema de información. 
    

    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2 MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/117744?page=23" target="_blank" rel="noopener noreferrer") Casas Roma, J. Nin Guerrero, J. & Julbe López, F. (2019). Big data: análisis de datos en entornos masivos: ( ed.). Editorial UOC. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/59093?page=55" target="_blank" rel="noopener noreferrer") López Murphy, J. J. & Zarza, G. (2017). La ingeniería del big data: cómo trabajar con datos: ( ed.). Editorial UOC. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=M26iIqmqWkI" target="_blank" rel="noopener noreferrer") EDteam. (2019, 13 de abril). ¿Qué es el Big Data? - La mejor explicación en español 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')


</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Big Data: procesamiento de datos masivos, mediante algoritmos',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              'En un sistema de mantenimiento predictivo con IA, ¿qué algoritmo sería más apropiado para predecir el desgaste progresivo de una pieza industrial?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Regresión lineal',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Búsqueda binaria',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Algoritmo quicksort',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Algoritmo recursivo',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué tecnología permite la interconexión de dispositivos sin requerir intervención humana?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Big Data',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Internet de las Cosas (IoT)',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Realidad aumentada',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Manufactura aditiva',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              'En el contexto de un algoritmo de búsqueda binaria, ¿qué sucedería si buscamos el valor 7 en la lista ordenada [2,4,6,8,10]?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'El algoritmo retornaría el valor 8',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'El algoritmo retornaría -1 (valor no encontrado)',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'El algoritmo se quedaría en un bucle infinito',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'El algoritmo retornaría el valor más cercano (6)',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto: '¿Cuál es la función principal de Synthesia?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Crear imágenes hiperrealistas',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Programar código',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Generar videos con avatares digitales que leen textos personalizados',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Procesar lenguaje natural',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              'En una plataforma de streaming, ¿qué aplicación práctica del Big Data se implementa principalmente?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Análisis del tráfico web',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Predicción de enfermedades',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Análisis de datos para recomendación de contenido',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Optimización de rutas de transporte',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
