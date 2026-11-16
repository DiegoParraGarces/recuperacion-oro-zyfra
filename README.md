# Predicción de la recuperación de oro

## Descripción

Prototipo de machine learning para **Zyfra**, empresa de soluciones de eficiencia para la industria pesada. El modelo predice cuánto oro se recupera del mineral en las etapas de flotación y purificación, para optimizar la producción y descartar parámetros de operación no rentables.

## Resultados principales

- Validé la fórmula de recuperación (error prácticamente cero).
- Identifiqué 35 variables que solo existen después del proceso y las excluí para evitar fuga de información.
- Comparé modelo constante, regresión lineal, árboles y bosques aleatorios con validación cruzada y una métrica sMAPE ponderada.
- El mejor modelo (bosque aleatorio) obtuvo sMAPE de 8.68 en prueba, frente a 8.37 del modelo que predice el promedio: con las variables disponibles no supera la referencia. Lo reporto así, con recomendaciones de mejora.

## Herramientas

Python, pandas, NumPy, scikit-learn, Matplotlib

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
jupyter notebook 01_recuperacion_oro_zyfra.ipynb
```

Los datos provienen del programa de formación en ciencia de datos y no se incluyen en este repositorio. El notebook se puede revisar con todas sus salidas directamente en GitHub.

## Autor

Diego Parra · [LinkedIn](https://www.linkedin.com/in/diegoparragar)
