# 🛒💰 ANÁLISIS DE SUPERMERCADO: CARACTERÍSTICAS Y DESEMPEÑO DE VENTAS 🛒💰

## 📖 Descripción
El primer punto a tratar en este análisis es que la base de datos dada no tiene un conjunto de datos 100% fiable y reseñable, por lo que los datos aportados no son muy significativos para poder hacer un análisis exhaustivo o, incluso, encontrar algún problema de manera clara. Es por ello por lo que nos hemos centrado en hacer un análisis general de la situación de la compañía.

Para ello nos hemos centrado en analizar cómo se comporta cada tipo de tienda (Grocery Store, Supermarket Type 1, Type 2 y Type 3) en base a dos dashboards:

1. **Su relación con el tamaño de la población y el tamaño de la tienda:**
Donde podremos ver una imagen general de la compañía y sabremos si se vende más en ciudades más grandes o más pequeñas y si las tiendas más grandes venden más que las pequeñas.

2. **Su relación con los productos vendidos según el tipo de producto y sus características alimenticias**: Aquí podremos tener una visión global de los productos más vendidos en cada tienda y las ventas en función de sus características nutricionales (Low Fat o Regular).

Aunque este análisis es muy descriptivo y general de la compañía, nos va a ayudar a sacar algunas conclusiones importantes tanto para las futuras recopilaciones de datos de la compañía, como para intentar implementar acciones de cara al futuro para la mejora de la empresa.

Cabe destacar que se han incluído algunos datos en los dashboards con el simple hecho de conocer si son relevantes o no, como puede ser el peso de los productos. Unos datos que, de primeras no son relevantes, pero que nos pueden ayudar a saber si recopilarlos en un futuro puede servirnos o no.


## 🗂️ Estructura del Proyecto

├── Data/                      # Archivo Excel con todos los datos transformados y analizados para la realización del dashboard

├── README.md            # Descripción del proyecto


## 🛠️ Instalación y Requisitos
Este proyecto usa Excel para Mac en la versión 16.90.2 (24102719)


## 📊 Resultados y Conclusiones
### 1. RESULTADOS

#### 🌃 ANÁLISIS DE CADA TIPO DE TIENDA EN RELACIÓN A SU TAMAÑO Y AL TAMAÑO DE LA POBLACIÓN
    DASHBOARD 1

- A nivel general de la compañía, **el tamaño de la población NO es un factor muy relevante para las ventas**. Siendo las ubicaciones con mayor población las que más productos venden y más ingresos generan.

- En base al tamaño de cada tienda, podemos afirmar que **las tiendas más grandes son las que menos productos venden y menos ingresos generan**.

- El total de productos vendidos en **Supermarkets Type 1 es casi 2 veces más grande que en el resto de tipos de tienda juntos** (5.579 vs 2.947).

- Las tiendas **Grocery Store** solo están ubicadas en ubicaciones con mucha o con poca población, nunca con una **población media** (Tier 2).

- Las tiendas **Supermarket Type 2 y 3** solo están en ubicaciones con **grandes poblaciones** (Tier 3).

#### 🛍️ ANÁLISIS DEL TIPO DE PRODUCTO Y DE SUS CARACTERÍSTICAS NUTRICIONALES VENDIDO EN CADA TIENDA 
    DASHBOARD 2

- **Los 3 productos más vendidos** en **todas** las tiendas son: frutas y verduras, snacks y productos para el hogar. 

- En el top 10 de productos más vendidos, **todos los produdctos se venden en todas las tiendas**. 

- Los productos más vendidos en general son los **''Low Fat''** con **casi el doble de ventas** en cada tienda frente a los productos ''Regular''.

### 2. CONCLUSIONES

1. Teniendo en cuenta lo poco representativos que son los datos, la situación de la compañía aparentemente es buena. Se vende en ciudades más grandes y tienen ingresos que superan el millón de euros.

2. El grueso de ventas viene dado gracias a los Supermarket Type 1. Además, están en todos los tipos de ubicaciones y son los que más ingresos generan.

3. Los productos "Low Fat" se venden mucho más que los productos "Regular".

4. Hay muchos datos irrelevantes en el conjunto de datos que se pueden estudiar para valorar si merece la pena recopilarlos o no.

5. Este conjunto de datos sin tener un periodo de tiempo especificado, puede ser muy confuso ya que no podemos sacar conclusiones reales. Todo depende de ese periodo para saber si la situación de la compañía es positiva o negativa.

## 🔄 Próximos Pasos

1. El primer paso es intentar recopilar una serie de datos más representativos, empezando por un periodo de tiempo específico para poder contrastar todas las conclusiones obtenidas.

2. Sería muy interesante analizar el coste que supone mantener las tiendas Grocery Store, Supermarket Type 2 y Type 3, ya que los ingresos que generan son muy bajos en comparación con los Supermarket Type 1 y podrían estar generando problemas en la compañía.

3. Valorar la inversión en los Supermarket Type 1 en más ubicaciones para intentar aumentar los ingresos de la empresa.

## ✒️ Autor
- **Gonzalo Julián** - [@gonzalo8julian](https://github.com/Gonzalo8julian)
