# 🌀 Oscilador de Relajación con Amplificador Operacional  

**Laboratorio de Síntesis de Redes Activas – Circuito Adicional**

Este ejercicio consiste en el diseño y simulación de un **oscilador de relajación** basado en un amplificador operacional con realimentación positiva y un capacitor que determina el tiempo de carga/descarga.  
El objetivo es que el circuito oscile aproximadamente a **1 kHz**, utilizando un AO ideal saturado y un capacitor de , junto con resistencias a determinar.

---

## 📘 Descripción del circuito

El oscilador utiliza:

- Un **AO en configuración comparador con realimentación positiva**  
- Un par de resistencias que generan la **histeresis** (R3 y R4)  
- Una resistencia en serie con el capacitor (R2), que fija la constante de tiempo  
- Un capacitor **C1** que se carga y descarga entre los niveles de referencia definidos por la histéresis  
- Alimentación **asimétrica** 

Cuando el capacitor alcanza uno de los umbrales, el AO conmuta, cambiando la polaridad de su salida y forzando al capacitor a cargarse hacia el nivel opuesto.  
Este ciclo genera una **onda cuadrada en la salida** y una **onda de diente de sierra en el nodo del capacitor**, formando el clásico comportamiento de un oscilador de relajación.

---

## ⚙️ Objetivo del ejercicio

Diseñar valores de resistencias para que el oscilador produzca una frecuencia cercana a:

