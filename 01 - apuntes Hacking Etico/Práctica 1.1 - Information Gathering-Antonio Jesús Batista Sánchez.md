

# Ejercicio 1: La herramienta whois es muy útil cuando debemos obtener información sobre un dominio sin que pueda ser detectado por el blue team de este dominio. Esta herramienta está disponible para su uso tanto por consola como desde la web de domaintools.com. Haz pruebas empleando tanto la herramienta por consola como a través de la web.

Yo utilizare cuatro dominio diferentes siendo estos los siguientes:
- **urbanroosters.com**
- **llibnamic.com**
- **espinof.com**
- **grazalema.es**
en este ejercicio desde Kali utilizamos el comando whois para que nos de algo de información, A continuación se añadirá varias de las búsquedas realizadas de algunos de los dominios buscado desde el comando y otro dominio lo hemos buscado desde la pagina web de whois.
![[Pasted image 20241003202018.png]]
captura relacionada a la búsqueda de dominio:<span style="color:rgb(100, 132, 96)">espinof.com</span>

![[Pasted image 20241003202336.png]]
captura relacionada a la búsqueda de dominio:<span style="color:rgb(100, 132, 96)">urbanroosters.com</span>

![[Pasted image 20241003202728.png]]
captura relacionada a la búsqueda de dominio:<span style="color:rgb(100, 132, 96)">libnamic.com</span>

![[Pasted image 20241004173937.png]]
después de este apartado hemos conseguido algunas direcciones de esos dominios gracia a whois

espinof.com-hemos scado cuatro direcciones ip siendo las siguientes:
![[Pasted image 20241004175103.png]]

grazalema.es-hemos sacado la siguiente direccion:82.223.69.105

de los otros dominios no he sacado información relevante 

**Ejercicio 2:** El uso de la herramienta domaindossier puede ser muy interesante para obtener información del registro de una web, de sus DNS y otros aspectos. Empléala, haciendo énfasis en obtener datos interesantes y analizar dichos resultados objetivos. Obtener los datos y no analizarlos no nos servirá de nada, por lo **que este trabajo es tan importante como lanzar la propia herramienta.**
![[Pasted image 20241003203207.png]]

![[Pasted image 20241003203407.png]]


![[Pasted image 20241003203445.png]]

![[Pasted image 20241004174151.png]]
th

  ![[Pasted image 20241003203633.png]]the
  
![[Pasted image 20241003204128.png]]
![[Pasted image 20241003204145.png]]

![[Pasted image 20241003204258.png]]
![[Pasted image 20241003204428.png]]
![[Pasted image 20241003204852.png]]
![[Pasted image 20241003205346.png]]
# **Ejercicio 4:** Shodan es un buscador muy potente para realizar footprinting. En esta práctica vamos a comenzar a ver cómo se podría usar en nuestro beneficio.  

  

En primer lugar debemos tener configurada ya la herramienta “theHarvester”. Con ella podemos lanzar búsquedas de dominios para encontrar emails o subdominios.

  

1. Escojamos un objetivo (imaginemos por ejemplo que nos ha contratado una universidad pública o alguna administración a nivel local, autonómico, etc… Sed creativos).
    
2. Realicemos una búsqueda con theHarvester para obtener subdominios.
    
3. Con esa búsqueda de subdominios dirijámonos a shodan. 
    
4. Para emplear shodan tenemos dos opciones. Existe un plugin para Firefox que funciona bastante bien o también podemos emplearlo desde la propia web.
    

1. NOTA: Para obtener la ip de un dominio podemos usar la herramienta “host -a” o “ping”
    

6. En la web escribimos el subdominio y obtenemos información sobre el tipo de servidor web que está ejecutando.
    
7. Ahora procederemos a hacer una búsqueda en google de ese servidor web y versión para buscar vulnerabilidades.
    

1. Por ejemplo “nginx 1.1 vulnerabilities”
    

9. Buscamos el CVE de alguna vulnerabilidad
    
10. Vamos a [https://www.rapid7.com/db/?type=nexpose](https://www.rapid7.com/db/?type=nexpose) para buscar más información sobre la misma.
    

  

Ejercicio 5: Uso de la extensión de navegador Hunter para encontrar direcciones de correos asociadas a dominios.

  

Ejercicio 6: Uso de la extensión de navegador Wappalyzer para encontrar las tecnologías con las que está hecha la página web