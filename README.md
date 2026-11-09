# EstadiApp · MotoExpres S.A.S.

**EstadiApp es una aplicación web desarrollada para MotoExpres S.A.S.** 
Nuestra app orientada a la validación de datos del esquema oficial de 21 columnas y al análisis probabilístico e inferencial (Módulos M1, M2, M3, M4, M5 y M9).

## README de la integrante:
**Laura Valentina Torres Castiblanco** 

## Integrantes del Equipo

**Laura Valentina Torres Castiblanco** 
**Katherin Julieth Basto Parra** 


## Requisitos e Instalacion

Al ser una aplicación web de un solo archivo independiente que consume librerías desde CDN (**PapaParse para CSV y SheetJS / XLSX para Excel**), 
no requiere instalación de dependencias ni servidores backend.

## Prerrequisitos
Para abrir nuestra app se necesita un navegador web moderno, el recomendado en este caso Google Chrome o Microsoft Edge

## Pasos de Instalacion
1. Clona o descarga este repositorio en tu equipo local:
   ```bash
   git clone [https://github.com/laura150-stack/MotoExpress.git](https://github.com/laura150-stack/MotoExpress.git)

2. O simplemente descarga el archivo ZIP del repositorio y extráelo en una carpeta, despues haz click en el archivo (index.html).


## Como Ejecutar la Aplicación

Existen dos maneras sencillas de ejecutar la aplicación:

## Opción A: Ejecución Directa (Recomendada)
1. Navega a la carpeta del proyecto.
2. Haz doble clic sobre el archivo `index.html` (o ábrelo directamente en tu navegador de preferencia).

## Opción B: Mediante Servidor Local (Live Server)
1. Abre la carpeta del proyecto en **Visual Studio Code**.
2. Haz clic derecho sobre el archivo `index.html` y selecciona **Open with Live Server** (requiere la extensión *Live Server*).

## Uso de la Aplicación

1. Módulo M1 (Cargar datos): Carga un archivo en formato .csv o .xlsx (hoja datos) que cumpla con el esquema oficial de 21 columnas de MotoExpres S.A.S. (ejemplos: MotoExpres_P1_Anual_2025.csv, MotoExpres_P4_Piloto_Magdalena.csv). La app validará el esquema y habilitará el resto de módulos de manera reactiva.

2. Módulo M2 (Análisis descriptivo): Explora las estadísticas descriptivas, histogramas, diagramas de caja y resumen detallado por sede o mecánico.

3. Módulo M3 (Probabilidad y Bayes): Visualiza las probabilidades básicas, la tabla de contingencia por mecánico, el análisis del Teorema de Bayes para el mecánico con mayor tasa de garantía y las pruebas de independencia. 

4. Módulo M4 (Binomial y Poisson): Analiza la variable discreta repuestos_usados ($E(X)$ y $V(X)$), la calculadora interactiva Binomial basada en la probabilidad de recomendación, y el modelo Poisson para estimar la llegada de servicios y la capacidad mínima $c$ con saturación menor al 5%.

5. Módulo M5 (Normal y Exponencial): Verifica el comportamiento del tiempo_diagnostico_min mediante el histograma con la campana de Gauss superpuesta, la calculadora de probabilidad normal y percentiles, así como el modelado Exponencial del tiempo entre llegadas.

6. Módulo M9 (Informe y decisiones): Muestra el resumen ejecutivo para la gerencia con tarjetas de KPIs clave y 3 decisiones estratégicas dinámicas (Capacidad, Calidad y Finanzas) calculadas a partir de reglas aplicadas directamente sobre los datos del archivo activo, con opción de exportación e impresión directa en PDF para entrega formal