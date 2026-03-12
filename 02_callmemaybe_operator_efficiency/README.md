# 📞 Operator Efficiency Analysis — CallMeMaybe

## 🎯 Objetivo
Evaluación de la eficiencia operativa de un call center mediante KPIs y tests estadísticos
para detectar operadores ineficientes y proponer mejoras accionables.

## 🛠️ Herramientas
Python · Pandas · Seaborn · Scipy.stats · Mann-Whitney U · Tableau

## 📌 Metodología
- Filtrado de outliers por IQR en duración de llamadas
- Índice compuesto de ineficiencia con z-scores ponderados
- Clasificación en 3 niveles: Alto (273), Medio (544), Bajo (273)
- Análisis temporal y correlación con plan tarifario del cliente

## 💡 Insights clave
- Top 10 ineficaces: 30.3% llamadas perdidas y espera de 3,414 min vs. 0% y 9 min en los más eficaces
- 98.5% de llamadas sin operador asignado fueron perdidas — fallo sistémico crítico
- Tests Mann-Whitney U sugieren origen sistémico, no individual

## 🎯 Impacto
Intervención prioritaria en 273 operadores + detección de fallo sistémico responsable
de la tasa de llamadas perdidas del 98.5% en el grupo sin asignación.

## 📁 Archivos
-  https://public.tableau.com/shared/6P5JB8W5Z?:display_count=n&:origin=viz_share_link — Dashboard interactivo exportado de Tableau
