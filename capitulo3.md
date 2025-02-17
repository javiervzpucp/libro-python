# Capítulo 3: Listas, Estructuras de Datos y FIFO

## 📌 ¿Qué es FIFO?
FIFO (*First In, First Out*) es una estructura donde el primer elemento en entrar es el primero en salir.

## 🖥️ Implementación en Python
```python
# Lista con clientes en una fila
clientes = ["Cliente 1", "Cliente 2", "Cliente 3"]

# Se atienden en orden de llegada
while clientes:
    cliente_actual = clientes.pop(0)
    print(f"Atendiendo a {cliente_actual}")

