# SprinbootOpenFeign-
Implementacion de OpenFeign

Creas una interfaz con la anotación @FeignClient. Defines los métodos como si fueran controladores de Spring MVC (@GetMapping, @PostMapping).
Spring Boot genera la implementación de esa interfaz por ti en tiempo de ejecución. No escribes código para abrir conexiones ni parsear JSON.
Cuando llamas a un método de la interfaz, Feign construye la URL, añade parámetros, ejecuta la petición HTTP y te devuelve el objeto ya convertido


pomp:
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-openfeign</artifactId>
</dependency>
