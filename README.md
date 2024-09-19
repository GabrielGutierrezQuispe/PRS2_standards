## 🛠️ Tecnologías Utilizadas

Nuestro stack tecnológico está seleccionado cuidadosamente para proporcionar un rendimiento óptimo, escalable, mantenible y adaptable para cada proyecto:

- **Lenguajes <img width="25" height="25" src="https://img.icons8.com/deco/48/graphql.png" alt="graphql"/>**
    <details>
    <summary> <a href="https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html">Java</a> (versión 17) <img width="20" height="20" src="https://img.icons8.com/external-flaticons-flat-flat-icons/64/external-java-computer-programming-flaticons-flat-flat-icons.png" alt="external-java-computer-programming-flaticons-flat-flat-icons"/></summary>
        Java es un lenguaje de programación orientado a objetos ampliamente utilizado para desarrollar aplicaciones empresariales, móviles y web. 
        La versión 17 es una versión de soporte a largo plazo (LTS) que incluye mejoras en rendimiento, seguridad y nuevas características.
    </details>
- **Herramientas <img width="25" height="25" src="https://img.icons8.com/color/48/administrative-tools.png" alt="administrative-tools"/>**
    <details>
    <summary><a href="https://spring.io/projects/spring-boot">Spring Boot</a> con <a href="https://docs.spring.io/spring-framework/reference/web/webflux.html">Spring WebFlux</a> <img width="20" height="20" src="https://img.icons8.com/color/48/spring-logo.png" alt="spring-logo"/></summary>
        <ul>
            <li><b>Spring Boot:</b> Un framework que simplifica la creación de aplicaciones Java al proporcionar configuraciones predeterminadas y herramientas para el desarrollo rápido.</li>
            <li><b>Spring WebFlux:</b> Parte de Spring Framework que soporta programación reactiva, permitiendo manejar grandes volúmenes de solicitudes de manera eficiente y no bloqueante.</li>
        </ul>
    </details>
    <details>
    <summary><a href="https://maven.apache.org/">Maven</a> <img width="20" height="20" src="https://img.icons8.com/water-color/50/maven-ios.png" alt="maven-ios"/></summary>
       Una herramienta de gestión de proyectos y automatización de compilación para Java. Facilita la gestión de dependencias, la compilación del código, la ejecución de pruebas y la generación de informes.
    </details>
    <details>
    <summary><a href="https://about.gitlab.com/">GitLab</a> <img width="20" height="20" src="https://img.icons8.com/color/48/gitlab.png" alt="gitlab"/> y <a href="https://github.com/">GitHub</a> <img width="20" height="20" src="https://img.icons8.com/ios-glyphs/30/github.png" alt="github"/> </summary>
        <ul>
            <li><b>GitLab:</b> Una plataforma de DevOps que ofrece control de versiones, integración continua (CI/CD), gestión de proyectos. Es ideal para equipos que buscan una solución completa para el ciclo de vida del desarrollo.</li>
            <li><b>GitHub:</b> Una plataforma de control de versiones y colaboración que es muy popular entre desarrolladores de código abierto. Ofrece herramientas para la revisión de código, gestión de proyectos y CI/CD.</li>
        </ul>
    </details>
    <details>
    <summary><a href="https://projectlombok.org/">Lombok</a> 🌶</summary>
        Una biblioteca para Java que reduce el código repetitivo mediante anotaciones.
    </details>
    <details>
    <summary><a href="https://www.postman.com/">Postman</a> <img width="20" height="20" src="https://img.icons8.com/dusk/64/postman-api.png" alt="postman-api"/> </summary>
        Una herramienta para probar y documentar APIs. Permite crear y ejecutar solicitudes HTTP, verificar respuestas y automatizar pruebas de API, facilitando el desarrollo y la depuración de servicios web.
    </details>
- **Base de datos <img width="25" height="25" src="https://img.icons8.com/stickers/50/search-database.png" alt="search-database"/>**
    <details>
    <summary><a href="https://www.mongodb.com/es/lp/cloud/atlas/try4?utm_source=bing&utm_campaign=search_bs_pl_evergreen_atlas_core_prosp-brand_gic-null_amers-pe_ps-all_desktop_es-la_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=662815051&adgroup=1323814371704522&cq_cmp=662815051&msclkid=9afd3c44716c1db308365aa836acf6d6">MongoDB</a> (Atlas) <img width="30" height="30" src="https://img.icons8.com/color/48/mongo-db.png" alt="mongo-db"/></summary>
        Una base de datos NoSQL que almacena datos en formato JSON. MongoDB Atlas es la versión en la nube de MongoDB, que ofrece escalabilidad automática, copias de seguridad y seguridad avanzada, ideal para aplicaciones modernas           que requieren flexibilidad y rendimiento.
    </details>
- **Testing y Calidad <img width="25" height="25" src="https://img.icons8.com/fluency/48/test--v1.png" alt="test--v1"/>**
    <details>
    <summary><a href="https://sonarcloud.io/login">SonarCloud</a> <img width="20" height="20" src="https://img.icons8.com/dusk/64/cloud.png" alt="cloud"/></summary>
        Una plataforma de análisis de código estático que ayuda a identificar problemas de calidad y seguridad en el código. Proporciona métricas y reportes sobre la mantenibilidad, la cobertura de pruebas y las vulnerabilidades.
    </details>
    <details>
    <summary><a href="https://junit.org/junit5/">JUnit 5</a> <img width="20" height="20" src="https://img.icons8.com/bubbles/50/5-circle.png" alt="5-circle"/></summary>
        Un framework de pruebas unitarias para Java. Permite escribir y ejecutar pruebas automatizadas para asegurar que el código funciona correctamente. JUnit 5 introduce nuevas características y mejoras en comparación con                 versiones anteriores, facilitando la creación de pruebas más robustas.
    </details>
- **Por Implementar <img width="25" height="25" src="https://img.icons8.com/color/48/idea.png" alt="idea"/>**
    <details>
    <summary><a href="https://jmeter.apache.org/">Apache JMeter</a> 📈</summary>
        Una herramienta para realizar pruebas de rendimiento y carga. Permite simular múltiples usuarios y medir cómo se comporta una aplicación bajo diferentes condiciones de carga, ayudando a identificar cuellos de botella y               mejorar el rendimiento.
    </details>



---
   
   ### Gestión de Cors (Cross-Origin Resource Sharing)
   Emplear `@CrossOrigin` en los controladores de Spring para controlar el acceso desde dominios específicos, mejorando la seguridad y la interoperabilidad de la aplicación.

   Para mantener una buena consistencia definimos una politica de estandar clara:

   Todos los controladores deben incluir la configuración de CORS utilizando la anotación `@CrossOrigin` con los siguientes parámetros:

- **origins**: `https://{Nombre-de-la-ruta}`
- **methods**: `GET, POST, PUT, DELETE`
- **allowedHeaders**: `Content-Type, Authorization` (Opcional)
- **allowCredentials**: `true` (Opcional)
   
   ```java
    import org.springframework.web.bind.annotation.CrossOrigin;
    import org.springframework.web.bind.annotation.RequestMapping;
    import org.springframework.web.bind.annotation.RestController;
    import org.springframework.web.bind.annotation.GetMapping;
    import org.springframework.web.bind.annotation.PostMapping;
    import org.springframework.web.bind.annotation.RequestBody;
    import org.springframework.http.ResponseEntity;
    import reactor.core.publisher.Flux;
    import reactor.core.publisher.Mono;
    import java.net.URI;
    
    @RestController
    @RequestMapping("/public/api/v1")
    @CrossOrigin(origins = "https://{Nombre-de-la-ruta}", methods = {RequestMethod.GET, RequestMethod.POST, RequestMethod.PUT, RequestMethod.DELETE})
    public class UserController {
    
        @GetMapping("/users")
        public Flux<User> getAllUsers() {
            // Lógica para obtener todos los usuarios
            return userService.getAllUsers();
        }
    
        @PostMapping("/users")
        public Mono<User> createUser(@RequestBody User user) {
            // Lógica para crear un nuevo usuario
            User createdUser = userService.createUser(user);
            return ResponseEntity.created(URI.create("/api/v1/users/" + createdUser.getId())).body(createdUser);
        }
    }
**Buenas Prácticas**
- **Especificar Orígenes:** Evita usar `*` en `origins`. Especifica los dominios que realmente necesitan acceso.
- **Revisar y Limitar Métodos y Encabezados:** Solo permite los métodos y encabezados necesarios para tu aplicación.
- **Manejo de Credenciales:** Solo permite credenciales si es absolutamente necesario y asegúrate de que los orígenes permitidos sean seguros  

