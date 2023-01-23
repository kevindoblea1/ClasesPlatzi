# Seguridad de las aplicaciones.

### Ciclo de desarrollo seguro:
* Recopilación de los requerimientos de la aplicación (Funcionales y no funcionale)
* Diseño (Componentes de la app, arquitectura, comunicacion de componentes, lenguajes, frameworks) 
* Desarrollo (programacion de la app) 
* Pruebas (unitarias, funcionales, de seguridad con ataques comunes como inyeccion de codigo, etc ) 
* Despliegue (Publicacion de la app ) 
* Operaciones (Mantenimiento continuo y agregar funcionalidades para los usuarios)
* Repeticion del ciclo desde Recopilacion de los requerimientos.

### Los principales controles de seguridad que se suelen aplicar son:

* Entrenamiento OWASP Top 10:
Como protegernos del top 10 fallos de seguridad mas comunes
* Análisis estatico de código: 
Analizar el codigo sin compilar linea por linea con herramientas como SonarQube y Git Hub
* Análisis dinámico de código: 
Con el codigo ya compilado y corriendo. Intentar forzar fallos.
* Arquitecturas seguras: 
Asegurarse que todos los componentes sean seguros y comunicacion correcta.
* Modelo de Madurez (OWASP SAMM): 
Es un modelo que ayuda a formular e implementar una estrategia de mitigación de riesgos basandose en 5 pilares: Governance, Design, Implementation, Verification, Operations.
* Estandares mas conocidos de seguridad:

```Estandares mas conocidos de seguridad:
  - CERT Secure Coding
  - ISO/IEC 27034-1:2011
  - ISO/IEC TR 24772:2013
  - NIST Special Publication 800-53 
  - OWASP ASVS: Web Application Security Verification Standard
```
