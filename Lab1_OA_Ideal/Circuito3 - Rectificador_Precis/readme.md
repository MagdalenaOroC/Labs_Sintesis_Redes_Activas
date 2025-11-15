# 🔧 Circuito 3 – Rectificador de Precisión

## 📌 Descripción
Un rectificador de precisión utiliza un op-amp para compensar la caída del diodo, permitiendo rectificar señales de muy baja amplitud (mV), imposibles para un rectificador convencional.

---

## 🧠 Funcionamiento
- **Etapa 1 (Vo1):** Rectificación de media onda precisa  
- **Etapa 2 (Vo2):** Restauración y amplificación  
- El op-amp entrega la tensión necesaria para forzar la conducción del diodo sin pérdidas

---

## 🔍 Comparación con puente de diodos
| Común | Precisión |
|-------|-----------|
| Caída 1.4 V | Sin caída |
| No rectifica mV | Sí rectifica mV |
| Mayor distorsión | Muy lineal |

---

## 🧪 Simulaciones realizadas
- Transitorios con onda senoidal  
- Comparación Vin – Vo1 – Vo2  
- Barrido DC: Vo1=f(Vin) y Vo2=f(Vin)  
- Comparación con rectificador de diodos adicional

---

## 📊 Resultados
- Se obtuvo rectificación perfecta para señales desde 1.2V  
- El rectificador convencional no pudo rectificar señales menores a 1.4V  
- El rectificador de precisión mostró linealidad y fidelidad en la salida

---

## 📁 Archivos
- `Rect_Precis.asc`  
- `circ3.ipynb`
