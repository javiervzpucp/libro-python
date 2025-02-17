# Capítulo 2: Representación de Algoritmos mediante Esquemas

En este capítulo aprenderemos a visualizar algoritmos utilizando diagramas de flujo y otros esquemas.

## 1. ¿Por qué Representar Algoritmos?

Los esquemas ayudan a visualizar procesos antes de codificarlos. Nos permiten:
- Identificar pasos innecesarios.
- Detectar errores en la secuencia lógica.
- Planificar de forma clara antes de programar.

## 2. Ejemplo: Cola en un Banco (FIFO)

**Concepto:** En una fila de banco, el primero en llegar es el primero en ser atendido (*First In, First Out - FIFO*).

**Diagrama de Flujo:**
📌 (Aquí podrías insertar una imagen con un diagrama de flujo mostrando el proceso de atención en una cola)

```python
cola = ["Cliente 1", "Cliente 2", "Cliente 3"]

for cliente in cola:
    print(f"Atendiendo a {cliente}")

