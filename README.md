# Produccion Fiscalizada de Cololmbia para el 2017
La medición de la producción fiscalizada de hidrocarburos es un proceso que consiste en medir y determinar los volúmenes de petróleo, gas natural y condensados en los puntos de fiscalización de las empresas contratistas que operan en los diferentes lotes petroleros en nuestro país, de acuerdo con procedimientos basados en los Estándares Internacionales del API, ASTM, AGA. Se incluyen los datos de producción fiscalizada mensual de petróleo durante el año 2017. Periodo 2017-enero al 2017-diciembre. Doce (12) ciclos.

El enlace al proyecto, es:

https://beta.observablehq.com/@ansegura7/produccion-fiscalizada-de-colombia-para-el-2017

## OBJETIVO DEL PROYECTO
Crear una visualización web de la producción petrolera fiscalizada mensual de Colombia para el 2017, que permita agrupar dicha información por diferentes entidades (Departamento, Municipio, Operador y Campo), con el fin de poder analizar y descubrir información tal como: ¿Cuál entidad es la que más barriles de petróleo produce para la Nación y en qué mes? Con lo cual, el Estado puede tomar decisiones asociadas a la inversión de recursos económicos de manera optimo y/o asignación de yacimientos a los operadores más rentables.

## ALGUNOS INSIGHTS
- Departamentos que más petróleo producen: META (420 Kbbls/mes) y CASANARE (160 Kbbls/mes)
- Municipios que más petróleo producen: PUERTO GAITAN (200 Kbbls/mes), ACACIAS (95K bbls/mes) y CASTILLA NUEVA (76 bbls/mes)
- Operadores que más petróleo producen: COPETROL LLANOS (325 Kbbls/mes) y COPETROL S.A. (115 325 Kbbls/mes)
- Campos que más petróleo producen: RUBIALES (119 Kbbls/mes), CASTILLA (75 Kbbls/mes) y CHICHIMENE (52 Kbbls/mes)

## TECNOLOGÍAS USADAS
Para el desarrollo del proyecto se usaron las siguientes tecnologías:
- Observable para el desarrollo Web
- Javascript y el framework d3.js para crear el gráfico de barras y la respectiva interacción con él
- GitHub para almacenar los datos en el repositorio: https://github.com/ansegura7/ProduccionFiscalizadaCol2017

## PRERREQUISITOS Y USO
El proyecto sólo depende del acceso a los datos almacenados en el repositorio https://github.com/ansegura7/ProduccionFiscalizadaCol2017 y a la disponibilidad del servicio de https://beta.observablehq.com

El gráfico principal depende de 2 filtros, que son Tipo de Entidad y Mes Actual. A partir de estos 2 Combo Boxes, se filtrarán los datos y se actualizará el gráfico, para su respectivo análisis.

## AUTORES
El autor de los datos es la "Agencia Nacional de Hidrocarburos" del Estado. Los datos están actualizados al 7 de septiembre de 2018 y en el siguiente link se puede acceder a ellos: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-Fiscalizada-de-Petr-leo-2017/xhmd-pcpc

El autor de la visualización es Andrés Segura Tinoco, CE 201711582.

## SCREENSHOT
A continuación, se presenta un pantallazo del proyecto:

![GitHub Logo](https://raw.githubusercontent.com/ansegura7/ProduccionFiscalizadaCol2017/master/screenshot/VA-Tarea2-Screenshot.PNG)

## LICENCIA
Este proyecto está bajo la licencia MIT, la cual reza lo siguiente:

"Copyright (c) 2018 Andres Segura

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software."
