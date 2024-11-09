
# Tarea - APIs Externas
  
Esta tarea consiste en la implementación de tres proyectos en **Spring Boot** (con **JDK 17**), que interactúan con la API de Sunat utilizando tres diferentes métodos para el consumo de APIs externas:

1. **RestTemplate**
2. **OpenFeign**
3. **Retrofit**

Cada proyecto implementa un método `GET` para invocar la siguiente URL de la API de Sunat y obtener los datos de una empresa por su RUC:

```
https://api.apis.net.pe/v2/sunat/ruc/full?numero=RUC
```


1. **msresttemplate**: Utiliza `RestTemplate` para realizar la llamada a la API externa.
2. **msopenfeign**: Usa `OpenFeign` para gestionar la solicitud `GET`.
3. **msretrofit**: Emplea `Retrofit` para hacer la petición a la API.

Cada proyecto está ubicado dentro de su respectiva carpeta y contiene todos los archivos necesarios para su ejecución.