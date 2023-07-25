<h1>Structure Of A C++ Program</h1>
<hr />

<h2>Introduction</h2>
<p>
  <strong><code>C++</code></strong> was developed by <strong>Bjarne Stroustrup</strong> at Bell Labs as an extension to <strong>C</strong>, starting in 1979. The language adds many new features to the C language, and is perhaps best thought of as a superset of C<br />
  <br /><strong>C++</strong>’s claim to fame results primarily from the fact that it is an <strong>Object-Oriented Language</strong>.
</p>    

<hr />
<h2> Hello World!</h2>
<p>The best way to learn a programming language is by writing programs. Typically, the first program beginners write is a program called 'Hello World' , which simply prints <strong><code>Hello World</code></strong> to your computer screen. Although it is very simple, it contains all the fundamental components C++ programs have:</p>

```C++
#include <iostream>  // (1)

using namespace std; // (2)

int main() // (3)
{
  cout << "Hello World" << endl; // (4)

  return  0; // (5)

}
```
<ul>
  <li>
   <h3><a href="https://en.cppreference.com/w/cpp/language/main_function">The Main Function </a><code>(1)</code></h3>
    <p>The <strong><code>main()</code></strong> Function is a special function in all C++ programs. It's the function called when the program is executed. The execution of all C++ programs begins with this function, regardless of where it's actually located within the code.<br />
<br />The open brace <strong><code>{</code></strong> indicates the beginning of the main's function definition, and the closing brace <strong><code>}</code></strong>  indicates its end. Everything between these braces is the function's body that defines what happens when main is called
</p>
  </li>
</ul>



<br /> <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Durim-D/CppBible">CppBible</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/Durim-D">Durim Delilaj</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-NonCommercial-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 
