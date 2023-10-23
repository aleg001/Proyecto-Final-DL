# Proyecto Final de Deep Learning: Desenvolviendo el Sonido en la Universidad del Valle de Guatemala

> Este trabajo se basa en el proyecto [Music Source Separation](https://github.com/andabi/music-source-separation) desarrollado durante el [Jeju Machine Learning Camp 2017](http://mlcampjeju.kakao.com). Sin embargo, ha sido extensamente modificado y mejorado como parte del proyecto final para la Universidad del Valle de Guatemala por Ale Gómez, Michy Solano, Andrea Lam, Chris García, Gabo Vicente y Rodri Barrera.

## Introducción 🎵

La separación de fuentes musicales es una tarea esencial en el procesamiento de señales de audio, que se centra en separar diferentes componentes de una canción, como la voz y los instrumentos. Este proyecto busca mejorar la arquitectura y la eficacia del modelo inicial propuesto en el repositorio base, explorando técnicas avanzadas en redes neuronales y procesamiento de señales.

## Cambios y Mejoras Realizadas 🛠️

### Optimización de la Arquitectura Neural:

- Se experimentó con diferentes configuraciones de las capas RNN y CNN, incluyendo la incorporación de mecanismos de atención para mejorar la captura de características temporales y espaciales.
- Implementación de una arquitectura de red neuronal híbrida que integra características de CNNs para el procesamiento de características espaciales y RNNs (LSTM) para la captura de dependencias temporales.

### Funciones de Pérdida Personalizadas:

- Diseño de nuevas funciones de pérdida que se alinean mejor con la tarea de separación de fuentes, enfocándose en minimizar la interferencia entre la señal vocal e instrumental.

### Técnicas de Regularización y Optimización:

- Implementación de técnicas de regularización como Dropout y Normalización de Lotes para prevenir el sobreajuste.
- Utilización de optimizadores avanzados y ajuste de hiperparámetros para mejorar la convergencia del entrenamiento.

### Utilización de Modelos Pre-entrenados y Fine-tuning:

- Exploración de modelos pre-entrenados en tareas de separación de fuentes y realización de fine-tuning para adaptar estos modelos a nuestro dataset específico, acelerando el entrenamiento y mejorando el rendimiento inicial.

### Comparativas con Herramientas Existentes:

- Comparación de rendimiento con herramientas existentes como Splitter AI, validando las mejoras implementadas y proporcionando un benchmark sobre el estado del arte.

### Actualización de Dependencias:

- Actualización de las dependencias a versiones más recientes como TensorFlow 2.x y Librosa 0.8.x, y asegurando la compatibilidad del código con estas nuevas versiones.

## Evaluación y Métricas 📊

- Utilización de métricas estándar en la tarea de separación de fuentes como SDR, SIR y SAR, además de otras métricas relevantes como la precisión y la recall en la detección de componentes vocales e instrumentales.
- Documentación meticulosa de los resultados obtenidos, incluyendo visualizaciones de espectrogramas y comparativas cualitativas.

## Conclusión 🎉

Las mejoras y modificaciones realizadas en este proyecto buscan no solo mejorar el rendimiento en la tarea de separación de fuentes de audio, sino también proporcionar una implementación más robusta y actualizada, demostrando la aplicabilidad de las técnicas de Deep Learning en el procesamiento de señales de audio.

## Créditos 🙌

- Este proyecto fue desarrollado como parte del proyecto final de Deep Learning en la Universidad del Valle de Guatemala por Ale Gómez, Michy Solano, Andrea Lam, Chris García, Gabo Vicente y Rodri Barrera.
- Agradecemos a los autores originales del repositorio base, así como a los instructores y compañeros de clase por su apoyo y orientación durante el desarrollo de este proyecto.
