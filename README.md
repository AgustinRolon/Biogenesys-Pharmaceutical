# 🌟 Expansión Estratégica de Laboratorios para Investigación y Vacunación de COVID-19 🌟

## 📜 Introducción

BIOGENESYS Pharmaceutical busca identificar las ubicaciones óptimas para expandir sus laboratorios enfocados en la investigación y vacunación contra el COVID-19. El objetivo es mejorar la respuesta a la pandemia y facilitar el acceso a las vacunas.

Este proyecto tiene como propósito:

- Realizar un análisis exploratorio de datos sobre la incidencia de COVID-19 y factores relevantes mediante estadísticas y visualizaciones 📊.
- Aplicar técnicas de limpieza de datos para asegurar la calidad de la información 🧹.
- Mejorar el acceso a los datos mediante ETL (Extracción, Transformación y Carga) 🔄.
- Desarrollar dashboards interactivos para una toma de decisiones informada 📈.

## 🔄 Desarrollo del Proyecto

### Pasos de Transformación de Datos

1. **Carga de Datos:** Uso de `Numpy` y `Pandas` para cargar y transformar los datos 📥.
2. **Lectura del Dataset:** Carga del archivo CSV en un DataFrame usando `pandas.read_csv()` 📂.
3. **Verificación Inicial:** Confirmación del número de registros y columnas con `.shape` y visualización de los primeros registros con `.head()` 🔍.
4. **Filtrado por Países:** Selección de países de interés y filtrado del DataFrame desde el 01/01/2021 🌍.
5. **Tratamiento de Valores Nulos:** Manejo de valores nulos en columnas con más del 30% de datos faltantes, rellenando con media o ceros 🔄.
6. **Transformación de Datos:** Conversión de columnas relevantes de `float64` a `int` 🛠️.
7. **Almacenamiento de Datos Transformados:** Guardado del DataFrame final en `DatosFinalesFiltrados.csv` 📁.

### 📊 Análisis Exploratorio de Datos (EDA)

1. **Insights de Temperatura:** La temperatura no afecta significativamente a los casos de COVID-19 🌡️.
2. **Análisis de Series Temporales:** Identificación de picos en la tasa de crecimiento de casos confirmados entre enero y febrero de 2022 📅.
3. **Vacunación:** Evaluación del número de vacunas administradas y relación de dosis por habitante 💉.
4. **Distribución Poblacional:** Análisis de la distribución etaria de la población 👶👵.
5. **Cobertura de Vacunas y Reducción de Casos:** Correlación positiva entre cobertura de vacunas y disminución de casos nuevos 📉.
6. **Enfermedades Prevalentes:** Impacto de enfermedades como diabetes y tabaquismo en diferentes países 💔.
7. **Análisis de Mortalidad:** Tendencia de la tasa de letalidad a lo largo del tiempo ⚰️.

## 📈 Análisis del Dashboard

El dashboard incluye:

- **Portada:** Título del proyecto, logo de la empresa y navegación 🔗.
- **Países:** Casos confirmados, recuperados y muertes por país 🌍.
- **Vacunación:** Datos sobre la población vacunada y evolución de vacunas 💉.
- **Población:** Distribución poblacional en América Latina 👥.
- **Infraestructura Sanitaria:** Capacidad hospitalaria y recursos médicos por país 🏥.

  ## 📝 Conclusiones y Recomendaciones

### 🏆 Ubicaciones Óptimas para la Expansión de Laboratorios Farmacéuticos:

1. **Brasil** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1e7-1f1f7.svg" alt="Brasil" style="width: 16px; height: 16px;">

   - **Conclusión:** Brasil enfrenta la mayor carga de enfermedad en América Latina con 27 millones de casos confirmados y 491,000 muertes. La tasa de mortalidad es alta (231 muertes por cada 100,000 personas) y la tasa de vacunación es baja (1.5 dosis por persona). La infraestructura sanitaria necesita mejoras significativas para manejar la alta demanda de vacunas y la extensión geográfica.
   - **Recomendaciones:**
     - Desarrollar infraestructura sanitaria para mejorar la capacidad de distribución de vacunas 🏥.
     - Implementar campañas de vacunación masiva y optimizar la logística de distribución para alcanzar regiones remotas y urbanas 🚚.
     - Reforzar los recursos humanos sanitarios para apoyar la distribución de vacunas 👩‍⚕️👨‍⚕️.

