# 🛒💰 ANÁLISIS DE SUPERMERCADO: CARACTERÍSTICAS Y DESEMPEÑO DE VENTAS 🛒💰

## 📖 Descripción
El primer punto a tratar en este análisis es que la base de datos dada no tiene un conjunto de datos 100% fiable y reseñable, por lo que los datos aportados no son muy significativos para poder hacer un análisis exhaustivo o, incluso, encontrar algún problema de manera clara. Es por ello por lo que nos hemos centrado en hacer un análisis general de la situación de la compañía.

Para ello nos hemos centrado en analizar cómo se comporta cada tipo de tienda (Grocery Store, Supermarket Type 1, Type 2 y Type 3) en base a dos dashboards:

1. **Análisis de tiendas por tamaño y ubicación**: Exploramos el rendimiento de los tipos de tienda en función del tamaño de la población y la tienda, con el objetivo de identificar patrones de ventas según estas variables.

2. **Análisis de ventas por tipo de producto y atributos nutricionales**: Examinamos la popularidad de distintos productos y su relación con atributos como "Low Fat" o "Regular", para comprender las preferencias de los clientes.

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

- **Población y ventas**: A nivel general de la compañía, **el tamaño de la población NO es un factor muy relevante para las ventas**. Siendo las ubicaciones con mayor población las que más productos venden y más ingresos generan.

- **Tamaño de tienda y ventas**: Las tiendas más grandes son las que menos productos venden en comparación con las pequeñas y medianas.

- **Tipos de tienda y ventas**:

    - Las tiendas de tipo Supermarket Type 1 tienen casi el doble de ventas que el resto de tiendas juntas (5.579 vs 2.947).

    - Las tiendas **Grocery Store** solo están ubicadas en ubicaciones con mucha o con poca población, nunca con una **población media** (Tier 2).

    - Las tiendas **Supermarket Type 2 y 3** solo están en ubicaciones con **grandes poblaciones** (Tier 3).

#### 🛍️ ANÁLISIS DEL TIPO DE PRODUCTO Y DE SUS CARACTERÍSTICAS NUTRICIONALES VENDIDO EN CADA TIENDA 
    DASHBOARD 2

- **Productos más vendidos**:
    - Los 3 productos más vendidos en todas las tiendas son: frutas y verduras, snacks y productos para el hogar.

    - En el top 10 de productos más vendidos, **todos los produdctos se venden en todas las tiendas**. 

- **Características nutriconales**: Los productos con la etiqueta "Low Fat" representan casi el doble de las ventas en comparación con los productos "Regular" en cada tienda.

### 2. CONCLUSIONES

- **Rendimiento de Supermarket Type 1**: Estos supermercados son clave para el negocio, generando la mayor parte de las ventas.

- **Preferencias del cliente**: Existe una clara inclinación hacia los productos "Low Fat," lo cual podría ser aprovechado para futuras estrategias de marketing.

- **Datos adicionales**: Algunos campos, como el peso de los productos, parecen irrelevantes en este contexto, pero podrían ser útiles en un análisis futuro.

## 🔄 Próximos Pasos

1. **Ampliar la recolección de datos**: Recopilar datos en periodos de tiempo específicos para obtener análisis más precisos y detectar tendencias estacionales.

2. **Reevaluar el portafolio de tiendas**: Evaluar el costo-beneficio de mantener los tipos de tienda menos rentables, como "Grocery Store" y "Supermarket Type 2 y 3".

3. **Potenciar los Supermarket Type 1**: Considerar la expansión de este tipo de tienda en áreas con demanda similar para aumentar los ingresos.

## ✒️ Autor
- **Gonzalo Julián** - [@gonzalo8julian](https://github.com/Gonzalo8julian)
