# Tripleten-da-sprint7-final-project
ConnectaTel - Telecom company looking to understand current users mobile patterns.


# 📊 Análisis de Clientes – ConnectaTel

## 🎯 Objetivo del proyecto

El objetivo de la empresa es:
- Identificar patrones de uso.
- Detectar comportamientos atípicos.
- Comprender qué segmentos de clientes muestran necesidades diferenciadas

---

## 📂 Datasets utilizados

El proyecto trabaja con uno o varios datasets relacionados con clientes de una empresa de telecomunicaciones ficticia (**ConnectaTel**).  

Los datasets utilizados son:
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Los datasets se cargan directamente en el notebook y se procesan usando **pandas**. Los archivos para el proyecto se encuentran en la carpeta datasets dentro del mismo repositorio.

---

## 🧪 Etapas del análisis

El análisis se estructura en las siguientes etapas:

**Paso 1. Cargar y explorar**
   - Importación de librerías
   - Carga de datasets
   - Revisión de estructura, tipos de datos y valores faltantes

**Paso 2. Identificación de problemas de calidad de datos**
   - Manejo de valores nulos
   - Revisión de inconsistencias
   - Revisión y estandarización de fechas

**Paso 3. Limpieza básica de datos**
   - Corregir sentinels y fechas imposibles

**Paso 4. Summary statistics de uso por usuario**
   - Agrupación por comportamiento de uso
   - Resumen estadístico por usuario durante el 2024

**Paso 5. Visualización de distribuciones (uso y clientes) y outliers**
   - Visualización de Distribuciones
   - Identificación de Outliers

**Paso 6. Segmentación de Clientes**
   - Segmentación de Clientes Por Uso
   - Segmentación de Clientes Por Edad
   - Visualización de la Segmentación de Clientes

**Paso 7. Insight Ejecutivo para Stakeholders**
  - Análisis ejecutivo

**Paso 8. Cargar tu notebook y README a GitHub**
  - Opción A : Subir archivos desde la interfaz de GitHub (UI)
  - Opción B : Guardar directo desde Google Colab

---

## ▶️ Cómo ejecutar el notebook

### Google Colab (recomendado)
1. Abre https://colab.research.google.com
2. Haz clic en **File → Upload notebook**
3. Sube el archivo `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
4. Sube los datasets (_.csv) al directorio raiz
5. Ejecuta las celdas en orden (Shift + Enter)

> No se requiere instalación local si usas Colab.

---

