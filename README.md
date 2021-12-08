# tests_hackmd

### Edges style
```graphviz
graph cg{
    a -- b [color=red, penwidth=3, label=1];
    a -- c;
    a -- d [color=blue, penwidth=3, label=4];
    b -- c [color=green, penwidth=3, label=2];
    b -- d;
    c -- d [color=yellow, penwidth=3, label=3];
}
```

```flow
st=>inputoutput: Lectura de datos
st1=>dunctions

op1=>operation: Grafo
op2=>operation: Inicialización ACO
op3=>operation: Selección de hiper-parámetros
op4=>operation: Solución TSP
op5=>operation: Visualización

st->op1->op2->op3->op4->op5
st1->op1
```