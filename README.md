# 🎮 Análisis de Ventas de Videojuegos – Tiendas ICE

## 📊 Descripción del proyecto
Este proyecto forma parte del bootcamp de análisis de datos de TripleTen.  
El objetivo fue **identificar patrones en las ventas de videojuegos** para ayudar a la empresa ficticia *Tiendas ICE* a **planificar sus campañas de marketing** de forma más efectiva.

Se analizan datos históricos de ventas, puntuaciones de usuarios y críticos, géneros y plataformas, para entender cómo varía el éxito de los juegos según diferentes factores.

---

## 🧰 Herramientas utilizadas
- **Python**
- **pandas** – limpieza y análisis de datos  
- **matplotlib / seaborn** – visualización de datos  
- **scipy.stats** – pruebas estadísticas (t-test)

---

## ⚙️ Pasos realizados
1. **Carga y limpieza de datos**
   - Conversión de tipos de datos (años, puntuaciones).
   - Cálculo de ventas totales globales.

2. **Análisis exploratorio**
   - Juegos lanzados por año.
   - Ventas totales por plataforma y género.
   - Comparación de correlaciones entre puntuaciones y ventas.

3. **Análisis regional**
   - Plataformas y géneros más populares en Norteamérica, Europa y Japón.
   - Impacto de las clasificaciones ESRB por región.

4. **Pruebas de hipótesis**
   - Comparación de puntuaciones de usuarios entre plataformas (Xbox One vs PC).
   - Comparación de puntuaciones entre géneros (Acción vs Deportes).

---

## 🔍 Principales hallazgos
- Las plataformas con mayor volumen de ventas históricas fueron **PS2, X360 y Wii**.  
- Existe **una correlación positiva entre la puntuación de críticos y las ventas**, aunque no tan fuerte con las puntuaciones de usuarios.  
- Los géneros de **Acción y Deportes** dominan las ventas globales.  
- En Japón, los géneros **de rol y aventura** son más populares que en otras regiones.  
- No se encontró diferencia significativa entre las puntuaciones promedio de Xbox One y PC.

---

## 🧾 Conclusión
El análisis permite entender cómo el rendimiento comercial de los videojuegos depende de su plataforma, género y recepción crítica.  
Estos hallazgos pueden ayudar a orientar estrategias de lanzamiento y marketing en diferentes mercados.

---

## 📁 Estructura del repositorio
