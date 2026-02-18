# 🏠 Sistema IoT para Casa Inteligente

## 📌 Objetivo
Implementar un escenario de prototipado que plantee una solución de aplicaciones IoT, permitiendo el control, administración y monitoreo remoto de dispositivos de una casa inteligente mediante una API REST simulada.

---

## 🧩 Problema
Las casas inteligentes requieren un control remoto confiable que permita al usuario interactuar con los dispositivos aun cuando se encuentra fuera de casa o en distintos modos de operación (en casa, dormido, fuera), garantizando seguridad, comodidad y supervisión constante.

## 🖥️ Aplicación Web de Administración

    Permite:
    Crear dispositivos IoT
    Editar nombre, tipo y estado
    Eliminar dispositivos
    Gestionar el inventario IoT de la vivienda

## 🎛️ Aplicación Web de Control

Permite:
    Encender y apagar dispositivos mediante botones
    Cambiar el modo de la vivienda:
        🏠 EN CASA
        🌙 DORMIDO
        🚨 FUERA
    Visualizar retroalimentación visual inmediata
    Activar alertas si se detecta una puerta o garaje abierto en modo seguro

## 📊 Aplicación Web de Monitoreo

Incluye:
    Dashboard visual del estado de los dispositivos
    Indicadores gráficos
    Historial de los últimos 10 estados
    Actualización periódica sin recargar la página
    Alertas de seguridad en tiempo real

## 🌡️ Simulación del Sensor de Temperatura

El sistema simula temperaturas realistas de una vivienda, con cambios graduales que representan condiciones reales del entorno, evitando variaciones bruscas irreales.

## 🎨 Tecnologías Utilizadas:
    HTML5
    CSS3
    Bootstrap 5
    JavaScript (Vanilla)
    Chart.js
    MockAPI (API REST simulada)
---

## 🏗️ Arquitectura de la Solución

La solución se compone de:

- **API REST (MockAPI)**
- **Aplicación Web de Administración**
- **Aplicación Web de Control**
- **Aplicación Web de Monitoreo (Dashboard)**

---

## 🔌 Dispositivos IoT Simulados

La solución contempla al menos **3 dispositivos IoT**, entre ellos:

- 💡 Luces (sala, cocina, entrada)
- 🌪 Ventiladores
- ❄️ Aire acondicionado
- 🚪 Puerta principal
- 🚗 Garaje
- 🏠 Sistema (modo de la vivienda)

---

## 🗄️ Base de Datos (MockAPI)

Recurso principal: `dispositivos_IoT`

### Estructura del recurso:
```json
{
  "id": "1",
  "nombre": "Luz Cocina",
  "tipo": "Luz",
  "estado": "ON",
  "valor": "23.5"
}

