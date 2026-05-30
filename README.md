# Pildora SLMs y Ollama

Pildora introductoria sobre SLMs y Ollama de carácter educativo

# 🤓 Que son

> Los SLMs (Small Language Models o Modelos de Lenguaje Pequeños) son sistemas de inteligencia artificial diseñados para procesar y generar lenguaje natural de forma eficiente. A diferencia de los modelos gigantes (LLMs), cuentan con menos parámetros y están optimizados para ejecutarse localmente en dispositivos con recursos limitados.
* [Fuente Microsoft]

> Ollama es una plataforma gratuita y de código abierto que permite descargar, configurar y ejecutar Modelos de Lenguaje Grande (LLM) y Pequeño SLM directamente en tu propio ordenador. En lugar de depender de servidores en la nube como ChatGPT o Gemini, Ollama te permite tener tu propia inteligencia artificial operando de forma 100% local y privada.
* [Fuente Xataca]

---

## 📢 Presentaciones

Modelos de lenguaje pequeños y eficientes 

https://gamma.app/docs/Modelos-de-Lenguaje-Pequenos-y-Eficientes-wjkjird4w0leygo

IA-Ligera glosario esencial 

https://gamma.app/docs/IA-Ligera-Glosario-Esencial-lcbfkc40zcpm0c6

---

## 💾 Descargar programas

- Ollama -> https://ollama.com/
- Ollama Download -> https://ollama.com/download
- Ollama models -> https://ollama.com/search

---

## 🛠️ Comandos de Ollama

* **ollama list** -> Lista los modelos locales que tienes descargados.
* **ollama pull [nombre-modelo]** -> Descarga el modelo en local.
  - por ejemplo : ollama pull llama3
* **ollama run [nombre-modelo]** -> Ejecuta el modelo en la terminal y si no está decargado, lo descarga y luego lo ejecuta.
  - por ejemplo : ollama run llama3
* **ollama show** [nombre-modelo] -> Ver datos del modelo.
* **ollama show --parameters** [nombre-modelo] -> Ver parámetros del modelo.
  - otras opciones : [--license, --modelfile, --system, --template]
* **ollama cp [nombre-modelo1] [nombre-modelo2]** -> Hace una copia del modelo1 con otro nombre modelo2 para poder personalizarlo.
  - por ejemplo : ollama cp llama3 mi_llama
* **ollama rm [nombre-modelo]** -> Borra el modelo con ese nombre.
  - por ejemplo : ollama rm mi_llama
* **ollama ps** -> Revisa qué modelos se están ejecutando y usando tu memoria RAM en este momento.

---

## 🎇 Comandos dentro del modelo (una vez ejecutado el modelo)

* **/bye o /exit** : Cierra la sesión, sale del chat y descarga el modelo de la memoria RAM.
* **/list** : Muestra una lista de todos los modelos que tienes descargados en tu equipo.
* **/show** : Muestra información sobre el modelo activo (parámetros, plantilla del sistema, etc.).
  - Ejemplo: /show info o /show parameters.
* **/set** : Modifica los parámetros del modelo en tiempo real.
  - Ejemplo para cambiar la creatividad: /set temperature 0.2 (valores cercanos a 0 son más precisos; cercanos a 1, más creativos).
  - Ejemplo para el contexto: /set num_ctx 4096 (aumenta el límite de memoria de la conversación).
* **/system** : Permite cambiar las instrucciones del sistema en medio de la conversación.
  - Ejemplo: /system Eres un programador experto en Python.
* **/?** : Muestra una lista completa con todos los comandos y atajos disponibles dentro de la ejecución

---

## 🪄 Enlaces de interés

1.- Curso de Ollama 🦙: TODO lo que Necesitas Saber para una IA PRIVADA y segura -> https://www.youtube.com/watch?v=vOgISvkcF5k

2.- Curso de OLLAMA 2026: Tu propia Inteligencia Artificial en LOCAL (Instalación, Uso y Casos Reales) -> https://www.youtube.com/watch?v=FFjvZV05vxM

3.- Github de Ollama -> https://github.com/ollama/ollama





