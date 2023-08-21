# Struttura Di Un Programma C++

Un esempio classico di codice , che si usa per imparare , stampa sullo schermo la frase `Hello World!`. Questo programma, pur essendo molto semplice, illustra le principali componenti di un programma C++

```cpp

#include <iostream>  // (3)

int main() // (1)
{
    std::cout << "Hello World" << std::endl; // (2)

    return 0; // (4)
}
```

<ul>
    <li>
        <h3>La Funzione Main <code>(1)</code></h3>
        <p>
            Ogni programma è composto da una o più <strong>funzioni</strong> , istruzioni racchiuse tra due parentesi graffe <strong><code>{ }</code></strong> che vengono eseguite 
            sequenzialmente dal computer.<br /><br />
            La funzione <strong><code>main()</code></strong> è una funzione <strong>speciale</strong> presente in tutti i programmi C++  che viene chiamata quando il programma si avvia . L'esecuzione di tutti i                programmi inizia con questa funzione , indipendentemente da dove si trova nel codice.
        </p>
    </li>
    <li>
        <h3>L'Output Standard <code>(2)</code></h3>
        <p>
            Questa è la linea di codice è responsabile della visualizzazione del messaggio `Hello World!` sul nostro computer.
        </p>
    </li>
    <li>
        <h3>La Libreria Iostream <code>(3)</code></h3>
        <p>
            Il C++ include una libreria standard , che ci permette di usare nei nostri programmi tantissime funzionalità diverse tra cui l'input e l'output , 
            stiamo parlando della libreria <strong>iostream</strong>.<br /><br /> Per ora l'unica cosa che devi sapere è che std::cout non funzionerebbe se non includessimo questa libreria.
        </p>
    </li>
        <li>
        <h3>L'Istruzione Return <code>(4)</code></h3>
        <p>
           L'istruzione <strong><code>return</code></strong> termina una funzione e restituisce un valore. Nel caso di <strong><code>main()</code></strong> il valore restituito è 
            anche un <strong>indicatore di stato</strong>
        </p>
            <ul>
                <li>
                    <p>Se il valore restituito è <strong><code>0</code></strong> allora il programma è stato eseguito correttamente</p>
                </li>
                <li>
                    <p>Se il valore restituito è diverso da <strong><code>0</code></strong> c'è un errore nel codice</p>
                </li>
            </ul>
    </li>
    
     
</ul>

### License
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" />
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/DurimDelilaj/CppBible">CppBible</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/DurimDelilaj">Durim Delilaj</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a><br /></p> 
