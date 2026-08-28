# 🍃 AirQualityMx (Aire Limpio)
### *Tu salud comienza con un respiro.*

¡Bienvenido a la guía oficial de **AirQualityMx**! Nuestra misión es proporcionarte información precisa, técnica y en tiempo real sobre la calidad del aire, radiación UV y temperatura, ayudándote a tomar decisiones informadas para proteger tu bienestar.

---

## ✨ ¿Qué hace especial a AirQualityMx?

A diferencia de otras aplicaciones, **AirQualityMx** integra redes ciudadanas y algoritmos de salud personalizados en una experiencia fluida y sin anuncios.

### 🚀 Funciones Principales

#### 1. Red de Monitoreo Ciudadano 🌍
Conéctate a las redes más grandes de sensores de bajo costo:
*   **Redspira:** Identificados con **hexágonos verdes**.
*   **PurpleAir:** Identificados con **círculos morados**.
*   Datos de clima precisos vía **WeatherAPI**.

#### 2. Asistente de Salud Inteligente 🏥
No solo recibes datos, recibes consejos. Configura tu perfil (**Niño, Anciano, Deportista, Sensible o Estándar**) y sincroniza con **HealthKit (iOS)** o **Health Connect (Android)** para obtener recomendaciones basadas en tu edad y condición física (asma, alergias, etc.).

#### 3. Alertas Críticas (Silent Push) 🔔
Nuestra app te protege sin molestar. Te notificaremos automáticamente cuando:
*   El AQI pase a una categoría peor (ej. de "Aceptable" a "Mala").
*   La **Radiación UV** sea extrema (≥ 8.0).
*   La **Temperatura** sea crítica (≤ 0°C o ≥ 40°C).

#### 4. Mapas Interactivos y Optimizados 🗺️
Explora más de 27,000 sensores sin lag gracias a nuestro motor de **QuadTree**. 
*   **Android:** Basado en OpenStreetMap (osmdroid).
*   **iOS:** Integración nativa con MapKit y menús personalizados.

#### 5. Consumo Justo y Transparente ⚖️
Respetamos las cuotas de las APIs gratuitas. La app incluye un monitor de **Consumo Justo** (límite de 200 consultas diarias) para asegurar que el servicio siga siendo gratuito para todos.

---

## 🧘 Consejos para tu Salud

El **Banner de Consejos** dinámico en el header prioriza la amenaza más severa. Si la temperatura es más peligrosa que el aire, la app te avisará primero:
*   "Nivel de UV extremo: busca sombra y usa protector solar."
*   "AQI no saludable: evita actividades intensas al aire libre."
*   "Clima gélido: protégete de cambios bruscos de temperatura."

---

## 🛠️ Cómo funciona (Paso a Paso)

1.  **Configura tu Sensor Prioritario:** Marca un sensor con el icono de la **Campana** para recibir notificaciones de ese lugar específico.
2.  **Personaliza tu Inicio:** Elige entre ver tus **Favoritos**, la lista de **Sensores** o el **Mapa** al abrir la app.
3.  **Comparte con Impacto:** Genera una **imagen PNG** elegante de tus sensores favoritos para compartir en redes sociales o envía un reporte detallado en texto.
4.  **Sincroniza tu Salud:** Conecta tus datos biométricos para que la app sepa si eres un deportista o una persona mayor y ajuste sus consejos automáticamente.

---

## 🌍 Multiplataforma Real
Desarrollada con **Kotlin Multiplatform (KMP)** y **Compose Multiplatform**, garantizando que la lógica de cálculo sea idéntica en todos tus dispositivos:
*   **Android:** Con widgets de escritorio (Glance).
*   **iOS:** Con soporte para WidgetKit y (próximamente) Live Activities.
*   **Web (Wasm):** Consulta rápida desde cualquier navegador sin rastreadores.

---

## 🛡️ Tu Privacidad y Ética
*   **100% Libre de Anuncios:** Sin AdMob ni rastreo publicitario.
*   **Sin Contenido UGC:** Un entorno seguro y puramente informativo.
*   **Privacidad Web:** No solicitamos tu ubicación en la web a menos que tú lo pidas explícitamente.

### [Privacy Policy](privacy.md)
---

> **"Monitorea el aire, protege tu vida."**  
> ¡AirQualityMx es un proyecto independiente mantenido por la comunidad!
