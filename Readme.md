## Clase 26/09

## REPASO CLASE ANTERIOR 


### PILAS:LIFO-> Ultimo entrar, primero en salir
### COLA: FIFO-> Primero entrar, primero salir
### LISTAS:Cada elemento conoce su siguente(recorre, busca, inserttar y eliminar)
Se van a utilizar las siguentes estructuras o funciones:
Insetar, Insertar Ordenado,  Buscar y Eliminar 

**aca va el grafico**

No se puede impletar la busqueda binaria 

```bash
#include<iostream>

using namesapace std;

struct Nodo{
int id;
Nodo* sig;
};

Nodo* CrearNodo(int valor){
Nodo* nuevoNodo = new Nodo();
nuevoNodo ->id =valor;
nuevoNodo->sig=NULL;
return nuevoNodo;
}

Nodo* cargarLista(Nodo* inicio, int valor){
Nodo* nuevoNodo = crearNodo(valor);
if(inicio==NULL){
    inicio=nuevoNodo;
}else{
    Nodo* actual=inicio;
    While(actual->sig != NULL){
    actual=actual->sig;
}
actual->sig=nuevoNodo;
}
Return inicio;
}

void imprimirLista(Nodo* inicio){
    Nodo* actual=inicio;
    while(actual != NULL){
        cout<<actual -> info << " ";
        actual = actual ->sig;
    }
    cout <<endl;
}

int main(){
    Nodo* lista = crearNodo(10);
    lista->sig=crearNodo(20);
    lista->sig ->sig = crearNodo(30);

    cout<< "listas: ";
    imprimirListas(lista);

    delete lista-> sig ->sig;
    delete lista ->sig;
    delete lista;
    return 0;
}

## ejercicio de final
tenemos que hacer una funcion que recibe una pila y cola que te devuelva una lista ordenada y sin repetir.
```
