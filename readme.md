# 🔌 Fuente Variable Controlada por Microcontrolador

## 📌 Descripción general

Este proyecto consiste en el desarrollo de una **fuente de alimentación variable controlada digitalmente mediante un microcontrolador**, permitiendo ajustar el voltaje de salida de forma precisa y programable.

El sistema combina electrónica analógica (regulación de tensión) con control digital, integrando conceptos de:

- Sistemas embebidos  
- Electrónica de potencia (baja potencia)  
- Conversión analógico-digital  
- Control mediante PWM  

Este tipo de soluciones es ampliamente utilizado en laboratorio, testing electrónico y sistemas industriales. :contentReference[oaicite:0]{index=0}  

---

## ⚙️ Objetivos del proyecto

- Diseñar una fuente de alimentación con salida variable  
- Implementar control digital del voltaje mediante microcontrolador  
- Integrar señal PWM para regulación de tensión  
- Permitir interacción del usuario (ajuste de salida)  
- Validar el comportamiento del sistema mediante pruebas  

---

## 🧠 Principio de funcionamiento

El sistema se basa en el uso de un microcontrolador que genera una señal PWM para controlar el nivel de tensión de salida.

- El ciclo de trabajo (duty cycle) de la señal PWM determina el voltaje de salida  

Esto permite:

- Ajuste digital del voltaje  
- Mayor flexibilidad frente a soluciones analógicas puras  
- Posibilidad de automatización o control remoto  

Este enfoque es común en fuentes modernas controladas digitalmente. :contentReference[oaicite:1]{index=1}  

---

## 🔌 Arquitectura del sistema

### 🧠 Control
- Microcontrolador (generación de PWM y lógica de control)

### ⚡ Etapa de potencia
- Regulador de tensión (lineal o con control externo)  
- Etapa de adaptación de señal  

### 🎛️ Interfaz de usuario
- Pulsadores / potenciómetro / entrada digital  
- (Opcional) Display para visualización  

### 🔄 Señales principales
- PWM → control de tensión  
- ADC (si aplica) → lectura de voltaje o referencia  

---

## 🔄 Funcionamiento del sistema

1. El usuario define el voltaje deseado  
2. El microcontrolador genera una señal PWM proporcional  
3. La etapa de potencia regula la salida en función de esa señal  
4. Se obtiene una tensión de salida ajustable  

---

## 🛠️ Tecnologías utilizadas

- Microcontrolador (STM32 / ARM Cortex M4)  
- Programación en C/C++ (o entorno Arduino)  
- Señales PWM  
- Electrónica analógica (regulación de tensión)  

---

## 📊 Características del sistema

- Ajuste de voltaje variable  
- Control digital  
- Alta flexibilidad de configuración  
- Posibilidad de expansión (control automático o remoto)  

---

## 🧪 Aplicaciones

- Laboratorios de electrónica  
- Testing de circuitos  
- Alimentación de prototipos  
- Sistemas embebidos  

También puede escalarse a sistemas más complejos utilizados en industria y automatización. :contentReference[oaicite:2]{index=2}  

---

## 🚀 Posibles mejoras

- Medición de corriente (fuente CV/CC)  
- Implementación de display (LCD / OLED)  
- Control por encoder rotativo  
- Interfaz serial (PC)  
- Protección contra cortocircuito  
- Implementación de fuente switching (mayor eficiencia)  

---

## 📷 Documentación del proyecto

El repositorio puede incluir:

- Esquemático del circuito  
- Simulación (Proteus / LTSpice / similar)  

---

## 👨‍💻 Autor

**Emanuel Decima**  
Estudiante avanzado de Ingeniería Electrónica  
---