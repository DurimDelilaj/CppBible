# Struttura Di Un Programma C++
---

## Hello World!

Il primo programma che ogni principiante scrive si chiama **`Hello World!`** , esso fa apparire nello schermo del nostro computer la scritta `Hello World!`. Nonostante sia un programma molto semplice , contiene tutte le componenti fondamentali di un programma C++:

```cpp

#include <iostream>  // (3)

using namespace std;

int main() // (1)
{
    cout << "Hello World" << endl; // (2)

    return 0; // (4)
}
```

- **La Funzione Main `(1)`**
Ogni programma presenta una o più funzioni , un insieme di istruzioni  comprese tra due parentesi graffe **`{}`**  che vengono eseguite in base all'ordine in cui sono scritte. 
Tra tutte le funzioni , quella principale è la funzione **`main()`** che viene eseguita prima di tutte le altre.



