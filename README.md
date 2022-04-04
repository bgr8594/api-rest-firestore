# api-rest-firestore

Este es un api restfull para consumir firebase desde java, para el objeto de lugar se esta considerando
con la siguiente estructura
lugar:{
  id: numeroGeneradoFirebase // este no se especifica para dar de alta
  latitud: 25.7987796,
  longitud: -100.3253946,
  nombre: "Otro lugar bgr malo"
}

para ponerla en marcha, deben obtener una llave privada, en su consola de firebase desde el apartado de configuracion de una app web icono </>
ir a la pestaña cuentas de servicio y generar nueva clave privada teniendo el check de java, se debe descargar y renombrar como private-key-firestore.json para luego guardarla en carpeta resources de el proyecto firestorewebionic
