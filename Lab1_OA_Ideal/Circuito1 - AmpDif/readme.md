# 🔧 Circuito 1 – Amplificador Diferencial Ideal

## 📌 Descripción
El amplificador diferencial toma dos señales de entrada y amplifica únicamente su diferencia, rechazando el modo común. Es el bloque básico de los amplificadores instrumentales.

---

## 🧠 Conceptos Clave
- Ganancia diferencial:  
  \[
  V_o = A_d (V_2 - V_1)
  \]
- Rechazo al modo común (CMRR): fundamental para eliminar ruido.
- En un operacional ideal:
  - Rin → ∞  
  - Rout → 0  
  - No hay corriente de entrada  
  - A_OL → ∞

---

## 🧪 Simulaciones realizadas
- Barrido DC: Vo = f(V1), f(V2), f(VD)  
- Análisis de modo común y diferencial  
- Obtención del CMRR  
- Transitorio con senoidales

---


## 📁 Archivos importantes
- `Diff_amp.asc` – circuito LTspice  
- `circ1.ipynb` – graficas en Python  
- Capturas y reportes incluidos en esta carpeta
