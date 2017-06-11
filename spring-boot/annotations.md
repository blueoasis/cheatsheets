# Annotations

Annotation | Purpose
--- | --- 
@SpringBootApplication | Same effect as manually adding @EnableAutoConfiguration, @Configuration and @ComponentScan
@EnableAutoConfiguration | Tells Spring to search for classes and jars on the classpath and enable certain features based on what it finds.
@Configuration | Tells Spring that this class is a source for @Bean definitions
@ComponentScan | Tells Spring to scan the current package and all child packages for annotated Spring Beans with annotations such as @Component, @Service, @DAO, @Controller, etc

