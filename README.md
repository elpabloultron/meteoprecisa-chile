# 🌦️ MeteoPrecisa Chile

> **Clima Hiper-Local y Agroclimático de Alta Precisión para Chile**  
*Unificando la Red Agromet (INIA), Dirección Meteorológica de Chile (DMC), CEAZA y RedMeteo en una sola aplicación Open-Source.*

---

## 📌 Visión del Proyecto
En Chile, la diversidad geográfica y la presencia de microclimas hacen que los modelos globales de predicción (como GFS o ECMWF sin ajustar) cometan desvíos importantes de temperatura y precipitación.

**MeteoPrecisa Chile** soluciona esto combinando:
1. **Mediciones en tiempo real** de más de 400 Estaciones Meteorológicas Automáticas (EMAs) físicas instaladas en terreno a lo largo de Chile.
2. **Geolocalización inteligente (Haversine):** Vincula al usuario automáticamente con la estación física más cercana a su posición GPS.
3. **Pronóstico calibrado (Corrección de Sesgo Local):** Ajusta los modelos globales utilizando el historial y comportamiento de la estación local.
4. **Métricas Agroclimáticas:** Alertas de heladas, acumulación de Horas Frío, evapotranspiración (ETo) y radiación UV.

---

## 🛠️ Tecnologías Utilizadas
- **Frontend / UI:** HTML5, CSS3 (OLED Dark Minimalist), Vanilla JavaScript ES6+.
- **Geo-motor:** Algoritmo Haversine para cálculo de distancia a estaciones.
- **Móvil Native Bridge:** [Capacitor.js](https://capacitorjs.com/) para compilar a Android (`.apk`/`.aab`) e iOS (`.ipa`).
- **Fuentes de Datos:** Red Agromet (INIA), DMC, CEAZA, API RedMeteo 3.0, Open-Meteo API.

---

## 🚀 Cómo ejecutar localmente
```bash
# 1. Clonar el repositorio
git clone [https://github.com/TU-USUARIO/meteoprecisa-chile.git](https://github.com/TU-USUARIO/meteoprecisa-chile.git)

# 2. Entrar a la carpeta
cd meteoprecisa-chile

# 3. Abrir index.html en tu navegador o servidor local