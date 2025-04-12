# **Guía de DevSecOps de OWASP**

### La Guía DevSecOps de OWASP explica cómo implementar un pipeline seguro, aplicar las mejores prácticas e introducir herramientas útiles para ello. Además, el proyecto busca ayudarnos a promover la cultura de seguridad de cambio a la izquierda en nuestro proceso de desarrollo. Este proyecto ayuda a empresas de cualquier tamaño que cuenten con un pipeline de desarrollo o, en otras palabras, con un pipeline de DevOps. Durante este proyecto, buscamos definir la perspectiva de un pipeline de DevOps seguro y luego mejorarlo según nuestros requisitos específicos.

## El objetivo ideal es “detectar problemas de seguridad (por diseño o vulnerabilidad de la aplicación) lo más rápido posible”.

## Pasos iniciales:
### En primer lugar, consideramos implementar los siguientes pasos en una tubería básica:

### Escanee los repositorios Git para encontrar posibles fugas de credenciales.
- SAST (Prueba de seguridad de aplicaciones estáticas)
- SCA (Análisis de composición de software)
- IAST (Pruebas de seguridad de aplicaciones interactivas)
- DAST (Prueba de seguridad de aplicaciones dinámicas)
- Escaneo de IaC (escaneo de código de Terraform y HelmChart para detectar errores de configuración)
- Escaneo de infraestructura
- Comprobación de cumplimiento

---
  
![Diagrama DevSecOps](DevSecOps-pipeline.png)

----

[pagina owasp](https://owasp.org/www-project-devsecops-guideline/)

---

[video owasp](https://www.youtube.com/watch?v=vf9Waxh3I04)

