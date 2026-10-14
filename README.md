# Comparador de Modelos Llama

##  Objetivo del reto
Construir un comparador que envíe 3 preguntas reales a Llama y registre, para cada una, el tiempo de respuesta y el número de tokens consumidos.

## ️ Tecnologías utilizadas
- Python
- Ollama (modelo `llama3.2:3b`)
- Google Colab (con GPU T4)

## ▶️ Cómo ejecutar
1. Abre el notebook en [Google Colab](https://colab.research.google.com/).
2. Activa la GPU T4: **Entorno de ejecución → Cambiar tipo de entorno de ejecución → T4 GPU**.
3. Ejecuta las celdas en orden (Shift + Enter).
4. El notebook instalará Ollama, descargará el modelo y ejecutará las 3 preguntas automáticamente.

## 📊 Resultados
- Tiempo total: ~81 segundos
- Tokens totales consumidos: 1373
- Conclusión: El modelo ligero resolvió las 3 preguntas satisfactoriamente.
