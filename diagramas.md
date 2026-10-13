# Arboles binarios aplicados al atletismo

## 1. Arbol lleno

Cada nodo tiene cero o dos hijos.

```text
       Atletismo
       /       \
 Salto largo  Salto alto
```

## 2. Arbol completo

Todos los niveles estan llenos, excepto
posiblemente el ultimo, ocupado de izquierda a derecha.

```text
       Atletismo
       /       \
 Salto largo  Salto alto
     /
80 metros
```

## 3. Arbol perfecto

Todos los nodos internos tienen dos hijos
y todas las hojas estan al mismo nivel.

```text
          Atletismo
          /       \
    Salto largo  Salto alto
      /    \      /    \
  Vallas  Fondo  80 m  100 m
```

## 4. Arbol degenerado

Cada nodo tiene como maximo un hijo.

```text
Atletismo
    \
  Carreras
      \
    Vallas
       \
     Fondo
```

## 5. Referencias nulas

Cuando un nodo no tiene hijo izquierdo o derecho,
esa referencia es nula.

Un nodo hoja no tiene hijos.