2. **Chile** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1e8-1f1f1.svg" alt="Chile" style="width: 16px; height: 16px;">
   - **Conclusión:** Chile tiene una alta tasa de mortalidad (253 muertes por cada 100,000 personas) a pesar de una alta tasa de vacunación (3.5 dosis por persona). La infraestructura sanitaria es robusta, y la alta prevalencia de tabaquismo y diabetes contribuye a la mortalidad.
   - **Recomendaciones:**
     - Enfocar las intervenciones en factores de riesgo como el tabaquismo 🚭.

3. **México** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1f2-1f1fd.svg" alt="Chile" style="width: 16px; height: 16px;">
   - **Conclusión:** México presenta una alta carga de enfermedad con 6 millones de casos confirmados y 178,000 muertes. La tasa de vacunación es relativamente alta (casi 2 dosis por persona), pero la mortalidad sigue siendo preocupante.
   - **Recomendaciones:**
     - Reforzar los recursos humanos sanitarios para apoyar la distribución de vacunas 👩‍⚕️👨‍⚕️.

4. **Argentina** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1e6-1f1f7.svg" alt="Chile" style="width: 16px; height: 16px;">
   - **Conclusión:** Argentina tiene 8 millones de casos confirmados y 84,000 muertes. La tasa de mortalidad es moderada (187 muertes por cada 100,000 personas) y la tasa de vacunación es baja (2.5 dosis por persona). La infraestructura sanitaria y la alta cantidad de personal médico y de enfermería son aspectos positivos.
   - **Recomendaciones:**
     - Incrementar la tasa de vacunación 💉.

5. **Perú** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1f5-1f1ea.svg" alt="Chile" style="width: 16px; height: 16px;"> 
   - **Conclusión:** Perú tiene una alta tasa de mortalidad (419 muertes por cada 100,000 personas) y una alta tasa de vacunación (casi 3 dosis por persona). La infraestructura sanitaria es adecuada y el país tiene una alta cantidad de médicos y enfermeras.
   - **Recomendaciones:**
     - Buscar oportunidades con otros productos que ayuden a combatir las enfermedades prevalecientes 💡.

6. **Colombia** <img src="https://images.emojiterra.com/google/noto-emoji/unicode-15.1/color/svg/1f1e8-1f1f4.svg" alt="Chile" style="width: 16px; height: 16px;">
   - **Conclusión:** Colombia tiene 5 millones de casos confirmados y 116,000 muertes, con una tasa de mortalidad de 227 muertes por cada 100,000 personas. La tasa de vacunación es moderada y la infraestructura sanitaria es relativamente buena.
   - **Recomendaciones:**
     - Optimizar la capacidad de distribución y acceso a vacunas 📦.

## 🚀 Conclusión

El proyecto permite identificar oportunidades para expandir laboratorios en América Latina, basándose en datos sobre COVID-19, tasas de vacunación y recursos sanitarios. Los insights obtenidos facilitan decisiones estratégicas para mejorar el acceso a vacunas y optimizar la respuesta a la pandemia.

## 🛠️ Requisitos

- Python 3.x 🐍
- Librerías: `numpy`, `pandas`, `matplotlib`, `seaborn` 📚

## 📝 Instalación

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
2. Instalar las dependencias:
    ```bash
    pip install numpy pandas matplotlib seaborn
    ```
3. Ejecutar el script principal:
    ```bash
    python main.py
    ```

## 👤 Autor

[Agustin Rolon](https://github.com/AgustinRolon)

---

# 💛 Agradecimiento Especial

[![Henry](https://github.com/user-attachments/assets/00eeb5c8-4dcf-4124-ac29-d4ba7b113e6f)](https://www.soyhenry.com)  
[Henry](https://www.soyhenry.com)
