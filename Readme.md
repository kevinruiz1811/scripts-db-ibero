## Reglas del torneo – copa continental
    1.	El torneo se disputará entre 8 equipos en total, los cuales en los encuentros se realizarán en los barrios de cada equipo, en este se seguirá el reglamento oficial del fútbol del barrio.
    2.	El torneo se organizará en eliminación directa iniciando desde los cuartos de final, los equipos clasificados avanzarán a la siguiente ronda.

## Deportistas
    1.	Todos los deportistas deberán estar inscritos en el torneo.
    2.	Antes de los partidos se realizar control antidopaje.
    3.	Los deportistas deberán respetar el código de conducta establecido por la organización.

## Encuentros
    1.	Los horarios de los encuentros se publicarán con antelación.
    2.	Cada equipo deberá presentarse en el lugar designado con la indumentaria correspondiente.
    3.	Los encuentros se llevarán a cabo bajo la supervisión de los árbitros designados.


## Resultados
    1.	Los resultados de cada encuentro se registrarán oficialmente.
    2.	Se elaborarán informes detallados de cada fase del torneo.
    3.	Los informes de lesiones, incidentes o reclamaciones serán documentados y gestionados adecuadamente.

## Árbitros
    1.	Deberán contar con la certificación requerida.
    2.	Su decisión será final e inapelable.
    3.	Se velará por el respeto hacia los árbitros.

## Scripts
`Se crea la base de datos llamada 'TorneoContinental'

db.Arbitros.insertOne(
  {
    "_id": {
      "$oid": "663d925d810d8c280d04cd59"
    },
    "Certificacion": "Deberán contar con la certificación requerida",
    "DecisionesFinales": "Su decisión será final e inapelable",
    "RespetoArbitros": "Se velará por el respeto hacia los árbitros"
  }
)

db.Deportistas.insertOne(
  {
    "_id": {
      "$oid": "663d9130810d8c280d04cd51"
    },
    "InscripcionDocumentacion": "Debe estar debidamente inscrito y contar con documentación",
    "ControlesAntidopaje": "Se realizarán controles antidopaje",
    "CodigoConducta": "Deberán respetar el código de conducta establecido"
  }
)

db.Encuentros.insertOne(
  {
    "_id": {
      "$oid": "663d918a810d8c280d04cd54"
    },
    "Horarios": "Se publicarán con antelación",
    "PresentacionEquipo": "Deberán presentarse con la indumentaria correspondiente",
    "SupervisionArbitros": "Se llevarán a cabo bajo la supervisión de árbitros"
  }
)

db.reglas.insertOne(
  {
    "_id": {
      "$oid": "663d8969810d8c280d04cd4a"
    },
    "DuracionTorneo": "1 mes",
    "EquiposParticipantes": "8",
    "LugaresEncuentros": "Barrios",
    "Reglamento": "Reglamento oficila del fútbol del barrio",
    "Tipo": "Eliminación directa desde cuartos de final"
  }
)

db.Resultados.insertOne(
  {
    "_id": {
      "$oid": "663d91d2810d8c280d04cd56"
    },
    "RegistroResultados": "Se registrarán oficialmente los resultados",
    "ElaboracionInformes": "Se elaborarán informes detallados de cada fase",
    "GestionIncidentes": "Los informes de lesiones, incidentes o reclamaciones serán documentados"
  }
)`