use torneo_deportivo

db.createCollection('deportistas')
db.createCollection('entrenadores')
db.createCollection('arbitros')
db.createCollection('encuentros')
db.createCollection('resultados')
db.createCollection('tabla_posiciones')
db.createCollection('equipos')

Ejemplo para subir información
use torneo_deportivo
db.deportistas.insertMany([
{"docIdent" : 1044321345, "nombres" : "Juan", "apellidos" : "Perez", "fecha_nacimiento" : new Date("2002-12-19")},
{"docIdent" : 1044321345, "nombres" : "Diego", "apellidos" : "Hernández", "fecha_nacimiento" : new Date("2001-04-04")},
{"docIdent" : 1044321345, "nombres" : "Pedro", "apellidos" : "Rodríguez", "fecha_nacimiento" : new Date("2002-06-20")},
{"docIdent" : 1044321345, "nombres" : "Brayan", "apellidos" : "Bonilla", "fecha_nacimiento" : new Date("2002-02-07")},
{"docIdent" : 1044321345, "nombres" : "Ricardo", "apellidos" : "Preciado", "fecha_nacimiento" : new Date("2001-08-15")},
{"docIdent" : 1044321345, "nombres" : "Mateo", "apellidos" : "Lopez", "fecha_nacimiento" : new Date("2001-04-30")},
])








