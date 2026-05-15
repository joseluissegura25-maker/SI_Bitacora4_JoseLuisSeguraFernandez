

El Marco Legal y la Estructura del "Relato"

Nombre: Jose Luis Segura Fernández  
Asignatura: Sistemas informáticos  
Profesor/a: Willman Acosta Lugo  
Fecha de entrega: 15/05/2026  
ÍNDICE

[**1\. Analisis de Necesidades**](#id1)

[**2\. Que problema de la empresa resolvemos con Guacamole y Docker**](#id2)

[**3\. ¿Porque elegimos esta solucion y no conectar directamente por RDP a cada maquina?**](#id3)

# 

1. # Análisis de Necesidades<a name="id1"></a>

# 
La infraestructura de nuestra organizacion enfrenta retos signficiativos en cuanto a la gestion de accesos remotos y la eficiencia operativa. Hasta ahora la administracion de multiples estaciones de trabajo y servidores se realizaba de manera fragmentada, lo cual genera vulnerabilidades de seguridad y un uso ineficiente de los recursos de hardware. El objetivo de implementar Guacamole sobre una arquitectura de contenedores Docker no es una eleccion arbitraria, sino una respuesta estrategica a esas deficiencias.

2. # Que problema de la empresa resolvemos con Guacamole y Docker<a name="id2"></a>

# 
El principal problema que se resuelve es la falta de centralizacion. En un entorno corporativo moderno, depewnder de conexiones individuales para cada equipo es insostenible. Mediante Guacamole, establecemos un portal único de aceso basado en navegador lo que permite a los colaboradores accedes a sus entornos de trabajo por HTML5 sin necesidad dee instalar software cliente adicional

# 

3. # ¿Porque elegimos esta solucion y no conectar directamente por RDP a cada maquina?<a name="id3"></a>

# 

Se elije por la escalabilidad y mantenimiento, accesibilidad universal y la auditoria de control que no spermite implementar politicas de autenticacion robustas.