# Python-avanzado
En este repositorio pondremos a prueba los conocimientos adquiridos en el curso usando un nivel de python avanzado.

# Descripción del proyecto

Trabajas en una empresa emergente que vende productos alimenticios. Debes investigar el comportamiento del usuario para la aplicación de la empresa.

Primero, estudia el embudo de ventas. 
Descubre cómo los usuarios y las usuarias llegan a la etapa de compra. 
¿Cuántos usuarios o usuarias realmente llegan a esta etapa? 
¿Cuántos se atascan en etapas anteriores? ¿Qué etapas en particular?

Luego, observa los resultados de un test A/A/B. 
(Sigue leyendo para obtener más información sobre los test A/A/B). 
Al equipo de diseño le gustaría cambiar las fuentes de toda la aplicación, pero la gerencia teme que los usuarios y las usuarias piensen que el nuevo diseño es intimidante. Por ello, deciden tomar una decisión basada en los resultados de un test A/A/B.

Los usuarios se dividen en tres grupos: 
dos grupos de control obtienen las fuentes antiguas y un grupo de prueba obtiene las nuevas. Descubre qué conjunto de fuentes produce mejores resultados.


Paso 1. Abrir el archivo de datos y leer la información general


Paso 2. Preparar los datos para el análisis

Cambia el nombre de las columnas de manera que sea conveniente para ti
Comprueba si hay tipos de datos y valores ausentes. Corrige los datos si es necesario
Agrega una columna de fecha y hora y una columna separada para las fechas

Paso 3. Estudiar y comprobar los datos

¿Cuántos eventos hay en los registros?
¿Cuántos usuarios y usuarias hay en los registros?
¿Cuál es el promedio de eventos por usuario?
¿Qué periodo de tiempo cubren los datos? Encuentra la fecha máxima y mínima. Traza un histograma por fecha y hora. ¿Puedes tener seguridad de que tienes datos igualmente completos para todo el periodo? Los eventos más antiguos podrían terminar en los registros de algunos usuarios o usuarias por razones técnicas y esto podría sesgar el panorama general. Encuentra el momento en el que los datos comienzan a estar completos e ignora la sección anterior. ¿Qué periodo representan realmente los datos?
¿Perdiste muchos eventos y usuarios al excluir los datos más antiguos?
Asegúrate de tener usuarios y usuarias de los tres grupos experimentales.

Paso 4. Estudiar el embudo de eventos

Observa qué eventos hay en los registros y su frecuencia de suceso. Ordénalos por frecuencia.
Encuentra la cantidad de usuarios y usuarias que realizaron cada una de estas acciones. Ordena los eventos por el número de usuarios y usuarias. 
Calcula la proporción de usuarios y usuarias que realizaron la acción al menos una vez.
¿En qué orden crees que ocurrieron las acciones? 
¿Todas son parte de una sola secuencia? No es necesario tenerlas en cuenta al calcular el embudo.

Utiliza el embudo de eventos para encontrar la proporción de usuarios y usuarias que pasan de una etapa a la siguiente. (Por ejemplo, para la secuencia de eventos A → B → C, calcula la proporción de usuarios en la etapa B a la cantidad de usuarios en la etapa A y la proporción de usuarios en la etapa C a la cantidad en la etapa B).
¿En qué etapa pierdes más usuarios y usuarias?
¿Qué porcentaje de usuarios y usuarias hace todo el viaje desde su primer evento hasta el pago?

Paso 5. Estudiar los resultados del experimento

¿Cuántos usuarios y usuarias hay en cada grupo?
Tenemos dos grupos de control en el test A/A, donde comprobamos nuestros mecanismos y cálculos. Observa si hay una diferencia estadísticamente significativa entre las muestras 246 y 247.
Selecciona el evento más popular. En cada uno de los grupos de control, encuentra la cantidad de usuarios y usuarias que realizaron esta acción. Encuentra su proporción. Comprueba si la diferencia entre los grupos es estadísticamente significativa. Repite el procedimiento para todos los demás eventos (ahorrarás tiempo si creas una función especial para esta prueba). ¿Puedes confirmar que los grupos se dividieron correctamente?
Haz lo mismo para el grupo con fuentes alteradas. Compara los resultados con los de cada uno de los grupos de control para cada evento de forma aislada. Compara los resultados con los resultados combinados de los grupos de control. ¿Qué conclusiones puedes sacar del experimento?
¿Qué nivel de significación has establecido para probar las hipótesis estadísticas mencionadas anteriormente? Calcula cuántas pruebas de hipótesis estadísticas has realizado. Con un nivel de significancia estadística de 0.1, uno de cada 10 resultados podría ser falso. ¿Cuál debería ser el nivel de significación? Si deseas cambiarlo, vuelve a ejecutar los pasos anteriores y comprueba tus conclusiones.