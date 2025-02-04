# Pilas

Son una lista que sigue el sistema FIFO.

### Constructor
```C#
 Stack miPila = new Stack();
 Stack<string> miPila = new Stack<string>();
```

### Metodos

```C#
stack.Pop(); // Devuelve y Elimina el primer dato de la lista
stack.Push(dato); // Inserta un dato a la lista
stack.Peek(); // Mira el primer dato de la lista sin eliminarlo
stack.Clear(); // Elimina la lista al completo
stack.Contain(); // Busca en la lista
stack.ToArray(); // Convierte la lista en un array
```