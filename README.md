# 📊 Razones Financieras

Este proyecto forma parte de un ejercicio académico para aplicar **razones financieras** en la evaluación de empresas.  
Las razones financieras son indicadores que permiten **interpretar la información contable**, analizar la salud económica de una organización y tomar mejores decisiones administrativas y de inversión.

---

## 🎯 Objetivos del proyecto
- Explicar qué son las **razones financieras** y su utilidad práctica.
- Calcular los principales indicadores financieros a partir de estados financieros ficticios.
- Comparar los resultados con valores de referencia o estándares del sector.
- Presentar los resultados en un **notebook interactivo** con cálculos en Python.
- Mostrar visualizaciones dinámicas de los indicadores mediante **Plotly**.

---

## 📑 Razones financieras incluidas
1. **Liquidez**
   - Razón corriente = Activo circulante / Pasivo circulante.
   - Prueba ácida = *(Activo circulante – Inventarios) / Pasivo circulante*.
2. **Endeudamiento**
   - Razón de endeudamiento total.
   - Deuda a capital contable.
3. **Rentabilidad**
   - Margen de utilidad neta.
   - ROA (rendimiento sobre activos).
   - ROE (rendimiento sobre capital).
4. **Eficiencia**
   - Rotación de inventarios.
   - Días de cuentas por cobrar.
   - Días de cuentas por pagar.

---

## 🧾 Ejemplo práctico

### Balance general simplificado
| Concepto              | Monto (MXN) |
|------------------------|-------------|
| **Activo circulante**  | 500,000     |
| Inventarios            | 150,000     |
| **Activo total**       | 1,200,000   |
| **Pasivo circulante**  | 250,000     |
| Pasivo total           | 600,000     |
| **Capital contable**   | 600,000     |

### Estado de resultados simplificado
| Concepto                  | Monto (MXN) |
|----------------------------|-------------|
| Ventas netas               | 1,000,000   |
| Utilidad neta              | 120,000     |

### Cálculo de razones
- **Razón corriente** = 500,000 / 250,000 = **2.0**
- **Prueba ácida** = (500,000 – 150,000) / 250,000 = **1.4**
- **Endeudamiento total** = 600,000 / 1,200,000 = **0.5 (50%)**
- **Deuda a capital** = 600,000 / 600,000 = **1.0**
- **Margen neto** = 120,000 / 1,000,000 = **12%**
- **ROA** = 120,000 / 1,200,000 = **10%**
- **ROE** = 120,000 / 600,000 = **20%**

---

## 📂 Archivos de ejemplo
- `data/razones_ejemplo.xlsx` → Dataset con estados financieros ficticios.
- `notebooks/RAZONES_financieras.ipynb` → Notebook con los cálculos de las razones.
- `requirements.txt` → Librerías necesarias para ejecutar el proyecto.

---

## 🚀 Tecnologías utilizadas
- **Python 3**
- **Pandas** → manejo de datos financieros.
- **Plotly** → gráficos interactivos.
- **Jupyter Notebook** → desarrollo de cálculos y explicación paso a paso.

---

## 🏁 Conclusión esperada
Con este proyecto se busca demostrar cómo las **razones financieras permiten diagnosticar la situación económica** de una empresa ficticia y generar reportes claros, que son aplicables también en empresas reales.
