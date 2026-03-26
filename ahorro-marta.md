# Ahorro · Marta

## Qué es

Aplicación web personal de planificación financiera para Marta. Permite registrar ingresos, gastos y objetivos de ahorro, planificar viajes y simular una hipoteca.

Es un único archivo `index.html` — sin frameworks, sin build — que se sirve directamente en el navegador.

## Tecnología

- **Frontend**: HTML + CSS + JavaScript vanilla, todo en `index.html`
- **Datos**: localStorage (sin sincronización, uso personal en un dispositivo)
- **Hosting**: pendiente

## Qué hace la app

### Panel de métricas
Cuatro tarjetas actualizadas en tiempo real: Ingresos, Gastos totales, Ahorro mensual, Libre para gastar.

### Ingresos
Campo único (sueldo neto de Marta).

### Objetivo de ahorro
Porcentaje de ingresos o cantidad fija mensual.

### Gastos fijos y variables
Listas editables con categorías predefinidas. Se pueden añadir y eliminar filas.

### Planificador de viajes
Asignación de % del dinero libre a viajes. Tarjetas por destino con nombre, presupuesto, fecha y cuenta atrás en tiempo real.

### Proyección de ahorro
Cards de 1/3/5 años con interés compuesto al 3% anual. Simulador de ahorro extra mensual.

### Simulador de hipoteca
- Precio del piso
- Ahorro actual
- % de entrada requerida (slider)
- Tipo de interés y plazo
- Resultados: dinero necesario, cuánto falta, cuota mensual, meses para alcanzar el objetivo, alerta si la cuota supera el 30-40% de ingresos

---

## Instrucciones para Claude

- Al iniciar sesión en este proyecto, activar el modelo opusplan (`/model opusplan`)
- Cada cambio realizado en el código debe añadirse al final de la sección **Historial de cambios** de este archivo

---

## Historial de cambios

| Fecha | Descripción |
|-------|-------------|
| 2026-03-26 | Commit inicial: app de ahorro personal para Marta con diseño Revolut+Apple, localStorage, planificador de viajes y simulador de hipoteca |
| 2026-03-26 | Cambiar tema a claro: fondo blanco, cards con sombra sutil, paleta de colores adaptada para fondo claro |
| 2026-03-26 | Añadir icono de pantalla de inicio iOS: silueta de chica sobre fondo degradado morado, archivo PNG real |
