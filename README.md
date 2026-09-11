# Análisis de Inferencia Estadística: Nivel de Satisfacción de Estudiantes

## Descripción del Proyecto
Este proyecto evalúa el impacto y nivel de satisfacción de estudiantes pertenecientes a un curso en línea mediante técnicas de inferencia estadística paramétrica[cite: 16, 17]. A partir de una muestra de 200 observaciones, se analizan los momentos muestrales, se construye un intervalo de confianza al 95% para la media poblacional y se ejecuta una prueba de hipótesis bilateral para contrastar el desempeño frente a un estándar corporativo de 7.0 puntos[cite: 16, 17].

## Estructura del Análisis
1. **Carga y Exploración de Datos:** Inspección de variables (`Edad`, `Género`, `Puntaje_satisfaccion`, `Horas_estudio`), estadísticas descriptivas y definición de estrategia de imputación robusta mediante la mediana ante valores nulos[cite: 16, 17].
2. **Distribución y Visualización:** Histograma con estimación de densidad kernel (KDE) y cálculo de momentos muestrales insesgados (media y varianza con `ddof=1`), contextualizados bajo el Teorema del Límite Central (TLC)[cite: 16, 17].
3. **Intervalo de Confianza (95%):** Estimación por distribución t-Student ante desviación estándar poblacional desconocida ($\sigma$ no conocida)[cite: 16, 17].
4. **Prueba de Hipótesis:** One-Sample t-test bilateral ($\alpha = 0.05$) para contrastar $H_0: \mu = 7.0$ vs $H_1: \mu \neq 7.0$[cite: 16, 17].
5. **Conclusión y Toma de Decisiones:** Interpretación aplicada orientada a la reducción de incertidumbre empresarial y validación empírica[cite: 16, 17].

## Tecnologías Utilizadas
* **Python 3**[cite: 16, 17]
* **Pandas & NumPy:** Manejo matricial de datos y estadísticos insesgados[cite: 16, 17].
* **SciPy (`scipy.stats`):** Modelado probabilístico y prueba t de una muestra[cite: 16, 17].
* **Matplotlib & Seaborn:** Visualización de distribuciones empíricas[cite: 16, 17].

## Instrucciones de Ejecución
1. Clonar el repositorio[cite: 3, 4]:
```bash
git clone [https://github.com/Daratteon/inferencia-estadistica-satisfaccion.git](https://github.com/Daratteon/inferencia-estadistica-satisfaccion.git)