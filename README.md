API para consulta de cédulas profesionales de la SEP
===========

buscar por el nombre o consultar por #num de cédula 


http://search.sep.gob.mx/solr/cedulasCore/select?fl=%2A%2Cscore&q=andres+manuel+lopez+obrador&start=0&rows=100&facet=true&indent=on&wt=json

```
{
  "responseHeader":{
    "status":0,
    "QTime":0,
    "params":{
      "facet":"true",
      "fl":"*,score",
      "indent":"on",
      "start":"0",
      "q":"andrés manuel lópez obrador",
      "wt":"json",
      "rows":"100"}},
  "response":{"numFound":810686,"start":0,"maxScore":3.51532,"docs":[
      {
        "nombre":"ANDRÉS MANUEL",
        "id":"1418552|C1",
        "numCedula":"1418552",
        "titulo":"LICENCIATURA EN CIENCIAS POLÍTICAS Y ADMINISTRACIÓN PÚBLICA",
        "genero":"1",
        "institucion":"UNIVERSIDAD NACIONAL AUTÓNOMA DE MÉXICO",
        "materno":"OBRADOR",
        "anioRegistro":1989,
        "tipo":"C1",
        "paterno":"LÓPEZ",
        "timestamp":"2020-08-21T06:14:06.082Z",
        "score":3.51532},
      
	...
```
