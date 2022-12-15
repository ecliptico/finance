### Instrucciones:

#### 0 - Antes que todo.

Buscamos los tickers del SP500 , con la funcion tq_index lo logramos.

#### 1 - Primero agregamos nuestros inputs que creemos relevantes.

-   SelectInput para los tickers
-   dateInput(1) para la fecha inicial
-   dateInput(2) para la fecha final
-   numericInput para elegir una tasa libre de riesgo

#### 2 - Posterior a crear los inputs, creamos los outputs para ir agregando al mainpanel.

-   

    1.  Usamos renderTable para mostrar un resumen o información que es relevante sobre la empresa de la cual se esta investigando.

-   

    2.  Usamos renderPlot para unir dos graficos sobre la evolucion del precio de la accion que se esta investigando y el SP500

-   

    3.  Usamos renderTable para mostrar 2 informaciones sumamente importantes, el promedio de retornos y la varianza del retorno de la accion que estamos buscando.

-   

    4.  Usamos renderTable para mostrar el beta calculado mediante: Eri = rf + [Erm -- rf] βi. El usuario puede elegir la tasa libre de riesgo que desea usar

-   

    5.  Por último graficamos.
