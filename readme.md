

# Laboratorio Devsecops con Github Actions: Snyk y SonarCloud

<br>



Este repositorio tiene como objetivo proporcionar una guía paso a paso para integrar herramientas de análisis de código, seguridad y calidad dentro de un flujo de trabajo de GitHub Actions. A continuación, se describen las principales herramientas que se utilizarán:


<br>
<br>

## Snyk

<br>

![image](https://github.com/user-attachments/assets/03722a6e-6d4e-4c50-9ce7-4cbbbbf2abec)

<br>


Snyk es una plataforma que permite detectar y corregir vulnerabilidades en las dependencias de código, contenedores, infraestructura como código y configuraciones de nube. Snyk ayuda a los desarrolladores a identificar fallas de seguridad antes de que el código llegue a producción.
<br>
<br>
### Funcionalidades clave de Snyk:

* Detección de Vulnerabilidades: Escanea los archivos de dependencias para identificar vulnerabilidades conocidas en bibliotecas de terceros.
* Correcciones Automáticas: Snyk puede generar automáticamente parches o sugerencias de actualización para remediar vulnerabilidades.
* Monitoreo Continuo: Permite monitorear continuamente las dependencias para detectar nuevas vulnerabilidades una vez que se publican.
* Soporte para Múltiples Lenguajes: Compatible con varios lenguajes y entornos, incluyendo JavaScript, Python, Java, y más.
<br>
<br>

### Integración con GitHub Actions:
Snyk se puede integrar con GitHub Actions para ejecutar escaneos de seguridad automáticamente durante el ciclo de desarrollo, lo que asegura que cualquier vulnerabilidad en las dependencias se identifique antes de fusionar cambios al código principal.
<br>
<br>
