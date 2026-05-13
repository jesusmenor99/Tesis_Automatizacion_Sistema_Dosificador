# Tesis_Automatizacion_Sistema_Dosificador
# Automatización de Sistema Dosificador por Ganancia de Peso | ISA-88 + Allen Bradley

> Repositorio oficial del trabajo de grado para optar al título de Tecnólogo en Implementación de Sistemas Electrónicos Industriales.  
> **Unidades Tecnológicas de Santander (UTS) - 2025**

---

## Descripción General

Este proyecto recupera y rediseña un **sistema dosificador por ganancia de peso** que estaba fuera de servicio. La intervención incluyó:

- **Mantenimiento correctivo** completo (eléctrico y mecánico)
- **Nueva programación** en RSLogix 5000 (Ladder) bajo el estándar **ISA-88**
- **Interfaz HMI** en FactoryTalk View para supervisión y control
- **Integración de sensores**: celdas de carga, encoders, sensores capacitivos
- **Control de motores** mediante variadores PowerFlex 40

El sistema operó nuevamente con niveles aceptables de precisión (error < 6.2% en rangos específicos) y se validó como herramienta didáctica para automatización industrial.

---

## Objetivo del Proyecto

Recuperar y rediseñar el sistema dosificador para restablecer su funcionamiento y potenciar su uso como instrumento educativo en la enseñanza de automatización industrial, bajo estándares actuales y tecnología Rockwell Automation.

---

## Tecnologías y Herramientas

| Categoría          | Tecnología |
|--------------------|------------|
| **PLC**            | Allen‑Bradley CompactLogix 1769‑L23E QBFC1B |
| **Software Control** | RSLogix 5000 (Lenguaje Ladder) |
| **HMI**            | PanelView Plus 400 + FactoryTalk View |
| **Variadores**     | PowerFlex 40 |
| **Sensores**       | Celdas de carga (2), Encoders, Sensor capacitivo |
| **Acondicionamiento** | Caja sumadora + Transmisor de fuerza (0‑10 VDC) |
| **Estándar**       | ISA‑88 (modelo jerárquico para procesos batch) |

---

## Arquitectura de Control (ISA-88)

El sistema sigue la estructura modular del estándar **ISA S88**, separando la lógica de control de las funciones de proceso. Esto permite:

- Gestión clara de recetas
- Reconfiguración flexible
- Mayor claridad en la programación Ladder

## Autores

- **Paul Camilo Gutiérrez España**  
- **Jesús Alejandro Sarmiento Villamizar**  

**Director:** Jairo Iván Flores Barrera  
**Institución:** Unidades Tecnológicas de Santander (UTS) – Programa de Ingeniería Electrónica  
**Año:** 2025
