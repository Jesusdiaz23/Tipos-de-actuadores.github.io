---
layout: page
title: "tipos de actuadores"
---
## Actuadores Eléctricos
### Tipos
- **Motores eléctricos**: Corriente alterna (CA) o corriente continua (CC) para movimiento rotacional.
- **Servomotores**: Control preciso de posición a través de retroalimentación.
- **Actuadores lineales eléctricos**: Transforman movimiento rotacional en lineal.
- **Solenoides**: Dispositivos electromagnéticos para movimiento lineal.

### Funcionamiento
- Convierten energía eléctrica en energía mecánica. Utilizan la ley de Lorentz, donde la corriente eléctrica en un campo magnético genera movimiento.

### Características
- **Precisión**: Control exacto de posición y velocidad.
- **Eficiencia**: Consumen energía solo durante el movimiento.
- **Reversibilidad**: Invierten fácilmente la dirección de movimiento.
- **Bajo mantenimiento**: No requieren mantenimiento frecuente.

### Modo de comunicación
- Se controlan mediante señales analógicas (0-10V, 4-20 mA) o digitales (PWM, Modbus, CANbus, Profibus).
- **Servomotores**: Utilizan sensores de retroalimentación como encoders.

---

## Actuadores Mecánicos

### Tipos
- **Cremallera y piñón**: Convierte movimiento rotacional en lineal.
- **Tornillo de bolas**: Transforma rotación en movimiento lineal.
- **Levas y seguidores**: Movimiento rotacional para generar movimiento lineal.

### Funcionamiento
- Dependen de engranajes, levas, tornillos y otros mecanismos para convertir movimiento rotacional en lineal o viceversa.

### Características
- **Durabilidad**: Soportan grandes cargas y movimientos constantes.
- **Simplicidad mecánica**: No requieren componentes eléctricos complejos.
- **Precisión dependiente del diseño**: Un buen diseño evita desgaste prematuro.

### Modo de comunicación
- No tienen comunicación integrada. Su control se realiza a través de motores o sistemas hidráulicos.

---

## Actuadores Hidráulicos

### Tipos
- **Cilindros hidráulicos**: Movimiento lineal (simple o doble efecto).
- **Motores hidráulicos**: Movimiento rotacional.

### Funcionamiento
- Utilizan fluido presurizado para mover un pistón o generar rotación. La presión del fluido impulsa el movimiento.

### Características
- **Alta fuerza**: Pueden generar grandes fuerzas con componentes pequeños.
- **Precisión moderada**: Su control es más difícil de modular que los actuadores eléctricos.
- **Robustez**: Ideales para trabajos pesados en ambientes difíciles.

### Modo de comunicación
- Controlados mediante válvulas hidráulicas. Estas válvulas se controlan mediante señales eléctricas o electrónicas (PLC, controladores de servo-válvulas).
