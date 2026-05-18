# Predeterminar

Desde hoy, hace 18 años que existe esto: https://code.google.com/archive/p/predeterminar/downloads

Y para mi sorprensa, aún existe.

## Log

> Cuando grabé esta información en code.google.com ni sabía que décadas despúes iba a volver a encontrar esta info, así que el log, si bien tiene versiones, no tiene fechas.

v.0.1 La primera version de este archivo solamente modificaba la configuración de la hoja activa. Todo comenzó cuando Florencia me pregunta si existe una opción para predeterminar la configuración de las páginas de Excel 2000. Yo creía que si, pero para mi sorpresa esa opción está desde la version 2003 en adelante. Los excel que usamos en el trabajo carecen de semejante opción.

Es entonces cuando me puse a realizar el primer macro...

v.0.2 En la 2da versión busqué tomar todas las hojas activas, para que sea más simple la predeterminación

v.1.0 La versión definitiva (la testeada por Flor), modifica exitosamente todas las hojas del archivo en cuestion. Agradecimientos a David. =)

v.1.1 La versión 1.1 permite la personalización previa, para hacer la predeterminación de todas las hojas.

v.1.2 La version 1.2 agrega un cronómetro; y protege las hojas contra escritura.

v.1.3 Se agrega la opción para configurar el tamaño del texto de las pestañas.

Lamentablemente no logro configurar el macro para que tome el valor que el usuario quiere. Es decir no puedo hacer que el "Arial 8" sea configurable por el usuario, sino que viene por defecto. En una proxima version, si es que se logra... Espero poder lograrlo.

v.1.4 Una vez más aparece David en escena... Gracias al mismo, pude entender como hacer que sea personalizable el valor del tamaño del texto.

v.1.5 Bug en la version 1.4: resulta ser que cambiaba el estilo de letras a "normal" y color "automatico" lo que producía como resultado una pestaña completamente sin colores. Y donde había negrita, pasaba a ser un texto normal. La version 1.5 resuelve el inconveniente.

v.1.6 Bug! Jaja... Na.. El finde largo de Agosto estuve soñando con este Macro, y lamentablemente hoy me puse a testear con distintas hojas y detecté que si había una configuración previa de página por ejemplo "hoja apaisada" ... Despues de ejecutar el Macro quedaba todo con configuración vertical.

Con la v1.6 este problema se ha solucionado el 19 de Agosto, 2008 =)

v.1.7 Se agregaron botones de selección para determinar la orientación de las HOJAS.

