# Struttura Di Un Programma C++
---

## Hello World!

Il primo programma che ogni principiante scrive si chiama **`Hello World!`** , esso fa apparire nello schermo del nostro computer la scritta `Hello World!`. Nonostante sia un programma molto semplice , contiene tutte le componenti fondamentali di un programma C++:

```cpp

#include <iostream>  // (3)

int main() // (1)
{
    std::cout << "Hello World" << std::endl; // (2)

    return 0; // (4)
}
```

- **La Funzione Main `(1)`**
Ogni programma presenta una o più funzioni , un insieme di istruzioni  comprese tra due parentesi graffe **`{}`**  che vengono eseguite in base all'ordine in cui sono scritte. 
Tra tutte le funzioni , quella principale è la funzione **`main()`** che viene eseguita prima di tutte le altre.
<br />
- **The Standard Output `(2)`**
Questa è la linea di codice che provvede a far comparire nel nostro computer la scritta `Hello World!`. 
<br />
- **La Libreria Iostream `(2)`**
Il C++ include una libreria standard , che ci permette di usare nei nostri programmi tantissime funzionalità diverse tra cui l'input e l'output , stiamo parlando della libreria **iostream**. Per ora l'unica cosa che devi sapere è che std::cout non funzionerebbe se non includessimo questa libreria.
<br />
- **L'Istruzione Return `(4)`**
return è un istruzione che termina una funzione e restituisce un valore. Nel caso di main() è anche un indicatore di stato :
- se il valore restituito è 0 allora il programma è stato eseguito correttamente
<br />

<ul>
    <item>L'Istruzione Return `(4)`</item>
</ul>

