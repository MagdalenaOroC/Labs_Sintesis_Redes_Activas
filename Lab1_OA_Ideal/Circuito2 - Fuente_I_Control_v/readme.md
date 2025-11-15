# 🔧 Circuito 2 – Fuente de Corriente Controlada por Tensión

## 📌 Descripción
Esta etapa actúa como una fuente de corriente donde IL depende de Vin y se mantiene prácticamente constante frente a variaciones en la carga RL.

---

## 🧠 Claves del circuito
- El op-amp regula Vout para forzar una corriente fija.  
- Relación principal:
  \[
  I_L \approx \frac{V_{in}}{R_3}
  \]
- La carga RL provoca saturaciones si es muy grande o muy pequeña.

---

## 🧪 Simulaciones realizadas
- Barrido DC:
  - IL = f(Vin, RL)
  - Vo = f(Vin, RL)

---

## 📊 Resultados destacados
- IL se mantiene casi constante para cada RL  
- Vout entra en saturación según RL y Vin  

---

## 📁 Contenido
- `Fuente_I_V.asc`  
- `circ2.ipynb`  
- Gráficos y tablas listos para informe
