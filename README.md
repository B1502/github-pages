API para consulta de cédulas SEP
===========

API para consulta de cédulas profesionales de la SEP

http://search.sep.gob.mx/solr/cedulasCore/select?fl=%2A%2Cscore&q=miriam+cruz+lechuga&start=0&rows=100&facet=true&indent=on&wt=json

```
{
  "responseHeader":{
    "status":0,
    "QTime":1,
    "params":{
      "facet":"true",
      "indent":"on",
      "wt":"json",
      "rows":"100",
      "fl":"*,score",
      "start":"0",
      "q":"miriam cruz lechuga"}},
  "response":{"numFound":153546,"start":0,"maxScore":3.4999735,"docs":[
      {
        "nombre":"MIRIAM",
        "id":"1629426|C1",
        "numCedula":"1629426",
        "titulo":"LICENCIATURA EN PEDAGOGÍA",
        "genero":"2",
        "institucion":"RECONOCIMIENTOS DE SABERES ADQUIRIDOS - ACUERDO 286",
        "materno":"CRUZ",
        "anioRegistro":2024,
        "tipo":"C1",
        "paterno":"LECHUGA",
        "timestamp":"2025-031-22T09:14:58.313Z",
        "score":3.4999735},
	...
```
}
