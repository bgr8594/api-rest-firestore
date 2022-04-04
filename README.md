# api-rest-firestore

Este es un api restfull para consumir firebas desde java, para el objeto de lugar se esta considerando
el objeto de entrada seria un destino de la forma
lugar:{
  id: numeroGeneradoFirebase // este no se especifica para dar de alta
  latitud: 25.7987796,
  longitud: -100.3253946,
  nombre: "Otro lugar bgr malo"
}

para ponerla en marcha, deben obtener una llave privada, en su consola de firebase desde el apartado de configuracion de una app web icono </>
ir a la pestaña cuentas de usuario y generar llave privada para java, se debe descargar y renombrar como private-key-firestore.json para luego guardarla en carpeta sources de el proyecto firestorewebionic
