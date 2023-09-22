# Chatea con tus archivos
## 

## Índice

- [1. Consideraciones generales](#1-consideraciones-generales)
- [2. Preámbulo](#2-preámbulo)
- [3. Resumen del proyecto](#3-resumen-del-proyecto)
- [4. Objetivos de aprendizaje](#4-objetivos-de-aprendizaje)
- [5. Criterios de aceptación](#5-criterios-de-aceptación)
- [6. Getting started](#6-getting-started)
- [7. Valida tu solución](#7-valida-tu-solución)
- [8. Recursos](#8-recursos)

***

- [ ] [Flowise basics](https://www.youtube.com/watch?v=tD6fwQyUIJE&list=PL4HikwTaYE0HDOuXMm5sU6DH6_ZrHBLSJ)
- [ ] [Langchain Components](https://docs.langchain.com/docs/category/components)
- [ ] [Chat models](https://docs.flowiseai.com/chat-models)
- [ ] [Chat Flows Basics](https://www.youtube.com/watch?v=fn4GCZuiwdk&list=PL4HikwTaYE0HDOuXMm5sU6DH6_ZrHBLSJ&index=3)

- [ ] Document Labels
  + [Flowise: Document loaders](https://docs.flowiseai.com/document-loaders)
  + [Langchain Concepts: Document loaders](https://docs.langchain.com/docs/components/indexing/document-loaders)
- [ ] Text Splitters
  + [Text Splitters demo](https://www.youtube.com/watch?v=kMtf9sNIcao&list=PL4HikwTaYE0HDOuXMm5sU6DH6_ZrHBLSJ&index=3)
  + [Langchain Concepts: Text Splitters](https://docs.langchain.com/docs/components/indexing/text-splitters)
- [ ] [Embeddings](https://docs.flowiseai.com/embeddings/azure-openai-embeddings)
- [ ] Vector Stores:
  + [Flowise: Vector Stores](https://docs.flowiseai.com/vector-stores)
  + [Langchain Concepts: Vector Stores](https://docs.langchain.com/docs/components/indexing/vectorstore)

## 5. Criterios de aceptación

1. Deberás configurar tu chatflow de manera que acepta la carga de al menos 1
   archivo de texto, en formato `txt` o `pdf`.

2. Utilizar el módelo `gpt-3.5-turbo`.

3. El chatbot generado debe ser capaz de contestar preguntas usando la
   información de el/los archivos cargados.

4. Tus github actions deben pasar exitosamente.

5. Debes utilizar al menos lo siguientes nodos:

- Conversational Retrival QA Chain
- Document Loaders
- Text Splitters
- Vector Stores
- Embeddings
- Memory
- Conversational Agent
